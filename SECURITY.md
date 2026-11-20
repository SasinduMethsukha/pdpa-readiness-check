# Security policy

## Design
The PDPA Readiness Check is a static site. It has no backend, no database, no accounts and no analytics. Assessment answers are stored only in the user's browser (localStorage) and are never transmitted.

Deployed with strict security headers (see `vercel.json`): Content-Security-Policy, HSTS, X-Content-Type-Options, X-Frame-Options, Referrer-Policy, Permissions-Policy and Cross-Origin-Opener-Policy.

## Reporting a vulnerability
Please report security issues privately using GitHub's **"Report a vulnerability"** button on the repository's **Security** tab, rather than opening a public issue. Include steps to reproduce and the impact. You can expect an acknowledgement within 7 days.

## Scope
In scope: the code in this repository and the deployed site. Out of scope: third-party services (Vercel, Google Fonts) and the content of external links.
