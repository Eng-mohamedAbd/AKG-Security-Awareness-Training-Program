# AKG IT Security Awareness Training

**Document ID:** IT-SEC-AWARE-01  
**Version:** 1.0  
**Owner:** IT Department  
**Approved by:** IT Manager  
**Last Updated:** June 2026  

---

## Overview

This repository contains AKG's mandatory Security Awareness Training for all new employees during the onboarding process. The training consists of five modules followed by a scored knowledge assessment.

### Delivery Formats

| Format | Location | Use Case |
|--------|----------|----------|
| Interactive HTML Site | `index.html` (GitHub Pages) | Primary delivery — onboarding |
| Markdown Modules | `/docs/` | Reference, offline, future editing |

---

## Training Modules

| # | Module | File |
|---|--------|------|
| 01 | Phishing & Social Engineering | [docs/01-phishing.md](docs/01-phishing.md) |
| 02 | Password & MFA Policy | [docs/02-passwords-mfa.md](docs/02-passwords-mfa.md) |
| 03 | Acceptable Use Policy | [docs/03-acceptable-use.md](docs/03-acceptable-use.md) |
| 04 | Incident Reporting | [docs/04-incident-reporting.md](docs/04-incident-reporting.md) |
| 05 | Physical Security & Clean Desk | [docs/05-physical-security.md](docs/05-physical-security.md) |

**Estimated Duration:** ~30 minutes  
**Pass Threshold:** 70% (7/10 questions)

---

## Hosting on GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. GitHub Pages will publish `index.html` automatically
5. Share the URL `https://<your-org>.github.io/<repo-name>/` with new employees

---

## Repository Structure

```
security-awareness/
├── index.html              # Full interactive training site
├── README.md               # This file
└── docs/
    ├── 01-phishing.md
    ├── 02-passwords-mfa.md
    ├── 03-acceptable-use.md
    ├── 04-incident-reporting.md
    └── 05-physical-security.md
```

---

## Maintenance

- Review and update content **annually** or following any significant security incident
- Quiz questions should be refreshed when AKG policies change
- All updates require IT Manager approval before merge to `main`

---

## Contact

**IT Security Team**  
📧 itgroup@akg.com  
📞  777
