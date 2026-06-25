# 🔄 Forward Reverse Star Delta Motor Starter Simulation

## 📖 Project Overview

This project demonstrates the implementation of a **Forward-Reverse Star-Delta Motor Starter** using **Automation Studio**. The simulation is designed to control the starting, stopping, and direction reversal of a three-phase induction motor while minimizing starting current through a star-delta transition mechanism.

The project replicates industrial motor control systems commonly used in manufacturing plants, pumping stations, HVAC systems, conveyor systems, and heavy-duty motor applications.

---

## 🎯 Objectives

- Reduce motor starting current using the Star-Delta starting method.
- Enable Forward and Reverse motor operation.
- Implement electrical and mechanical interlocking for safety.
- Simulate real-world industrial motor control logic.
- Improve understanding of industrial motor starter circuits.

---

## ⚙️ Working Principle

### Forward Operation

1. Press the Forward Start Push Button.
2. Forward Contactor energizes.
3. Motor starts in Star configuration.
4. Timer begins counting.
5. Star Contactor de-energizes after preset delay.
6. Delta Contactor energizes.
7. Motor continues running in Forward direction.

### Reverse Operation

1. Press the Reverse Start Push Button.
2. Reverse Contactor energizes.
3. Motor starts in Star configuration.
4. Timer begins counting.
5. Star Contactor de-energizes after preset delay.
6. Delta Contactor energizes.
7. Motor continues running in Reverse direction.

---

## 🛡️ Safety Features

- Electrical Interlocking
- Mechanical Interlocking
- Forward-Reverse Protection
- Star-Delta Transition Delay
- Overload Protection
- Emergency Stop Function

---

## 🔧 Components Used

| Component | Purpose |
|------------|------------|
| MCB | Circuit Protection |
| Contactor | Motor Switching |
| Timer Relay | Star-Delta Transition |
| Overload Relay | Motor Protection |
| Push Buttons | Start/Stop Control |
| Indicator Lamps | Status Indication |
| Three-Phase Induction Motor | Load |

---

## 🏭 Industrial Applications

- Conveyor Systems
- Industrial Blowers
- Water Pumping Stations
- HVAC Systems
- Industrial Fans
- Compressors
- Manufacturing Plants

---

## 💻 Software Used

- Automation Studio
- Electrical Control Circuit Design
- Motor Control Simulation

---

## 📂 Project Structure

```text
Forward-Reverse-Star-Delta/
│
├── Simulation File (.ast)
├── Power Circuit Diagram
├── Control Circuit Diagram
├── Screenshots
├── Documentation
└── README.md
```

---

## 📸 Simulation Preview

Add your screenshots here.

### Power Circuit

![Power Circuit](images/power-circuit.png)

### Control Circuit

![Control Circuit](images/control-circuit.png)

### Simulation Running

![Simulation](images/simulation-running.png)

---

## 📚 Key Learning Outcomes

- Industrial Motor Control
- Star-Delta Starter Design
- Forward-Reverse Interlocking
- Electrical Protection Systems
- Motor Starting Methods
- Industrial Automation Fundamentals

---

## 🚀 Future Improvements

- PLC-Based Control Logic
- HMI Integration
- SCADA Monitoring
- VFD-Based Motor Control
- Fault Detection and Alarm System
- Industrial Network Communication

---

## 👨‍💻 Author

**Muntakim Mizan Rihan**

Electrical Engineering | Industrial Automation | Control Systems

---

## 🏷️ Topics

`industrial-automation` `automation-studio` `electrical-engineering`
`motor-control` `star-delta-starter` `forward-reverse`
`industrial-control` `three-phase-motor`
`electrical-design` `control-systems`
