# Robozon Hackathon

Engineering repository for the **RoboZon Intelligent Robotic Sorting System** hackathon project.

The repository contains all project artifacts including competition documentation, architecture decisions, hardware development, firmware, computer vision, simulation, experiments, and final implementation.

---

# Repository Structure

```text
.
├── docs/
│   ├── competition/
│   └── decisions/
│
├── hardware/
├── mechanics/
├── electronics/
├── firmware/
├── software/
├── vision/
├── simulation/
├── datasets/
├── experiments/
├── scripts/
├── tools/
├── assets/
│
└── README.md
```

---

# Documentation

## Competition

| Document                                                                       | Description                                   |
| ------------------------------------------------------------------------------ | --------------------------------------------- |
| [Competition Overview](docs/competition/README.md)                             | Entry point for all competition documentation |
| [Requirements](docs/competition/requirements.md)                               | Original competition task                     |
| [Requirements Clarifications](docs/competition/requirements_clarifications.md) | Official Q&A from organizers                  |
| [Constraints](docs/competition/constraints.md)                                 | Technical and organizational limitations      |
| [Assumptions](docs/competition/assumptions.md)                                 | Engineering assumptions                       |
| [Evaluation Criteria](docs/competition/evaluation_criteria.md)                 | Judging criteria analysis                     |
| [Submission](docs/competition/submission.md)                                   | Submission requirements and checklist         |

---

## Engineering Decisions

| Document                                                  | Description                         |
| --------------------------------------------------------- | ----------------------------------- |
| [Architecture Decision Records](docs/decisions/README.md) | Engineering decisions and rationale |

---

# Planned Project Modules

## Hardware

* Mechanical design
* Conveyor system
* Manipulator
* Sorting mechanism
* Storage bins
* Sensors

---

## Electronics

* MCU
* Motor drivers
* Power distribution
* Safety systems
* Communication interfaces

---

## Firmware

* Motion control
* Device drivers
* Communication protocols
* Safety logic

---

## Computer Vision

* Synthetic dataset generation
* Dataset management
* Training
* Inference
* Tracking
* Segmentation
* Classification

---

## Simulation

* Blender
* BlenderProc
* Digital Twin
* Motion simulation
* Validation

---

## Software

* Control software
* Scheduler
* Communication layer
* Monitoring
* Logging
* Configuration

---

## Experiments

Experimental prototypes, benchmarks, calibration procedures and engineering investigations.

---

# Current Focus

Current development is primarily focused on:

* Hardware architecture
* Embedded firmware
* Electronics integration
* Robotic sorting mechanism
* System integration
* Competition documentation
* Engineering decision tracking

Computer vision components are developed in parallel and integrated through clearly defined interfaces.

---

# Repository Goals

* Maintain a single source of truth for the project.
* Document engineering decisions.
* Ensure reproducibility.
* Track assumptions and constraints.
* Simplify onboarding for new contributors.
* Produce a competition-ready engineering project.

---

# Development Philosophy

The project follows an engineering-first approach:

```
Requirements
        ↓
Clarifications
        ↓
Constraints
        ↓
Assumptions
        ↓
Architecture Decisions
        ↓
Prototype
        ↓
Validation
        ↓
Final System
```

Each engineering decision should be traceable back to either an official requirement, an organizer clarification, or a documented project assumption.
