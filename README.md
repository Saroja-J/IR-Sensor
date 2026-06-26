# 📡 IR Sensor using LM358 Comparator

A simple **Infrared (IR) Sensor** designed in **KiCad** using the **LM358 operational amplifier** as a comparator. The circuit detects nearby objects by transmitting infrared light and sensing its reflection. The received signal is compared with a reference voltage, and when an object is detected, the output changes state and the indicator LED turns ON. The detection sensitivity can be adjusted using a potentiometer, making the circuit suitable for applications such as obstacle detection, object counting, line-following robots, and automation projects.

---

## 📖 Overview

This project consists of an **IR LED** that continuously emits infrared light and a **photodiode** that receives the reflected IR light from nearby objects. The **LM358 Op-Amp** compares the photodiode's output with a reference voltage set by the potentiometer. If the reflected IR light is strong enough, the comparator output becomes HIGH, turning ON the output LED and providing a digital output signal. The adjustable potentiometer allows the sensing distance to be tuned according to the application.

---

## 📷 PCB Design

> Add the PCB layout image below.

![PCB Layout](pcb.png)

---

## ⚙️ How It Works

1. A **5V DC** supply powers the circuit.
2. The IR LED emits infrared light continuously.
3. When an object comes near, the IR light is reflected back to the photodiode.
4. The photodiode converts the reflected light into a voltage.
5. The LM358 compares this voltage with the reference voltage.
6. If the reflected signal exceeds the set threshold, the output goes HIGH and the LED turns ON.

---

## ✨ Features

- ✔️ Infrared object detection
- ✔️ Adjustable sensing sensitivity
- ✔️ LM358 used as a comparator
- ✔️ LED indication for object detection
- ✔️ Simple and low-cost design
- ✔️ Designed using KiCad

---

## 🛠️ Components

| Component | Description |
|-----------|-------------|
| LM358 Op-Amp | Compares the sensor signal with the reference voltage and generates the output. |
| IR LED | Emits infrared light for object detection. |
| Photodiode | Detects the reflected infrared light from nearby objects. |
| Potentiometer (RV1) | Adjusts the sensing sensitivity. |
| Resistors (R1, R2, R3) | Limit current and help set the operating conditions of the circuit. |
| LED | Indicates when an object is detected. |
| 5V DC Supply | Powers the entire circuit. |
| Output Connector | Provides the digital output signal. |

---

## 📄 License

This project is intended for **educational and learning purposes**.
```
