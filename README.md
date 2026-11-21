# 3MW-Grid-Connected-Solar-PV-System
# 3 MW Grid-Connected Solar PV System Using MATLAB/Simulink

**Project Status:** In Progress

## 1. Project Overview

This project involves the tutorial-guided implementation and simulation of a 3 MW grid-connected Solar Photovoltaic (PV) system using MATLAB/Simulink.

The model is being developed to understand solar PV generation, maximum power point tracking, DC-DC power conversion, three-phase inverter control and grid integration.

## 2. System Specifications

| Parameter | Reference Value |
|---|---:|
| PV Module Rating | 213.15 W |
| Modules per Series String | 11 |
| Parallel Strings | 1300 |
| Nominal Array Capacity | Approximately 3.048 MW |
| Reference Irradiance | 1000 W/m² |
| Reference Temperature | 25°C |
| DC-Link Voltage Reference | 600 V |
| Grid Voltage | 400 V |
| Grid Frequency | 50 Hz |
| MPPT Algorithm | Perturb and Observe |
| Switching Frequency | 10 kHz |

*These are reference specifications from the tutorial and will be checked against the implemented model.*

## 3. Main System Components

1. Solar PV Array
2. DC-DC Boost Converter
3. Perturb and Observe (P&O) MPPT Controller
4. DC-Link Capacitor
5. Three-Phase IGBT Inverter
6. PI-Based Control System
7. Phase-Locked Loop (PLL)
8. dq-Axis Current Control
9. L-Filter
10. Three-Phase Grid

## 4. Working Methodology

### Stage 1: Solar PV Generation
The PV array converts solar energy into DC electrical power.

### Stage 2: Maximum Power Point Tracking
The P&O algorithm adjusts the operating point of the PV array to track its maximum power point.

### Stage 3: DC-DC Boost Conversion
The boost converter increases the PV-side DC voltage and transfers power to the DC link.

### Stage 4: DC-Link Regulation
A PI controller is used to regulate the DC-link voltage around its reference value.

### Stage 5: DC-AC Conversion
A three-phase IGBT inverter converts DC power into AC power.

### Stage 6: Grid Synchronisation
A PLL estimates the grid phase angle, while dq-axis current control regulates inverter current.

### Stage 7: Grid Integration
An L-filter is used to reduce switching-frequency current harmonics before grid connection.

## 5. Simulation and Validation

The following results will be documented after implementation and testing:

- PV voltage and current characteristics.
- PV output power and MPPT response.
- DC-link voltage regulation.
- Three-phase inverter voltage and current.
- Grid synchronisation.
- Response to changes in solar irradiance and temperature.

## 6. Software and Tools

- MATLAB
- Simulink

## 7. Learning Objectives

- Understand utility-scale solar PV systems.
- Study DC-DC boost converter operation.
- Implement P&O MPPT control.
- Understand three-phase inverter operation.
- Study PLL and dq-axis control.
- Understand grid-connected renewable energy systems.

