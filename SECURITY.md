# Security Policy

Virtual Healthcare Technologies Inc. (VHT.ai) takes the security and privacy of our members seriously. We welcome reports from security researchers and will work with you to understand, validate and fix issues quickly.

This policy mirrors the contact published at `https://vht.ai/.well-known/security.txt`.

## Reporting a vulnerability

**Email: security@vht.ai**

Please do **not** report security vulnerabilities through public GitHub issues, discussions or pull requests.

Include as much of the following as you can:

- A description of the issue and its potential impact
- Steps to reproduce, or a proof of concept
- The affected product, URL, app version or platform (iOS / Android / web)
- Any mitigations you are aware of

Preferred language: English. We do not currently publish a PGP key; if you need to share something especially sensitive, say so in your first email and we will arrange an encrypted channel.

## What to expect

| Step | Target |
|---|---|
| Acknowledgement of your report | Within **1 business day** (24 hours, Monday to Friday) |
| Initial triage and severity assessment | Within **3 business days** |
| Status updates | At least every **7 days** while the issue is open |
| Fix targets after confirmation | Critical: within 48 hours · High: 7 days · Medium: 30 days · Low: next release cycle |

Timelines are targets, not guarantees; complex issues may take longer and we will tell you if that is the case.

## Coordinated disclosure

We ask that you give us a reasonable opportunity to fix an issue before disclosing it publicly. Our default disclosure window is **90 days** from acknowledgement, or sooner once a fix has shipped. We are happy to coordinate a disclosure date and to credit you (if you wish) when the issue is resolved.

## Safe harbor

We will not pursue or support legal action against researchers who, in good faith:

- Follow this policy and make a good-faith effort to avoid privacy violations, data destruction, and service disruption
- Only interact with accounts they own or have explicit permission to test
- Report the vulnerability promptly and do not exploit it beyond what is necessary to demonstrate it
- Do not access, download, retain or share any data belonging to other people — if you encounter such data accidentally, stop, do not store it, and tell us in your report
- Do not use the vulnerability for financial gain, extortion or publicity before disclosure

We consider research conducted under this policy to be authorized, and we will not bring a claim against you under anti-circumvention or computer-misuse laws for activity that stays within it. If a third party brings legal action against you for research that complied with this policy, we will make it known that your actions were authorized.

## Rules of engagement

- **Never test against real member accounts or real health data.** Create your own test account. Any access to another person's personal or health information is out of bounds, full stop.
- No denial-of-service, resource exhaustion, or volumetric testing.
- No social engineering, phishing or physical attacks against VHT staff, contractors, members or providers.
- No automated scanning that generates significant load.
- Stop and report immediately if you believe you have reached PHI or another person's data.

## Scope

**In scope**

- `vht.ai` and its subdomains
- The VHT.ai member app on iOS, Android and the web
- APIs that these apps call

**Out of scope**

- Third-party services we use (hosting, analytics, app stores, email providers) — report those to the vendor
- Findings from automated scanners without a demonstrated impact
- Missing security headers, SPF/DKIM/DMARC configuration or similar best-practice notes without a working exploit
- Clickjacking on pages with no sensitive actions
- Self-XSS, or issues that require a victim to paste code into their own browser
- Rate limiting on non-authentication endpoints
- Outdated software versions without a proven exploitable vulnerability
- Social engineering, physical attacks and denial of service (see rules above)
- Reports about the public `.github` and `community` repositories themselves (these contain no code)

If you are unsure whether something is in scope, ask at security@vht.ai first.

## Recognition

We do not currently run a paid bug bounty. With your permission we will credit you in release notes or an acknowledgements page once the issue is fixed.

Thank you for helping keep VHT.ai members safe.
