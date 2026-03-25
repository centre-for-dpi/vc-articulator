# VC Articulator

**An interactive briefing tool that makes the case for Verifiable Credentials — built for CDPI.**

VC Articulator is a single-page web application designed to help government decision-makers, technologists, and policy advisors understand *why* Verifiable Credentials (VCs) matter and *how* to implement them. It combines live demos, economic modelling, and technical guidance into three focused pages.

## What's inside

### Page 1 — Forgery Demo

Upload any identity document and the app instantly demonstrates how easily it can be forged using AI-based image manipulation. It then shows a difficulty-to-forge analysis, a step-by-step attacker playbook, and explains how cryptographically signed VCs eliminate the forgery risk entirely.

### Page 2 — Economics Model

An interactive cost calculator for KYC / Financial Services that compares traditional manual verification ($4–8 per check) against VC-based verification (near $0). Includes:

- A population slider to model costs at national scale
- Scenario toggles (Conservative / Base / Optimistic)
- Unit economics broken down by actor: Infrastructure Holder, Issuer (Government), and Acceptor (Bank/Institution)
- Citizen time burden comparison (hours lost to manual processes vs. instant digital verification)
- Sector extrapolation for healthcare, education, and more

### Page 3 — How to Build

Sector-specific implementation guidance covering 11 sectors (National ID, Education, Healthcare, Driver's Licence, and more). For each sector it shows:

- **Credentialing priorities** — Privacy, Interoperability, Adoption, Offline Use
- **Primary standards** — EBSI / eIDAS 2.0, mDL ISO 18013-5, OID4VC, W3C VC, AnonCreds (ZKP), SD-JWT VC
- **Complementary standards** — additional standards relevant to the sector
- Links to the CDPI Vision Paper and the VC Use-Cases deep-dive site

## Tech stack

- Pure HTML / CSS / JavaScript — single `index.html` file, no build step
- Fonts: Instrument Serif, DM Sans, JetBrains Mono (Google Fonts)

## Getting started

Open `index.html` in a browser, or serve it from any static file host.

## About CDPI

The [Centre for Digital Public Infrastructure](https://cdpi.dev) provides pro bono advisory to governments on deploying digital public infrastructure, including Verifiable Credentials.