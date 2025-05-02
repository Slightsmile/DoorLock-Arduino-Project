# 🔐 Digital Door Lock using Arduino

This project demonstrates a secure and smart **digital door lock system** built using Arduino Nano. It utilizes a **4x4 keypad** for user input, an **LCD display** for real-time feedback, and a **servo motor** to physically lock or unlock the door. This system is ideal for basic home or office security projects.

---

## 📌 Features

- Password-protected door locking system
- Real-time LCD feedback
- Servo motor-based locking mechanism
- Easy hardware integration with Arduino Nano
- Prototype made using Styrofoam for demonstration

---

## 🧰 Components Used

| Component         | Description |
|------------------|-------------|
| Arduino Nano      | Main controller for processing input and controlling output |
| 4x4 Keypad Module | Used to enter the password |
| SG90 Servo Motor  | Acts as the door lock actuator |
| I2C 16x2 LCD      | Displays status messages to the user |
| Breadboard        | For assembling the circuit without soldering |
| Jumper Wires      | For electrical connections |
| Door Lock & Styrofoam | For creating a model prototype of the locking system |

---

## ⚙️ Working Principle

1. **Initialization**:
   - LCD displays: `WELCOME TO DOOR LOCK SYSTEM`
   - System is ready to receive input.

2. **Password Entry**:
   - User enters password via keypad.
   - LCD displays: `Enter Password` and shows the digits.

3. **Validation**:
   - If password is correct, servo motor rotates to unlock the door.
   - If incorrect, the lock remains engaged.

---

## 🔄 Workflow Summary

1. **Arduino Setup**:
   - Arduino Nano acts as the main controller.
2. **Hardware Connections**:
   - Keypad connected to D2-D9
   - Servo connected to D11
   - I2C LCD connected to A4 (SDA) and A5 (SCL)
3. **Code Upload**:
   - Use Arduino IDE to upload the code to the Nano.
4. **Enclosure Build**:
   - Components installed in a Styrofoam model for demonstration.

---

## 🛠️ How to Build

- Connect all components as described in the schematic.
- Power up the Arduino Nano.
- Upload the code.
- Input the password using the keypad.
- Watch the servo motor engage or remain static depending on correctness.

---

## 📘 Future Improvements

- Add buzzer alerts for wrong attempts.
- Enable dynamic password change via master mode.
- Integrate RFID or fingerprint scanner.
- Add IoT capabilities for remote monitoring.

---

## 📄 Project Report

A detailed project report is available in the attached [PDF file](Digital%20Lock%20with%20Binary%20Code%20Report.pdf), which includes:
- Component descriptions
- Circuit explanation
- Flowchart
- Working logic
- Conclusion

---

## 📬 Authors

- Project developed by a student team as part of a learning activity in Arduino-based security systems.

---

