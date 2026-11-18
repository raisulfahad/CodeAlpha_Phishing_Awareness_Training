# CodeAlpha_PhishingAwarenessTraining

**CodeAlpha Cybersecurity Internship · Task 2: Phishing Awareness Training**

A short training module that teaches how to spot phishing emails and fake websites, recognise social engineering, and apply defensive best practices.

## Contents

| File | Description |
|---|---|
| `Phishing_Awareness_Training.pdf` | 11-slide training deck |
| `index.html` | Interactive 8-question scenario quiz (self-contained HTML/CSS/JS, no dependencies) |
| `README.md` | This file |

## Live quiz

After enabling GitHub Pages: `https://github.com/raisulfahad/CodeAlpha_Phishing_Awareness_Training/`

You can also open `index.html` locally in any browser.

## Deck outline

1. Title
2. Overview and agenda
3. Anatomy of a phishing email (From vs Reply-To, generic greeting, urgency, bad links and attachments)
4. Header checks: SPF, DKIM and DMARC
5. Fake websites and URL spoofing (typosquatting, homograph attacks, deceptive subdomains)
6. Social engineering triggers (urgency, fear, authority/CEO fraud, reward lures)
7. Case study: credential harvesting (the 2022 "0ktapus" SMS-phishing campaign)
8. Case study: Business Email Compromise (BEC)
9. Phishing-resistant MFA (FIDO2/passkeys) and password managers
10. Hover-before-clicking checklist and reporting workflow
11. Summary checklist and quiz pointer

## Quiz

Eight scenarios using mock email headers, URLs and messages: Reply-To mismatch, typosquatting, deceptive subdomains, failed SPF/DKIM/DMARC, punycode homograph, CEO fraud, a legitimate password-reset email (so not everything is flagged as malicious), and a password manager that refuses to autofill. Each answer shows a **SAFE / MALICIOUS** verdict and an explanation, followed by a final score and review.

All addresses in the quiz and deck are fictional examples. Nothing in the quiz is a live link.

## Notes on case studies

- The 0ktapus summary is based on public reporting (Group-IB, 2022).
- The BEC email is an illustrative scenario. Real-world BEC losses are referenced from public sources such as FBI IC3 reports, SEC filings and US DOJ releases.

## Deploying with GitHub Pages

Repository **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `/ (root)`** → Save.
