# Contributing to REINA

Thank you for your interest in contributing to REINA! This document provides guidelines for contributing to the project.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Reporting Issues](#reporting-issues)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Clinical Feedback](#clinical-feedback)
- [Evidence Updates](#evidence-updates)
- [Development Guidelines](#development-guidelines)

---

## Code of Conduct

### Our Standards

We are committed to providing a welcoming and professional environment. All contributors are expected to:

- Be respectful and constructive in communications
- Focus on patient safety and clinical accuracy
- Acknowledge diverse perspectives and expertise
- Accept constructive feedback gracefully

### Clinical Responsibility

Given the clinical nature of this tool, contributors must:

- Prioritize patient safety in all suggestions
- Support recommendations with evidence where possible
- Acknowledge limitations and uncertainties
- Avoid making claims beyond the evidence

---

## How Can I Contribute?

### Types of Contributions

| Type | Description | How to Submit |
|------|-------------|---------------|
| 🐛 Bug Reports | Technical issues or errors | GitHub Issue |
| 💡 Feature Requests | New functionality ideas | GitHub Issue |
| 📚 Evidence Updates | New trials or guidelines | GitHub Issue |
| 🏥 Clinical Feedback | Practice-based insights | GitHub Issue |
| 📝 Documentation | Improvements to docs | GitHub Issue |
| 🔧 Code Contributions | By arrangement only | Contact first |

---

## Reporting Issues

### Before Submitting

1. **Check existing issues** to avoid duplicates
2. **Verify the issue** is reproducible
3. **Note browser and device** information

### Bug Report Template

When reporting a bug, please include:

```markdown
**Description**
A clear description of the issue

**Steps to Reproduce**
1. Go to '...'
2. Enter '...'
3. Click '...'
4. See error

**Expected Behavior**
What should happen

**Actual Behavior**
What actually happens

**Environment**
- Browser: [e.g., Chrome 120]
- Device: [e.g., Desktop/Mobile]
- OS: [e.g., Windows 11]

**Screenshots**
If applicable

**Clinical Impact**
Could this affect clinical decisions? How?
```

---

## Suggesting Enhancements

### Enhancement Request Template

```markdown
**Problem Statement**
What clinical or usability problem does this address?

**Proposed Solution**
Describe your suggested enhancement

**Clinical Rationale**
Why would this improve clinical decision-making?

**Evidence Base**
Any supporting evidence or guidelines?

**Alternatives Considered**
Other approaches you've thought about

**Additional Context**
Any other relevant information
```

---

## Clinical Feedback

### We Value Clinical Insights

As REINA is designed for ICU clinicians, feedback from practicing healthcare professionals is invaluable:

- **Workflow observations**: How the tool fits into clinical practice
- **Edge cases**: Clinical scenarios not well-handled
- **Usability issues**: Interface elements that are confusing
- **Missing features**: Functionality that would be helpful
- **Regional variations**: Differences in local practice

### Clinical Feedback Template

```markdown
**Your Background**
- Role: [e.g., Intensivist, ICU Nurse, Fellow]
- Setting: [e.g., MICU, SICU, Mixed ICU]
- Experience with RRT: [e.g., Daily, Weekly, Occasional]

**Feedback Type**
[ ] Workflow issue
[ ] Clinical accuracy concern
[ ] Missing feature
[ ] Usability suggestion
[ ] Other

**Description**
Detailed description of your feedback

**Clinical Scenario**
If applicable, describe a case where this was relevant

**Suggested Improvement**
Your recommendation
```

---

## Evidence Updates

### Keeping REINA Current

Medical evidence evolves continuously. Help us stay current by reporting:

- New clinical trials relevant to RRT
- Updated guidelines (KDIGO, SCCM, etc.)
- Meta-analyses or systematic reviews
- Corrections to existing evidence summaries

### Evidence Update Template

```markdown
**Citation**
Full reference in standard format

**Key Finding**
Main result relevant to REINA

**Clinical Implication**
How should this change REINA's recommendations?

**REINA Section Affected**
[ ] Initiation timing
[ ] Modality selection
[ ] Dosing
[ ] Anticoagulation
[ ] Monitoring
[ ] Discontinuation
[ ] Other: ___

**Evidence Quality**
- Study type: [RCT, meta-analysis, etc.]
- Sample size: 
- Limitations:

**Link to Full Text**
If available
```

---

## Development Guidelines

### Architecture Principles

REINA follows these design principles:

1. **Single-file deployment**: All functionality in one HTML file
2. **Client-side only**: No server dependencies
3. **Privacy by design**: No data collection
4. **Evidence-based**: All recommendations supported by evidence
5. **Real-time updates**: Calculations update automatically
6. **Mobile-friendly**: Responsive design

### Code Style

If you're proposing code changes:

- **HTML/CSS/JavaScript** in single file
- **Semantic HTML** structure
- **CSS custom properties** for theming
- **Vanilla JavaScript** (no frameworks)
- **Comments** for clinical logic

### Clinical Logic Requirements

Any clinical logic must:

- Reference supporting evidence
- Include appropriate caveats
- Handle edge cases gracefully
- Fail safely (conservative recommendations when uncertain)

---

## Review Process

### How Contributions Are Reviewed

1. **Initial triage**: Acknowledgment within 1 week
2. **Clinical review**: Assessment of clinical accuracy and safety
3. **Technical review**: Code and implementation review
4. **Integration**: If approved, incorporated into next release

### Timeline

- Simple issues: 1-2 weeks
- Feature requests: Variable (may be queued for future versions)
- Evidence updates: Prioritized based on clinical impact

---

## Recognition

Contributors may be acknowledged in:

- Release notes
- README acknowledgments section
- CITATION.cff (for significant contributions)

Please indicate if you prefer to remain anonymous.

---

## Questions?

If you're unsure how to contribute or have questions:

1. Open a GitHub issue with the "question" label
2. Describe what you're trying to accomplish
3. We'll guide you to the best approach

---

## License Reminder

By contributing to REINA, you agree that your contributions will be subject to the project's proprietary license. See [LICENSE](LICENSE) for details.

---

*Thank you for helping improve REINA for clinicians and patients everywhere!*
