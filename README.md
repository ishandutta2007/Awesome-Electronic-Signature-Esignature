# Awesome-Electronic-Signature-Esignature

# Top Electronic Signature (eSignature) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Digital Signing Workflows, Document Trust & Self-Hosted Alternatives*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Electronic Signature (eSignature)**. These tools enable individuals and organizations to send, sign, and manage legally binding documents digitally—replacing paper-based workflows with audit trails, identity verification, and compliance with regulations like ESIGN, UETA, and eIDAS.

**Examples** include DocuSign, PandaDoc, Adobe Acrobat Sign, Dropbox Sign (HelloSign), SignNow, OneSpan Sign, Xodo Sign (formerly eversign), SignRequest, Nitro Sign, and RightSignature (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom integration, and transparent document signing—ideal for organizations that prioritize data sovereignty, developers building embedded signing workflows, and privacy-conscious teams. The open-source eSignature landscape is anchored by **Documenso** (the leading DocuSign alternative), with strong contenders in **DocuSeal**, **OpenSign**, and **LibreSign**.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[DocuSign](https://www.docusign.com/)**  
  The market leader in eSignature with the broadest integration ecosystem (1,000+ partners) and enterprise-grade compliance. Personal plan includes 5 envelopes/month; Standard and Business Pro offer 100 envelopes/user/year on annual plans . Best for organizations that need maximum integrations and brand recognition.

- **[PandaDoc](https://www.pandadoc.com/)**  
  Document workflow platform combining eSignature with proposal creation, CPQ, and payment collection. Free tier allows 5 documents/month; Starter at $19/seat/month (annual) and Business at $49/seat/month . Strong for sales teams that need document generation alongside signing.

- **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)**  
  eSignature solution tightly integrated with Adobe's PDF ecosystem (Acrobat, Reader). Offers enterprise features like bulk send, workflow designer, and advanced authentication . Best for organizations already standardized on Adobe tools.

- **[Dropbox Sign (HelloSign)](https://sign.dropbox.com/)**  
  Developer-friendly eSignature API with embedded signing, templates, and branding options. Essentials plan starts at $75/month (annual) . Ideal for SaaS companies embedding signing into their own applications.

- **[SignNow](https://www.signnow.com/)**  
  Mobile-first eSignature app with offline signing, kiosk mode, and templates. Business plan at $19.99/month or $95.99/year; Business Premium at $29.99/month or $179.99/year . Strong for field workers and on-the-go signing.

- **[OneSpan Sign](https://www.onespan.com/)**  
  Enterprise eSignature with advanced identity verification (government ID, biometrics, knowledge-based authentication), video signing, and high-assurance compliance (SOC 2, ISO 27001, FedRAMP). Transaction-based pricing for high-volume automated workflows .

- **[Xodo Sign (formerly eversign)](https://xodo.com/)**  
  Budget-friendly eSignature with a free tier (1 document/week, single signer) and Personal plan at $3/month (annual) for 12 documents/month and multi-party signing . Good entry-level option for individuals.

- **[SignRequest](https://signrequest.com/)**  
  Simple eSignature with Google Workspace integration. Free plan allows 10 documents/month; Professional adds unlimited documents, templates, and team features; Business adds unlimited templates and premium integrations . Acquired by Box, making it a natural fit for Box users.

- **[Nitro Sign](https://www.gonitro.com/)**  
  Standalone eSignature plans launched in 2025, with Standard (core eSigning), Plus (bulk send, templates, SSO), and Enterprise (API, qualified signatures) tiers. Transparent pricing with no overage penalties .

- **[RightSignature](https://rightsignature.com/)**  
  eSignature solution from Citrix, offering in-person and remote signing, custom branding, and integration with Citrix ShareFile. Pricing starts around $60/month for teams .

## Open-Source GitHub Projects

- **[Documenso](https://github.com/documenso/documenso)**  
  The leading open-source DocuSign alternative, built with TypeScript, React Router, Prisma, and Tailwind. Self-hostable via Docker, with a developer-friendly API and a mission to create "open trust infrastructure" . AGPL-3.0 licensed. Best for teams that want a modern, actively developed platform with a clear path to production.

- **[DocuSeal](https://github.com/docusealco/docuseal)**  
  Self-hosted eSignature platform with a WYSIWYG PDF form editor (12 field types), multi-signer support, automated emails via SMTP, and storage backends including S3, Google Cloud, and Azure. Version 2.3.0 added AI-powered field detection and non-root Docker execution . AGPL-3.0 licensed, 17k+ stars . Offers a cloud-hosted tier with US/EU data residency . Best for teams that want a polished, feature-rich self-hosted experience.

- **[OpenSign](https://github.com/opensignlabs/opensign)**  
  Free and open-source DocuSign alternative with unlimited documents even on the cloud-hosted free tier. Features multi-signer support with sequence enforcement, email OTP verification for guest signers, expiring documents, rejection with reason, custom email templates, and OpenSign Drive for document storage . Best for users who want a generous free tier and a feature set that competes directly with commercial offerings.

- **[LibreSign](https://github.com/LibreSign/libresign)**  
  Open-source digital signature platform designed for organizations that need control over document workflows and infrastructure. Developed by LibreCode Coop (Brazil) with a focus on enterprise support and Nextcloud integration . Best for organizations already using Nextcloud or those that want a cooperatively maintained, enterprise-oriented solution.

### Additional Strong Open-Source Options

- **Documenso Forks** — White-labeled variants like SuiteOp Sign demonstrate the extensibility of Documenso's codebase for branded deployments .
- **PDF Signature Libraries** — Libraries like `@documenso/pdf-sign` (launching) and `pdf-lib` enable custom signature embedding for developers building bespoke workflows .
- **Digital Signature Standards (DSS)** — The European Commission's DSS library implements advanced electronic signature standards (XAdES, PAdES, CAdES) for high-assurance use cases .
- **Frameworks for building custom systems**: Use **Documenso** or **DocuSeal** as the signing backend, integrate with **Nextcloud** (via LibreSign) for file management, and build custom frontends with the REST APIs exposed by each platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Self-hosted eSignature solutions generate their own signing certificates by default, which may not be recognized by Adobe or meet qualified signature requirements under eIDAS without additional configuration .
- Legally binding signatures require compliance with applicable regulations (ESIGN, UETA, eIDAS) and proper identity verification workflows.

---

**Made for legal teams, operations managers, developers, and organizations building private, trustworthy document signing infrastructure.**  
Let's make electronic signatures more open, self-hostable, and accessible.
