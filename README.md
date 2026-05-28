# 🌌 SpaceFlow

> *Fluids are everywhere—from a gentle breeze to the violent heat of a spacecraft's re-entry.*
> *The Navier-Stokes equations describe them all, yet they remain one of the greatest unsolved mysteries in mathematics.*
> *SpaceFlow is where this mathematical beauty is captured into a digital grid.*

<br/>

![Python](https://img.shields.io/badge/Python-3.14-3776AB?logo=python&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-Testing-0A9EDC?logo=pytest&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-Planned-3178C6?logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-WASM-00599C?logo=c%2B%2B&logoColor=white)
![WebGL](https://img.shields.io/badge/WebGL-Render-990000?logo=webgl&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue)

<br/>

## 📖 The Soul of the Project

This project is not just another web application. 

While many engineers focus on building standard interfaces, the most complex and beautiful challenges lie in translating the physical laws of our universe into code. **SpaceFlow is an experimental fluid dynamics simulation engine** designed to calculate and visualize the aerodynamic flow and heat diffusion during a spacecraft's re-entry.

By discretizing the Navier-Stokes equations into a grid-based system, this project bridges the gap between pure mathematical theory and real-time computational physics. It serves as a sister project to the `pale-blue-code` universe—bringing the mechanics of space travel down to the granular level of code.

<br/>

## ✨ What is Being Built

| Feature | Description |
|---|---|
| 💨 **2D Density Diffusion** | Simulating the spread of heat and gas using grid discretization. |
| 🌊 **Navier-Stokes Solver** | Core engine computing Advection, Diffusion, and Projection. |
| 🚀 **Re-entry Boundaries** | Simulating fluid behavior around a solid spacecraft hull. |
| 📊 **Real-time Visualization** | WebGL/Canvas rendering of the fluid velocity and pressure fields. |
| ⚡ **WASM Acceleration** | Porting heavy mathematical logic to C++ / WebAssembly for performance. |

<br/>

## 🗺️ 5-Phase Roadmap

Each Phase builds upon the rigorous mathematical validation of the previous one.

| Phase | Name | Core Objective | Status |
|:---:|---|---|:---:|
| 0 | Pre-flight | Architecture & TDD Pipeline Setup | Active |
| 1 | Foundation (Python) | 2D Grid, Density Diffusion & Advection | Planned |
| 2 | The Solver (Python) | Full Navier-Stokes equation validation | Planned |
| 3 | Translation (TS) | Porting logic to TypeScript & WebGL Render | Planned |
| 4 | Boundary & Heat | Implementing spacecraft hull collisions | Planned |
| 5 | Acceleration (C++) | WebAssembly integration for extreme scale | Planned |

> 📜 Detailed phase handoffs and mathematical proofs are tracked in `docs/phase-handoffs/`.

<br/>

## 🛠️ Tech Stack

### Phase 1 & 2: Prototyping & Verification
- **Language**: Python 3.14
- **Testing**: `pytest` (Strict TDD)
- **Math**: `numpy`

### Phase 3+: Visualization & Scale
- **Language**: TypeScript, C/C++ (Basic to Advanced)
- **Rendering**: WebGL / HTML5 Canvas
- **Performance**: WebAssembly (WASM)

<br/>

## 📂 Project Structure

```text
SpaceFlow/
├── README.md
├── LICENSE                          MIT
│
├── docs/
│   ├── COLLABORATION.md             📜 Pair Programming Rules
│   ├── WORKFLOW.md                  🔄 PCTC Cycle Standard
│   ├── HANDOFF.md                   🛰️ Handoff Templates
│   │
│   └── phase-handoffs/              Phase completion summaries
│
├── src/                             Core fluid dynamics engine
│   └── physics/                     Mathematical algorithms
│
└── tests/                           Pytest suite for TDD
```

<br/>

## 🚀 Getting Started

### Prerequisites
- Python 3.14+
- Git

### Installation

```bash
# Clone the repository
git clone [https://github.com/2daKaizen-gun/SpaceFlow.git](https://github.com/2daKaizen-gun/SpaceFlow.git)
cd SpaceFlow

# Setup Python Virtual Environment
python3.14 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install pytest numpy
```

<br/>

## 🤝 Collaboration System

This project is developed through strict pair programming with **Gemini (Google AI)**. To maintain context and mathematical accuracy over a long-term simulation project, we enforce a strict system:

| Document | Role | Content |
|---|---|---|
| 📜 `COLLABORATION.md` | Rules | Strict formatting, TDD enforcement, no-hallucination checks. |
| 🔄 `WORKFLOW.md` | Action | The **PCTC (Plan-Code-Test-Check)** execution cycle. |
| 🛰️ `HANDOFF.md` | State | Compressed mathematical context passed between sessions. |

<br/>

## 📚 Data Sources & References
- *Jos Stam* - "Real-Time Fluid Dynamics for Games" (The core solver algorithm)
- *Navier-Stokes Equations* - Millennium Prize Problems
- Fluid dynamics discretization theory

<br/>

## 📝 License
Distributed under the MIT License. See `LICENSE` for more information.

<br/>

## 👤 Developer

**Leegun Kwon** Hansung University, Computer Engineering  
- **GitHub**: [@2daKaizen-gun](https://github.com/2daKaizen-gun)
- **Email**: hkys1223@gmail.com
- **Skills & Focus**: AI Automation, Data Engineering, Fluid Simulation, Linux Systems, Japanese (JLPT N3 / N2 Candidate)