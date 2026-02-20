<h1 align = "center">🌟Orange Pi 4A🌟</h1>
 
---
<p align="center">
  <span style="font-size: 1.1em; color: #FFD700; font-weight: bold;">✨ Enjoying this project? Support our work! ✨</span>
</p>

<p align="center" style="margin: 15px 0;">
  <a href="https://buymeacoffee.com/pylin" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" style="height: 40px; width: 150px;">
  </a>
</p>

<p align="center" style="margin: 15px 0;">
  <a href="https://www.youtube.com/channel/UCKKhdFV0q8CV5vWUDfiDfTw" target="_blank">
    <img src="https://img.shields.io/badge/SUBSCRIBE%20ON%20YOUTUBE-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Subscribe on YouTube" style="height: 40px;">
  </a>
</p>

---

## 🟩 Shorts

| S.No | Title | Links | Project |
|------|-------|-------|---------| 
| 1 | 🆓️ Unboxing Orange Pi 4A Palm Size SBC (Allwinner T527, 2GB) | [Watch](https://youtube.com/shorts/7_msW7Os2Vo?feature=share) | | 
| 2 | ⏳️ Orange Pi 4A Palm Size Linux SBC \| IoT \| IIoT \| Computer | [Watch] | |

---

## 🟩 Getting Started Guide

| S.No | Title | Links | Project |
|------|-------|-------|---------| 
| 1 | 🆓️ Flash Ubuntu Jammy Server Linux OS to SD Card, SSH, WIFI | [Watch](https://youtu.be/QYYwaP-cx-E) | | 
| 2 | 🆓️ Flash Ubuntu Jammy XFCE Desktop Linux OS to SD Card, SSH, WIFI | [Watch](https://youtu.be/AYGstq-sK3Q) | | 
| 3 | 🆓️ Flash Ubuntu Jammy Gnome Desktop Linux OS to SD Card, SSH, WIFI | [Watch](https://youtu.be/DSpfqHI-4Bw) | |

---

## 🟩 Node-RED

| S.No | Title | Links | Project |
|------|-------|-------|---------| 
| 1 | 🆓️ Install Node-RED on Orange Pi 4A (Node.js, NPM, IoT, IIoT) | [Watch](https://youtu.be/R1blSGHwgyg) | [GitHub](https://github.com/papercodeIN/Embedded_Devices/blob/main/Orange%20Pi/Readme.md) |
| 2 | 🆓️ Control Orange Pi 4A GPIO from Node-RED (`node-red-contrib-opi-gpio`) | [Watch](https://youtu.be/ePs6oerTwyU) | |

---

## 🟩 GPIO

| S.No | Title | Links | Project |
|------|-------|-------|---------| 
| 1 | 🆓️ Control Orange Pi 4A GPIO with Python using WiringPi Library | [Watch](https://youtu.be/BK9-z6sEGoQ) · [GitHub](https://github.com/papercodeIN/Embedded_Devices/blob/main/Orange%20Pi/installaion_wiringPi.md) | |

---

## 🟩 Application

| S.No | Title | Links | Project |
|------|-------|-------|---------| 
| 1 | ⏳️ Make WIFI to Ethernet Bridge using Orange Pi 4A (NAT Method) | [Watch] | | 

---

## 📌 Orange Pi 4A Pinout

```
root@orangepi4a:~# gpio readall
+------+-----+----------+--------+---+ OPI 4A +---+--------+----------+-----+------+
| GPIO | wPi |   Name   |  Mode  | V | Physical | V |  Mode  | Name     | wPi | GPIO |
+------+-----+----------+--------+---+----++----+---+--------+----------+-----+------+
|      |     |   3.3V   |        |   |  1 || 2  |   |        | 5V       |     |      |
|  257 |   0 |   SDA.4  |    OFF | 0 |  3 || 4  |   |        | 5V       |     |      |
|  256 |   1 |   SCL.4  |    OFF | 0 |  5 || 6  |   |        | GND      |     |      |
|   36 |   2 |   PWM8   |    OUT | 0 |  7 || 8  | 0 |    OFF | TXD.7    |   3 |   45 |
|      |     |    GND   |        |   |  9 || 10 | 0 |    OFF | RXD.7    |   4 |   46 |
|   32 |   5 |   TXD.2  |    OFF | 0 | 11 || 12 | 0 |    OFF | PB05     |   6 |   37 |
|   33 |   7 |   RXD.2  |    OFF | 0 | 13 || 14 |   |        | GND      |     |      |
|   34 |   8 |   PB02   |    OFF | 0 | 15 || 16 | 0 |    OFF | PI13     |   9 |  269 |
|      |     |   3.3V   |        |   | 17 || 18 | 0 |    OFF | PI14     |  10 |  270 |
|  260 |  11 |  MOSI.1  |    OFF | 0 | 19 || 20 |   |        | GND      |     |      |
|  261 |  12 |  MISO.1  |    OFF | 0 | 21 || 22 | 0 |    OFF | TXD.6    |  13 |  262 |
|  259 |  14 |  SCLK.1  |    OFF | 0 | 23 || 24 | 0 |    OFF | CE.1     |  15 |  258 |
|      |     |    GND   |        |   | 25 || 26 | 0 |    OFF | RXD.6    |  16 |  263 |
|  265 |  17 |   SDA.5  |    OFF | 0 | 27 || 28 | 0 |    OFF | SCL.5    |  18 |  264 |
|   35 |  19 |   PB03   |    OFF | 0 | 29 || 30 |   |        | GND      |     |      |
|   43 |  20 |   PB11   |    OFF | 0 | 31 || 32 | 0 |    OFF | PWM12    |  21 |  267 |
|  268 |  22 |  PWM13   |    OFF | 0 | 33 || 34 |   |        | GND      |     |      |
|   38 |  23 |   PB06   |    OFF | 0 | 35 || 36 | 0 |    OFF | PI10     |  24 |  266 |
|   44 |  25 |   PB12   |    OFF | 0 | 37 || 38 | 0 |    OFF | PB07     |  26 |   39 |
|      |     |    GND   |        |   | 39 || 40 | 0 |    OFF | PB08     |  27 |   40 |
+------+-----+----------+--------+---+----++----+---+--------+----------+-----+------+
| GPIO | wPi |   Name   |  Mode  | V | Physical | V |  Mode  | Name     | wPi | GPIO |
+------+-----+----------+--------+---+ OPI 4A +---+--------+----------+-----+------+
```

---

## 📢 Reach Out to Us for Any Queries

| 📞 Contact Method | 🔗 Details |
|-------------------|-----------|
| Call / WhatsApp | +91-9974477759 |
| Telegram | [@fusionautomate](https://t.me/fusionautomate) |
| Email | eng.innovativ@gmail.com |

