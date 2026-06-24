[README.md](https://github.com/user-attachments/files/29299645/README.md)
# Pranav Gumma Cyber Risk Consulting Portfolio

A publishable, interactive cybersecurity consulting portfolio built as one **self-contained HTML file**. All styling, JavaScript, case-study data, fallback data, and interactive logic are embedded in `index.html`.

## Flagship Activision case study

The website now includes an independent, public-data cyber risk and controls assessment of Activision. It contains:

- Executive cyber-risk assessment and board-level conclusion
- Official-source evidence register and scoped data-flow model
- 12-item risk register with inherent and residual hypotheses
- Risk owners, business scenarios, control treatment, KRIs, and framework mappings
- NIST CSF 2.0 public-evidence profile
- Player identity, privileged access, software delivery, resilience, privacy, vendor, and game-integrity control design
- NIST SP 800-53 and CIS Controls crosswalk
- 20-item audit evidence request tracker
- Six detailed design and operating-effectiveness test procedures
- Three-phase 90-day remediation roadmap with CSV export
- Build-pipeline compromise incident tabletop and decision scorecard

The assessment is explicitly labeled as an educational portfolio exercise. It was not commissioned by Activision or Microsoft, uses no non-public information, and does not claim to establish Activision's actual internal control maturity.

## Additional interactive projects

- Live CISA Known Exploited Vulnerabilities prioritization dashboard
- NIST CSF 2.0 maturity assessment and 90-day roadmap generator
- AWS IAM policy analyzer
- Executive cybersecurity report generator
- Security framework crosswalk and CSV export

## Publish with Netlify

Drag `index.html` into Netlify Drop, or upload this entire folder.

## Data and privacy

The CISA dashboard requests the official Known Exploited Vulnerabilities JSON feed. If the request is unavailable, it uses a clearly identified embedded snapshot. IAM policy analysis and all case-study tools run locally in the browser and do not upload entered content.

## Validation completed

The final build was checked for:

- Valid JavaScript syntax
- No duplicate HTML IDs
- Desktop and mobile responsiveness
- Zero horizontal overflow at a 390-pixel viewport
- Activision section navigation
- Risk-register filters and detail views
- Evidence progress tracker
- Control, audit-test, and roadmap rendering
- Existing vulnerability, NIST, IAM, and reporting tools
