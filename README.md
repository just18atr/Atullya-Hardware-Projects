

# Elevator Control System in Verilog

This project implements a **4-floor Elevator Control System** using **Verilog HDL**, modeled as a **Moore Finite State Machine (FSM)**. The design replicates real-life elevator functionality, processing floor requests and moving between floors with clock-driven timing control.

---

## 🔑 Features

* **Moore FSM Design**

  * States represent each floor (Ground to 3rd) with well-defined transitions.
* **Request Handling**

  * Processes **`call`** (external) and **`go`** (internal) inputs.
* **Timing Control**

  * Floor transitions executed with a **100 ns controlled delay** on a **20 ns clock cycle**.
* **Simulation & Debugging**

  * Thoroughly tested and simulated in **Xilinx Vivado** to ensure robust and optimized performance.

---

## 🛠️ Technology & Tools

* **HDL**: Verilog
* **Design Style**: Moore Finite State Machine
* **Simulation**: Xilinx Vivado

---

## 📊 Results

* Verified correct operation across **4 floors**.
* Successfully handled **simultaneous `call` and `go` requests**.
* Achieved reliable floor transitions with controlled timing.

---

## 📂 Repository Structure

```
├── /rtl             # Verilog source files (FSM design)
├── /tb              # Testbenches for simulation
├── /docs            # State diagrams, reports, timing analysis
└── README.md        # Project description
```

---

## 🚀 Applications

* Demonstrating **Finite State Machine (FSM)** design in hardware.
* Modeling real-world **elevator systems** using HDL.
* Extendable to multi-floor elevators with advanced scheduling.

---


Do you want me to also include a **state transition diagram** (in text/ASCII or schematic style) so someone reading your repo immediately understands the floor logic?
