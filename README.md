# 🩺 REINA - RRT Evidence-Based Integrated Nursing & Attending Support

**Version 11** | Goal-Directed RRT Decision Support Tool for ICU Settings

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-11.0-green.svg)]()

## Overview

REINA is a clinical decision support tool designed to assist intensivists and ICU staff in making evidence-based decisions about Renal Replacement Therapy (RRT) in critically ill patients. The tool provides goal-directed prescription guidance backed by peer-reviewed evidence rather than protocol-based recommendations alone.

**Live Demo:** [https://shoyu21.github.io/REINA/](https://shoyu21.github.io/REINA/)

## 🆕 What's New in v11

### Dose Personalisation System
- **Interactive dose slider** allowing clinicians to modify prescribed doses (20-50 ml/kg/hr)
- **Transparent dose calculations** showing the formula: `Delivered = Prescribed × Efficiency Factor`
- **Live calculation preview** showing expected delivered dose in real-time
- **Clinical prompts** that adapt based on dose selection to support critical thinking
- **Evidence-based defaults**: 35 ml/kg/hr prescribed to achieve 20-25 ml/kg/hr delivered (accounting for ~72% efficiency)

### Additional v11 Features
- Improved MICU Protocol reference tables
- Enhanced dysnatremia management protocols
- Prescribed vs Delivered dose comparison
- Reset to default functionality

## 🎯 Key Features

### Three-Tiered Assessment Framework

1. **Tier 1: Emergency Indications** - Life-threatening conditions requiring immediate RRT
   - Uraemic encephalopathy/pericarditis
   - Refractory pulmonary oedema
   - Refractory hyperkalaemia (K⁺ >6.5 with ECG changes)
   - Severe metabolic acidosis (pH <7.1)
   - Dialysable toxin removal

2. **Tier 2: Treatment Goals** - Multi-select goals that drive prescription
   - Volume removal
   - Acid-base correction
   - Potassium control
   - Solute clearance
   - Sodium management

3. **Tier 3: Clinical Context** - Modifying factors
   - Sepsis/SIRS
   - Cardiorenal syndrome
   - Hepatorenal/Liver failure
   - Rhabdomyolysis
   - Tumour lysis syndrome
   - Brain injury/ICP concerns
   - Post-cardiac surgery
   - ECMO

### ☕ Coffee Analogy for Modality Selection

Understanding CRRT modalities made simple:
- **CVVH** (French Press) = Convection only - pressure-driven solute drag
- **CVVHD** (Pour Over) = Diffusion only - concentration gradient
- **CVVHDF** (Espresso Machine) = Both diffusion + convection

### 🫀 Hemodynamic Assessment

- Multi-select shock phenotype identification
- Pre-RRT hemodynamic stability check
- VExUS grade calculator
- Renal Resistive Index (RRI) calculation
- Integration with Dr. Ross Prager's shock calculator methodology

### 💉 Anticoagulation Selection

- Evidence-based citrate vs heparin decision support
- Automatic contraindication detection
- Circuit history integration
- Citrate toxicity management protocol

### 📊 Monitoring Protocols

- Colour-coded monitoring timeline by blood tube colour
- Electrolyte monitoring schedules
- Citrate accumulation protocol
- Goal achievement tracking

### 🧂 Dysnatremia Management

- Hyponatremia protocol (Na⁺ <125 mmol/L)
- Hypernatremia protocol (Na⁺ >155 mmol/L)
- Custom dialysate preparation tables
- Safe correction rate guidance (≤10 mmol/L/24h)

## 📚 Evidence Base

REINA integrates evidence from:
- **STARRT-AKI** (NEJM 2020) - RRT timing
- **AKIKI** (JAMA 2016) - Delayed strategy safety
- **IDEAL-ICU** (NEJM 2018) - Septic shock timing
- **RENAL/ATN Trials** - Dosing evidence
- **IVOIRE Trial** - High-volume hemofiltration in sepsis
- **Cochrane Reviews** - Anticoagulation evidence
- **KDIGO 2012 Guidelines**
- **NUH MICU RRT Protocol v6.0**

## 🚀 Getting Started

### Quick Start
Simply visit: [https://shoyu21.github.io/REINA/](https://shoyu21.github.io/REINA/)

### Local Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shoyu21/REINA.git
   ```
2. Open `index.html` in a modern web browser

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- No server or database required - runs entirely client-side

## ⚠️ Disclaimer

REINA is a clinical decision support tool intended to assist healthcare professionals in their clinical decision-making. It is **NOT** a substitute for clinical judgement, training, or experience.

- All recommendations should be verified against local protocols
- Clinical decisions must be made by qualified healthcare professionals
- The tool should be used in conjunction with, not instead of, clinical assessment
- No patient data is collected or stored by this application

See [DISCLAIMER.md](DISCLAIMER.md) for full disclaimer.

## 🔒 Privacy

REINA operates entirely client-side and does not:
- Collect any patient data
- Send data to external servers
- Require user accounts or authentication
- Store any information between sessions

See [PRIVACY.md](PRIVACY.md) for full privacy policy.

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### Areas for Contribution
- Evidence updates from new trials
- Additional clinical scenarios
- UI/UX improvements
- Accessibility enhancements
- Translation to other languages

## 📖 Citation

If you use REINA in research or clinical publications, please cite:

```bibtex
@software{reina2025,
  title = {REINA: RRT Evidence-Based Integrated Nursing & Attending Support},
  author = {shoyu21},
  year = {2025},
  version = {11.0},
  url = {https://github.com/shoyu21/REINA}
}
```

See [CITATION.cff](CITATION.cff) for full citation information.

## 📝 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- NUH MICU team for protocol reference
- Dr. Ross Prager for shock calculator methodology
- Critical Care Time podcast for educational content
- The ARISE project team for inspiration

---

**Note:** REINA is under active development. Features and recommendations may change as new evidence emerges.

*Last updated: January 2025*
