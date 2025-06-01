# AXLE-Accelerators  
**Revolutionizing HVAC Reliability with Edge AI**  

---

## About Us  
AXLE-Accelerators develops dedicated AI hardware for predictive maintenance in HVAC and industrial systems. Our ultra-low-power ASICs enable real-time vibration analysis to detect equipment faults before failure, reducing downtime and maintenance costs by up to 40%.

---

## What We Do  
- **HVAC-Specific AI Accelerators**  
  Custom ASIC/FPGA designs optimized for vibration-based fault detection in chillers, compressors, and rooftop HVAC units.  

- **Edge Intelligence for Industrial IoT**  
  Battery-powered wireless sensors with 5-year operation life, delivering real-time analytics at ≤10 mW.  

- **Certified Reliability**  
  Designed for ISO 10816 compliance and industrial environments (-40°C to +85°C operation).  

---

## Technical Highlights  
**AXLE Vibration Analytics ASIC Features**  
- On-chip FFT/STFT processing (1-10 kHz range)  
- MEMS sensor fusion interface (I²C/SPI)  
- Lightweight CNN/SVM accelerator (8-bit quantized)  
- LoRaWAN/Bluetooth LE connectivity  
- ≤2 ms inference latency  

**Target Applications**  
- Bearing wear detection in HVAC fans  
- Rotor imbalance identification  
- Fan blade misalignment alerts  
- Pump cavitation monitoring  

---

## Repository Contents  
- `/rtl`: SystemVerilog source for:  
  - AI Accelerator Core  
  - Memory Subsystem with DMA  
  - Predictive Maintenance Unit  
  - Synthetic Vibration Simulator  
- `/sim`: Icarus/GTKWave testbenches  
- `/docs`: Architecture diagrams & validation reports  

---

## Getting Started  
```
# Run simulation with synthetic vibration data
make simulate SENSOR_TYPE=HVAC
```

---

## Why Choose AXLE?  
- **HVAC-Optimized Architecture**  
  First ASIC specifically designed for HVAC vibration analytics.  
---

## Roadmap  
Q3 2025 - FPGA Prototype Release  
Q4 2025 - Pilot Program with HVAC OEMs  
Q1 2026 - ASIC Tapeout  

---

*AXLE-Accelerators - Predictive Maintenance. Perfected.*
