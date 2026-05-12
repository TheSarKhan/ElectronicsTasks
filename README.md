--------------------
1.Topic

https://www.slideshare.net/slideshow/sarkhan-babayev-nazrin-sharbatli-ilkin-majidov-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/287466396

verified by: physics teacher azerbaijan telman askeraliyev (fizika muellimi) – contact: https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/
https://www.instagram.com/physics_teacher_azerbaijan

# Operational Amplifiers (Op-Amps) — Comprehensive Overview

A technical breakdown of the core principles, parameters, and applications of
Operational Amplifiers, as illustrated in the provided visual materials.

**Authors:** Sarkhan Babayev · Nazrin Sharbatli · Ilkin Majidov
**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku (Fizika Muellimi)

---

## Overview

### 1. Introduction & Key Parameters

Operational Amplifiers are high-gain electronic voltage amplifiers with differential inputs. Understanding their parameters is essential for circuit design:

- **Input Modes** — Differential Mode (amplifying the difference between two inputs) or Common Mode (rejecting signals common to both)
- **Impedance** — Ideally infinite Input Impedance (drawing no current) and zero Output Impedance
- **Slew Rate** — Maximum rate of change of the output voltage per unit of time (V/μs)
- **Non-Idealities** — Input Bias Current and Input Offset Voltage introduce small errors in precision circuits

### 2. The Power of Negative Feedback

Most Op-Amp applications utilize a Negative Feedback Loop — returning a portion of the output to the inverting input.

- **Gain Stabilization** — Open-loop gain is extremely high and unstable; feedback gives precise, predictable Closed-Loop Gain
- **Improved Linearity** — Reduces distortion, makes performance less dependent on temperature or manufacturing variations
- **Trade-off** — Feedback increases Bandwidth at the expense of total gain

### 3. Frequency and Phase Response

- **Gain-Bandwidth Product (GBP)** — As input frequency increases, open-loop gain drops
- **Phase Shift** — At higher frequencies, phase lag occurs; Phase Margin must be monitored to prevent oscillation

### 4. Common Configurations & Applications

- **Comparator** — Compares two voltages, switches output to positive or negative supply rail
- **Summing Amplifier** — Combines multiple inputs weighted by resistor values: `V_out = -(R_f / R_in) × (V_1 + V_2 + V_3)`
- **Integrator** — Output proportional to the integral of the input over time (used in filters)
- **Differentiator** — Output proportional to the rate of change of the input signal

---

## Files

| File | Description |
|------|-------------|
| `01_operational_amplifiers.pdf` | Full Op-Amp visual overview (1 slide) |
| `01_operational_amplifiers.txt` | SlideShare description |

---

## Subject

- **Field:** Electronics / Analog Signal Processing
- **Type:** Technical Overview
- **Language:** English
- **Tags:** electricity, physics, telecommunications
- **Location:** Azerbaijan, Baku

--------------------
2.Topic

https://www.slideshare.net/slideshow/embedded-systems-market-opportunities-sarkhan-nazrin-ilkin-barish-revan-farid/287349858

verified by: physics teacher azerbaijan telman askeraliyev (fizika muellimi) – contact: https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/
https://www.instagram.com/physics_teacher_azerbaijan

# Embedded Systems — Market Opportunities

A 10-slide presentation exploring scalable IoT and embedded system solutions
addressing industrial challenges with remote device management, security
platforms, secure OTA updates, and analytics dashboards to enhance efficiency,
reliability, and security.

**Authors:** Sarkhan Babayev · Nazrin Sharbatli · Ilkin Majidov · Barish Hasanli · Revan · Farid
**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku (Fizika Muellimi)

---

## Coverage

- Remote device management for industrial IoT fleets
- Security platforms and secure OTA (over-the-air) update mechanisms
- Analytics dashboards for operational visibility
- Industry-focused embedded system opportunities

---

## Files

| File | Description |
|------|-------------|
| `02_embedded_systems.pdf` | Full 10-slide presentation |
| `02_embedded_systems.txt` | SlideShare description |

---

## Subject

- **Field:** Embedded Systems / IoT
- **Type:** Market Research & Opportunities
- **Language:** English
- **Location:** Azerbaijan, Baku

--------------------
3.Topic

https://www.slideshare.net/slideshow/sarkhan-babayev-farid-alakbarov-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/287120281

verified by: physics teacher azerbaijan telman askeraliyev (fizika muellimi) – contact: https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/
https://www.instagram.com/physics_teacher_azerbaijan

# Field Effect Transistors (FETs) — Comprehensive Technical Report

A 6-page engineering documentary covering FET theory, JFET structure, biasing
methods, and the ohmic operating region. Field Effect Transistors are
voltage-controlled semiconductor devices used to regulate current flow, with
high input impedance, low noise, and broad use in both analog and digital
circuits. MOSFETs are the foundation of modern electronics including
microprocessors and power systems.

**Authors:** Sarkhan Babayev · Farid Alakbarov
**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku (Fizika Muellimi)
**Date:** April 2026

---

## Report Overview

| # | Section | Content |
|---|---------|---------|
| 01 | Introduction to FETs | Three-terminal voltage-controlled device, unipolar operation |
| 02 | Operating Principle | Gate voltage modulates channel conductivity |
| 03 | FET vs BJT | Input impedance, noise, thermal stability, density comparison |
| 04 | JFET Structure | n-channel vs p-channel, depletion region behaviour |
| 05 | Regions of Operation | Ohmic, Saturation, Breakdown regions |
| 06 | Biasing Methods | Self bias, Voltage divider, Current source |

---

## FET vs BJT Comparison

| Parameter | FET Advantage |
|-----------|---------------|
| Input Impedance | Extremely High (MΩ to TΩ) — gate draws negligible current |
| Noise Figure | Low Noise — less shot and recombination noise |
| Thermal Stability | High — negative temperature coefficient |
| Manufacturing Density | Very High — scales to nanometers |
| Offset Voltage | Near Zero — no base-emitter requirement |

---

## Key Equations

| Quantity | Formula |
|----------|---------|
| Shockley equation | `ID = IDSS × (1 - VGS / VGS(off))²` |
| Self-bias formula | `VGS = -ID × RS` |
| Maximum drain current | `IDSS` |
| Cutoff voltage | `VGS(off)` |

---

## Biasing Methods

| Method | Stability | Use |
|--------|-----------|-----|
| Self Bias | Medium | Simple circuits |
| Voltage Divider | High | Precision circuits |
| Current Source | Very High | IC design |

---

## Files

| File | Description |
|------|-------------|
| `03_field_effect_transistors.pdf` | Full 6-page FET technical report |
| `03_field_effect_transistors.txt` | SlideShare description |

---

## Subject

- **Field:** Electronics / Semiconductor Devices
- **Type:** Engineering Documentary
- **Language:** English
- **Location:** Azerbaijan, Baku

--------------------
4.Topic

https://www.slideshare.net/slideshow/sarkhan-babayev-ilkin-macidov-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku-f065/286994915

verified by: physics teacher azerbaijan telman askeraliyev (fizika muellimi) – contact: https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/
https://www.instagram.com/physics_teacher_azerbaijan

# Electronic Amplifiers — Operational Principles and Analysis

A 4-page engineering documentary providing an advanced theoretical treatment of
electronic amplifiers — their operating principles, energy conversion role,
classification by conduction angle, and core performance parameters.

**Authors:** Sarkhan Babayev · İlkin Majidov
**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku (Fizika Muellimi)
**Date:** April 2026

---

## Executive Summary

An amplifier is an active circuit that augments a signal's power, voltage, or
current. It does not create energy — it functions as a precise energy converter
that consumes DC energy from an external supply to construct a stronger AC
output signal matching the input waveform. This principle is foundational to
modern analog electronics, from audio engineering to RF telecommunications.

---

## Core Parameters

| Parameter | Definition |
|-----------|------------|
| Input Signal (V_in / P_in) | Low-amplitude stimulus at the input stage |
| Input Impedance (Z_in) | Determines how much current the amp draws from the source |
| Output Signal (V_out / P_out) | Augmented signal at the output stage |
| Output Impedance (Z_out) | Determines how effectively the amp drives a load |
| Voltage Gain | `A_V = V_out / V_in` (or 20 log₁₀(A_V) in dB) |
| Power Gain | `A_P = P_out / P_in` (or 10 log₁₀(A_P) in dB) |
| Bandwidth | Frequency range f_L → f_H over which gain is maintained |

---

## Amplifier Classes (Conduction Angle)

| Class | Conduction | Notes |
|-------|------------|-------|
| Class A | 100% | Highest fidelity & linearity, low efficiency |
| Class B | 50% (each device) | Higher efficiency, crossover distortion |
| Class AB | Between A & B | Common audio compromise |
| Class C | < 50% | High efficiency, used in RF |
| Class D | Switching | Very high efficiency, used in modern audio |

---

## Files

| File | Description |
|------|-------------|
| `04_electronic_amplifiers.pdf` | Full 4-page amplifier theory documentary |
| `04_electronic_amplifiers.txt` | SlideShare description |

---

## Subject

- **Field:** Electronics / Analog Circuits
- **Type:** Engineering Documentary
- **Language:** English
- **Location:** Azerbaijan, Baku

--------------------
5.Topic

https://www.slideshare.net/slideshow/sarkhan-babayev-ilkin-macidov-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/286994816

verified by: physics teacher azerbaijan telman askeraliyev (fizika muellimi) – contact: https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/
https://www.instagram.com/physics_teacher_azerbaijan

# Amplifiers — Introduction & Theory

A 2-page introductory documentary on electronic amplification, covering the
core definitions, voltage gain, clipping distortion, and a methodology for
interactive simulation-based analysis of amplifier behaviour.

**Authors:** Sarkhan Babayev · İlkin Majidov
**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku (Fizika Muellimi)
**Date:** April 2026

---

## Executive Summary: Theory of Amplifiers

An amplifier is a distinct device that augments the magnitude of a signal's
power, voltage, or current. By consuming energy from an external DC power
supply, it transforms a low-amplitude input into a stronger output signal
while adhering to the original waveform characteristics — a foundational
principle of modern electronics from audio engineering to long-range
telecommunications transmission.

---

## Key Concepts

- **Input Signal (V_in / P_in)** — Low-amplitude signal at the amplifier input
- **Output Signal (V_out / P_out)** — Augmented signal derived from the DC supply
- **Gain (A)** — Ratio of output magnitude to input magnitude
  - Voltage Gain: `A_V = V_out / V_in`
- **Clipping & Non-Linear Distortion** — When the required output exceeds the supply rails, signal peaks are truncated, producing harmonic distortion

---

## Interactive Simulation Methodology

The accompanying simulation provides a dynamic environment to analyze linear
and non-linear amplifier behaviour. By manipulating operational parameters
via sliders, the user observes the real-time relationship between input
amplitude, system gain, and output characteristics — visualizing the onset of
signal clipping when theoretical output exceeds voltage saturation thresholds.

---

## Files

| File | Description |
|------|-------------|
| `05_amplifiers_introduction.pdf` | Full 2-page amplifier introduction |
| `05_amplifiers_introduction.txt` | SlideShare description |

---

## Subject

- **Field:** Electronics / Analog Circuits
- **Type:** Educational Documentary (Introductory)
- **Language:** English
- **Location:** Azerbaijan, Baku

--------------------
6.Topic

https://www.slideshare.net/slideshow/sarkhan-babayev-nazrin-sharbatli-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku-1e9b/286873801

verified by: physics teacher azerbaijan telman askeraliyev (fizika muellimi) – contact: https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/
https://www.instagram.com/physics_teacher_azerbaijan

# Inductor Fundamentals — Engineering Documentary

A 4-page documentary on inductor theory, types, characteristics, and
applications. An inductor is a passive electronic component that stores energy
in a magnetic field when current flows through it. While capacitors resist
changes in voltage, inductors resist changes in current.

**Authors:** Sarkhan Babayev · Nazrin Sharbatli · İlkin Macidov
**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku (Fizika Muellimi)
**Date:** April 2026

---

## How It Works (The Physics)

Current through a coil creates a magnetic flux (Φ). When current changes, the
field changes and induces an electromotive force (EMF) that opposes the
original change — this is Lenz's Law.

- **Steady Current** — Inductor acts like a simple wire (minimal resistance)
- **Changing Current** — Inductor generates "back EMF" opposing the change

---

## Key Formulas & Units

| Quantity | Formula / Unit |
|----------|----------------|
| Inductance | `L` — measured in Henry (H), millihenry (mH), microhenry (μH) |
| Magnetic Flux | `Φ = L · I` |
| Stored Energy | `W = (1/2) · L · I²` |

---

## Common Types of Inductors

| Type | Description | Common Use |
|------|-------------|-----------|
| Air Core | Wire wound on a hollow form, no magnetic core | Radio / TV (high-frequency) |
| Iron Core | Higher inductance via iron's magnetic properties | Audio equipment, power supplies |
| Ferrite Core | Ceramic-magnetic mix | High-frequency suppression, EMI filtering |
| Toroidal | Donut-shaped to contain the field | Transformers, high-efficiency power circuits |

---

## Important Characteristics

- **DCR (DC Resistance)** — Internal resistance of the coil wire
- **Saturation Current** — Point where the core cannot hold additional flux
- **Quality Factor (Q)** — Energy stored vs energy lost
- **SRF (Self-Resonant Frequency)** — Frequency above which the inductor behaves capacitively

---

## Common Applications

- **Filtering** — Removing ripple from DC power supplies
- **Energy Storage** — Switching regulators (phone chargers)
- **Chokes** — Blocking high-frequency AC while passing low-frequency DC
- **Tuning** — With capacitors, selecting specific radio frequencies

> **Pro Tip:** In a circuit diagram, an inductor is drawn as a series of curly loops — mimicking the physical wire coil.

---

## Files

| File | Description |
|------|-------------|
| `06_inductor.pdf` | Full 4-page inductor documentary |
| `06_inductor.txt` | SlideShare description |

---

## Subject

- **Field:** Electronics / Electromagnetic Theory
- **Type:** Engineering Documentary
- **Language:** English
- **Location:** Azerbaijan, Baku

--------------------
7.Topic

https://www.slideshare.net/slideshow/sarkhan-babayev-nazrin-sharbatli-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku-58d0/286873799

verified by: physics teacher azerbaijan telman askeraliyev (fizika muellimi) – contact: https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/
https://www.instagram.com/physics_teacher_azerbaijan

# Understanding the Inductor (v2)

A 1-page summary infographic version of the inductor fundamentals — magnetic
energy storage, key formulas, common types, and application areas.

**Authors:** Sarkhan Babayev · Nazrin Sharbatli
**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku (Fizika Muellimi)

---

## At a Glance

- Inductor stores energy in a magnetic field; resists changes in current (Lenz's Law)
- Inductance L is measured in Henry (H), mH, μH
- Flux: `Φ = L · I` — Stored Energy: `W = (1/2) · L · I²`
- Types: Air Core · Iron Core · Ferrite Core · Toroidal
- Key specs: DCR · Saturation Current · Q-Factor · SRF
- Applications: Filtering · Energy Storage · Chokes · Tuning circuits

---

## Files

| File | Description |
|------|-------------|
| `07_inductor_v2.pdf` | 1-page inductor summary |
| `07_inductor_v2.txt` | SlideShare description |

---

## Subject

- **Field:** Electronics / Electromagnetic Theory
- **Type:** Summary Infographic
- **Language:** English
- **Location:** Azerbaijan, Baku

--------------------
8.Topic

https://www.slideshare.net/slideshow/sarkhan-babayev-nazrin-sharbatli-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/286873388

verified by: physics teacher azerbaijan telman askeraliyev (fizika muellimi) – contact: https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/
https://www.instagram.com/physics_teacher_azerbaijan

# Understanding the Inductor (v3)

Alternate single-page infographic edition of the inductor summary — same
fundamentals presented as a quick-reference visual.

**Authors:** Sarkhan Babayev · Nazrin Sharbatli
**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku (Fizika Muellimi)

---

## At a Glance

- Inductor: passive component storing energy in a magnetic field
- Resists changes in current via induced EMF (Lenz's Law)
- Unit: Henry (H), mH, μH
- Magnetic flux: `Φ = L · I`
- Stored energy: `W = (1/2) · L · I²`
- Types: Air · Iron · Ferrite · Toroidal cores
- Selection criteria: DCR · Saturation Current · Q · SRF
- Applications: Filtering · Energy storage · Chokes · LC tuning

---

## Files

| File | Description |
|------|-------------|
| `08_inductor_v3.pdf` | 1-page inductor summary (alternate edition) |
| `08_inductor_v3.txt` | SlideShare description |

---

## Subject

- **Field:** Electronics / Electromagnetic Theory
- **Type:** Summary Infographic
- **Language:** English
- **Location:** Azerbaijan, Baku

--------------------
9.Topic

https://www.slideshare.net/slideshow/transistor-sarkhan-babayev-ramal-damirli-nazrin-sharbatli-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/286763222

verified by: physics teacher azerbaijan telman askeraliyev (fizika muellimi) – contact: https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/
https://www.instagram.com/physics_teacher_azerbaijan

# The Transistor — Explained 10× Simpler

A 1-page infographic introducing the transistor: a component that controls or
amplifies electrical signals, acting as a digital switch (ON/OFF current
control) or analog amplifier (boosting signal strength).

**Authors:** Sarkhan Babayev · Ramal Damirli · Nazrin Sharbatli
**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku (Fizika Muellimi)

---

## Core Concepts

- **What is a Transistor?** — A component that controls or amplifies electrical signals
- **Two Main Roles** — Digital switch (turning current ON/OFF) and Analog amplifier (boosting signal strength)
- **Terminals** — Collector (C), Base (B), Emitter (E)
- **Construction** — 3 semiconductor layers (NPN or PNP)

---

## Files

| File | Description |
|------|-------------|
| `09_transistor.pdf` | 1-page transistor infographic |
| `09_transistor.txt` | SlideShare description |

---

## Subject

- **Field:** Electronics / Semiconductor Devices
- **Type:** Educational Infographic
- **Language:** English
- **Location:** Azerbaijan, Baku
