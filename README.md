# 🏛 Digital Preservation Simulator — OAIS Model

> Interactive tool for exploring and simulating the OAIS reference model compliant with ISO 14721:2025, PREMIS 3.0, ISO 16363 and ISO 19005.

[![ISO 14721](https://img.shields.io/badge/ISO%2014721%3A2025-OAIS-4ade80?style=flat-square)]()
[![ISO 16363](https://img.shields.io/badge/ISO%2016363-Trustworthy%20Repository-a78bfa?style=flat-square)]()
[![PREMIS](https://img.shields.io/badge/PREMIS%203.0-Preservation%20Metadata-f472b6?style=flat-square)]()
[![ISO 19005](https://img.shields.io/badge/ISO%2019005-PDF%2FA-38bdf8?style=flat-square)]()
[![HTML5](https://img.shields.io/badge/HTML5-No%20dependencies-fb923c?style=flat-square)]()
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-4ade80?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)

**[🌐 Live demo →](https://gibco.github.io/digital-preservation-oais-simulator/)**

> 🇪🇸 Spanish version: [simulador-preservacion-oais](https://github.com/gibco/simulador-preservacion-oais)

---

## 📌 Description

The **Digital Preservation Simulator — OAIS Model** is a standalone, dependency-free interactive web application designed for archivists, records managers, digital preservation officers and IT teams who need to **explore, simulate and evaluate** the core components of the OAIS digital preservation model.

The tool embodies a fundamental principle of ISO 14721:2025:

> *A trustworthy digital repository is not a server with backups. It is an institutional system with policies, processes, metadata and a defined Designated Community.*

---

## 🎯 Purpose

Many organisations confuse "having files in the cloud" with "digital preservation". This simulator makes the difference tangible — showing what separates a storage solution from an **OAIS-compliant digital archive**, by letting users interact with its six functional entities, three information package types and digital migration strategies.

---

## ✨ Features — 6 interactive modules

### 🏛 Module 1 — OAIS Model
- **6 functional entities** of ISO 14721:2025 §4.1 — each clickable with evaluation criteria and diagnostic questions
- **Mandatory responsibilities** table (§3.1) with compliance status
- **Maturity scale 0–5** aligned with ISO 16363, with per-level descriptions

### 📦 Module 2 — SIP · AIP · DIP Packages
- Interactive **Producer → OAIS → Consumer** flow diagram
- The **5 mandatory PDI categories** (Provenance, Reference, Fixity, Context, Access Rights) with normative descriptions
- **Format matrix by role**: TIFF master, PDF/A preservation, JPEG2000 access, formats to avoid

### 📥 Module 3 — Ingest Simulator
- Configure object type, format, PREMIS metadata, QA and SHA-256 checksum
- Animated real-time log with **OAIS quality index** calculation
- Activates applicable standards by process phase: ISO 14721, ISO 19005, PREMIS, ISO 23081

### 🔄 Module 4 — Digital Migration
- **4 migration strategies** (Refreshment, Replication, Repackaging, Transformation) with risk levels per ISO 14721 §5
- Format migration simulator with JHOVE validation, checksums and PREMIS event recording

### 🔐 Module 5 — Integrity & PREMIS
- SHA-256 checksum verification with **bit rot detection**
- Real **PREMIS 3.0 XML** generation with UUID, ISO timestamp and fixity check event
- 3-2-1 backup rule explained · Algorithm comparison table (SHA-256, SHA-512, MD5, CRC-32)

### ⚠ Module 6 — Risk Matrix
- 9 critical preservation risks cross-referenced with affected OAIS entity, likelihood, impact and mitigation
- Compliant with ISO 21946 (risk assessment for records management processes and systems)

---

## 📐 Standards implemented

| Standard | Application |
|---|---|
| **ISO 14721:2025 (OAIS)** | Full reference model — 6 entities, packages, mandatory responsibilities |
| **ISO 16363** | Maturity scale for trustworthy digital repositories |
| **PREMIS 3.0** | Preservation metadata — events, agents, objects, rights |
| **ISO 19005 (PDF/A)** | Preservation format for electronic documents |
| **ISO 23081** | Metadata for records management |
| **ISO 15489** | Records management framework in ingest processes |
| **ISO 21946** | Risk assessment for records management |
| **FADGI / Metamorfoze** | Technical quality parameters for digitisation |

---

## 🌍 International context

This simulator applies to any institution responsible for long-term preservation of digital records, regardless of country or jurisdiction:

- **National and state archives** (NARA, TNA, BnF, AGN, NAA...)
- **University and research libraries** (LoC, BL, Europeana...)
- **Public sector organisations** managing digital records under e-government frameworks
- **Museums and cultural heritage institutions**
- **Private organisations** with legal or regulatory record retention obligations

The OAIS model (ISO 14721) is the internationally recognised reference framework adopted by institutions on every continent. All functional concepts, terminology and evaluation criteria in this simulator follow the standard directly.

---

## 🚀 Usage

Single self-contained HTML file. No server, no framework, no installation required.

```bash
git clone https://github.com/gibco/digital-preservation-oais-simulator.git
cd digital-preservation-oais-simulator
open index.html
```

Or access directly online:

**[🌐 Open simulator →](https://gibco.github.io/digital-preservation-oais-simulator/)**

---

## 📁 Repository structure

```
digital-preservation-oais-simulator/
│
├── index.html      # Complete self-contained application
└── README.md       # This file
```

---

## 👤 Author

**Jhon Alexander González Flórez**
Digital Archivist & Records Management Consultant
Specialist in Electronic Records Management Systems (ERMS), Digital Preservation and Web Accessibility

- 🌐 [archivistadigital.com](https://archivistadigital.com)
- 💼 [LinkedIn](https://linkedin.com/in/TU-PERFIL)
- 🇪🇸 Spanish version: [simulador-preservacion-oais](https://github.com/gibco/simulador-preservacion-oais)

Clients and projects span public sector institutions in Colombia and Latin America, including national regulatory agencies, judicial bodies, civil aviation authorities, housing funds, and territorial planning entities.

---

## 📄 License

This project is published under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** licence.

You may share and adapt the material provided appropriate attribution is given and it is not used for commercial purposes.

[View full licence →](https://creativecommons.org/licenses/by-nc/4.0/)

---

## 🤝 Contributing

Found an error in the normative content? Have a suggestion for an additional module? Open an issue or submit a pull request. Contributions that improve alignment with ISO 14721:2025, PREMIS 3.0 or ISO 16363 are especially welcome.

---

<div align="center">

*"A digital repository is not trustworthy because of the hardware it runs on.*
*It is trustworthy because of the policies, processes and community that sustain it."*

**Jhon González · Digital Archivist · archivistadigital.com · Colombia**

</div>
