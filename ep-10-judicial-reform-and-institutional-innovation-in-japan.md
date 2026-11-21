---
title: "Modernizing Judicial Systems: Japan's Three-Pillar Digital Architecture and E-Peradilan Reforms"
series: "Japan Judicial Knowledge Audio Series"
episode: 10
source_menu_title: "Judicial Reform and Institutional Innovation in Japan"
author: "Cecep Mustafa"
orcid: "https://orcid.org/0000-0003-0037-497X"
affiliation: "Indonesian Judicial College (IJC)"
audio_url: "https://res.cloudinary.com/jiwtgnlx/video/upload/v1789377571/Cecep-Mustafa_Modernizing-Judicial-Systems.mp3"
audio_duration: "20:26"
source_url: "https://www.cecepmustafa.my.id/podcast-audio/digital-justice-audio-series/japan-judicial-knowledge-audio-series/ep-10-judicial-reform-and-institutional-innovation-in-japan"
website: "https://bsdkijc-dev.github.io/japan-judicial-knowledge-audio-series/ep-10.html"
license: "CC BY 4.0"
retrieved: "2026-11-21"
---
# Episode 10: Modernizing Judicial Systems: Japan's Three-Pillar Digital Architecture and E-Peradilan Reforms

**Japan Judicial Knowledge Audio Series** · By **Cecep Mustafa** (Indonesian Judicial College (IJC)) · ORCID [0000-0003-0037-497X](https://orcid.org/0000-0003-0037-497X)

Source page: [Ep. 10 Judicial Reform and Institutional Innovation in Japan](https://www.cecepmustafa.my.id/podcast-audio/digital-justice-audio-series/japan-judicial-knowledge-audio-series/ep-10-judicial-reform-and-institutional-innovation-in-japan) · Website: https://bsdkijc-dev.github.io/japan-judicial-knowledge-audio-series/ep-10.html

## About This Episode

In this episode, Cecep Mustafa examines Japan's centralized civil court digitalization framework established under the Code of Civil Procedure Amendment (Act No. 48 of 2022) and the Comprehensive Digitalization Integration Act of 2023. He analyzes Japan's Three Pillars of Civil Procedure Digitalization, known as the "3e" framework, including e-Court, mandatory attorney e-Filing through the mints platform, and centralized cloud-based e-Case Management. Cecep Mustafa then contrasts Japan's statutory approach with Indonesia's regulatory e-Court, SIPP, and e-Berpadu ecosystem under Supreme Court Regulation (PERMA) No. 7 of 2022. The episode concludes by presenting the e-Peradilan Modern reference architecture and a practical 90-day pilot deployment plan for trial courts in Central Jakarta and Surabaya, with a focus on interoperability, procedural efficiency, digital governance, and sustainable judicial transformation.

## Listen to the Episode

Modernizing Judicial Systems: Japan's Three-Pillar Digital Architecture and E-Peradilan Reforms

🎧 [Listen to the MP3 (20:26)](https://res.cloudinary.com/jiwtgnlx/video/upload/v1789377571/Cecep-Mustafa_Modernizing-Judicial-Systems.mp3)

## Key Topics

Digital Justice, 3e Framework, mints Platform, Act 48 2022, SIPP Database, LegalDocML, E-Peradilan Modern, PDP Law.

## Why This Topic Matters

The transition from paper-based dockets to digital case management represents a fundamental reconfiguration of judicial administration. While digital filing and remote hearings reduce litigation costs and processing times, implementing technology through decentralized administrative decrees can create database fragmentation, synchronization failures, and data privacy vulnerabilities. Analyzing Japan's statutory civil court digitalization offers actionable technical and governance insights for building a centralized, semantically structured, and constitutionally aligned judicial cloud architecture.

## Japan Perspective

Japan's civil court digitalization is anchored in primary parliamentary legislation enacted through the Code of Civil Procedure Amendment (Act No. 48 of 2022) and the Comprehensive Digitalization Integration Act of June 2023. These statutes establish a mandatory enforcement timeline culminating on May 21, 2026, structured around the "Three Pillars of Civil Procedure Digitalization" ("3e" framework).

The first pillar, e-Court, embeds remote proceedings directly into statutory procedural law. Code of Civil Procedure Article 179 Paragraph 3 codifies web-conferenced preparatory proceedings, while Article 87-2 authorizes web-conferenced oral arguments. To satisfy the constitutional open-court requirement under Article 82 of the Constitution of Japan, the presiding judge sits in a physical courtroom, where remote video feeds of litigating counsel are projected onto public monitors in the courtroom gallery.

The second pillar, e-Filing, centers on the mints platform (MINji saiban shorui denshi Teishutsu System), operated directly under the administrative authority of the Supreme Court (Saikō Saibansho). Electronic submission via mints is mandatory for approximately 30,000 licensed attorneys represented through the Japan Federation of Bar Associations (Nichibenren). To preserve access to justice under Article 32 of the Constitution, unrepresented (pro-se) litigants retain the legal right to submit paper pleadings, which court clerical personnel scan and ingest directly into the digital record.

The third pillar, e-Case Management, replaces physical dossier transmission across Summary Courts, District Courts, High Courts, and the Supreme Court with a centralized cloud repository. Authenticated parties inspect digital case files around the clock, while public inspection at dedicated courthouse terminals enforces automated redaction under the Act on the Protection of Personal Information (APPI). The entire system operates over a dedicated judicial wide-area network connecting all 438 Summary Courts, 50 District Courts, 8 High Courts, and the Supreme Court over an isolated private intranet.

COMPARATIVE PERSPECTIVE A comparative evaluation between Japan and Indonesia highlights contrasting legal foundations, database topologies, and operational safeguards.

In Indonesia, judicial modernization has been executed through autonomous rulemaking (regelende bevoegdheid) under Supreme Court Regulations, including PERMA No. 1 of 2019 and PERMA No. 7 of 2022. The ecosystem comprises e-Filing, e-Payment, e-Summons, and e-Litigasi within the e-Court portal, alongside the Case Tracking Information System (Sistem Informasi Penelusuran Perkara / SIPP) across more than 800 working units, and e-Berpadu for criminal case management. In 2024, first-instance courts registered 410,754 civil, religious, and administrative cases through e-Court.

However, technical assessment reveals structural contrasts across core operational dimensions:

First, Indonesia operates a decentralized database network where each court manages an independent local database instance (historically MySQL or MariaDB) that transmits daily batch updates to central servers. In remote island and border circuits (daerah 3T), telecommunications disruptions cause frequent batch synchronization failures, data discrepancies, and registry lockouts. Japan operates a single centralized cloud repository serving all judicial tiers without local synchronization lag.

Second, Indonesian court repositories store documents as unstructured binary artifacts (flat PDFs and Word files) linked to relational database tables. The lack of adoption of machine-readable legal schemas, such as OASIS LegalDocML (Akoma Ntoso), prevents automated parsing of procedural backgrounds, legal reasoning (pertimbangan hukum), and operative dispositions (diktum putusan). In Japan, submissions through mints utilize structured PDF formats accompanied by XML metadata headers.

Third, public judgment publishing on Indonesia's Direktori Putusan faces security challenges, including scraping by commercial AI botnets and incomplete redaction of national identification numbers (Nomor Induk Kependudukan / NIK) under Law No. 27 of 2022 on Personal Data Protection (PDP Law). Japan enforces strict Public Key Infrastructure (PKI) encryption via bar association certificate authorities and applies automated PII redaction at public courthouse terminals.

Observe → Understand → Compare → Adapt → Pilot → Improve

The operational methodology for adapting Japanese digital court practices into Indonesian judicial reform follows six structured stages:

Observe: Identify technical vulnerabilities in Indonesia's digital court architecture, including local SIPP database synchronization failures, unstructured binary PDF storage, and PII exposure under the PDP Law.

Understand: Recognize that Japan achieves high-integrity digital justice by anchoring reforms in primary parliamentary statutes, centralizing cloud storage, and maintaining dual-track pro-se access safeguards.

Compare: Contrast Indonesia's decentralized local SIPP databases and autonomous PERMA decrees against Japan's centralized mints cloud repository and Code of Civil Procedure Act No. 48 of 2022 amendments.

Adapt: Formulate the e-Peradilan Modern reference architecture for Mahkamah Agung:

Anchor digital mandates directly in primary legislation via the upcoming national Civil Procedure Code revision (RUU Hukum Acara Perdata).

Transition SIPP from local relational databases to a high-availability, multi-tenant PostgreSQL central cloud repository with Apache Kafka event streaming.

Adopt the OASIS LegalDocML (Akoma Ntoso) standard to convert flat PDFs into machine-readable legal XML schemas.

Deploy automated PDP-compliant PII redaction microservices and BSrE-BSSN hardware security module (HSM) digital signatures.

Install guided self-service kiosks at Integrated One-Stop Service (Pelayanan Terpadu Satu Pintu / PTSP) desks to protect pro-se citizen filing rights.

Pilot: Deploy a 90-day pilot program across two commercial hubs: Central Jakarta District Court (PN Jakarta Pusat Kelas IA Khusus) and Surabaya District Court (PN Surabaya Kelas IA Khusus).

Improve: Evaluate pilot performance against established quantitative benchmarks:

Reduce docket data synchronization latency from 12-24 hours to under 5 seconds.

Accelerate Puskarda inter-agency criminal warrant handshake velocity from 3-5 business days to under 120 minutes.

Convert 95 percent or more of rendered pilot decisions into valid LegalDocML XML schemas.

Attain 99.2 percent precision and recall in automated PDP Law PII redaction across protected identifiers.

Increase unassisted pro-se filing completion at PTSP kiosks from 22 percent to at least 80 percent.

Maintain zero unauthorized database modifications during red-team penetration testing.

## Judicial Knowledge Takeaways

Primary Statutory Codification Secures Digital Mandates: Establishing electronic procedures within primary civil procedure statutes resolves constitutional challenges regarding due process and ink signature requirements.

Centralized Cloud Repositories Eliminate Record Discrepancies: Replacing decentralized local court databases with a unified cloud architecture eliminates batch synchronization failures and physical dossier transmission.

Dual-Track Submission Models Safeguard Pro-Se Access: Guaranteeing that unrepresented citizens can submit paper filings while court staff handle digital ingestion prevents technology from creating a justice divide.

Machine-Readable Semantic Schemas Enable Advanced Analytics: Structuring court records into OASIS LegalDocML XML format enables automated citation validation and PII redaction without exposing confidential case details to external commercial AI models.

## Frequently Asked Questions

Q: What primary statutes establish civil court digitalization in Japan? A: Civil court digitalization in Japan is established under the Code of Civil Procedure Amendment (Act No. 48 of 2022) and the Comprehensive Digitalization Integration Act of June 2023, taking full effect on May 21, 2026.

Q: What are Japan's "Three Pillars of Civil Procedure Digitalization"? A: The "3e" framework comprises e-Court (web-conferenced oral arguments and preparatory proceedings), e-Filing (mandatory online submissions via mints for attorneys), and e-Case Management (centralized cloud repository for 24/7 docket inspection).

Q: How does Japan preserve the constitutional open-court principle during remote web hearings? A: Under Article 82 of the Constitution of Japan, the presiding judge sits in an open courtroom where remote video feeds of litigating counsel are projected onto public gallery monitors viewable by citizens and journalists.

Q: What is the main architectural limitation of Indonesia's current SIPP database network? A: SIPP relies on decentralized, local database instances across 800+ courts that transmit daily batch updates to central servers, causing synchronization delays, packet loss in remote island circuits (daerah 3T), and record mismatches.

Q: What is the proposed e-Peradilan Modern reference architecture for Indonesia? A: It is an integrated judicial IT framework that replaces local SIPP databases with a central cloud-native repository, adopts OASIS LegalDocML XML schemas, integrates Puskarda 2.0 Kafka event streaming, and automates PDP Law PII redaction.

## Related Topics

Japan Judicial Research | Comparative Judicial Knowledge | Judicial Learning | Legal Explainer | International Judicial Cooperation | Japanese Mediation | Digital Justice | Judicial Reform

## Closing Note

Listen to the full episode above to learn how centralized cloud architectures and statutory digital reforms can modernize court systems, and visit the IJC Knowledge Portal for complete reference blueprints.

---

**Cite as:** Mustafa, C. (2026). Modernizing Judicial Systems: Japan's Three-Pillar Digital Architecture and E-Peradilan Reforms (Japan Judicial Knowledge Audio Series, Ep. 10) [Audio podcast episode and text]. Judicial Knowledge & Education Hub, Indonesian Judicial College (IJC). https://bsdkijc-dev.github.io/japan-judicial-knowledge-audio-series/ep-10.html

_Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Statistics, figures and legal references in the episode texts are the author’s commentary as published on the source site; they were not independently verified for this release. Consult the primary legal sources before relying on them._
