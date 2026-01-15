# REINA Privacy Policy

**Last Updated:** January 2025

---

## Overview

REINA (RRT Evidence-Based Integrated Nursing & Attending Support) is designed with privacy as a fundamental principle. This document outlines how data is handled when using REINA.

---

## Data Collection

### What We Do NOT Collect

REINA **does not** collect, store, or transmit:

- ❌ Patient names or identifiers
- ❌ Medical record numbers
- ❌ Dates of birth or admission
- ❌ Contact information
- ❌ IP addresses
- ❌ Device identifiers
- ❌ Usage analytics
- ❌ Any personally identifiable information (PII)
- ❌ Any protected health information (PHI)

### Client-Side Processing

All calculations and recommendations are performed **entirely within your web browser**:

- No data is transmitted to external servers
- No data is stored in databases
- No data persists after closing the browser tab
- No cookies are used
- No local storage is used

---

## Technical Architecture

### How REINA Works

1. **Static Hosting**: REINA is hosted as a static HTML file on GitHub Pages
2. **No Backend**: There is no server-side processing or database
3. **No APIs**: The tool does not connect to external data services
4. **Browser-Only**: All logic executes in the user's web browser

### Data Flow

```
User enters data → Browser processes locally → Results displayed
                    (No external transmission)
```

---

## Best Practices for Users

While REINA does not collect data, we recommend the following practices:

### In Clinical Settings

- Use REINA on hospital-approved devices when possible
- Do not enter actual patient identifiers (the tool does not require them)
- Close the browser tab when finished to clear any entered values
- Follow your institution's policies for clinical decision support tools

### On Shared Devices

- Clear browser data after use if using a shared computer
- Do not save or bookmark pages with entered data
- Be aware of your surroundings when entering clinical information

---

## Third-Party Services

### GitHub Pages

REINA is hosted on GitHub Pages. GitHub's privacy policy applies to the hosting infrastructure:

- GitHub may collect standard web server logs (IP addresses, browser type)
- This is standard for any website and is not controlled by REINA developers
- GitHub's privacy policy: https://docs.github.com/en/site-policy/privacy-policies

### No Other Third Parties

REINA does not integrate with:

- Analytics services (Google Analytics, etc.)
- Advertising networks
- Social media platforms
- External APIs or services

---

## Compliance

### PDPA (Singapore)

REINA is designed to comply with Singapore's Personal Data Protection Act:

- No personal data collection
- No consent required (as no data is collected)
- No cross-border data transfer
- No data retention

### HIPAA (United States)

While not specifically designed for US healthcare:

- No PHI is collected or stored
- No transmission of health information
- Client-side processing eliminates server-side risks

### GDPR (European Union)

REINA's architecture aligns with GDPR principles:

- Data minimization (no collection)
- Privacy by design
- No tracking or profiling

---

## Institutional Use

### For Healthcare Organizations

If your institution is evaluating REINA for use:

- The tool requires no data sharing agreements
- No business associate agreements needed (no PHI handling)
- Can be used without IT infrastructure changes
- Consider institutional policies for clinical decision support tools

### For IT/Security Teams

Security considerations:

- Static HTML/CSS/JavaScript only
- No server-side code execution
- No external API calls
- No data storage mechanisms
- Can be reviewed and audited (source code visible)

---

## Children's Privacy

REINA is a professional medical tool intended for healthcare provider use. It is not designed for or directed at children, though it may be used by healthcare providers treating pediatric patients.

---

## Changes to This Policy

We may update this privacy policy periodically. Changes will be noted by updating the "Last Updated" date. Significant changes will be documented in the project repository.

---

## Contact

For privacy-related questions or concerns, please:

1. Open an issue in the project repository
2. Review the source code (publicly available)

---

## Summary

| Aspect | Status |
|--------|--------|
| Patient data collection | ❌ None |
| Usage tracking | ❌ None |
| Cookies | ❌ None |
| External data transmission | ❌ None |
| Server-side storage | ❌ None |
| Account required | ❌ No |
| Data processing location | ✅ User's browser only |

---

*REINA is committed to privacy by design. The simplest way to protect data is to never collect it.*
