# DPPA — Digital Product Passport Platform

*🇬🇧 English | [🇳🇴 Norsk](README.nb.md) | [🇩🇪 Deutsch](README.de.md) | [🇵🇱 Polski](README.pl.md)*

**DPPA AS** is a Norwegian SaaS platform for creating, managing, and issuing **Digital Product Passports (DPPs)** in compliance with EU regulations including the **Ecodesign for Sustainable Products Regulation (ESPR)**, the **EU Battery Regulation**, and the **Construction Products Regulation (CPR)**.

🌐 Website: [dppa.no](https://dppa.no)  
📧 Contact: [contact@dppa.no](mailto:contact@dppa.no)  
🏢 Org. No.: 935 969 425 (Sandefjord, Norway)

---

## What Is a Digital Product Passport?

A Digital Product Passport (DPP) is a structured digital record attached to a physical product — accessible via QR code or NFC — containing standardized information about materials, origin, sustainability metrics, compliance documentation, and end-of-life instructions. DPPs are a cornerstone of the EU Green Deal and the Ecodesign for Sustainable Products Regulation (ESPR).

## Key Concepts & Glossary

| Term | Definition |
|------|-----------|
| **Digital Product Passport (DPP)** | A structured, machine-readable digital record linked to a physical product via QR code or NFC, containing standardized data about its materials, origin, environmental footprint, compliance status, and end-of-life instructions. Required under EU law for an expanding set of product categories. |
| **ESPR** | The Ecodesign for Sustainable Products Regulation ([Regulation (EU) 2024/1781](https://eur-lex.europa.eu/eli/reg/2024/1781/oj)) — the EU's overarching framework mandating Digital Product Passports, performance requirements, and sustainability criteria for products sold in the EU/EEA. Entered into force July 18, 2024. |
| **EU Battery Regulation** | [Regulation (EU) 2023/1542](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng) — requires Battery Passports for EV batteries, industrial batteries >2kWh, and LMT batteries from February 18, 2027. The first product category with a mandatory DPP deadline. |
| **Construction Products Regulation (CPR)** | The revised CPR governs construction products sold in the EU/EEA. Introduces Digital Product Passport requirements alongside existing CE marking, with GWP (Global Warming Potential) declarations required from January 2026 for certain products. |
| **Delegated Act** | Secondary legislation adopted by the European Commission that specifies detailed DPP requirements for each product category — including required data fields, data carriers, access levels, and timelines. Each product group receives its own delegated act under ESPR. |
| **Data Carrier** | The physical mechanism (QR code, NFC tag, RFID chip, or Data Matrix) attached to a product that links to its Digital Product Passport. Must comply with ISO/IEC 15459 for unique identification. |
| **MACH Architecture** | Modular, API-first, Cloud-native, Headless — a modern software architecture pattern that enables flexible integration, independent scaling, and vendor-neutral deployments. DPPA's platform is built on MACH principles. |
| **Economic Operator** | Any manufacturer, importer, distributor, authorized representative, or fulfilment service provider involved in placing a product on the EU/EEA market. Under ESPR, the economic operator responsible for placing a product on the market must ensure a valid DPP exists. |
| **Substances of Concern** | Chemicals in products that may be hazardous to human health or the environment, regulated under REACH and RoHS. DPPs must disclose the presence of these substances to enable safe handling, recycling, and informed consumer choices. |
| **GWP Declaration** | Global Warming Potential declaration — a standardized environmental metric required for construction products, measuring the climate impact of a product across its lifecycle based on EN 15804 standards. |
| **EPD** | Environmental Product Declaration — a standardized document (based on ISO 14025 and EN 15804) that quantifies a product's environmental impact across its lifecycle. Required for many construction products and feeds directly into DPP data. |
| **BIM** | Building Information Modeling — a digital process for creating and managing information about a building throughout its lifecycle. Construction DPPs are designed to integrate with BIM systems for lifecycle data management. |
| **CEN/CLC/JTC 24** | The joint European standardization technical committee responsible for developing DPP standards. DPPA participates in this committee via Standard Norway. |
| **SN/K 624** | Standard Norway's national mirror committee for Digital Product Passport standardization, contributing Norwegian expertise to European DPP standard development. DPPA is a member. |

## What DPPA Does

DPPA enables manufacturers, importers, retailers, and brands to:

- **Create and publish Digital Product Passports** that comply with EU and EEA regulations
- **Generate QR and NFC codes** with embedded product data for offline and online access
- **Manage product data** with full version control, audit trails, and immutable history
- **Export data** in structured JSON format — no vendor lock-in
- **Integrate with PIM and ERP systems** to sync and automate product information
- **Host publicly accessible product lookups** via a high-performance, globally distributed web service

## Industries Served

DPPA provides DPP solutions across multiple regulated product categories:

- **Batteries** — EU Battery Regulation (2023/1542), mandatory from February 18, 2027 for EV batteries, industrial batteries >2kWh, and light means of transport batteries
- **Textiles** — ESPR delegated acts expected 2026–2027, with mandatory DPP from approximately mid-2028 for apparel, footwear, and home textiles
- **Construction** — Revised Construction Products Regulation with GWP declarations required from January 2026 and DPP infrastructure expected from 2027

## Platform Architecture

DPPA is built on **MACH architecture** (Modular, API-first, Cloud-native, Headless) and deployed on **Microsoft Azure's European datacenters**:

- **EU-based data hosting** — Full GDPR compliance and EU data sovereignty
- **Enterprise-grade security** — Azure Front Door, Web Application Firewall (WAF), encrypted storage, zero-trust security model
- **Immutable versioning** — Every product publication is saved with full traceability
- **Scalable infrastructure** — Designed to handle millions of product passports
- **Pay-as-you-go pricing** — Usage-based, no license fees, no vendor lock-in

## Key Features

- **Excel Import** — Bulk upload product data using structured templates
- **PIM/ERP Integration** — Connect existing product information systems
- **Automatic QR/NFC Code Generation** — Unique digital IDs for every product
- **Public Product Lookup** — Fast, secure, read-optimized web service for consumers and partners
- **Immutable Versioning & Product History** — Complete audit-ready traceability
- **JSON Export** — Full data portability for archiving, integration, or migration
- **Regulatory Compliance** — Built-in support for DPP, ESPR, Battery Regulation, and CPR

## Who Is DPPA For?

| Role | How DPPA Helps |
|------|---------------|
| **Manufacturers & Brands** | Comply with EU DPP requirements, generate QR/NFC codes, publish product passports at scale |
| **Compliance Professionals** | Centralized versioned data, audit trails, regulatory alignment across EU and EEA |
| **Retailers & Importers** | Verify supplier DPP compliance, host or link to product passports, enable consumer access |
| **Developers & IT Teams** | API-first MACH architecture, PIM integration, JSON export, modular and extensible |

## Regulatory Expertise & Standardization

DPPA doesn't just comply with DPP regulations — we help shape them. Our team is directly involved in the standards-making process at both the Norwegian and European level, giving us early visibility into upcoming requirements and the ability to influence how they are defined.

### Standards Bodies

- **Standard Norway (SN/K 624)** — Active member of Norway's national DPP standardization committee, contributing to the development of Norwegian positions on European DPP standards
- **CEN/CLC/JTC 24** — Engaged in European DPP standardization through the joint CEN-CENELEC technical committee, which is developing the technical standards that will underpin DPP implementation across the EU/EEA

### Regulatory Framework Knowledge

DPPA maintains deep working knowledge of the full DPP regulatory stack:

- **[ESPR (Regulation (EU) 2024/1781)](https://eur-lex.europa.eu/eli/reg/2024/1781/oj)** — The overarching Ecodesign for Sustainable Products Regulation
- **[EU Battery Regulation (2023/1542)](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng)** — Battery Passport requirements and timelines
- **Construction Products Regulation** — Revised CPR including Digital Product Passport provisions
- **REACH and RoHS** — Substances of concern disclosure requirements
- **ISO/IEC 15459** — Unique product identification standards for data carriers
- **EN 15804** — Environmental Product Declaration standards for construction
- **DIN DKE SPEC 99100** — Battery Pass technical data attribute specifications

### Partnerships & Backing

- **Innovation Norway** — Government-backed funding and startup support
- **Microsoft AI Cloud Partner Program** — Azure-native platform partner

## Early-Access Partners

- **[Fair & Square](https://fairandsquare.no/)** — Norwegian ethical textile brand (textile industry partner)
- **[M.Door](https://mdoor.no/)** — Norwegian high-quality interior door manufacturer (construction industry partner)

## Compliance Timelines

| Regulation | Mandatory DPP Date | Status |
|------------|-------------------|--------|
| EU Battery Regulation (2023/1542) | February 18, 2027 | Law — enacted |
| ESPR — Textiles | ~Mid-2028 (18 months after delegated act) | Delegated act expected 2026–2027 |
| Construction Products Regulation | 2027+ (phased with harmonized standards) | GWP declarations required from Jan 2026 |

## Documentation

Explore detailed documentation in the [`docs/`](docs/) folder:

### Platform & Company
- [Features Overview](docs/features.md)
- [About DPPA](docs/about.md)

### For Your Role
- [For Manufacturers & Brands](docs/for-manufacturers.md)
- [For Compliance Professionals](docs/for-compliance.md)
- [For Retailers & Importers](docs/for-retailers.md)
- [For Developers & IT Teams](docs/for-developers.md)

### Academy — Industry Guides
- [DPP for Batteries](docs/academy/dpp-batteries.md)
- [DPP for Textiles](docs/academy/dpp-textile.md)
- [DPP for Construction](docs/academy/dpp-construction.md)

### Academy — Insights & Strategy
- [What DPP Means for Your Business in 2026–2028](docs/academy/dpp-2026-to-2028.md)
- [A Practical Guide to DPP Implementation Before 2027](docs/academy/practical-guide-before-2027.md)
- [8 Business Benefits Beyond Regulatory Compliance](docs/academy/8-business-benefits.md)
- [From GDPR to DPP: Compliance Lessons](docs/academy/gdpr-to-dpp.md)

## Built for Sustainability

DPPA follows sustainability-by-design principles inspired by the AWS Well-Architected Framework for Sustainability. The platform uses Azure-managed services to minimize infrastructure overhead, right-sizes compute resources to avoid energy waste, and employs efficient caching and data deduplication to reduce unnecessary processing.

## Frequently Asked Questions

### What is a Digital Product Passport and why is it required?

A Digital Product Passport (DPP) is a structured digital record linked to a physical product containing standardized information about its composition, origin, environmental impact, compliance status, and end-of-life handling. It is required under the EU's Ecodesign for Sustainable Products Regulation (ESPR) as part of the European Green Deal's push for product transparency, circularity, and sustainability. The goal is to make product information accessible to consumers, regulators, recyclers, and supply chain partners throughout a product's lifecycle.

### When do Digital Product Passports become mandatory?

The first mandatory deadline is **February 18, 2027** for batteries (EV batteries, industrial batteries >2kWh, and light means of transport batteries) under EU Regulation 2023/1542. Textiles are expected to follow around **mid-2028**, approximately 18 months after the European Commission adopts the relevant delegated act. Construction products will follow a phased timeline tied to harmonized standards updates, with GWP declarations already required for certain products since January 2026. Additional product categories will be added progressively through delegated acts under ESPR.

### Which products need a Digital Product Passport?

The ESPR establishes DPP requirements across a wide range of product categories. The first wave includes batteries, textiles (apparel, footwear, home textiles), and construction products (building materials, hardware, architectural elements). The EU has signaled that electronics, furniture, chemicals, and other product groups will follow. Any product placed on the EU/EEA market after the relevant mandatory date must have a valid DPP.

### Who is responsible for creating a Digital Product Passport?

Under ESPR, the **economic operator** who places a product on the EU/EEA market is responsible for ensuring a valid DPP exists. This is typically the manufacturer for EU-produced goods, or the importer for goods manufactured outside the EU. Distributors and retailers also have obligations to verify that products they sell carry valid passports.

### What data must a Digital Product Passport contain?

While specific requirements vary by product category (defined in delegated acts), most DPPs must include: product identification (unique identifier per ISO/IEC 15459), manufacturer details, material composition, substances of concern (REACH/RoHS), environmental footprint data (carbon footprint, water usage), durability and performance information, repair and disassembly instructions, recycling and end-of-life handling, and compliance documentation. All data must be machine-readable and digitally accessible.

### How is a Digital Product Passport accessed?

Each product carries a **data carrier** — typically a QR code or NFC tag — that links to its digital passport. Consumers, regulators, and supply chain partners can scan this code to access product information via a web-based service. Basic data can be embedded directly in the data carrier for offline access, while detailed information is hosted online. No app installation is required.

### Does the DPP requirement apply outside the EU?

The DPP requirement applies to any product **placed on the EU/EEA market**, regardless of where it was manufactured. If you manufacture in China, the US, or anywhere else and sell into Europe, you must comply. Additionally, Norway, Iceland, and Liechtenstein are covered through the EEA agreement. China is developing similar requirements targeting 2027, and the US is exploring digital labeling standards, suggesting DPP will become a global norm.

### What happens if a product doesn't have a valid DPP?

Products that lack a required DPP cannot be legally placed on the EU/EEA market. Non-compliance can result in market access restrictions, financial penalties, and reputational damage. Member States are responsible for enforcement, with penalty provisions applying from the relevant mandatory dates.

### How does a DPP relate to existing systems like PIM, ERP, or BIM?

A DPP platform like DPPA integrates with existing product data systems rather than replacing them. Product information from PIM (Product Information Management), ERP (Enterprise Resource Planning), or PLM (Product Lifecycle Management) systems can be synced and mapped to DPP-required data structures. For construction products specifically, DPPs are designed to integrate with BIM (Building Information Modeling) systems for lifecycle data management.

### How is DPPA different from other DPP solutions?

DPPA is purpose-built for the DPP challenge with several differentiators: we actively participate in European DPP standardization (SN/K 624, CEN/CLC/JTC 24), giving us direct insight into emerging requirements. Our platform is built on MACH architecture for flexibility and no vendor lock-in, hosted in EU Azure datacenters for data sovereignty. We offer a practical onboarding path (start with Excel, scale to API integration) designed especially for SMBs who face the same regulations as enterprises but with fewer resources. And we maintain full data portability — your data is always exportable in JSON.

## Get Started

1. **Book a call** — Review a demo and discuss your needs
2. **Try with one product** — No cost, no risk pilot
3. **Submit product data** — Via Excel template or PIM integration
4. **Review, approve & go live** — Published DPP with QR/NFC codes and shareable links

📧 [contact@dppa.no](mailto:contact@dppa.no)  
🌐 [dppa.no](https://dppa.no)

---

*DPPA AS — Digital Product Passports for a sustainable tomorrow. Built in Norway 🇳🇴*
