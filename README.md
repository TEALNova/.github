# TEAL Nova – Industrial Automation Software Platform

Welcome to **TEAL Nova**, the software development organization for Titan Engineering and Automation Limited (TEAL).

TEAL Nova focuses on developing scalable, modular, reusable, and maintainable software solutions for industrial automation systems.

Our platform includes multiple generations of Master Control Software, supporting machine automation, hardware integration, device communication, process control, monitoring, and production workflows.

---

## 🚀 Projects Overview

### 1. Master Module V2 – Interstellar

**Technology:** C# | Windows Forms | .NET Framework 4.7.2

Interstellar is the second-generation Master Module platform, designed to control and monitor industrial automation machines.

**Key Features**
- Machine control and automation.
- Hardware and device communication.
- Digital I/O management.
- Servo, Stepper, Cylinder and Vacuum control.
- Sequence execution and process management.
- Alarm handling and monitoring.
- Machine configuration management.
- Reusable device and controller libraries.

### 2. Master Module V3 – Odyssey

**Technology:** C# | WPF | .NET 8 / .NET Framework 4.7.2 compatible libraries

Odyssey is the next-generation Master Module platform, designed with a modern UI, modular architecture, and reusable software components.

**Key Features**
- Modern WPF-based user interface.
- MVVM architecture.
- Dependency Injection.
- State-based device and sequence management.
- Reusable hardware abstraction libraries.
- Configuration-driven machine setup.
- Alarm and event management.
- Multi-language support.
- Production, Dry Run, CPK, GRR and other operating modes.
- SFC / PDCA integration.

---

## 🏗️ Platform Architecture

The TEAL Nova platform follows a modular architecture.

```text
TEAL Nova
│
├── Master Module V2
│   └── Interstellar
│       ├── Interstellar.Code
│       └── Interstellar.Library
│
├── Master Module V3
│   └── Odyssey
│       ├── Odyssey.Master
│       └── Odyssey.Library
│
└── Shared / Reusable Components
    ├── Device Libraries
    ├── Hardware Communication
    ├── Configuration Management
    ├── Machine Control
    └── Common Utilities
```

---

## ⚙️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | C# |
| UI Framework | Windows Forms, WPF |
| Runtime | .NET Framework 4.7.2, .NET 8 |
| Architecture | OOP, MVVM, State Pattern, DI |
| Database | SQL Server, MySQL |
| Configuration | XML, JSON, CSV |
| Hardware Integration | Advantech, EtherCAT, Serial, TCP/IP |
| Version Control | Git |
| IDE | Visual Studio 2022 |

---

## 🔌 Hardware & Device Integration

The platform is designed to support different industrial hardware and communication interfaces.

- Advantech Motion and I/O Cards.
- Servo and Stepper Motors.
- Pneumatic Cylinders.
- Vacuum Controllers.
- Digital and Analog I/O.
- CCD Cameras.
- Barcode / QR Code Scanners.
- Industrial Robots.
- EtherCAT Devices.
- Serial and TCP/IP Communication.

---

## 📁 Development Guidelines

All repositories should follow common development practices:

1. Maintain modular and reusable code.
2. Follow SOLID principles wherever applicable.
3. Keep UI, business logic and hardware communication separated.
4. Avoid unnecessary dependencies between modules.
5. Use configuration-driven implementations wherever possible.
6. Implement proper exception handling and logging.
7. Provide meaningful comments and documentation.
8. Perform unit testing before submitting changes.
9. Avoid committing generated binaries and temporary files unless required.
10. Maintain backward compatibility for shared libraries wherever applicable.

---

## 🌿 Git Branching & Pull Request Workflow

All development activities must follow the organization Git workflow.

**Recommended workflow:**

```text
main
  │
  ├── feature/feature-name
  │
  ├── bugfix/issue-name
  │
  └── hotfix/issue-name
          │
          ▼
    Pull Request
          │
          ▼
    Code Review
          │
          ▼
    Approval & Merge
          │
          ▼
         main
```

**Guidelines**
- Do not push development changes directly to `main`.
- Create feature or bugfix branches.
- Submit Pull Requests for code changes.
- Ensure code review before merging.
- Resolve merge conflicts before approval.
- Keep commit messages meaningful.

---

## 👨‍💻 Contribution

All team members contributing to TEAL Nova repositories are expected to:

- Follow the defined coding standards.
- Maintain proper repository documentation.
- Update task tracking systems.
- Perform appropriate testing.
- Submit changes through Pull Requests.
- Coordinate changes affecting shared libraries and dependent projects.

---

## 🎯 Vision

To build a unified, reusable, scalable, and reliable industrial automation software ecosystem that simplifies machine development, improves engineering efficiency, and accelerates future automation projects.

**TEAL Nova – Building the Next Generation of Industrial Automation Software.**
