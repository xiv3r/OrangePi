# Nextcloud Installation Guide

A quick guide to installing Nextcloud on Ubuntu using Snap, including fixes for common GPG key errors during `apt update`.

---

## Prerequisites

- Ubuntu 20.04 or later
- `sudo` privileges

---

## Installation

Update your system and install Nextcloud via Snap:

```bash
sudo apt update
sudo apt-get upgrade -y
sudo apt install snapd -y
sudo snap install nextcloud
```

Once installed, Nextcloud will be available at `http://<your-server-ip>`.

---

## Troubleshooting: GPG Key Errors

If `apt update` or `apt upgrade` fail with errors like:

```
W: GPG error: ... NO_PUBKEY 6ED0E7B82643E131
```

Use one of the following methods to resolve missing public keys.

### Option 1 — Auto-Fix (Recommended)

This script automatically detects and imports all missing keys:

```bash
sudo apt update 2>&1 | grep "NO_PUBKEY" | \
  awk '{print $NF}' | \
  sort -u | \
  xargs -r -I % sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys %

sudo apt update
```

### Option 2 — Manual Fix

If the auto-fix doesn't work, import the keys manually. This is the approach that resolved the issue in the original setup:

```bash
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys \
  6ED0E7B82643E131 \
  78DBA3BC47EF2265 \
  762F67A0B2C39DE4 \
  BDE6D2B9216EC7A8 \
  8E9F831205B4BA95

sudo apt update
```

> **Note:** `apt-key` is deprecated in Ubuntu 22.04+. If you're on a newer system and still seeing key errors, consider using the `/etc/apt/trusted.gpg.d/` method instead.

---

## Next Steps

- Open `http://<your-server-ip>` in a browser to complete the setup wizard
- Create your admin account and choose your data directory
- Install the [Nextcloud desktop or mobile client](https://nextcloud.com/install/#install-clients) to sync files
