# Sachin Salaskar | Mechanical Design & Testing Portfolio

Passionate Mechanical Engineer specializing in **Test Bench Design, Pneumatic Actuation, Mechanical Durability Testing (Fatigue), and SolidWorks CAD**.

📫 **Location:** Germany | **Focus:** Testing & Quality Engineering

---

## 🛠️ Core Engineering Competencies
* **Testing & Validation:** Accelerated Life Testing (ALT), Pneumatic Rig Design, Mechanical Fatigue & Durability Testing, FMEA, Data Acquisition (DAQ).
* **CAD & Prototyping:** SolidWorks (3D Assemblies, GD&T 2D Drawings, Exploded Views), Modular Aluminum Profiles (T-Slot), Rapid Prototyping.
* **Hardware & Lab:** Pneumatic Components (Compressors, Solenoids, Reservoirs), Force/Pressure Sensors, Workshop Measuring Tools.

---

## 🚀 Featured Engineering Projects

### 🚀 Automated Modular Pneumatic Reliability & Climatic Test System

> **Project Scope:** Designed and built a modular accelerated life testing (ALT) setup to qualify 20 medical pneumatic sub-assemblies (air compressors, molded reservoirs, solenoids) across a **simulated 5-year operational lifecycle (365,000 pressure cycles)** at $40^\circ\text{C}$.

---

### 🔧 Mechanical & Test Bench Architecture:
* **Chamber Envelope Optimization:** Designed a compact 10-UUT structural aluminum rack ($938 \times 688 \times 688\text{ mm}$) to maximize testing density within standard climatic chamber dimensions.
* **Parallel Dual-Chamber Execution:** Built and commissioned **two identical 10-unit test rigs across two thermal chambers** to evaluate the full $n=20$ statistical sample size simultaneously.
* **Pneumatic Loop & Closed-Loop Control:** Integrated automated $24\text{ V}$ power switching and solenoid manifolds to generate high-frequency cyclic pressure pulses (**$2600\text{ mbar} \leftrightarrow 2800\text{ mbar}$**).
* **Automated Data Acquisition (DAQ):** Programmed an Arduino-based DAQ system logging continuous pressure decay curves, cycle counts, and thermal stability.
* **Leakage Acceptance Criteria:** Enforced automated 60-second pressure decay measurements every 30 cycles to verify leak rates remained strictly below **$<3.4\text{ mbar/min}$ @ $2.8\text{ bar}$**.

---

### 📊 Key Technical Metrics:
* **Sample Size:** 20 UUTs total ($2\times$ 10-unit modular test rigs in parallel chambers)
* **Cyclic Endurance:** 365,000 pressure pulses per unit (simulating 5 years / 1,825 clinical treatments)
* **Test Conditions:** Continuous 45-day operation at $40^\circ\text{C}$ ambient temperature
* **Acceptance Benchmarks:** Pressurization time $<40\text{ sec}$ to $2800\text{ mbar}$, leak decay $<3.4\text{ mbar/min}$

---

### 2. X-Ray C-Arm Mechanical Durability & Structural Fatigue Testing
> **Objective:** Validated multi-axis structural integrity, joint wear, and counterbalance mechanisms of a heavy kinematic assembly under dynamic cyclic loads.

![C-Arm Test Setup](assets/c_arm_durability/test_setup.jpg)

#### 🔧 Technical Highlights:
* **Dynamic Cyclic Loading:** Subjected structural pivot points and joints to multi-axis mechanical duty cycles.
* **Deflection & Backlash Measurement:** Monitored joint play, mechanical backlash, and structural deflection using precision dial indicators and sensors.
* **Wear & Failure Analysis:** Identified structural stress concentration areas and provided root-cause analysis and design improvements to R&D engineers.

---

### 3. ANTLIA & Precision Mechanisms (Ergonomics & CAD)
* **Articulating Arm:** Designed a counterbalanced multi-axis positioning arm for medical instrumentation.
* **Complex Enclosure:** Modeled injection-molded housings in SolidWorks with rib structures, bosses, and snap-fit joints.
