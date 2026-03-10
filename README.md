EV DC Motor Powertrain Simulation (MATLAB Simulink)

Project Overview

This project demonstrates a basic electric vehicle (EV) motor drive system simulated using MATLAB Simulink and Simscape Electrical.

The model represents how electrical energy from a battery is converted into mechanical rotation through a DC motor. Mechanical elements such as inertia and friction are included to simulate real vehicle load conditions.

This simulation helps understand the fundamental behavior of EV powertrains.

---

System Components

The system consists of the following components:

- Battery – Provides DC electrical power.
- Current Sensor – Measures motor current.
- Half-Bridge Converter – Controls power flow from battery to motor.
- DC Motor – Converts electrical energy into mechanical rotation.
- Inertia Block – Represents vehicle mass / wheel inertia.
- Rotational Damper – Represents mechanical friction and air resistance.
- Ideal Rotational Motion Sensor – Measures motor angular velocity.
- Voltage Sensor – Measures voltage across the motor.

---

System Working Principle

1. The battery supplies DC voltage to the motor drive circuit.
2. The half-bridge converter controls how electrical energy is delivered to the motor.
3. The DC motor converts electrical energy into rotational motion.
4. Inertia and damping simulate vehicle load conditions such as weight and friction.
5. The motion sensor measures motor speed, which is displayed using a scope.

---

Simulation Output

The simulation demonstrates:

- Motor acceleration from 0 rad/s to approximately 82 rad/s
- Speed limitation due to vehicle load and friction
- Voltage and current behavior of the motor drive system

This behavior closely represents basic EV drivetrain dynamics.

---

Tools Used

- MATLAB
- Simulink
- Simscape Electrical

---

Learning Outcomes

Through this project, the following concepts are demonstrated:

- EV drivetrain modeling
- DC motor behavior under load
- Mechanical inertia and friction effects
- Electrical-to-mechanical energy conversion
- Sensor-based measurement in Simulink

---

Applications

This type of simulation is used in the development of electric vehicles such as:

- Electric cars
- Electric bikes
- Hybrid electric vehicles
- Motor drive systems

---
Author

IMMANUVEL M
Mechatronics Engineering Student
Interest: Electric Vehicles, Motor Control, Powertrain
