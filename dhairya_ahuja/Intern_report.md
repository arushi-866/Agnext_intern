# Low-Power NIR Automation & Product Development Platform

---

## Internship Technical Report (6 Months)

**Intern:** Dhairya Ahuja  
**Duration:** January 2026 – July 2026  
**Primary Focus:** Automation & Modeling on Low-Power NIR Devices  
**Secondary Track:** Avocado Dry Matter Meter (Full Product Lifecycle)  
**Additional Track:** Market Research & Target Strategy  

---

# Project Description

This internship focuses on developing a **low-power Near-Infrared (NIR) sensing ecosystem**, integrating:

- Embedded system configuration
- Spectral preprocessing automation
- Hybrid chemometric modeling (PLS + ANN)
- Low-power model deployment
- Avocado Dry Matter (DM) device development
- Structured global market research
- Product positioning & pitch preparation

The goal is to create a **hardware-to-software NIR product framework** capable of moving from sensor-level acquisition to market-ready product strategy.

---

# Mindmap

```plantuml
@startmindmap
title Low-Power NIR Automation & Product Development

skinparam nodesep 20
skinparam ranksep 30
skinparam defaultFontSize 14
scale 0.8

* NIR Internship Platform

** Embedded Systems Foundation
*** Raspberry Pi OS Lite
*** X11 + Openbox
*** Tkinter Touch GUI
*** On-Screen Keyboard Integration
*** Boot-to-GUI Optimization

** Low-Power NIR Automation (Primary Focus)
*** Spectral Acquisition
*** Convert to Absorbance (log 1/R)
*** SNV Correction
*** Savitzky-Golay Filtering
*** Feature Engineering
*** PLS Regression
*** ANN Hybrid Model
*** Cross-Validation
*** RMSEP Optimization
*** Embedded Deployment

** Avocado DM Meter Development
*** Scientific Basis (Moisture ↓ Oil ↑)
*** 640–1050 nm Range
*** O–H (960 nm)
*** C–H (900–920 nm)
*** Interactance Geometry
*** MEMS Spectrometer
*** Outer Case Design
*** Prototype Calibration
*** Field Testing

** Market Research & Strategy
*** Global NIR Competitors
*** Import-Export Benchmarking
*** Wheat & Mustard Analysis
*** SaaS & QaaS Models
*** Target Market Selection
*** Pitch Deck Creation

** Automation Systems
*** Python Market Watch
*** AI Filtering Engine
*** Excel Intelligence DB
*** Duplicate Detection
*** Continuous Update System

@endmindmap
```

## Internship Gantt Chart (6 Months)

```mermaid
gantt
    title Low-Power NIR Automation Internship
    dateFormat YYYY-MM-DD
    axisFormat %b %d
    excludes weekends

    section Phase 1 - Embedded Systems
    Raspberry Pi Setup        :a1, 2026-01-20, 7d
    GUI Development           :a2, after a1, 7d
    OSK Integration           :a3, after a2, 7d
    Embedded Finalization     :milestone, m1, after a3, 0d

    section Phase 2 - NIR Modeling
    Optical Research          :b1, 2026-02-10, 10d
    Preprocessing Pipeline    :b2, after b1, 10d
    PLS Modeling              :b3, after b2, 10d
    ANN Hybrid Model          :b4, after b3, 10d
    Automation Framework      :milestone, m2, after b4, 0d

    section Phase 3 - Avocado DM Meter
    Optical Design            :c1, 2026-04-01, 10d
    Hardware Selection        :c2, after c1, 10d
    Outer Case Design         :c3, after c2, 7d
    Prototype Integration     :c4, after c3, 10d
    Lab Calibration           :c5, after c4, 14d
    MVP Validation            :milestone, m3, after c5, 0d

    section Phase 4 - Market Research
    Competitor Mapping        :d1, 2026-05-20, 10d
    Trade Analysis            :d2, after d1, 10d
    Target Market Strategy    :d3, after d2, 10d
    Pitch Preparation         :milestone, m4, after d3, 0d

    section Phase 5 - Optimization & Deployment
    Model Optimization        :e1, 2026-06-20, 10d
    Embedded Deployment       :e2, after e1, 10d
    Performance Benchmarking  :e3, after e2, 7d
    Final Demo & Report       :e4, after e3, 7d
    Internship Completion     :milestone, m5, 2026-07-30, 0d
```

