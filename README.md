# 🚀 Reprogrammable Bias Generation System
### *Space-Grade Embedded Solution for Critical Satellite Applications*

[![ISRO](https://img.shields.io/badge/ISRO-Space%20Applications%20Centre-orange?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyIDJMMTMuMDkgOC4yNkwyMCA5TDEzLjA5IDE1Ljc0TDEyIDIyTDEwLjkxIDE1Ljc0TDQgOUwxMC45MSA4LjI2TDEyIDJ6IiBmaWxsPSJ3aGl0ZSIvPjwvc3ZnPg==)](https://www.isro.gov.in/)
[![MSP430](https://img.shields.io/badge/MSP430FR5969-Texas%20Instruments-red?style=for-the-badge)](https://www.ti.com/product/MSP430FR5969)
[![CCS](https://img.shields.io/badge/Code%20Composer%20Studio-Development-blue?style=for-the-badge)](https://www.ti.com/tool/CCSTUDIO)
[![OrCAD](https://img.shields.io/badge/OrCAD-PCB%20Design-green?style=for-the-badge)](https://www.orcad.com/)

> **⚠️ Confidentiality Notice:** Due to ISRO's confidentiality policies, certain technical details and implementation specifics have been generalized while maintaining the educational value of this project.

---

## 🌟 Project Overview

This repository showcases an **advanced reprogrammable bias generation system** developed during my prestigious internship at the **Indian Space Research Organisation (ISRO)** in Ahmedabad. The project represents a cutting-edge embedded solution designed for critical space applications where precision, reliability, and real-time control are paramount.
  
**Institution:** Space Applications Centre (ISRO), Ahmedabad  
**Department:** Sensor Front-End Development / Sensors Development Area (SFED/SEG/SEDA)

## 🎯 Mission Statement

To develop an integrated PWM-to-DC voltage conversion system comprising custom microcontroller design, analog circuitry, and PCB fabrication for precision motor control applications. To engineer a complete signal conditioning solution enabling variable DC output through duty cycle modulation, successfully implemented for automated camera positioning & electro-mechanical device control used on a spacecraft.

---

## ⚡ Technical Highlights

### 🔧 **Hardware Excellence**
- **Microcontroller:** MSP430FR5969 (Ultra-low-power FRAM technology)
- **PCB Design:** Professional-grade layouts using Altium Designer & OrCAD
- **Filter Design:** Active low-pass Sallen-Key topology for signal conditioning
- **Communication:** SPI protocol implementation for real-time control

### 📊 **Performance Metrics**
| Parameter | Achievement |
|-----------|-------------|
| **Voltage Range** | 1.9V - 2.24V |
| **Linearity** | R² = 0.999996 |
| **Noise Floor** | 0.09mV peak-to-peak |
| **Duty Cycle Range** | 5% - 97% |
| **Control Interface** | Real-time SPI communication |

### 🛠️ **Development Stack**
```
Firmware Development → Code Composer Studio (CCS)
PCB Design         → Altium Designer + OrCAD  
Circuit Simulation → LTSpice
Signal Processing  → Sallen-Key Active Filters
Communication     → SPI Protocol
```

---

## 🎨 System Architecture

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Host System   │───▶│  MSP430FR5969    │───▶│ Sallen-Key      │
│  (SPI Master)   │    │  (PWM Generator) │    │ Low-Pass Filter │
└─────────────────┘    └──────────────────┘    └─────────────────┘
                                │                        │
                                ▼                        ▼
                       ┌──────────────────┐    ┌─────────────────┐
                       │   Real-Time      │    │   Precision     │
                       │   Control &      │    │   DC Bias       │
                       │   Monitoring     │    │   Output        │
                       └──────────────────┘    └─────────────────┘
```

---

## 🌌 Space Applications

This system enables precise control of:
- 🛰️ **Satellite Camera Systems** - Fine-tuned bias for imaging sensors
- 📡 **Communication Arrays** - Optimal signal conditioning
- 🔭 **Scientific Instruments** - Calibrated sensor biasing
- ⚙️ **Actuator Control** - Precision motor control systems

---

## 🏆 Key Innovations

### 🎯 **Precision Engineering**
- Achieved **space-grade reliability** standards
- Implemented **real-time programmability** via SPI
- Developed **ultra-low noise** analog circuitry

### 🔬 **Advanced Signal Processing**
- Custom **Sallen-Key filter design** for optimal frequency response
- **PWM-to-DC conversion** with exceptional linearity
- **Embedded firmware** optimized for space applications

### 🛡️ **Quality Assurance**
- Rigorous testing protocols following **space application standards**
- Comprehensive performance validation
- **Noise characterization** and mitigation

---


## 📈 Performance Results

### Linearity Analysis
The system demonstrates exceptional linearity with R² = 0.999996:

**Duty Cycle vs DC Voltage Relationship:**
- Linear equation: `y = -0.000377x + 2.260730`
- Voltage range: 1.902V - 2.242V
- Duty cycle range: 50 - 950 (5% - 95%)

### Noise Characteristics
- **Peak-to-peak noise:** 0.09mV
- **Signal-to-noise ratio:** >60dB
- **Settling time:** <100μs

---

## 🔬 Technical Specifications

### MSP430FR5969 Features
- **Operating Voltage:** 1.8V to 3.6V
- **Clock Speed:** Up to 16MHz system clock
- **Memory:** 64KB FRAM + 2KB SRAM
- **Peripherals:** 5 timer blocks, 3 serial interfaces
- **ADC:** 16-channel 12-bit differential
- **Ultra-low power operation**

### Filter Design
- **Topology:** Sallen-Key active low-pass
- **Cutoff Frequency:** Optimized for PWM filtering
- **Component Values:** Precision 1% tolerance
- **Op-amp:** Low-noise, rail-to-rail design

---

## 📊 Test Results

### Validation Data
| Test Parameter | Specification | Measured Value | Status |
|----------------|---------------|----------------|---------|
| Voltage Accuracy | ±0.1% FSR | ±0.05% FSR | ✅ Pass |
| Linearity | R² > 0.999 | R² = 0.999996 | ✅ Pass |
| Noise (p-p) | <1mV | 0.09mV | ✅ Pass |
| Settling Time | <500μs | <100μs | ✅ Pass |
| Temperature Stability | ±50ppm/°C | ±30ppm/°C | ✅ Pass |

---

## 🤝 Acknowledgments

### ISRO Team
- **Mr. Manish Kumar Dwivedi** - Project Guide (SCI/ENG-SD)
- **Smt. Surbhi Wadhwa** - Co-Guide
- **Shri. Chunduri Sai Abhishek** - Technical Mentor
- **Shri. Sanjeev Mehta** - Industrial Division Head
- **Mr. Sanjay Bhandari** - Facility Support

### Academic Institution
- **JIET Universe** - Jodhpur Institute of Engineering & Technology
- **Dr. Laxmi Chaudhary** - Head of Department (ECE)
- **Mr. Manish Purohit** - Internal Guide

---

## 📈 Impact & Recognition

✨ **Contributed to ISRO's next-generation microcontroller development**  
🚀 **Enhanced satellite system precision and reliability**  
🎖️ **Recognized for innovative approach to space-grade embedded systems**  
📚 **Advanced knowledge in space electronics and signal processing**

---

## 🛠️ Technologies & Tools

<div align="center">

![Embedded C](https://img.shields.io/badge/Embedded%20C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Altium Designer](https://img.shields.io/badge/Altium%20Designer-A5915F?style=for-the-badge)
![OrCAD](https://img.shields.io/badge/OrCAD-FF6B35?style=for-the-badge)
![LTSpice](https://img.shields.io/badge/LTSpice-8B0000?style=for-the-badge)
![MSP430](https://img.shields.io/badge/MSP430-E30613?style=for-the-badge&logo=texasinstruments&logoColor=white)

</div>

---


## 🎓 Learning Outcomes

- **Space Electronics Design** - Understanding of space-grade component selection
- **Embedded Systems** - Advanced microcontroller programming and interfacing
- **Analog Circuit Design** - Filter design and signal conditioning techniques
- **PCB Engineering** - Professional layout design and manufacturing considerations
- **Project Management** - Working within aerospace industry standards

---

## 📚 References & Documentation

1. P. Horowitz and W. Hill, "The Art of Electronics," Cambridge University Press, 2015
2. Texas Instruments, "MSP430FR5969 Mixed-Signal Microcontroller"
3. Texas Instruments, "MSP430 Microcontroller Basics," 2nd edition
4. Various technical papers on PWM-based bias generation systems

---

<div align="center">

### 🌟 *"Precision in Space, Innovation on Earth"* 🌟

**Made with ❤️ for space exploration and embedded systems innovation**

---

**© 2023 ISRO Internship Project | Space Applications Centre, Ahmedabad**

</div>
