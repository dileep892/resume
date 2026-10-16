# Dileep Velma — Resume page (clean summary)

This repository contains a single-file personal resume/portfolio HTML page for Dileep Velma (Network Architect / Security Consultant). The file index.html is a complete, self-contained resume site (HTML + internal CSS + small JS) intended for recruiting and showcasing consulting services.

Summary
- Title / Owner: Dileep Velma — Network Architect | Hybrid Cloud, Data Center & Network Security
- Page type: Single-file resume/portfolio (index-style HTML) with embedded styling and a small script that attaches an embedded base64 PDF resume to download links.
- Primary sections:
  - Header/navigation: Sticky top navigation pill with name, section links (Services, Approach, Experience, Credentials, Contact), and CV download CTA.
  - Hero: Intro badge, name and role (Penetration Tester · Security Researcher · Consultant), short bio, CTA buttons (download CV, email, LinkedIn), and skill chips (OWASP Top 10, API Top 10, VAPT, etc.).
  - Services: Grid of service cards (Network Security, API Security Reviews, Mobile Application Security, Network & Firewall Security, Vulnerability & Remediation Management, Security Reporting & Advisory).
  - Approach: Four-step engagement methodology (Scope & Recon, Test & Validate, Report & Prioritize, Support Remediation) displayed as horizontally scrollable cards.
  - Experience: Job history with two main entries (Cyber Security Analyst — Network Intelligence (NII); Senior Cyber Security Analyst — Talakunchi Networks Pvt Ltd) including responsibilities and tooling used.
  - Credentials: Certifications (PCNSE, CCNP, AWS network/security, F5), toolchain (Burp, Postman, Nmap, Wireshark, SQLMap, etc.), and education (B.Tech — JNTU / Nizam College).
  - Contact: Call-to-action card with download button, mailto and phone links, LinkedIn.

Technical details
- Styling: Embedded CSS using CSS variables, responsive grid and flex layouts, accessible reduced-motion preference, and a soft radial glow behind the hero.
- Fonts: Google Fonts (Plus Jakarta Sans).
- JS: A small script sets the href attribute of three download links (#dl1, #dl2, #dl3) to a data:application/pdf;base64 string of the resume PDF.
- Download: Resume is embedded as a base64 string; all three download buttons provide the same file.

Notable issues & suggested fixes
- Inconsistent name: Ensure the hero <h1> and repository metadata consistently show "Dileep Velma".
- Duplicate contact buttons: Keep only one mailto and one phone link where appropriate.
- Minor typos/truncated text fragments: Proofread and restore any missing text.
- Publishing: This repo includes an index.html at root so GitHub Pages can serve it from the main branch root.
