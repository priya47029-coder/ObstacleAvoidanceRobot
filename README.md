# 🤖 Obstacle Avoidance Robot Using Ultrasonic Sensor

### CodeOrbit Tech – Robotics & Automation Internship | Task 2

## 📌 Project Overview

This project demonstrates a sensor-based obstacle avoidance robot using Arduino Uno and an HC-SR04 ultrasonic sensor.

The robot detects nearby obstacles by measuring the distance using ultrasonic waves. Based on the sensor readings, the Arduino processes the information and decides whether the robot should move forward or stop and turn right.

The project is simulated using the Wokwi online simulator without requiring physical hardware.

## 🎯 Objective

To design and simulate a robotic system that detects obstacles using sensor inputs and performs automatic actions based on predefined logical conditions.

## 🛠️ Components Used

- Arduino Uno
- HC-SR04 Ultrasonic Sensor

## ⚙️ Working Principle

1. The ultrasonic sensor measures the distance to nearby objects.
2. Arduino receives the sensor reading.
3. The measured distance is compared with a threshold of 20 cm.
4. If the distance is greater than 20 cm, the robot moves forward.
5. If the distance is 20 cm or less, the robot stops and turns right.
6. The process repeats continuously.

## 💻 Technologies Used

- Arduino Programming (C++)
- Wokwi Simulator
- Ultrasonic Sensor Technology

## 📊 Expected Output

| Distance | Robot Action |
|---|---|
| 50 cm | Move Forward |
| 35 cm | Move Forward |
| 20 cm | Stop and Turn Right |
| 15 cm | Stop and Turn Right |
| 5 cm | Stop and Turn Right |

## 🌟 Features

- Obstacle detection using ultrasonic sensors.
- Automatic decision-making using conditional statements.
- Real-time distance measurement in simulation.
- Beginner-friendly robotics project.
- No physical hardware required for simulation.

## 🚀 Applications

- Autonomous robots
- Smart vacuum cleaners
- Industrial automation
- Robotic navigation systems

## 🔬 Simulation

The project is simulated using Wokwi.

**Wokwi Project Link:** Add your project URL here.

## 📁 Project Structure

```text
CodeOrbit_ObstacleAvoidanceRobot/
│
├── sketch.ino
├── README.md
└── Screenshots/
    ├── circuit.png
    ├── forward.png
    └── obstacle_detected.png
```

## 📝 Conclusion

This project demonstrates how ultrasonic sensors and Arduino programming can be combined to develop a basic obstacle avoidance system. It provides practical knowledge of sensor inputs, conditional logic, and robotic decision-making.

## 👩‍💻 Internship

Completed as part of the Robotics & Automation Internship at CodeOrbit Tech.

**Task:** Task 2 – Sensor-Based Logic Simulation
