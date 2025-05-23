# 🔧 Hardware Overview — Peat-GPS-Tracker

## 🧩 Main Components

Below is a list of the key components chosen for the project, along with a brief explanation of why they were selected:

### 1. **Microcontroller: ESP32**

- ✅ **Why chosen**: Powerful, energy-efficient, built-in Wi-Fi and Bluetooth, supports deep sleep, plenty of GPIO pins.
- 🛠 **Advantages**: Easy to flash via USB, large developer community, compatible with Arduino IDE and PlatformIO.

---

### 2. **GPS Module: _e.g., u-blox NEO-6M / A9G_**

- ✅ **Why chosen**: High positioning accuracy, affordable price.
- 📌 **Features**: UART interface, built-in antenna (or external depending on the model).

---

### 3. **Cellular Communication Module: 4G LTE (SIM7600, SIM800, A9G, etc.)**

- ✅ **Why chosen**: Supports modern cellular networks (2G is phasing out in Ukraine), stable data transmission, enables real-time GPS tracking.
- 🔌 **Note**: A9G is a combo module with GPS and GSM/4G in one.

---

### 4. **Power Supply**

- 🔋 **Battery**: 3.7V Li-Ion rechargeable (with charging via microUSB/TP4056).
- 🔌 **Why chosen**: Compact, rechargeable via Power Bank or solar panel.

---

## 📦 Other Hardware Elements

This section will include:

- Power management and charging board  
- Enclosure and component layout  
- Control buttons (if needed)  
- Status LEDs  

---

## ⚙️ Wiring Diagram

> A visual connection diagram  
> (KiCad / Fritzing / EasyEDA) will be added after the final component selection.

---

## 📌 Notes

- The project targets **low cost** and **small form factor**
- All components are selected with **3D-printable enclosure** in mind
- Final version should be a **compact GPS tracker for pets**

