# Grid-connected-solar-pv-design
Design and simulation of a 24 kW three-phase grid-connected rooftop solar PV system using PVSyst and PSCAD.

# 24 kW Grid-Connected Solar PV System Design

## Overview
This project presents the design, sizing, validation, and simulation of a 24 kW three-phase grid-connected rooftop solar PV system.

The system was designed as part of the EE4340 – Microgrids module.

## System Specifications
- 80 × 300 W Trina Solar Panels
- Total DC Capacity: 24 kW
- Huawei SUN2000-20KTL-M5 Inverter
- Three-phase grid connection
- DC/AC ratio: 1.2

## Work Performed
- Rooftop area assessment and panel layout optimization
- String sizing and inverter selection
- Energy yield calculation with derating factors
- Monthly grid export analysis
- PVSyst validation (<9% deviation from analytical results)
- PSCAD modeling of grid integration (630 kVA, 33/0.4 kV transformer model)
- Power quality verification (unity PF, stable PLL synchronization)

## Tools Used
- PVSyst
- PSCAD

## Results
- Estimated monthly generation: ~3034 kWh
- Confirmed stable grid injection under irradiance ramp-up, peak, intermittency, and shutdown scenarios
