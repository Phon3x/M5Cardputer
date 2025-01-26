# M5Stack Cardputer Modular Expander

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?logo=telegram&logoColor=white)](https://t.me/myinforaw)
<a href="https://github.com/Phon3x/M5Cardputer/blob/main/LICENSE">
  <img src="https://img.shields.io/badge/license-MIT-_red.svg">
</a>

<div align="center">
  <img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_1.png?raw=true" style="border-radius:28px;" alt="M5Stack Cardputer Modular Expander" />
  <p><em>M5Stack Cardputer with installed modular expander</em></p>
</div>

---

<details>
<summary>📷 Top view</summary>
<div align="center">
  <img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_2.png?raw=true" alt="Top">
</div>
</details>
<details>
<summary>📷 Side view</summary>
<div align="center">
  <img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_3.png?raw=true" alt="Side">
</div>
</details>
<details>
<summary>📷 Bottom view</summary>
<div align="center">
  <img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_4.png?raw=true" alt="Bottom">
</div>
</details>

---

## 📝 Project Description

The M5Stack Cardputer Modular Expander is an extension board designed to enhance the capabilities of the M5Stack Cardputer. This expander provides you oportunity to add add additional modules: WIFI external antenna, CC1101, IR Transmitter while maintaining the compact form factor of the original device.

## 📋 Table of Contents

- [Features](#features)
- [Components](#components)
- [Pin Connections](#pin-connections)
- [Assembly Instructions](#assembly-instructions)
- [3D Printing Guide](#3d-printing-guide)
- [Files](#Files)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- Wifi extended antenna
- CC1101
- IR transmitter

## 🔧 Components

### Required Hardware

| Component | Quantity | Notes |
|-----------|----------|--------|
| Ipex to sma male | 1 | For WIFI Antenna |
| 2.4-GHZ sma External WIFI Antenna | 1 | Antenna |
| CC1101 433MHz module | 1 | without soldered pins |
| DS-05 flat dial switch | 1 | 5 bit code switch 2.54mm |
| TSAL6400 5mm 940nm | 1 | IR transmitter led |
| LED Indicators | 2 |  5mm 5v, two different colors |

### Optional Components

| Component | Quantity | Notes |
|-----------|----------|--------|
| Protection Diodes | 2 | 1N4148 |
| Decoupling Capacitors | 4 | 0.1µF ceramic |

## 📊 Pin Connections

Below is the detailed pin connection diagram for the M5Stack Cardputer modular expander:

<div align="center">
  <img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/diagram.png?raw=true" alt="Pin Connection Diagram" />
  <p><em>Detailed pin connection scheme showing GPIO, power, and communication lines</em></p>
</div>

---

> Note: The diagram shows the complete interconnection between the program buttons, CC1101 module, IR transmitter, and the Cardputer's main connection points.

---

## 🔨 Assembly Instructions

<details>
<summary>Step 1: Pulling pins from the main Cardputer board</summary>
<div align="center">
  <a href="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_5.png?raw=true"><img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_5.png?raw=true" alt="Pulling pins" width="38%"></a>
  <a href="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_6.png?raw=true"><img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_6.png?raw=true" alt="Pulling pins" width="38%"></a>
</div>
  
#### ⚠️ Required Advanced level of soldering skills!
> [!TIP]
> Note: *USE 30AWG silicon wires*! if you do not have special equipment or skills for this step, you can go on any mobile repair shop and ask them. (probably cost you 10$ or free.)

*Pinouts discovered by @PAZGUSTAVO*

</details>

<details>
<summary>Step 2: Prepare hole for WIFI antenna</summary>
<div align="center">
  <a href="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_13.png?raw=true"><img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_13.png?raw=true" alt="hole for WIFI antenna" width="48%"></a>
  <a href="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_8.png?raw=true"><img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_8.png?raw=true" alt="WIFI antenna wire" width="48%"></a>
</div>
> [!IMPORTANT]
> Note: You will need a 3 mm drill (depending on the thickness of the antenna cable). I do not recommend taking more than 3 mm!

</details>

<details>
<summary>Step 3: Soldering the antenna</summary>
<div align="center">
  <a href="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_9.png?raw=true"><img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_9.png?raw=true" alt="hole for WIFI antenna" width="88%"></a>
</div>
> [!IMPORTANT]
> Note: You have to cut integrated antenna, which is attached on M5StackS3.
</details>

<details>
<summary>Step 4: Bring the wires to the back panel</summary>
<div align="center">
  <a href="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_7.png?raw=true"><img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_7.png?raw=true" alt="back panel" width="88%"></a>
</div>
</details>

<details>
<summary>Step 5: Preparation CC1101</summary>
<div align="center">
  <a href="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_11.png?raw=true"><img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_11.png?raw=true" alt="CC1101" width="88%"></a>
</div>
</details>

<details>
<summary>Step 6: Placing components in the extender</summary>
<div align="center">
  <a href="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_12.png?raw=true"><img src="https://github.com/Phon3x/M5Cardputer/blob/main/assets/images/dev_12.png?raw=true" alt="components assembling" width="88%"></a>
</div>
> [!TIP]
> Note: *Picture from first assembling test* forget to take final version, it is much clear 😆
</details>

## 🖨️ 3D Printing Guide

### Case Specifications

### Printing Parameters

| Parameter | Value |
|-----------|--------|
| Material | PLA (I use) or PETG |
| Layer Height | 0.2mm |
| Infill | 50% |
| Perimeters | 1 |
| Fuzzy Skin | Outside walls |
| Fuzzy Shickness | 0.1 |
| Fuzzy Point | 0.5 |
| Orientation | Print flat side down |

### Post-Processing

1. Remove supports carefully
2. Clean up any stringing

## 📁 Files

| Name | Download URL |
|-----------|--------|
| Modular Expander **BODY** | [download **.stl**](https://github.com/) |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?logo=telegram&logoColor=white)](https://t.me/myinforaw)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Phon3x/M5Cardputer/blob/main/LICENSE) file for details.

---

<div align="center">
  <p>Made with ❤️ by Phon3x for M5Stack Community</p>
</div>
