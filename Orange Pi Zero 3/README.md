<h1 align = "center">🌟Orange Pi Zero 3🌟</h1>
 
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

$\color{Green}\Huge{\textbf{Shorts}}$

1. 🆓️Unboxing Orange Pi Zero 3 | Palm Size Single Board Computer | 2GB | Allwinner H618 | OPI Zero 3 | [[Watch]](https://youtube.com/shorts/G46ZkNLde34?feature=share)
2. 🆓️DIY Hacking Device using Kali Linux in Orange Pi Zero 3 | OPI Zero 3 | Hacking | KALI | [[Watch]](https://youtube.com/shorts/jPWgji2v1Qw)
3. 🆓️Unboxing Orange Pi Expansion Board | 2 * USB2.0 | IR | AV Output | MIC | OPI Zero 3 | [[Watch]](https://youtube.com/shorts/MRjCD9KQTc0?feature=share)
4. 🆓️3D Printed Bumper Case for Orange Pi Zero 3 | Just in 179₹ Including Delivery | [[Watch]](https://youtube.com/shorts/9xQMRs7rphY)
5. 🆓️DIY Android Tablet Using Orange Pi Zero 3 | Android V12 | OPI Zero 3 | [[Watch]](https://youtube.com/shorts/Fa5Tzl2T9QA)
6. 🆓️DIY Mini PC Using Orange Pi Zero 3 | Ubuntu Jammy XFCE Desktop Linux | OPI Zero 3 | [[Watch]](https://youtube.com/shorts/rGa9mu3wpWA)
7. 🆓️Running Raspberry Pi OS in Orange Pi Zero 3 | OPI Zero 3 | [[Watch]](https://youtube.com/shorts/Z3Uvr2xv_yw)
8. ⏳️Orange Pi Zero 3 | Palm Size Linux SBC | Orange Pi | Pi | Linux SBC | IoT | IIoT | Computer | [Watch]

##
$\color{Green}\Huge{\textbf{Getting Started Guide}}$

1. 🆓️Getting Started with Orange Pi Zero 3 | Flash Ubuntu Jammy Server Linux OS to SD Card | Configure USB Debugging | SSH Access | WIFI Setup | [[Watch]](https://youtu.be/TlGMebe5iKk)
2. 🆓️Getting Started with Orange Pi Zero 3 | Flash Ubuntu Noble Server Linux OS to SD Card | Configure USB Debugging | SSH Access | WIFI Setup | [[Watch]](https://youtu.be/GKmrhXmMzrA)
3. 🆓️Getting Started with Orange Pi Zero 3 | Flash Raspberry Pi Desktop OS to SD Card | HDMI Screen Integration | [[Watch]](https://youtu.be/RhtY68-wrAY)
4. 🆓️Getting Started with Orange Pi Zero 3 | Flash Kali Linux to SD Card | HDMI Screen Integration | [[Watch]](https://youtu.be/xh20xW42654)
5. 🆓️Getting Started with Orange Pi Zero 3 | Flash Android to SD Card | HDMI Screen Integration | [[Watch]](https://youtu.be/36terYso7kU)
6. 🆓️‼️Setting Up an Expansion Board and Integrating a USB Drive with the Orange Pi Zero 3 [[Watch]](https://youtu.be/UjJ0PBWEXmo) [[GitHub]](https://github.com/papercodeIN/Embedded_Devices/blob/main/Orange%20Pi/setting_up_expansion_board.md)

##
$\color{Green}\Huge{\textbf{Node-RED}}$
1. 🆓️How to Install Node-RED in Orange Pi Zero 3 | Node.js | IoT | IIoT | NPM | OPI 4A | SBC | Linux | [[Watch]](https://youtu.be/IWFY3cSRJ7w) [[GitHub]](https://github.com/papercodeIN/Embedded_Devices/blob/main/Orange%20Pi/Readme.md)
2. 🆓️How to Control Orange Pi Zero 3 GPIO with Node-RED using `node-red-contrib-opi-gpio` node | [[Watch]](https://youtu.be/zwXkFZIVF-Q)

##
$\color{Green}\Huge{\textbf{GPIO}}$
1. 🆓️How to Control Orange Pi Zero 3 GPIO with Python using WiringPi Library | OPI Zero 3 | WiringPi | [[Watch]](https://youtu.be/JtGLKRQjZCw) [[GitHub]](https://github.com/papercodeIN/Embedded_Devices/blob/main/Orange%20Pi/installaion_wiringPi.md)

---

# Orange Pi Zero 3 PinOut
```
root@orangepizero3:~# gpio readall
 +------+-----+----------+--------+---+   H616   +---+--------+----------+-----+------+
 | GPIO | wPi |   Name   |  Mode  | V | Physical | V |  Mode  | Name     | wPi | GPIO |
 +------+-----+----------+--------+---+----++----+---+--------+----------+-----+------+
 |      |     |     3.3V |        |   |  1 || 2  |   |        | 5V       |     |      |
 |  229 |   0 |    SDA.3 |    OFF | 0 |  3 || 4  |   |        | 5V       |     |      |
 |  228 |   1 |    SCL.3 |    OFF | 0 |  5 || 6  |   |        | GND      |     |      |
 |   73 |   2 |      PC9 |    OUT | 0 |  7 || 8  | 0 | OFF    | TXD.5    | 3   | 226  |
 |      |     |      GND |        |   |  9 || 10 | 0 | OFF    | RXD.5    | 4   | 227  |
 |   70 |   5 |      PC6 |   ALT5 | 0 | 11 || 12 | 0 | OFF    | PC11     | 6   | 75   |
 |   69 |   7 |      PC5 |   ALT5 | 0 | 13 || 14 |   |        | GND      |     |      |
 |   72 |   8 |      PC8 |    OFF | 0 | 15 || 16 | 0 | OFF    | PC15     | 9   | 79   |
 |      |     |     3.3V |        |   | 17 || 18 | 0 | OFF    | PC14     | 10  | 78   |
 |  231 |  11 |   MOSI.1 |    OFF | 0 | 19 || 20 |   |        | GND      |     |      |
 |  232 |  12 |   MISO.1 |    OFF | 0 | 21 || 22 | 0 | OFF    | PC7      | 13  | 71   |
 |  230 |  14 |   SCLK.1 |    OFF | 0 | 23 || 24 | 0 | OFF    | CE.1     | 15  | 233  |
 |      |     |      GND |        |   | 25 || 26 | 0 | OFF    | PC10     | 16  | 74   |
 |   65 |  17 |      PC1 |    OFF | 0 | 27 || 28 | 0 | ALT2   | PWM3     | 21  | 224  |
 |  272 |  18 |     PI16 |   ALT2 | 0 | 29 || 30 | 0 | ALT2   | PWM4     | 22  | 225  |
 |  262 |  19 |      PI6 |    OFF | 0 | 31 || 32 |   |        |          |     |      |
 |  234 |  20 |     PH10 |   ALT3 | 0 | 33 || 34 |   |        |          |     |      |
 +------+-----+----------+--------+---+----++----+---+--------+----------+-----+------+
 | GPIO | wPi |   Name   |  Mode  | V | Physical | V |  Mode  | Name     | wPi | GPIO |
 +------+-----+----------+--------+---+   H616   +---+--------+----------+-----+------+
```

---


<h1 align="center">📢 Reach Out to Us for Any Queries ⤵️</h1>

<table align="center">
  <thead>
    <tr>
      <th>📞 Contact Method</th>
      <th>🔗 Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Call / WhatsApp</td>
      <td><a href="https://wa.me/919974477759">+91-9974477759</a></td>
    </tr>
    <tr>
      <td>Telegram</td>
      <td><a href="https://t.me/fusionautomate">@fusionautomate</a></td>
    </tr>
    <tr>
      <td>Email</td>
      <td><a href="mailto:eng.innovativ@gmail.com">eng.innovativ@gmail.com</a></td>
    </tr>
  </tbody>
</table>

---