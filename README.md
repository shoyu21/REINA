# REINA - RRT Evidence-Based Integrated Support

**Goal-Directed Renal Replacement Therapy Decision Support for Critical Care**

[![Version](https://img.shields.io/badge/version-9.4-blue.svg)](https://github.com/shoyu21/REINA)
[![License](https://img.shields.io/badge/license-Proprietary-red.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Web%20|%20Mobile%20|%20Desktop-green.svg)](https://shoyu21.github.io/REINA/)

---

## 🎯 What is REINA?

REINA is an evidence-synthesized clinical decision support tool designed to assist intensivists and critical care teams with Renal Replacement Therapy (RRT) decisions in the ICU setting. Moving beyond simple protocol-based recommendations, REINA provides goal-directed, personalized guidance throughout the complete RRT pathway—from initiation through discontinuation.

**Live Tool:** [https://shoyu21.github.io/REINA/](https://shoyu21.github.io/REINA/)

---

## ✨ Key Features

### Clinical Decision Framework
- **Three-Tiered Goal Selection**: Emergency indications → Treatment goals → Clinical context
- **Shock Phenotyping**: Distributive, cardiogenic, hypovolemic, obstructive, or mixed
- **Goal-Directed Prescriptions**: Recommendations tailored to individual patient goals

### Evidence-Based Guidance
- **RRT Timing**: Based on STARRT-AKI, AKIKI, IDEAL-ICU, ELAIN trials
- **Dosing**: Incorporates RENAL, ATN, and IVOIRE trial evidence
- **Anticoagulation**: Citrate vs heparin recommendations per KDIGO and Cochrane reviews

### Comprehensive Modules
| Module | Description |
|--------|-------------|
| 🚨 **Initiation** | Emergency criteria assessment with urgency stratification |
| 🎯 **Goals** | Multi-goal selection supporting concurrent indications |
| ☕ **Modality** | CVVH/CVVHD/CVVHDF selection with coffee filter analogy |
| 💉 **Anticoagulation** | Citrate/heparin/none with contraindication checking |
| 📋 **Prescription** | Complete Prismax settings with rationale |
| 📊 **Monitoring** | Timeline-based parameter tracking |
| 🧪 **Acidosis** | Structured metabolic acidosis workup framework |
| 🔄 **Transition** | CRRT→IHD and liberation criteria |
| 📚 **Evidence** | Quick reference to key trials |

### Smart Calculators
- Anion Gap with albumin correction
- Delta-Delta ratio
- Urine output rate
- VExUS Score (Venous Excess Ultrasound)
- Renal Resistive Index (RRI)
- MAP calculation

---

## 🚀 Quick Start

### Access Online
Simply visit: **[https://shoyu21.github.io/REINA/](https://shoyu21.github.io/REINA/)**

### Add to Mobile Home Screen

**iOS (iPhone/iPad):**
1. Open Safari → Navigate to REINA URL
2. Tap Share button (square with arrow)
3. Select "Add to Home Screen"
4. Name it "REINA" → Tap "Add"

**Android:**
1. Open Chrome → Navigate to REINA URL
2. Tap three-dot menu (⋮)
3. Select "Add to Home screen"
4. Name it "REINA" → Tap "Add"

---

## 📖 How to Use

### Step 1: Enter Patient Data
Input demographics, laboratory values, hemodynamics, and current clinical conditions in the left panel.

### Step 2: Select Treatment Goals
Use the three-tiered selection:
1. **Emergency Indications** (if present): Life-threatening K⁺, acidosis, uremia, pulmonary edema
2. **Treatment Goals**: Volume management, metabolic correction, uremia control, sepsis, toxin removal
3. **Clinical Context**: ARDS, brain injury, liver failure, heart failure

### Step 3: Review Recommendations
Navigate through tabs to see evidence-based guidance for:
- Initiation urgency
- Modality selection
- Anticoagulation choice
- Complete prescription with rationale
- Monitoring schedule
- Transition criteria

---

## 🔬 Evidence Base

REINA synthesizes evidence from major clinical trials:

| Trial | Key Finding |
|-------|-------------|
| **STARRT-AKI** (2020) | Early vs delayed RRT—no mortality difference; 44% avoided RRT with delayed strategy |
| **AKIKI** (2016) | Delayed strategy safe; 49% avoided RRT |
| **IDEAL-ICU** (2018) | No benefit from early RRT in septic shock |
| **RENAL + ATN** | 20-25 ml/kg/hr optimal; no benefit from higher doses |
| **IVOIRE** (2013) | High-volume HF shows no mortality benefit in sepsis |
| **Cochrane 2020** | Citrate: 60% less bleeding, 40% longer filter life vs heparin |

---

## ⚠️ Important Disclaimers

- **Educational Tool Only**: REINA is designed for educational purposes and clinical decision support
- **Not a Replacement**: Does not replace clinical judgment, institutional protocols, or direct patient assessment
- **No Patient Data Storage**: All calculations are performed client-side; no patient data is stored or transmitted
- **Regional Considerations**: Developed with Singapore ICU practice in mind; verify applicability to your setting

See [DISCLAIMER.md](DISCLAIMER.md) for full details.

---

## 🔒 Privacy

REINA operates entirely client-side:
- No patient data is collected, stored, or transmitted
- No cookies or tracking
- No account required
- Compliant with PDPA (Singapore) principles

See [PRIVACY.md](PRIVACY.md) for full details.

---

## 📄 License

REINA is proprietary software. See [LICENSE](LICENSE) for terms.

---

## 🙏 Acknowledgments

- Evidence synthesis informed by Critical Care Time podcast
- Hemodynamic assessment methodology inspired by Dr. Ross Prager (shockcalcs.com)
- Clinical feedback from ICU colleagues
- Built upon the foundation of [ARISE](https://github.com/shoyu21/ARISE) ICU Liberation tool

---

## 📬 Contact

For questions, feedback, or collaboration inquiries, please open an issue in this repository.

---

*REINA v9.4 | Goal-Directed RRT Decision Support*
*Last updated: January 2025*
