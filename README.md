# LED POV Holographic Display Fan

This repository contains source code, BOM(build of material), and assembly information on an **LED Holographic Display Fan**. 

---

## Hardware Bill of Materials (BOM)

The hardware components listed below are sourced from the project's tracking cart. All listed prices are in **Canadian Dollars (C$)**.

| # | Component Description | Undiscounted Price | Discounted Price |
|---|---|:---:|:---:|
| 1 | **[A2212 Brushless Motor (930KV/1000KV)](https://www.aliexpress.com/item/4000425121408.html)** <br> Provides the high RPM required to achieve the POV illusion. | C$ 8.41 | C$ 7.82 |
| 2 | **[30-125A XXD HW ESC Brushless Speed Controller](https://www.aliexpress.com/item/1005006945728088.html)** <br> Controls motor velocity safely via PWM signals. | C$ 7.37 | C$ 6.35 |
| 3 | **[GHPYQKC Hall Sensor Module](https://www.aliexpress.com/item/1005012941773160.html)** <br> Detects a passing magnet on each rotation to calculate exact RPM and index timing. | C$ 1.75 | C$ 1.71 |
| 4 | **[DC5V WS2812B LED Strip (1m / 144 LEDs, IP30)](https://www.aliexpress.com/item/1005007982624217.html)** <br> The dense light source array mounted to the fan blade. | C$ 10.38 | C$ 8.97 |
| 5 | **[Carbon Fiber Strip (1mm-18mm Dia. / 1x500mm)](https://www.aliexpress.com/item/1005005775627736.html)** <br> Serves as the ultra-lightweight, zero-flex structural spinning arm for the LEDs. | C$ 5.85 | C$ 2.85 |
| 6 | **[5x2mm N35 Strong Disc Neodymium Magnets](https://www.aliexpress.com/item/1005012734433854.html)** <br> Fixed to the spinning arm to trigger the Hall sensor once per full revolution. | C$ 12.05 | C$ 2.78 |
| 7 | **[ESP32-C3 SuperMini Development Board](https://www.aliexpress.com/item/1005012631245655.html)** <br> Ultra-compact Wi-Fi/BLE microcontroller that processes Hall sensor timing and drives the LED data signal. | C$ 4.49 | C$ 1.75 |
| - | **Total Component Cost** | **C$ 50.30** | **C$ 32.23** |

---

## Diagram

<img width="2155" height="1363" alt="1000035602" src="https://github.com/user-attachments/assets/f6bc6c10-013c-4644-8c61-b91d0b38f4d5" />
