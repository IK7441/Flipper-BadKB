# 🐬 Flipper-BadKB

[![Flipper Zero](https://shields.io)](https://flipperzero.one)
[![Language](https://shields.io)](#)

A collection of **BadUSB** and **BadBLT** (Bad Bluetooth) scripts for Flipper Zero devices. All payloads are written using **DuckyScript** syntax and optimized for automation tasks and security concepts demonstration.

---

## 📂 Repository Contents

* 🌐 **Browser Scripts** — Automated browser launch and specific URL navigation (e.g., fast web navigation templates).
* ⚙️ **System Utilities** — Automation scripts designed for Windows/Linux OS configuration.
* 🛡️ **Templates** — Clean boilerplate files and command examples to build your own payloads.

---

## 🚀 How to Use

To deploy any script on your Flipper Zero, follow these steps:

1. **Download** the desired `.txt` file from this repository.
2. Connect your Flipper Zero microSD card to your computer (or use the qFlipper app).
3. Move the downloaded files to the appropriate directory:
   * For wired BadUSB: `SD Card/badusb/`
   * For wireless BadBLT: `SD Card/badblt/` *(depending on your custom firmware)*.
4. Open your Flipper Zero menu, navigate to **BadUSB**, select your file, and press **Run**.

---

## ⚠️ Important Considerations

> [!IMPORTANT]
> **Keyboard Layout Sensitivity:** 
> DuckyScript payloads strictly emulate physical keystrokes. If the payload is written in English, the target computer **must have the English keyboard layout active** before execution. Otherwise, characters will be entered incorrectly.

> [!TIP]
> **Adjusting Delays (DELAY):** 
> If the target machine runs slowly or lags, commands might fire before the OS is ready. If a script fails to execute reliably, open the `.txt` file and increase the `DELAY` values (measured in milliseconds).

---

## 🤝 Contributing

Got an interesting script you want to share? Contributions are always welcome!
1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingScript`).
3. Commit your Changes (`git commit -m 'Add some AmazingScript'`).
4. Push to the Branch (`git push origin feature/AmazingScript`).
5. Open a Pull Request.

---

## 🛑 Disclaimer

This repository is created strictly for educational purposes, authorized penetration testing, and administrative workflow automation on your own devices. The author assumes no liability for any potential misuse or damage caused by these materials.
