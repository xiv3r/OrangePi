## Install Nexcloud
```
sudo apt update
sudo apt-get upgrade -y
sudo apt install snapd -y
sudo snap install nextcloud

```

### Auto-Fix All Missing Keys
```
sudo apt update 2>&1 | grep "NO_PUBKEY" | \
awk '{print $NF}' | \
sort -u | xargs -r -I % sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys %
sudo apt update

```
### Manual Fix (If Auto Fails)
```
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys \
6ED0E7B82643E131 78DBA3BC47EF2265 762F67A0B2C39DE4 \
BDE6D2B9216EC7A8 8E9F831205B4BA95
sudo apt update
```
