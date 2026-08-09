# Security — Starter Source Registry

| Source | Primary surface | Typical use |
|---|---|---|
| CISA | https://www.cisa.gov/news-events/cybersecurity-advisories | advisories |
| CISA KEV | https://www.cisa.gov/known-exploited-vulnerabilities-catalog | known exploitation |
| NIST NVD | https://nvd.nist.gov/ | CVE metadata/context |
| MITRE CVE | https://www.cve.org/ | CVE records |
| CERT/CC | https://www.kb.cert.org/ | vulnerability notes |
| GitHub Security Advisories | https://github.com/advisories | ecosystem advisories |
| Vendor advisories | vendor security page | affected versions, fixes, mitigation |

## Security story minimum evidence

Record:
- CVE or advisory identifier;
- vulnerable product/version;
- fixed version or mitigation;
- exploitation status and source;
- severity source;
- disclosure/publication date;
- vendor advisory;
- whether proof-of-concept/exploit availability is actually confirmed.

## Important distinctions

Do not equate:
- high CVSS score with active exploitation;
- public proof of concept with reliable weaponized exploit;
- affected software with confirmed compromise;
- researcher claim with vendor confirmation.

## Harm minimization

Explain impact and mitigation. Avoid adding operational exploitation detail that is unnecessary for
defenders to understand the issue.
