# Beyond Optical PPG: mmWave Radar Arterial Pulse Sensing

Final Year Project | Group 27 | EN4203  
Department of Electronic & Telecommunication Engineering, University of Moratuwa, Sri Lanka

## Overview

This project investigates the use of 60 GHz mmWave radar to detect arterial pulse signals from the wrist. We aim to develop a wearable prototype and evaluate radar sensing as an alternative or complementary method to optical photoplethysmography (PPG).

The study explores performance under conditions that can affect optical PPG, including motion, skin pigmentation, ambient light, and tissue characteristics.

## Objectives

- Develop a wrist-worn prototype integrating mmWave radar, an optical PPG sensor, and an inertial measurement unit (IMU).
- Extract pulse waveforms and estimate heart rate from radar signals.
- Investigate heart rate variability and blood pressure estimation, subject to experimental validation.
- Develop adaptive sensing and signal processing based on signal quality and motion.
- Compare radar and optical PPG performance during sitting, walking, and running.

## System Approach

The radar captures reflected signals from the wrist to detect small tissue movements associated with arterial pulsation. Signal processing extracts a pulse-related waveform for further analysis.

The planned prototype combines:

| Component | Purpose |
| --- | --- |
| Infineon BGT60TR13C radar | Acquire 60 GHz radar signals |
| Optical PPG sensor | Collect signals for comparison |
| IMU | Measure wrist motion |
| Microcontroller and wireless interface | Acquire and transmit sensor data |

Planned reference devices include a Polar H10 chest strap for heart rate and an Omron BP4350 monitor for blood pressure.

## Repository

This repository brings together project documentation, hardware designs, enclosure models, firmware, and signal processing work as development progresses.

## Project Status

The project is under development. Prototype design, radar data analysis, adaptive processing, and experimental validation are ongoing areas of work. Performance improvements and physiological estimates remain research goals to be evaluated.

## Team

| Member | Student Number |
| --- | --- |
| Ananthakumar T. | 220029T |
| Sivamynthan N. | 220619D |
| Mathujan S. | 220389U |
| Kopithan M. | 220327F |

**Supervisors:** Dr. Sampath Perera and Dr. Joshua Pranjeevan Kulasingham  
**External Collaborator:** Thivya Kandappu, Singapore Management University

## Research Use

This is an academic research prototype intended for development and experimental evaluation. It is not a validated medical device.
