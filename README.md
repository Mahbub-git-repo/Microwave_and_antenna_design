# ADS Antenna Engineering Lab

This repository contains laboratory work performed using **Keysight Advanced Design System (ADS)** for the **Antenna Engineering Sessional** course.

The objective of this lab is to design, simulate, and analyze a **microstrip patch antenna** using realistic fabrication constraints and impedance matching techniques.

---

## Software Used
- Advanced Design System (ADS)


---

## Antenna Structure
- Top layer: Patch conductor
- Middle layer: Dielectric substrate
- Bottom layer: Ground plane
- Surrounding medium: Air

Patch and ground layers are modeled as **copper conductors**.

---

## Substrate Details
- Material: Teflon / Alumina / FR4 (depending on availability)
- Relative permittivity (εr): Selected from ADS material library
- Thickness: **0.8 mm (or multiples)**  
  → Based on minimum PCB fabrication thickness

---

## Design Rules
- Ground plane size = **2 × patch dimensions**
- Substrate size = ground plane size
- Copper thickness = **0.018 mm**

---

## Frequency Plan
- Type: Linear sweep
- Targeted Frequency: 17 GHz
- Number of points: Odd number (e.g., 101)
  → Ensures center frequency alignment

---

## Impedance Matching
- Matching evaluated using **reflection coefficient (S11)**
- Antenna considered matched when:
