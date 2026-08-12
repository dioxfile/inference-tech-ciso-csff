![Inference Tech](assets/images/inference-tech-logo.png)

# CISO-CSFF

### Cybersecurity Framework Fuzzy Inference System

**Intelligent Cybersecurity Risk Assessment powered by Hierarchical
Fuzzy Logic**

CISO-CSFF is a proprietary **Software as a Service (SaaS)** platform for
cybersecurity risk assessment, security governance, and decision
support. It combines **CIS Controls v8.1** and **ISO/IEC 27002:2022**
with hierarchical fuzzy inference to transform security-control maturity
into contextualized cybersecurity risk indicators.

**Assessment models:** CIS Controls v8.1 · ISO/IEC 27002:2022 · Hybrid
CIS + ISO

> **Proprietary SaaS Technology**  
> This repository provides public product documentation, scientific
> information, demonstrations, and institutional material. Source code,
> proprietary fuzzy models, rule bases, internal algorithms, and
> infrastructure configuration are not publicly distributed.

------------------------------------------------------------------------

## Overview

Traditional cybersecurity assessments often rely on binary checklists,
compliance percentages, or qualitative risk matrices. These approaches
may hide critical weaknesses when strong results in some domains
compensate numerically for serious deficiencies in others.

CISO-CSFF addresses this limitation through **Hierarchical Fuzzy
Inference Systems (HFS)**. The platform distinguishes security maturity
from inferred cybersecurity risk and provides framework-specific as well
as consolidated risk indicators.

### Maturity is not Risk

**Security Maturity** represents the level of implementation or
adherence to evaluated security controls.

**Fuzzy Risk** is an inferred cybersecurity risk indicator produced by
the fuzzy inference process.

> **Risk ≠ 100 − Maturity**

Two organizations with similar maturity percentages may therefore
present different risk profiles depending on which controls or security
domains are deficient.

------------------------------------------------------------------------

## Assessment Models

### CIS Controls v8.1

The CIS model evaluates security-control maturity according to **CIS
Controls v8.1**. Its hierarchical fuzzy architecture processes
control-level information through multiple inference stages and produces
the final **CIS Risk** indicator.

### ISO/IEC 27002:2022

The ISO model evaluates information-security controls according to
**ISO/IEC 27002:2022**, considering organizational, people, physical,
and technological control domains. The model produces the final **ISO
Risk** indicator.

### Hybrid CIS + ISO

The Hybrid model operates at a higher inference level. It **does not
directly receive the individual CIS or ISO controls**. Instead, it
receives the final risk indicators independently produced by the CIS and
ISO models:

``` text
CIS Controls v8.1 ──► CIS Fuzzy Model ──► CIS Risk ──┐
                                                     ├──► Hybrid Fuzzy Model ──► Global Risk
ISO/IEC 27002:2022 ─► ISO Fuzzy Model ──► ISO Risk ──┘
```

Thus, **CIS Risk** and **ISO Risk** are the input variables of the
Hybrid Fuzzy Model, whose output is the consolidated **Global Risk**.

------------------------------------------------------------------------

## Hierarchical Fuzzy Intelligence

CISO-CSFF uses hierarchical fuzzy inference to decompose complex
cybersecurity assessments into interconnected inference stages rather
than concentrating all variables in a single monolithic rule base.

This architecture supports:

- modular and scalable risk processing;
- greater interpretability of intermediate results;
- reduced rule-base complexity;
- diagnostic visibility across security domains;
- integration of multiple cybersecurity frameworks.

The methodology also incorporates a **non-compensatory risk approach**,
so strong performance in one security domain does not automatically
neutralize a critical weakness in another.

------------------------------------------------------------------------

## Scientific Foundation

CISO-CSFF originates from academic research in cybersecurity risk
assessment, fuzzy logic, and decision-support systems.

The CIS, ISO, and Hybrid models were computationally evaluated using
**5,000 randomly generated scenarios for each assessment model**. The
validation examined output distributions, minimum and maximum values,
mean, standard deviation, sensitivity to input variations, behavior in
extreme scenarios, inference consistency, and model robustness.

### Research Paper

**CIS Controls and ISO/IEC 27002 – Cybersecurity Fuzzy Framework
(CISO-CSFF): A New Hierarchical Fuzzy Inference System Approach for
Security Risk Assessment**

**Authors:** Bruno Hernandes Carrilho Martins · Diógenes Antonio Marques
José · Armando da Silva Filho  
**Institution:** State University of Mato Grosso — UNEMAT, Brazil

Official bibliographic information will be added according to the
definitive publication record.

------------------------------------------------------------------------

## Platform Screens and Usage

The following screens illustrate the main access and organizational
setup flow of the CISO-CSFF SaaS platform.

### Home

Public presentation of CISO-CSFF, its cybersecurity assessment proposal,
supported frameworks, and platform access.

![CISO-CSFF Home](assets/screenshots/home.png)

### Login

Secure access for registered and authorized platform users.

![CISO-CSFF Login](assets/screenshots/login.png)

### User Registration

Account registration for access to the CISO-CSFF environment.

![CISO-CSFF User Registration](assets/screenshots/cadastro.png)

### Framework Selection

Selection of the assessment model: **CIS Controls v8.1**, **ISO/IEC
27002:2022**, or **Hybrid CIS + ISO**.

![CISO-CSFF Framework
Selection](assets/screenshots/escolha-framework.png)

### Organization

Registration and selection of the organization to which cybersecurity
assessments will be associated.

![CISO-CSFF Organization](assets/screenshots/adicionar-organizacao.png)

### Unit

Registration of organizational units for structured assessment across
different components of the organization.

![CISO-CSFF Unit](assets/screenshots/adicionar-unidade.png)

### Entity

Registration of entities associated with the organizational assessment
context.

![CISO-CSFF Entity](assets/screenshots/adicionar-entidade.png)

------------------------------------------------------------------------

## Demonstrations

Demonstration videos will be progressively published to present the main
CISO-CSFF workflows, including platform access, organizational
configuration, CIS assessment, ISO assessment, Hybrid assessment, risk
interpretation, and results.

------------------------------------------------------------------------

## Cybersecurity Governance and LGPD

CISO-CSFF can support cybersecurity governance initiatives involving
**CIS Controls v8.1**, **ISO/IEC 27002:2022**, **ISO/IEC 27001**,
information-security maturity assessment, GRC activities, and
cybersecurity risk management.

In Brazil, the platform can assist organizations in evaluating technical
and organizational security practices associated with data-protection
governance and security measures related to the **Lei Geral de Proteção
de Dados (LGPD)**.

> CISO-CSFF is a cybersecurity risk-assessment and decision-support
> platform. Its results do not, by themselves, constitute legal
> certification, regulatory approval, ISO certification, or an
> independent cybersecurity audit.

------------------------------------------------------------------------

## Intellectual Property

CISO-CSFF is proprietary technology developed from research conducted at
the **State University of Mato Grosso — UNEMAT, Brazil**.

### Registered Computer Program

The CISO-CSFF software is officially registered with the **Brazilian
National Institute of Industrial Property (INPI)**.

| Information            | Registration                                                               |
|------------------------|----------------------------------------------------------------------------|
| **Title**              | CIS Controls and ISO/IEC 27002 - Cybersecurity Fuzzy Framework (CISO-CSFF) |
| **INPI Registration**  | **BR512026005357-9**                                                       |
| **Creation Date**      | April 1, 2026                                                              |
| **Certificate Issued** | July 14, 2026                                                              |
| **Rights Holder**      | Universidade do Estado de Mato Grosso — UNEMAT                             |
| **Authors**            | Diógenes Antonio Marques José; Bruno Hernandes Carrilho Martins            |
| **Protection**         | Computer Program Registration — Brazil                                     |

[View the INPI Software Registration
Certificate](docs/intellectual-property/REGISTRO-CISO-CSFF-INPI.pdf)

### Patent-Pending Computational Method

In addition to the registered software, the computational method
underlying CISO-CSFF is the subject of a **patent application** related
to its cybersecurity risk-assessment methodology.

The technological approach includes hierarchical processing of
cybersecurity-control indicators, independent generation of **CIS Risk**
and **ISO Risk**, and higher-level fuzzy processing of these indicators
to produce **Global Risk**, together with mechanisms for
non-compensatory treatment of relevant security weaknesses.

> Public availability of this repository does not grant permission to
> reproduce, modify, reverse engineer, redistribute, sublicense, or
> commercially exploit the CISO-CSFF software, proprietary inference
> models, rule bases, algorithms, or protected computational methods.

------------------------------------------------------------------------

## Software as a Service

CISO-CSFF is delivered as a **web-based SaaS platform**. Users access
the assessment environment through the web interface while proprietary
computational models remain protected within the service infrastructure.

No local installation or source-code access is required for normal use.

------------------------------------------------------------------------

## Current Status

| Item                      | Status                   |
|---------------------------|--------------------------|
| **Product**               | CISO-CSFF                |
| **Delivery Model**        | SaaS                     |
| **Platform**              | Web                      |
| **Current Availability**  | Controlled testing       |
| **Commercial Release**    | Planned for October 2026 |
| **Software Registration** | INPI BR512026005357-9    |
| **Computational Method**  | Patent application filed |

------------------------------------------------------------------------

## Intended Users

CISO-CSFF is designed for organizations and professionals involved in
cybersecurity governance and risk management, including CISOs,
information-security managers, cybersecurity teams, GRC professionals,
risk managers, consultants, internal audit teams, public and private
organizations, and research or educational institutions.

------------------------------------------------------------------------

## Proprietary Software and Licensing

CISO-CSFF is **not an open-source project**. No source-code license is
granted through this repository.

Access to the software is provided through the official SaaS platform
under applicable commercial terms. Scientific publications and
third-party standards or frameworks referenced by the project remain
subject to their respective rights and licensing conditions.

------------------------------------------------------------------------

## Security

Potential security vulnerabilities should not be disclosed through
public GitHub Issues. Responsible-disclosure contact information will be
provided through the official CISO-CSFF channels.

------------------------------------------------------------------------

## Commercial Availability

CISO-CSFF is currently in controlled testing and preparation for
commercial availability.

**Commercial release is planned for October 2026.**

Information about SaaS subscriptions, institutional plans,
demonstrations, pilot projects, partnerships, and commercial access will
be published through the official project channels.

------------------------------------------------------------------------

## Contact

For institutional partnerships, research collaboration, technology
transfer, pilot projects, and commercial inquiries, please use the
official CISO-CSFF / Inference Tech contact channels.

------------------------------------------------------------------------

### CISO-CSFF

**From Security Maturity to Intelligent Cybersecurity Risk Assessment**

*Hierarchical Fuzzy Logic · CIS Controls v8.1 · ISO/IEC 27002:2022 ·
Cybersecurity Risk · Decision Support*

© 2026 Universidade do Estado de Mato Grosso — UNEMAT. CISO-CSFF. All
rights reserved.
