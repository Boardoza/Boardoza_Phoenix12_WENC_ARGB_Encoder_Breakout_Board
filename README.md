# Boardoza Phoenix-12WENC – Breakout Board

The **Boardoza Phoenix-12WENC Breakout Board** is a compact and versatile lighting control board featuring **12 addressable ARGB LEDs** combined with an integrated **rotary encoder interface**. It is designed to provide interactive and dynamic lighting effects while maintaining high compatibility with a wide range of digital systems.

This board is especially suitable for projects that require **visual feedback and user interaction**, such as control panels, UI knobs, decorative lighting, and embedded interfaces. With support for both **CMOS and TTL logic levels** and flexible **THT and SMD connection options**, the Phoenix-12WENC can be easily integrated into prototypes as well as final products.

## [Click here to purchase!](https://www.ozdisan.com/ureticiler/boardoza)
| Front Side | Back Side |
|:---:|:---:|
| ![Phoenix-12WENC Front](./assets/Phoenix-12WENC%20Front.png) | ![Phoenix-12WENC Back](./assets/Phoenix-12WENC%20Back.png) |

---

## Key Features

- **12 Addressable ARGB LEDs:** Equipped with 12 individually controllable ARGB LEDs (T3A33BRG-H9C0002X1U1930) for smooth and vibrant lighting effects.
- **Rotary Encoder Support:** Enables intuitive and real-time control of lighting modes, brightness, and effects through user interaction.
- **Flexible Signal Routing:** Provides DIN, CIN, DOUT, and COUT connections for easy daisy-chaining and signal continuity.
- **Dual Logic Compatibility:** Supports both CMOS and TTL logic levels, ensuring compatibility with a wide range of controllers and systems.
- **Multiple Connection Options:** Features both THT (Through-Hole) and SMD (Surface-Mount) pads for flexible assembly and design integration.
- **Designed for Interactive Applications:** Ideal for user interfaces, control panels, decorative lighting, and visual feedback systems.

---

## Technical Specifications

**Model:** Phoenix-12WENC    
**Manufacturer:** Boardoza  
**Functions:** Addressable RGB LED control with rotary encoder input  
**Input Voltage:** 3.3 V / 5 V  
**LED Model:** T3A33BRG-H9C0002X1U1930  
**Number of LEDs:** 12  
**LED Type:** Individually addressable RGB LEDs  
**Logic Compatibility:** TTL & CMOS  
**Data Interface:** Serial Data & Clock (DIN / CIN / DOUT / COUT)   
**Encoder Outputs:** Terminal A, Terminal B, Switch (Active Low)  
**Daisy-Chain Support:** Yes  
**Operating Temperature:** -40 °C to +85 °C  
**Board Dimensions:** 44.58 mm × 44.56 mm  

---

## Board Pinout

### ( J1 ) Data Output

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | DOUT | Series data output |

### ( J2 ) Clock Output

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | COUT | Clock output |

### ( J3 ) Data Input

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | DIN | Series data input |

### ( J4 ) Clock Input

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | CIN | Clock input |

### ( J5 ) Ground

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | GND | Ground |

### ( J6 ) Ground

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | GND | Ground |

### ( J7 ) Power

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | VCC | Power supply (3.3V / 5V) |

### ( J8 ) Power

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | VCC | Power supply (3.3V / 5V) |

### ( J9 ) Encoder Output B

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | Terminal_B | Encoder Channel B Output |

### ( J10 ) Encoder Output A

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | Terminal_A | Encoder Channel A Output |

### ( J11 ) Encoder Switch

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | SW | Push Button Output (Active Low) |  

---

## Board Dimensions

<img src="./assets/Phoenix-12WENC Dimensions.png" alt="Phoenix-12WENC Board Dimensions" width="450"/>

---

## Step Files

[Boardoza Phoenix-12WENC.step](./assets/Phoenix-12WENC%20Step.step)

---

## Datasheets

[T3A33BRG ARGB LED Datasheet](./assets/Phoenix-12WENC%20Datasheet.pdf)  
[Rotary Encoder Datasheet](./assets/Rotary%20Encoder%20Datasheet.pdf)

---

## Version History

- **V1.0.0** – Initial Release

---

## Support

- For questions or technical support, please contact **support@boardoza.com**

---

## **License**

This repository contains both hardware and software components:

### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

### **Software/Firmware**

[![BSD-3-Clause][bsd-shield]][bsd]

All software and firmware are licensed under [BSD 3-Clause License][bsd].

[bsd]: https://opensource.org/licenses/BSD-3-Clause
[bsd-shield]: https://img.shields.io/badge/License-BSD%203--Clause-blue.svg
