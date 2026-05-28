# 2-Bit ALU Using Logisim & Digital Logic Design
Smart implementation of a **2-Bit Arithmetic Logic Unit (ALU)** using **Logisim**, logic gates, multiplexers, and hardware IC components.

---

# Room Security Style Overview

## 🚀 Project Highlights

* Designed a fully functional **2-Bit ALU**
* Supports both **Arithmetic** and **Logic** operations
* Implemented using:

  * Logisim simulation
  * Breadboard hardware testing
  * TTL IC components
* Built using real digital logic design concepts

---

# ⚡ Supported Operations

## Arithmetic Operations

* ➕ Addition (A + B)
* ➖ Subtraction (A - B)
* ⬆️ Increment (A + 1)
* ⬇️ Decrement (A - 1)

## Logic Operations

* 🔹 AND
* 🔹 OR
* 🔹 XOR
* 🔹 NOT

---

# 🧠 ALU Architecture

The ALU is divided into 3 main sections:

### Arithmetic Unit

Performs:

* Addition
* Subtraction
* Increment
* Decrement

Implemented using:

* Full Adders
* Multiplexers
* Two’s Complement

---

### Logic Unit

Performs bitwise logic operations using:

* AND gates
* OR gates
* XOR gates
* NOT gates

---

### Selection Unit

Multiplexers are used to select the required operation using:

* S0
* S1
* S2 control signals

---

# 🛠 Technologies Used

* Logisim
* Digital Logic Design
* Breadboard Hardware Implementation
* TTL ICs
* Boolean Algebra

---

# 🔌 IC Components Used

* 74LS83 → 4-Bit Adder
* 74LS08 → AND Gate
* 74LS32 → OR Gate
* 74LS86 → XOR Gate
* 74LS157 / 74LS153 → Multiplexers

---

# 📊 Control Signals Table

| S0 | S1 | S2 | Operation |
| -- | -- | -- | --------- |
| 0  | 0  | 0  | A + B     |
| 0  | 0  | 1  | A - B     |
| 0  | 1  | 0  | A + 1     |
| 0  | 1  | 1  | A - 1     |
| 1  | 0  | 0  | A AND B   |
| 1  | 0  | 1  | A OR B    |
| 1  | 1  | 0  | A XOR B   |
| 1  | 1  | 1  | NOT A     |

---

# 🧪 Simulation & Hardware Testing

The circuit was first simulated using **Logisim** to verify all operations and outputs.

After successful simulation, the ALU was physically implemented on a breadboard using TTL ICs and tested successfully.

# ⚠️ Challenges Faced

* Floating input issues
* Incorrect multiplexer connections
* Complex breadboard wiring
* Debugging signal outputs

These issues were solved through systematic testing and signal verification.

---

# 📚 Learning Outcomes

This project helped in understanding:

* ALU architecture
* Digital logic systems
* Multiplexer functionality
* Binary arithmetic
* Hardware debugging
* Logic circuit simulation

---

# ✅ Conclusion

This project successfully demonstrates the design and implementation of a functional 2-Bit ALU capable of performing multiple arithmetic and logic operations using digital logic components and multiplexers.

---

# 👨‍💻 Author

### Yehia Elborhamy

Electronics & Communications Engineering Student
