# AI Vegetative Restoration UAV

**Open-source AI and UAV platform for precision vegetative restoration and intelligent seed dispersal.**

## Overview

**AI Vegetative Restoration UAV** is an open-source technological platform designed for precision ecological restoration using Unmanned Aerial Vehicles (UAVs), embedded artificial intelligence, computer vision, and intelligent seed dispensing.

The platform was developed as part of the research project **“Artificial Intelligence for Precision Reforestation Using Drone Technology”**, funded by the **Fondo Estatal de Ciencia, Tecnología e Innovación (FECTI), Chihuahua, Mexico**.

The system is designed as a **modular and UAV-independent architecture**, allowing its integration with different commercial and research drone platforms. Experimental validation was conducted using **DJI Matrice 100** and **Holybro X650** UAV platforms.

## Objectives

The main objective of the project is to develop an intelligent and scalable technological platform capable of:

* Identifying suitable areas for vegetative restoration using artificial intelligence.
* Processing RGB and LiDAR information using embedded computing.
* Performing selective aerial dispersion of pelleted seeds.
* Supporting the application of solid agro-inputs for ecological restoration.
* Operating with different UAV platforms.
* Enabling scalable restoration strategies for large or difficult-to-access areas.

## System Architecture

The platform integrates four main technological components:

### 1. Embedded Artificial Intelligence

An embedded AI architecture processes environmental information collected by the UAV to identify areas suitable for vegetative restoration.

The perception system integrates:

* RGB imagery
* LiDAR information
* Computer vision
* Deep learning
* Embedded inference

The objective is to perform **site-specific restoration**, avoiding seed dispersion in areas with low establishment potential.

### 2. Intelligent Seed Dispenser

A modular dispensing system was developed for controlled aerial deployment of pelleted seeds.

Main characteristics:

* **Payload capacity:** 500 g
* **Approximate capacity:** 5,400 pelleted *Pinus cembroides* seeds
* **Target seeding density:** 10 seeds/m²
* **Effective restoration area:** approximately 540 m² per payload

If approximately 50% of the evaluated terrain is suitable for restoration, the operational coverage is approximately **1,080 m² per flight**, corresponding to approximately **10 flights per hectare**.

### 3. UAV Integration and Control

The restoration system was designed to operate independently of a specific UAV platform.

The prototype has been experimentally integrated and tested with:

* DJI Matrice 100
* Holybro X650

This modular architecture facilitates adaptation to UAVs with different payload capacities and enables future large-scale deployment using multiple UAVs or higher-capacity aerial platforms.

### 4. Seed Pelletization

A pelletization process was developed to improve the mechanical properties of forest seeds during aerial deployment.

The process considers:

* Seed protection
* Adhesive materials
* Nutritional components
* Mechanical resistance
* Pellet uniformity
* Compatibility with the aerial dispensing mechanism

The methodology was experimentally evaluated using forest species including *Pinus cembroides* and *Pinus durangensis*.

## Field Validation

The system was evaluated under controlled and field conditions.

Initial experimental tests were conducted at **Tecnológico de Monterrey, Campus Chihuahua**, where the dispensing mechanism, UAV integration, flight control, and seed dispersion patterns were evaluated.

Field validation was subsequently conducted in **Nuevas Delicias, Chihuahua, Mexico**, in collaboration with local agricultural and livestock producers. These experiments allowed the platform to be evaluated under representative environmental and operational conditions.

## Repository Structure

```text
AI-Vegetative-Restoration-UAV/
│
├── software/
│   ├── embedded-ai/
│   ├── computer-vision/
│   ├── uav-control/
│   └── dispenser-control/
│
├── electronics/
│   ├── schematics/
│   ├── pcb/
│   ├── gerber/
│   └── bom/
│
├── mechanical/
│   ├── cad/
│   ├── step/
│   ├── stl/
│   └── drawings/
│
├── pelletization/
│   ├── protocols/
│   └── technical-report/
│
├── documentation/
│   ├── assembly/
│   ├── operation/
│   └── validation/
│
├── publications/
│
├── LICENSE
├── LICENSE-HARDWARE
├── LICENSE-DOCUMENTATION
├── NOTICE
├── CITATION.cff
└── README.md
```

## Scientific Publications

The development and experimental validation of the platform resulted in peer-reviewed scientific publications, including research on UAV control and embedded artificial intelligence for precision reforestation.

### Journal of Field Robotics

**Experimental Evaluation of an Observer-Based Controller for an Unmanned Aerial Vehicle in Reforestation Activities**

DOI: `10.1002/rob.22503`

### Drones

**Design and Field Validation of a Modular Vision-Guided UAV System for Real-Time Adaptive Vegetative Restoration**

DOI: `10.3390/drones10050379`

## Conference Publication

Part of the technological development was presented at the **IEEE Conference on Technologies for Sustainability (SusTech 2025)** through the work:

**“Modular Seed-Sowing Control System for Drone Reforestation.”**

## Open Technology

This project follows an **open technology approach** to facilitate scientific collaboration, reproducibility, technology transfer, and further development of UAV-based ecological restoration systems.

Different components of the repository are distributed under licenses appropriate to their nature:

| Component             | License                                           |
| --------------------- | ------------------------------------------------- |
| Software and firmware | Apache License 2.0                                |
| Electronic hardware   | CERN Open Hardware Licence Version 2 – Permissive |
| Mechanical designs    | CERN Open Hardware Licence Version 2 – Permissive |
| Documentation         | Creative Commons Attribution 4.0 International    |

Please refer to the corresponding license files in each directory before using or redistributing the materials.

## Applications

Potential applications of the platform include:

* Precision reforestation
* Ecological restoration
* Restoration of degraded land
* Aerial seed dispersal
* Site-specific application of restoration inputs
* Restoration of difficult-to-access areas
* UAV-based environmental monitoring
* Research and education in autonomous ecological restoration

## Scalability

The platform was conceived as a **modular, scalable, and UAV-independent system**.

The dispensing mechanism, embedded computing architecture, perception system, and control modules can be adapted to UAVs with different payload capacities. This enables the technology to evolve from experimental single-UAV missions toward coordinated or higher-capacity systems for large-scale ecological restoration.

## Research and Education

The project also contributed to the training of undergraduate and graduate students in:

* Mechatronics Engineering
* Biotechnology Engineering
* Sustainable Development Engineering
* Artificial Intelligence
* Embedded systems
* UAV technology
* Ecological restoration

A total of **15 undergraduate and graduate students** participated directly in research, prototype development, experimental validation, environmental assessment, and scientific publications associated with the project.

## Funding

This research and technological development was supported by the:

**Fondo Estatal de Ciencia, Tecnología e Innovación (FECTI)**
State of Chihuahua, Mexico

Project:

**“Inteligencia Artificial para la Reforestación de Precisión usando Tecnología de Drones”**

Project ID:

**FECTI/2024/CV-CDF/020**

## Institution

**Tecnológico de Monterrey**
School of Engineering and Sciences
Campus Chihuahua
Chihuahua, Mexico

## Citation

If you use this platform, hardware design, software, or documentation in academic research, please cite the corresponding scientific publications and this repository.

A `CITATION.cff` file is provided to facilitate citation of the project.

## Contributing

Contributions that improve the hardware, software, artificial intelligence models, documentation, or ecological restoration methodologies are welcome.

Please review the `CONTRIBUTING.md` guidelines before submitting modifications or proposing new features.

## Disclaimer

This platform is a research and development prototype. Users are responsible for complying with applicable UAV regulations, environmental regulations, land-use requirements, and safety procedures before deploying the system in field conditions.

## License

This repository contains software, hardware designs, and documentation distributed under different open licenses.

See the corresponding license files and individual directories for detailed licensing information.
