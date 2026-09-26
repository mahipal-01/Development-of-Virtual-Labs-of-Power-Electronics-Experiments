# ⚡ Development of Virtual Labs of Power Electronics Experiments

<p align="center">
  <b>An interactive virtual laboratory for learning, visualizing, and understanding Power Electronics experiments through simulation.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Power%20Electronics-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Virtual-Laboratory-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Simulation-Power%20Electronics-orange?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/mahipal-01/Development-of-Virtual-Labs-of-Power-Electronics-Experiments?style=for-the-badge">
</p>

---

## 📖 Overview

**Development of Virtual Labs of Power Electronics Experiments** is an educational project focused on developing a simulation-based virtual laboratory for studying fundamental **Power Electronics circuits and experiments**.

The project provides students with an environment to understand converter operation, observe electrical waveforms, perform theoretical calculations, and compare theoretical results with simulation results.

Virtual experimentation provides an accessible alternative to physical laboratory setups and allows students to repeatedly perform experiments while changing circuit parameters and observing their effects.

The project currently includes simulations and theoretical material related to:

- Single-phase half-wave rectifiers
- Single-phase full-wave rectifiers
- Three-phase half-wave rectifiers
- Power Electronics theory and fundamentals

---

## 🎯 Objectives

The main objectives of this project are:

- ⚡ Develop a virtual laboratory for Power Electronics experiments.
- 🔬 Provide simulation-based experimentation without requiring physical hardware.
- 📊 Visualize voltage and current waveforms.
- 🧮 Connect theoretical equations with simulation results.
- 🎓 Improve conceptual understanding of rectifier circuits.
- 🔄 Allow students to repeatedly perform experiments under different conditions.
- 💻 Provide an accessible learning environment for Power Electronics education.

---

# ⚡ Experiments

## 1. Single-Phase Half-Wave Rectifier

📁 **Directory:** `single phase Half wave simulation`

The single-phase half-wave rectifier is a fundamental AC-to-DC converter in which a diode allows only one half-cycle of the input AC waveform to reach the load.

### Key Concepts

- AC-to-DC conversion
- Diode conduction
- Half-wave rectification
- Input and output waveforms
- Average DC output voltage
- RMS output voltage
- Ripple
- Rectification efficiency
- Conduction interval

### Basic Operation

```text
       AC Supply
           │
           ▼
        ┌─────┐
        │Diode│
        └──┬──┘
           │
           ▼
        ┌─────┐
        │ Load│
        └──┬──┘
           │
           ▼
       DC Output
```

During the positive half-cycle, the diode conducts and supplies power to the load. During the negative half-cycle, the diode blocks the current.

---

## 2. Single-Phase Full-Wave Rectifier

📁 **Directory:** `single phase full wave simulation`

The single-phase full-wave rectifier utilizes both half-cycles of the AC supply to produce a unidirectional output.

### Key Concepts

- Full-wave rectification
- Diode conduction sequence
- Positive and negative half-cycles
- Output voltage waveform
- Average output voltage
- RMS output voltage
- Ripple frequency
- Rectification efficiency

### Basic Operation

```text
              AC Supply
                  │
                  ▼
          ┌───────────────┐
          │ Full-Wave     │
          │ Rectifier     │
          │               │
          │ D1 D2 D3 D4   │
          └───────┬───────┘
                  │
                  ▼
                Load
                  │
                  ▼
              DC Output
```

Unlike a half-wave rectifier, both halves of the input waveform contribute to the output.

---

## 3. Three-Phase Half-Wave Rectifier

📁 **Directory:** `3 phase half wave`

The three-phase half-wave rectifier demonstrates the conversion of three-phase AC power into DC power using semiconductor diodes.

### Key Concepts

- Three-phase AC systems
- Phase voltage relationships
- Diode conduction sequence
- Three-phase rectification
- Output voltage waveform
- Average DC output
- Ripple characteristics
- Comparison with single-phase rectifiers

### Basic Structure

```text
        Phase A ──────┐
                      │
        Phase B ──────┼────► Rectifier ────► DC Output
                      │
        Phase C ──────┘
```

The conducting diode changes according to the instantaneous phase voltage, resulting in a smoother DC output compared with a single-phase half-wave rectifier.

---

# 📚 Theory

📁 **Directory:** `theory`

The `theory` directory contains supporting material required to understand the Power Electronics experiments.

Important concepts include:

- Power semiconductor devices
- Diode operation
- Rectification
- AC-to-DC conversion
- Single-phase rectifiers
- Three-phase rectifiers
- Average output voltage
- RMS values
- Ripple
- Conduction angle
- Rectification efficiency
- Waveform analysis

The theory section should be studied before performing the corresponding simulation experiment.

---

# 🧪 Experiment Methodology

Each experiment follows a structured learning process:

```text
       ┌──────────────┐
       │    Theory    │
       └──────┬───────┘
              ↓
       ┌──────────────┐
       │Circuit Study │
       └──────┬───────┘
              ↓
       ┌──────────────┐
       │  Simulation  │
       └──────┬───────┘
              ↓
       ┌──────────────┐
       │   Waveforms  │
       └──────┬───────┘
              ↓
       ┌──────────────┐
       │  Calculation │
       └──────┬───────┘
              ↓
       ┌──────────────┐
       │   Analysis   │
       └──────────────┘
```

### Step 1 — Study the Theory

Understand the circuit topology, semiconductor operation, conduction sequence, and relevant mathematical equations.

### Step 2 — Analyze the Circuit

Identify:

- Input source
- Semiconductor devices
- Load
- Current path
- Expected output waveform

### Step 3 — Run the Simulation

Run the corresponding simulation contained in the experiment directory.

### Step 4 — Observe Waveforms

Analyze the input and output voltage/current waveforms and identify the conduction intervals.

### Step 5 — Perform Theoretical Calculations

Calculate quantities such as:

- Average output voltage
- RMS output voltage
- Ripple
- Efficiency

### Step 6 — Compare Results

Compare theoretical calculations with simulation results.

```text
       Theoretical
          Result
             │
             ↕
       Simulation
          Result
```

---

# 📊 Theory vs Simulation

A major purpose of the virtual laboratory is to help students connect mathematical analysis with actual converter behavior.

| Parameter | Theoretical Analysis | Simulation |
|---|---|---|
| Input voltage | Defined mathematically | Observed waveform |
| Output voltage | Calculated | Measured |
| Average DC voltage | Calculated | Obtained from waveform |
| RMS voltage | Calculated | Obtained from simulation |
| Ripple | Predicted | Observed |
| Conduction interval | Derived | Verified |
| Device operation | Based on theory | Observed through simulation |

This comparison helps identify the relationship between mathematical equations and practical converter operation.

---

# 🗂️ Repository Structure

```text
Development-of-Virtual-Labs-of-Power-Electronics-Experiments/
│
├── 📁 3 phase half wave/
│   └── Three-phase half-wave rectifier experiment
│
├── 📁 single phase Half wave simulation/
│   └── Single-phase half-wave rectifier simulation
│
├── 📁 single phase full wave simulation/
│   └── Single-phase full-wave rectifier simulation
│
├── 📁 theory/
│   └── Power Electronics theory and supporting material
│
└── 📄 README.md
```

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/mahipal-01/Development-of-Virtual-Labs-of-Power-Electronics-Experiments.git
```

Navigate to the project:

```bash
cd Development-of-Virtual-Labs-of-Power-Electronics-Experiments
```

Explore the available experiments:

```text
3 phase half wave/
single phase Half wave simulation/
single phase full wave simulation/
theory/
```

Open the required experiment and follow the simulation files and supporting theoretical material.

> **Note:** The exact software/environment required depends on the simulation files included in each experiment.

---

# 🧠 Learning Outcomes

After completing the experiments, students should be able to:

### Power Electronics Fundamentals

- Explain the purpose of rectifiers.
- Distinguish between half-wave and full-wave rectification.
- Understand diode conduction and blocking.
- Explain AC-to-DC conversion.

### Waveform Analysis

- Identify input and output voltage waveforms.
- Determine conduction intervals.
- Analyze output ripple.
- Relate waveform shape to semiconductor switching behavior.

### Mathematical Analysis

- Calculate average output voltage.
- Calculate RMS quantities.
- Analyze rectifier efficiency.
- Relate theoretical equations to simulation results.

### Converter Comparison

Compare rectifier configurations based on:

- Output characteristics
- Ripple
- Number of conducting devices
- Circuit complexity
- Power conversion characteristics

---

# 🏗️ Project Architecture

The project can be viewed as three interconnected learning layers:

```text
┌─────────────────────────────────────────────┐
│              📚 THEORY LAYER                │
│                                             │
│  Concepts • Equations • Circuit Operation   │
└──────────────────────┬──────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────┐
│             ⚡ SIMULATION LAYER              │
│                                             │
│  Rectifier Circuits • Switching • Waveforms │
└──────────────────────┬──────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────┐
│              📊 ANALYSIS LAYER              │
│                                             │
│  Measurements • Calculations • Comparison   │
└─────────────────────────────────────────────┘
```

This structure encourages students to move from:

**Concept → Implementation → Observation → Analysis**

---

# 🔮 Future Scope

The virtual laboratory can be extended with additional Power Electronics experiments and interactive learning features.

### Additional Rectifiers

- Single-phase bridge rectifier
- Three-phase full-wave bridge rectifier
- Controlled rectifiers
- Semi-controlled converters
- Fully controlled converters

### DC-DC Converters

- Buck converter
- Boost converter
- Buck-boost converter
- Cuk converter
- SEPIC converter
- Forward converter
- Flyback converter

### Inverters

- Single-phase half-bridge inverter
- Single-phase full-bridge inverter
- Three-phase inverter
- Square-wave inverter
- SPWM inverter
- Space Vector PWM

### Renewable Energy Applications

- Solar PV systems
- MPPT techniques
- DC-DC converters for PV systems
- Grid-connected inverters
- Battery energy storage converters

### Interactive Features

Future versions could include:

- Interactive parameter selection
- Automatic waveform plotting
- Real-time parameter variation
- Automatic theoretical calculations
- Simulation-result comparison
- Experiment quizzes
- Automated assessment
- Student performance tracking

---

# 🎓 Educational Applications

This project can be used as a supplementary learning resource for:

- Power Electronics
- Power Converters
- Electrical Engineering
- Renewable Energy Systems
- Industrial Electronics
- Electrical Drives
- Power Systems

It can also serve as a foundation for developing a larger **online/virtual Power Electronics laboratory**.

---

# 👨‍💻 Author

**Mahipal Meghwal**

Electrical Engineering  
Indian Institute of Technology Roorkee

GitHub: [mahipal-01](https://github.com/mahipal-01)

---

# 🤝 Contributing

Contributions and suggestions are welcome.

### Contribution Workflow

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature/new-experiment
```

3. Add or improve an experiment.
4. Commit your changes:

```bash
git commit -m "Add new Power Electronics experiment"
```

5. Push the branch:

```bash
git push origin feature/new-experiment
```

6. Open a Pull Request.

---

# 📜 License

If a specific open-source license is added to the repository, this section should be updated accordingly.

Please refer to the repository's licensing information before redistributing or modifying the project.

---

# ⭐ Support the Project

If you find this project useful for learning Power Electronics or developing virtual laboratories, consider giving the repository a ⭐ on GitHub.

<p align="center">
  <b>⚡ Learn • Simulate • Analyze • Understand ⚡</b>
</p>

<p align="center">
  <i>Making Power Electronics experimentation more accessible through virtual simulation.</i>
</p>
