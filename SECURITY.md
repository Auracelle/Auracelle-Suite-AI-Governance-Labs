# Security Policy — Auracelle AI Governance Labs

**Wargaming the Governance Asynchronously™**

---

## Supported Versions

This repository hosts the public-facing platform communications website for the Auracelle AI Governance Labs Simulation Suite. The following table reflects the current support status:

| Version | Status |
|---------|--------|
| Current (`main` branch) | ✅ Actively maintained |
| Archived / prior releases | ❌ Not supported |

The live simulation deployments (Stress Point, Orion, Lyra, Bach) are separately maintained and subject to their own security practices.

---

## Scope

This security policy covers:

- The static site hosted in this repository (`index.html`, `hero_image.png`)
- Any linked live simulation deployments under the `auracelle.github.io` domain
- The WinterStorm2030 demo deployment at `https://auracelle.github.io/Auracelle-WinterStorm2030-Demo/`

This policy does **not** cover:

- Third-party platforms (GitHub Pages infrastructure, Streamlit, Google Fonts CDN)
- Institutional systems operated by Bath Spa University, UC Berkeley CLTC, or NATO STO SAS-219
- Any classified or restricted systems associated with institutional partnerships

---

## Reporting a Vulnerability

Auracelle AI Governance Labs takes the security and integrity of its research platform seriously. If you discover a security vulnerability, please follow responsible disclosure practices.

**Do not open a public GitHub Issue for security vulnerabilities.**

### How to Report

Contact Grace-Alice Evans directly and privately via:

- **LinkedIn:** [https://www.linkedin.com/in/grace-alice-evans-5a9632a3](https://www.linkedin.com/in/grace-alice-evans-5a9632a3)

Please include in your report:

1. A clear description of the vulnerability
2. The affected component (URL, file, or feature)
3. Steps to reproduce the issue
4. Potential impact assessment
5. Any suggested mitigation, if known

---

## Response Timeline

| Stage | Target Timeframe |
|-------|-----------------|
| Acknowledgement of report | Within 5 business days |
| Initial assessment | Within 10 business days |
| Remediation (critical) | Within 30 days |
| Remediation (non-critical) | Within 90 days |
| Public disclosure (coordinated) | Upon mutual agreement |

---

## Security Considerations for This Repository

This is a **static single-page website** with no backend, no database, no authentication system, and no user data collection. Key security notes:

- All canvas animations are client-side JavaScript with no external API calls
- The hero image and all assets are locally referenced with no CDN dependency for assets
- Google Fonts is loaded via external CDN — standard web practice
- No cookies, localStorage, or session data are used
- No form submissions or user inputs are processed

---

## Proprietary Data Protection

Given the sensitive institutional and research context of this platform:

- **Framework taxonomies, scoring formulae, and simulation architectures** embedded in the code are proprietary IP. Any attempt to extract, reverse-engineer, or reproduce these constitutes a violation of the LICENSE.txt terms.
- **NATO STO SAS-219 materials** referenced or linked are subject to NATO information handling policies.
- Simulation access credentials (where applicable) are distributed only through authorised institutional channels.

---

## Acknowledgements

Responsible disclosure of valid security issues will be acknowledged in this document (with the reporter's permission). Auracelle AI Governance Labs is grateful to the research and security community for upholding responsible disclosure standards.

---

*© 2025–2026 Grace-Alice Evans / Auracelle AI Governance Labs. All Rights Reserved.*
