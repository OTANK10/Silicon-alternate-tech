# BLAST Device Characterization and Testing

This repository contains research work on BLAST (Biocompatible biLayer graphene-based Artificial Synaptic Transistor) devices - a breakthrough in neuromorphic computing that mimics brain synapses using graphene and Nafion materials. The project focuses on electrical characterization and stress testing of these novel neuromorphic devices using Agilent Source Measure Units (SMUs).

* What are BLAST Devices?

![image](https://github.com/user-attachments/assets/a36fd4bd-c3d6-4fa7-a3b4-0820fb21306f)  


BLAST devices represent a significant advancement in neuromorphic computing, bridging the gap between traditional CMOS-based computers and brain-like computational systems. These devices exhibit:

Long-term Potentiation (LTP): Similar to biological synaptic connections  
Metaplasticity: Ability to modify plasticity based on synaptic activity history  
Ultra-low switching energy: Significantly lower than previous neuromorphic devices  
Biocompatibility: Safe for biological system integration  

* Device Architecture  
The BLAST device consists of:  

Graphene layers: Providing excellent electrical conductivity  
Nafion electrolyte: Ion-conducting polymer whose properties change with proton concentration  
Source-Drain configuration: Standard transistor layout for electrical measurements  

* Research Objectives

Electrical Characterization: Comprehensive testing of BLAST device electrical properties  
Stress Testing: Evaluating device performance under various electrical stress conditions  
Synaptic Behavior Analysis: Investigating neuromorphic properties like LTP and metaplasticity  
Parameter Optimization: Finding optimal operating conditions for different applications  

# Methodology

![image](https://github.com/user-attachments/assets/f314b3c2-4020-4e4f-b8a5-d6b30b42c17a)  

* Equipment Used

Agilent/Keysight Source Measure Units (SMUs): Precision electrical measurement and sourcing  
Keysight B2900 Quick IV Measurement Software: Data acquisition and analysis  
Custom test fixtures: For device mounting and electrical connections  

* Test Protocols

1. Ramp and Level Testing  

Systematic voltage/current ramping  
Static level measurements  
I-V characterization curves  

2. Pulse Testing

Pulse width modulation studies  
Pulse amplitude variations  
Response time measurements  

3. Stress Testing

Extended operation under various conditions  
Temperature cycling (planned)  
Voltage stress applications  

# Key Findings

* Synaptic Behavior Demonstration  

![image](https://github.com/user-attachments/assets/f3e55ba9-b16a-4a09-9040-73a288508ff3)  


Successfully demonstrated synaptic-like current responses  
Observed characteristic triangular wave patterns indicating proper device operation  
Measured current ranges: ~10⁻⁶ to 10⁻⁴ Amperes  

Pulse Width Dependency  

Device response varies predictably with pulse width  
Decreasing pulse width shows progressive current modulation  
Consistent with biological synaptic timing dependencies  

Device Reliability  

Stable operation across multiple test cycles  
Reproducible electrical characteristics  
Low noise floor in measurements  

* Data Analysis  

Key Metrics Analyzed

Current-Voltage (I-V) characteristics  
Pulse response dynamics  
Long-term stability  
Switching energy calculations  
Conductance modulation range  

* Analysis Tools  

![image](https://github.com/user-attachments/assets/47066423-a942-44d9-aedb-35b0659d73d8)  

Keysight Quick IV
Python-based data processing scripts  
MATLAB integration for advanced signal analysis  
Statistical analysis of device-to-device variations  

*This research was conducted as part of undergraduate research at UMass Amherst BME Labs. For questions about methodologies or data, please reach out through the contact information below.*
