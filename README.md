# 🚒 Autonomous Fire Fighting Robot

### 📌 Project Overview
Built a fully autonomous fire-detection and suppression rover using **Arduino (C++)**, multi-directional **IR Flame Sensors**, and an **L298N motor driver**. The robot continuously scans its environment for thermal signatures, navigates autonomously toward the hazard source, and actuates a servo-mounted water pump mechanism to extinguish the flame.

---

### ⚙️ Key Features & Control Logic
* **Multi-Zone Flame Detection:** Uses an array of IR Flame Sensors (Left, Center, Right) to triangulate fire direction and calculate approach vectors in real time.
* **Autonomous Navigation:** Decision-making firmware written in C++ drives differential-drive DC motors via an L298N H-Bridge driver to steer toward the heat source and halt at a safe extinguishing distance.
* **Automated Suppression Mechanism:** Coordinates a 3V submersible water pump with a sweeping servo nozzle to cover the target zone until thermal sensors confirm the flame is extinguished.

---

### 🛠️ Hardware & Tech Stack
* **Microcontroller & Language:** Arduino Uno, Embedded C++
* **Sensors:** 3-Channel IR Flame Sensor Array
* **Motor Control & Actuation:** L298N Dual H-Bridge Motor Driver, DC Gear Motors, SG90 Servo Motor, 3V Water Pump + Relay Module

---

### Demo 



https://github.com/user-attachments/assets/81ead5c4-243c-435a-8db2-126e422ed4d9





https://github.com/user-attachments/assets/b8691d5d-09d7-4859-b4cf-6c069557006d






