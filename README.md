# Automotive Fundamentals

A structured learning repository for developing an understanding of **automotive systems, vehicle electronics, ECUs, sensors, actuators, and automotive engineering fundamentals**.

This repository supports my long-term goal of working in **automotive embedded systems and automotive R&D**.

---

## Purpose

The purpose of this repository is to understand:

- How modern vehicles are organised
- Major automotive systems
- Automotive electronics
- Electronic Control Units (ECUs)
- Sensors and actuators
- ECU architecture
- Vehicle signal flow
- Automotive communication fundamentals
- Vehicle networks
- The relationship between embedded systems and vehicle functions

---

## Repository Structure

```text
automotive-fundamentals/
│
├── README.md
│
├── phase-1/
│   └── Phase 1 learning documentation
│
└── phase-2/
    └── Phase 2 supporting automotive context
```

---

# Phase 1 — Automotive Foundation

Phase 1 establishes the fundamental automotive knowledge required before moving into deeper automotive embedded engineering.

Major areas include:

- Automotive electronics overview
- ECU fundamentals
- Sensors
- Actuators
- ECU architecture
- Vehicle signal flow
- CAN introduction
- Need for CAN
- CAN frames
- CAN communication
- Vehicle networks
- CAN nodes
- Automotive revision and integration

The objective is to understand the relationship between:

```text
Vehicle
   ↓
Vehicle System
   ↓
Electronic System
   ↓
ECU
   ↓
Sensor / Actuator
   ↓
Signal
```

---

# Phase 2 — Embedded Engineering Depth

Phase 2 is primarily focused on **microcontrollers, firmware, peripherals, drivers, and debugging**.

Therefore, automotive-specific content remains supporting context rather than becoming a separate automotive syllabus.

Phase 2 concepts can be understood in an automotive context through:

```text
Microcontroller
      ↓
Peripheral
      ↓
Firmware
      ↓
ECU
      ↓
Vehicle Function
```

For example, understanding GPIO, interrupts, timers, ADC, communication peripherals, drivers, and debugging provides the embedded foundation required for later automotive ECU work.

---

## Future Automotive Depth

More specialised automotive engineering topics will be introduced in later phases when the embedded foundation is sufficiently developed.

Potential future areas include:

- CAN deeper implementation
- LIN
- Automotive Ethernet
- AUTOSAR
- UDS
- ECU diagnostics
- Automotive software architecture
- Functional safety
- Automotive validation and verification
- Automotive networking
- ECU development processes
- Vehicle-level integration

These topics are intentionally not forced into Phase 2.

---

## Learning Progression

The overall automotive learning direction is:

```text
Vehicle
   ↓
Vehicle System
   ↓
Electronic System
   ↓
ECU
   ↓
Microcontroller
   ↓
Peripheral
   ↓
Firmware
   ↓
Vehicle Function
```

This progression connects vehicle-level understanding with embedded engineering.

---

## Career Direction

This repository supports the long-term progression toward:

```text
Embedded Systems
       ↓
Automotive Embedded
       ↓
Automotive R&D
       ↓
OEM Engineering
```

Relevant target roles include:

- Embedded Software Engineer
- Embedded Systems Engineer
- Embedded Firmware Engineer
- Automotive Embedded Engineer
- ECU Software Engineer
- Automotive R&D Engineer
- Automotive Electronics Engineer
- ECU Validation / Verification Engineer

---

## Scope

This repository focuses specifically on **automotive engineering fundamentals and automotive context**.

C and firmware concepts are primarily documented in:

- `embedded-c-fundamentals`

Microcontroller concepts are primarily documented in:

- `microcontroller-fundamentals`

Electronics concepts are primarily documented in:

- `electronics-fundamentals`

---

## Repository Principle

Automotive topics should remain focused on **automotive systems and their engineering context**.

Embedded implementation details should be documented in the relevant technical repositories rather than duplicated here.

For example:

- ECU concept → `automotive-fundamentals`
- MCU register configuration → `microcontroller-fundamentals`
- Embedded C implementation → `embedded-c-fundamentals`
- Electronic circuit behaviour → `electronics-fundamentals`

---

## Author

**Haresh R.**

BE Electronics and Communication Engineering
