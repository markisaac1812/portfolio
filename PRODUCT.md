# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Confirmed with Mark, 2026-11-12.

- **Primary: engineers and hiring managers.** Technical readers evaluating an internship candidate. They open the architecture, follow links to source, and judge whether the engineering is real. The site is built to hold up under that scrutiny first.
- **Secondary: recruiters.** They arrive from a resume or LinkedIn link and need the resume, contact channels, and availability without reading the technical detail.

## Product Purpose

A personal portfolio for Mark Lamee, a computer science student at Cairo University (expected June 2027).

It exists to get Mark hired. Target outcomes, in order:

1. Internships (primary).
2. A part-time engineering job (second option).

The portfolio must work for general software engineering openings, not only backend or cloud ones. Success is a technical reader finishing the page convinced Mark can build and operate real systems, and reaching out.

## Positioning

Mark presents as a **software engineer whose specialty is backend, cloud, and DevOps**. The title leads with software engineer so any SWE opening fits; the specialty is named as his strongest area.

The one thing a reader should remember is the pairing of two proofs:

- **AWS certifications**, including Solutions Architect – Associate.
- **QuickBite's engineering depth**: a three-service, event-driven food-delivery backend with a transactional outbox, per-country database sharding, idempotent writes, and real-time order tracking.

A student holding both the credential and a system that exercises it is the claim a neighbouring portfolio cannot copy.

The site states this as "Software Engineer" with "backend · cloud · DevOps" beneath it (page title, meta description, hero), updated 2026-11-13.

## Operating Context

- Readers reach the site from a resume, a LinkedIn profile, a GitHub profile, or a direct link in an application.
- Technical readers leave the site to verify: GitHub repositories for source, Credly and Coursera for credentials, Postman for API documentation.
- Recruiters download or open the one-page resume PDF and use email, LinkedIn, or GitHub to make contact. The site states that email is the fastest channel.

## Capabilities and Constraints

- The site is a single static `index.html` with inline CSS and JavaScript, plus `assets/`. There is no build step, framework, or package manifest.
- Source lives at `github.com/markisaac1812/portfolio`.
- Current sections, in order: home, QuickBite, certifications, experience, more projects, skills, about, resume, contact.
- QuickBite is feature-complete except for its last step, deployment to AWS. Mark expects that to finish around 2026-11-20 (stated 2026-11-13). The site says "Deploying to AWS · final step" in the QuickBite badge and "Deploying to AWS now" in the hero; both must change to a deployed status once it is live, and must not claim it earlier.
- **Undecided:** hosting and deploy target (GitHub Pages or other) and any custom domain. Not established in this session.
- The site asks for "software engineering internships and part-time roles". **Undecided:** an availability window (for example a start month); none is stated because none was confirmed.
- The visual concept (a Claude Code terminal session) is kept as it is by Mark's decision on 2026-11-12. Work on the site fixes content, order, mobile behaviour and accessibility around it.

## Brand Commitments

- Name: Mark Lamee.
- Identity statement: software engineer, specialising in backend, cloud, and DevOps (confirmed 2026-11-12).
- Existing copy is first person, plain, and specific about mechanisms. Observed in the current site, not separately confirmed as binding.

## Evidence on Hand

Real material in the repository:

- `assets/Mark_Lamee_Resume.pdf`: resume. As of 2026-11-13 it is unfinished: it contains bracket placeholders ("[operations management]", "[notifications, ...]", "[Oct 2026]"), a sentence missing a noun ("reports from 10+ into"), no mention of QuickBite, one certification where the site lists three, and a phone number the site does not show. The site embeds it as an inline preview in the resume section on desktop (restored at Mark's request on 2026-11-13 after it had been removed) and links to it on small screens, so its contents are publicly visible on the page.
- `assets/mark.jpg`: portrait.
- `assets/saa.png`, `assets/clf.png`, `assets/coursera-de.png`: certification badges and certificate.
- `assets/eks-architecture.png`: architecture diagram for the AWS EKS Microservices Platform project.
- `assets/icons.js`: technology icons.

Facts stated on the current site (source of record: `index.html`):

- Education: B.Sc. Computer Science, Cairo University, expected June 2027.
- Experience: Data Engineering Intern, Creo Technologies, July to September 2026. 256,000+ customer feedback reports mined with a TF-IDF pipeline and presented to the CEO; PySpark ETL from 15 production REST APIs into a medallion lakehouse on Microsoft Fabric; a capacity-monitoring alert across 3 workspaces.
- Certifications, each with a public verification link: AWS Certified Solutions Architect – Associate (SAA-C03, October 2026); AWS Certified Cloud Practitioner (CLF-C02, July 2026); DeepLearning.AI Data Engineering Professional Certificate (June 2026).
- Projects with public source: QuickBite (core, order, and analytics services), Real-Time Collaborative Code Review Platform, Crypto Market Data Pipeline, AWS EKS Microservices Platform, Natours. 18 public repositories in total.

Absences future work must not fabricate:

- No testimonials, references, or employer quotes.
- No live production deployment or uptime figures for QuickBite.
- No usage, traffic, or customer numbers for any project beyond those already stated.
- No screenshots of running applications.

## Product Principles

1. **Checkable by an engineer.** Every claim a technical reader might doubt sits next to something they can open: source, an architecture, a credential verification link.
2. **Generalist title, specialist proof.** Mark is introduced as a software engineer. Backend, cloud, and DevOps strength is demonstrated by the work, and never reads as a filter that turns away a general SWE opening.
3. **Two anchors outrank the rest.** The AWS certifications and QuickBite carry the story. Other projects, skills, and coursework support them and do not compete with them.
4. **The recruiter path stays short.** Resume, contact, and availability are reachable without reading the technical material.
5. **State things as they are.** In-progress work is labelled in progress, numbers come from real work, and nothing is added to look more senior than a student with one internship.
