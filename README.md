# Arduino 4 Servo Motors Control using Tinkercad

## Project Overview

This project demonstrates how to control **four servo motors** using an **Arduino Uno** in **Tinkercad Circuits**. The project was created to practice programming multiple servo motors and simulating an Arduino circuit.

The program controls four servo motors simultaneously. First, all servos perform a sweep movement from **0° to 180°** and then back to **0°**. After completing the sweep, all servo motors move to **90°** and remain in that position.

---

## Project Objectives

- Simulate an Arduino circuit using Tinkercad.
- Control four servo motors simultaneously.
- Practice programming servo motors using the Arduino Servo library.
- Understand servo movement and angle control.

---

## Hardware Components

- Arduino Uno
- 4 × SG90 Servo Motors
- Jumper Wires

---

## Software Used

- Tinkercad Circuits
- Arduino Servo Library

---

## How the Program Works

The program uses the **Servo** library to control four servo motors simultaneously.

- Four servo objects are created.
- Each servo is attached to a different Arduino PWM pin (3, 5, 6, and 9).
- The servos rotate together from **0° to 180°**.
- They then return from **180° to 0°**.
- Finally, all servos move to **90°** and remain in that position.
- Since the code is inside the `setup()` function, the sequence runs only once.

---

## Project Media

### Tinkercad Circuit

![Tinkercad Circuit](Servo%20Motors%20Control.png)

---

## Demonstration Video

Project demonstration:

[Click here to watch the project demonstration video](Servo%20Motors%20Control%20Test1.mp4)

---

## Project Files

- `servo_motors_control1 (1).ino`
- `README.md`
- `Servo Motors Control.brd`
- `Servo Motors Control.png`
- `Servo Motors Control Test1.mp4`

---

## Skills and Experience Gained

Through this project, I learned how to:

- Build and simulate Arduino circuits using Tinkercad.
- Control multiple servo motors simultaneously.
- Use the Arduino Servo library.
- Connect servo motors to Arduino PWM pins.
- Program synchronized servo motor movements.
- Test Arduino projects in a virtual environment before implementing them on real hardware.

---

