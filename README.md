#  Arduino 4 Servo Motors Control using Tinkercad

##  Project Overview

This project demonstrates how to control **four servo motors** using an **Arduino Uno** in **Tinkercad Circuits**. The project was created to practice programming multiple servo motors and simulating an Arduino circuit.

The program controls four servo motors simultaneously. First, all servos perform a sweep movement from **0° to 180°** and then back to **0°**. After completing the sweep, all servo motors move to **90°** and remain in that position.

---

##  Project Objectives

- Simulate an Arduino circuit using Tinkercad.
- Control four servo motors simultaneously.
- Practice programming servo motors using the Arduino Servo library.
- Understand servo movement and angle control.

---

##  Hardware Components

- Arduino Uno
- 4 × SG90 Servo Motors
- Jumper Wires

---

##  Software Used

- Tinkercad Circuits
- Arduino Servo Library

---

##  How the Program Works

The program performs the following steps:

1. Four servo motors are attached to Arduino digital pins **3, 5, 6, and 9**.
2. All servo motors rotate together from **0° to 180°**.
3. The motors then rotate back from **180° to 0°**.
4. Finally, all servo motors move to **90°** and remain in that position.
5. The sequence runs only once because it is written inside the `setup()` function.

---

##  Project Images

### Tinkercad Circuit

```md
![Tinkercad Circuit](images/connection.png)
```

---

##  Demonstration Video

Project demonstration:

*Add your video here.*

---

##  Project Files

- `Arduino_4_Servo_Control.ino`
- `README.md`
- Circuit Diagram
- Demonstration Video

---

##  Skills and Experience Gained

Through this project, I learned how to:

- Build and simulate Arduino circuits using Tinkercad.
- Control multiple servo motors simultaneously.
- Use the Arduino Servo library.
- Connect servo motors to Arduino PWM pins.
- Program synchronized servo motor movements.
- Test Arduino projects in a virtual environment before implementing them on real hardware.

---

## Conclusion

This project demonstrates the control of four servo motors using an Arduino Uno in Tinkercad. The motors perform a synchronized sweep movement before returning to a fixed position at **90°**. The project improved my understanding of Arduino programming, servo motor control, and circuit simulation using Tinkercad.
