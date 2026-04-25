# Sequential-Multi-Motor-Control-System-Schneider-PLC-


##  Project Overview

This project demonstrates a **sequential multi-motor control system** implemented using a Schneider PLC and tested on a real hardware board.

The system is designed to simulate an industrial process where multiple motors operate in a continuous loop with time-based sequencing.

Once the system starts, motors are activated one after another with fixed delays, creating a repeating cycle until the stop command is triggered.

---

##  Technology Stack

* PLC: Schneider PLC
* Programming Software: Schneider Task / EcoStruxure (based on setup)
* Control Type: Sequential Control (Time-Based Logic)
* Hardware: Real Electrical Control Board (Contactors, Relays, Timers)

---

##  System Workflow

The system follows a cyclic sequence:

1. Press **Start**
2. Motor 1 (M1) turns ON
3. After 5 seconds → Motor 2 (M2) turns ON
4. After 5 seconds → Motor 3 (M3) turns ON
5. After 5 seconds → Cycle repeats:

   * Motor 1 turns ON again
   * Then Motor 2
   * Then Motor 3
6. The loop continues indefinitely

 Press **Stop** at any time → All motors stop immediately

---

##  Control Logic Explanation

* The system is designed using **sequential timing logic**
* Each motor is activated based on a **5-second delay**
* The logic behaves like a **cyclic state machine**
* Timers are used to:

  * Control transition between motors
  * Maintain consistent operation timing
* The loop structure ensures continuous operation without manual restart

---

##  Technical Highlights

* Sequential Motor Control using PLC
* Time-Based Automation Logic
* Continuous Loop Operation
* Real Hardware Implementation (not simulation only)
* Integration of PLC with Contactors & Relays
* Industrial-style control strategy

---

##  Project Implementation

* Designed and tested using Schneider PLC software
* Logic verified through simulation
* Implemented on a real control board
* Motors controlled via contactors with proper wiring

---

##  How to Run

1. Power ON the system
2. Press **Start**
3. Observe sequential motor operation (M1 → M2 → M3)
4. System continues automatically
5. Press **Stop** to terminate operation

---

##  Future Improvements

* Add HMI interface for monitoring and control
* Add fault detection system (overload / failure)
* Implement speed control using VFD
* Add manual/auto operation modes

---

##  Demo

*(./vedio.mp4)*

---

##  Files Included

* PLC Program File (Schneider)
* Demo Video (Real Hardware Operation)

---

##  Notes

This project demonstrates practical understanding of:

* PLC programming
* Industrial control systems
* Sequential automation logic
* Real-world electrical implementation

---
