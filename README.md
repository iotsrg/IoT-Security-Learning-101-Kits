# IoT Security 101 Kits

This document provides tiered hardware kit recommendations for IoT and hardware security beginners, intermediates, and advanced hackers ( not too adavce).  

---

## 🔹 Basic Kit (~$110) – Absolute Beginners  
*No oscilloscope, minimal tools, focus on learning protocols & firmware*  

| Component             | Description                                            | Approx. Price (USD) | Buy Link |
|-----------------------|--------------------------------------------------------|----------------------|----------|
| BTD400                | Bluetooth Adapter (for pentesting Bluetooth)           | $15 | [Buy Here](https://www.kinivo.com/products/kinivo-btd-400-bluetooth-4-0-usb-adapter-for-windows-10-8-7-vista) |
| NRF52840              | BLE 5.0 Dongle, Zigbee, Thread pentesting purpose      | $20 | [Buy Here](https://in.element14.com/nordic-semiconductor/nrf52840-dongle/bluetooth-module-v5-2mbps/dp/2902521) |
| BusPirate / FT232H    | Hardware Debugger (I2C, SPI, UART, JTAG)               | $25 | [Buy Here](https://www.adafruit.com/product/2264) |
| Logic Analyzer 8 Pin  | Protocol analyzer (UART, SPI, I²C, etc.)               | $10 | [Buy Here](https://www.tanotis.com/products/sparkfun-usb-logic-analyzer-24mhz-8-channel?_pos=2&_sid=6a022df94&_ss=r) |
| STLink v2             | SWD Pin Connector                                       | $10 | [Buy Here](https://amzn.to/3uXm8hI) |
| ESP32                 | MCU for WiFi/Bluetooth testing                         | $10 | [Buy Here](https://amzn.to/33RSRZW) |
| RPi Zero              | MCU - good for USB attacks (with adapter)              | $15 | [Buy Here](https://amzn.to/3hyDBcK) |

**Total ~ $110**  

---

## 🔹 Intermediate Kit (~$200) – Expanding Skills  
*Adds electrical debugging with multimeter + lowest-cost oscilloscope (Hantek 6022BE)*  

| Component             | Description                                            | Approx. Price (USD) | Buy Link |
|-----------------------|--------------------------------------------------------|----------------------|----------|
| Basic Kit Components  | Includes all items from **Basic Kit**                  | $110 | - |
| Digital Multimeter    | Measure voltage, resistance, continuity                 | $45 | [Buy Here](https://www.fluke.com/en/product/electrical-testing/digital-multimeters/fluke-101) |
| Hantek 6022BE         | USB oscilloscope (cheap, hacker-approved)              | $70 | [Buy Here](https://amzn.to/3EzzXYi) |

**Total ~ $200–225**  

---

## 🔹 Advanced Kit (~$400+) – Pro Hardware Hacking  
*For serious research: adds professional oscilloscope + microprobing setup*  

| Component             | Description                                            | Approx. Price (USD) | Buy Link |
|-----------------------|--------------------------------------------------------|----------------------|----------|
| Intermediate Kit      | Includes all items from **Intermediate Kit**           | $200+ | - |
| Rigol DS1054Z         | 4-channel oscilloscope, hackable to 100MHz             | $350 | [Buy Here](https://amzn.to/3yAzsFl) |
| ICE-Bite              | Microprobing for embedded security research            | Open-source (DIY cost varies) | [Check Here](https://github.com/IoTSecurity101/ICEBite) |

**Total ~ $400–600+**  

---

## ⚡ Notes  
- Prices are approximate and vary by region/vendor.  
- Beginners should start with the **Basic Kit** and only upgrade once they’re comfortable.  
- Intermediate/Advanced kits provide tools for deeper analysis, fault injection, and side-channel research.  
