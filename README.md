# inference-tech-ciso-csff
CISO-CSFF — Intelligent cybersecurity risk assessment SaaS powered by Hierarchical Fuzzy Logic, CIS Controls v8.1, and ISO/IEC 27002:2022.
```{=html}
<p align="center">
```
`<img src="assets/images/inference-tech-logo.png" alt="Inference Tech" width="720">`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
`<strong>`{=html}Proprietary Cybersecurity Technology by Inference
Tech`</strong>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

# CISO-CSFF

### Cybersecurity Framework Fuzzy Inference System

**Cybersecurity Risk Assessment powered by Hierarchical Fuzzy Logic**

CISO-CSFF is a proprietary **Software as a Service (SaaS)** platform for
cybersecurity risk assessment, security governance, and decision
support.

The platform combines internationally recognized cybersecurity
frameworks with a hierarchical fuzzy inference methodology to transform
security-control maturity information into quantitative cybersecurity
risk indicators.

CISO-CSFF currently supports:

-   **CIS Controls v8.1**
-   **ISO/IEC 27002:2022**
-   **Hybrid CIS + ISO Assessment**

The Hybrid assessment consolidates the perspectives of both frameworks
into a unified cybersecurity risk indicator.

> **Proprietary SaaS Technology**\
> This public repository contains product documentation, scientific
> information, demonstrations, and public technical material. The
> CISO-CSFF source code, proprietary inference models, rule bases,
> internal algorithms, and infrastructure configuration are not
> distributed through this repository.

------------------------------------------------------------------------

## What is CISO-CSFF?

Traditional cybersecurity assessments frequently rely on binary
checklists, compliance percentages, or qualitative risk matrices.

Although useful, these approaches may not adequately represent
situations in which an organization has a high overall level of
compliance but still presents critical weaknesses in specific security
domains.

CISO-CSFF was developed to address this problem.

Instead of treating cybersecurity risk as a simple arithmetic inverse of
compliance, the platform uses **Fuzzy Logic and Hierarchical Fuzzy
Inference Systems** to analyze how different security-control maturity
levels interact.

The result is a contextualized representation of organizational
cybersecurity risk designed to support security governance and
decision-making.

------------------------------------------------------------------------

## Maturity is not Risk

A central concept of CISO-CSFF is the distinction between:

### Security Maturity

A quantitative measure representing the level of implementation or
adherence to evaluated security controls.

### Fuzzy Risk

A cybersecurity risk indicator generated through the fuzzy inference
process.

Therefore:

``` text
Risk ≠ 100 − Maturity
```

Two organizations with similar maturity percentages may present
significantly different risk profiles depending on which security
controls are absent, weak, or critically deficient.

CISO-CSFF is designed to capture this distinction.

------------------------------------------------------------------------

## Assessment Modes

### CIS Controls v8.1

Assessment based on the practical and prioritized cybersecurity controls
defined by the Center for Internet Security.

The CISO-CSFF hierarchical model processes control-level information
through multiple inference stages to generate a consolidated **CIS
Risk** indicator.

### ISO/IEC 27002:2022

Assessment based on the information-security controls defined by ISO/IEC
27002:2022.

The platform evaluates security maturity across organizational, people,
physical, and technological control domains and generates an **ISO
Risk** indicator.

### Hybrid CIS + ISO

The Hybrid model integrates the risk perspectives produced by the CIS
and ISO assessments.

Conceptually:

``` text
CIS Controls ──► Hierarchical Fuzzy Assessment ──► CIS Risk
                                                       │
                                                       ▼
                                              Global Fuzzy Assessment
                                                       │
                                                       ▼
                                                  Global Risk
                                                       ▲
                                                       │
ISO/IEC 27002 ───────── Fuzzy Assessment ───────► ISO Risk
```

This approach enables organizations to obtain framework-specific
indicators and a consolidated cybersecurity risk perspective.

------------------------------------------------------------------------

## Hierarchical Fuzzy Intelligence

CISO-CSFF uses a **Hierarchical Fuzzy System (HFS)** rather than relying
exclusively on a single monolithic inference model.

Security indicators are processed through interconnected fuzzy inference
stages. This architecture supports:

-   reduced rule-base complexity;
-   scalability;
-   interpretability;
-   modular risk processing;
-   diagnostic visibility across security domains;
-   multi-framework cybersecurity assessment.

------------------------------------------------------------------------

## Non-Compensatory Risk Assessment

Cybersecurity risk should not necessarily be reduced simply because an
organization performs well in unrelated security domains.

Strong performance in one domain should not automatically neutralize a
critical deficiency in another.

CISO-CSFF therefore incorporates a **non-compensatory risk philosophy**,
designed to reduce artificially optimistic risk indicators caused by
simple arithmetic averaging.

------------------------------------------------------------------------

## Scientific Foundation

CISO-CSFF originates from academic research in cybersecurity risk
assessment, fuzzy logic, and decision-support systems.

The CIS, ISO, and Hybrid models were computationally evaluated using
**5,000 randomly generated scenarios for each assessment model**.

The validation examined characteristics including:

-   statistical behavior of outputs;
-   minimum and maximum risk values;
-   mean and standard deviation;
-   output distribution;
-   model sensitivity;
-   behavior in extreme scenarios;
-   inference consistency;
-   robustness of the fuzzy models.

### Research Paper

**CIS Controls and ISO/IEC 27002 -- Cybersecurity Fuzzy Framework
(CISO-CSFF): A New Hierarchical Fuzzy Inference System Approach for
Security Risk Assessment**

**Authors**

-   Bruno Hernandes Carrilho Martins
-   Diógenes Antonio Marques José
-   Armando da Silva Filho

**Institution**

State University of Mato Grosso --- UNEMAT, Brazil

Official bibliographic information and citation data will be updated
according to the definitive publication record.

------------------------------------------------------------------------

## Cybersecurity Governance and LGPD Context

CISO-CSFF can support cybersecurity governance initiatives involving CIS
Controls v8.1, ISO/IEC 27002:2022, ISO/IEC 27001, information-security
maturity assessment, GRC activities, and cybersecurity risk management.

In Brazil, the platform can assist organizations in evaluating technical
and organizational security practices associated with data-protection
governance and the security measures expected under the **Lei Geral de
Proteção de Dados (LGPD)**.

CISO-CSFF is a **decision-support and cybersecurity risk-assessment
platform**. Its results do not, by themselves, constitute legal
certification, regulatory approval, ISO certification, or an independent
cybersecurity audit.

------------------------------------------------------------------------

## Screens and Platform Usage

This section presents the main screens and a high-level usage flow of
the CISO-CSFF SaaS platform.

> **Image organization:** place public screenshots in
> `assets/screenshots/`. The links below are already prepared for these
> filenames. Replace each placeholder file with the corresponding
> screenshot when it is ready.

### 1. Home

The public Home page introduces CISO-CSFF, its purpose, supported
cybersecurity frameworks, and access to the platform.

[View Home screen](assets/screenshots/home.png)

``` markdown
![CISO-CSFF Home](assets/screenshots/home.png)
```

### 2. Login

The Login screen provides access to the SaaS environment for registered
and authorized users.

[View Login screen](assets/screenshots/login.png)

``` markdown
![CISO-CSFF Login](assets/screenshots/login.png)
```

### 3. User Registration

The Registration screen supports the creation of an account for access
to the platform according to the applicable service and authorization
rules.

[View Registration screen](assets/screenshots/cadastro.png)

``` markdown
![CISO-CSFF User Registration](assets/screenshots/cadastro.png)
```

### 4. Framework Selection

After accessing the platform, the user can select the cybersecurity
assessment model to be used:

-   CIS Controls v8.1;
-   ISO/IEC 27002:2022;
-   Hybrid CIS + ISO.

[View Framework Selection
screen](assets/screenshots/escolha-framework.png)

``` markdown
![CISO-CSFF Framework Selection](assets/screenshots/escolha-framework.png)
```

### 5. Adding an Organization

The organization structure allows assessments to be associated with the
organizational context being evaluated.

[View Add Organization
screen](assets/screenshots/adicionar-organizacao.png)

``` markdown
![CISO-CSFF - Add Organization](assets/screenshots/adicionar-organizacao.png)
```

### 6. Adding a Unit

Units can be associated with an organization to support structured
assessments across different organizational components.

[View Add Unit screen](assets/screenshots/adicionar-unidade.png)

``` markdown
![CISO-CSFF - Add Unit](assets/screenshots/adicionar-unidade.png)
```

### 7. Adding an Entity

Entities can be registered within the platform's organizational
structure according to the assessment context.

[View Add Entity screen](assets/screenshots/adicionar-entidade.png)

``` markdown
![CISO-CSFF - Add Entity](assets/screenshots/adicionar-entidade.png)
```

### Suggested Public Screenshot Structure

``` text
assets/
└── screenshots/
    ├── home.png
    ├── login.png
    ├── cadastro.png
    ├── escolha-framework.png
    ├── adicionar-organizacao.png
    ├── adicionar-unidade.png
    └── adicionar-entidade.png
```

As the public documentation evolves, additional screens can be added for
assessment execution, dashboards, risk results, reports, and
administrative workflows.

------------------------------------------------------------------------

## Demonstrations

Public demonstration videos will be progressively released.

  -----------------------------------------------------------------------
  Demonstration           Description             Status
  ----------------------- ----------------------- -----------------------
  Platform Overview       Introduction to the     Coming soon
                          CISO-CSFF SaaS          
                          environment             

  Account and Access      Registration and        Coming soon
                          platform access         

  Organizational          Organization, Unit, and Coming soon
  Structure               Entity workflow         

  CIS Assessment          CIS Controls v8.1       Coming soon
                          assessment workflow     

  ISO Assessment          ISO/IEC 27002:2022      Coming soon
                          assessment workflow     

  Hybrid Assessment       Combined CIS and ISO    Coming soon
                          assessment              

  Risk Interpretation     Maturity and fuzzy-risk Coming soon
                          interpretation          

  Results and Reports     Assessment results and  Coming soon
                          reporting               
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Intellectual Property

CISO-CSFF is a **proprietary cybersecurity technology** developed from
research conducted at the **State University of Mato Grosso --- UNEMAT,
Brazil**.

### Registered Computer Program

The CISO-CSFF software is officially registered with the **Brazilian
National Institute of Industrial Property (INPI)**.

  ---------------------------------------------------------------------
  Information                        Registration
  ---------------------------------- ----------------------------------
  **Title**                          CIS Controls and ISO/IEC 27002 -
                                     Cybersecurity Fuzzy Framework
                                     (CISO-CSFF)

  **INPI Registration**              **BR512026005357-9**

  **Creation Date**                  April 1, 2026

  **Certificate Issued**             July 14, 2026

  **Rights Holder**                  Universidade do Estado de Mato
                                     Grosso --- UNEMAT

  **Authors**                        Diógenes Antonio Marques José;
                                     Bruno Hernandes Carrilho Martins

  **Protection**                     Computer Program Registration ---
                                     Brazil
  ---------------------------------------------------------------------

The registration provides legal protection for the computer program
under Brazilian software intellectual-property legislation.

### Patent-Pending Computational Method

In addition to the registered software, the computational method
underlying CISO-CSFF is the subject of a **patent application**
involving its cybersecurity risk-assessment methodology.

The technological approach includes hierarchical processing of
cybersecurity-control indicators, framework-specific risk assessment,
consolidated risk assessment, and mechanisms for non-compensatory
treatment of relevant security weaknesses.

> **CISO-CSFF is proprietary technology.** Public availability of this
> repository does not constitute publication or licensing of the
> platform's source code, proprietary inference models, fuzzy rule
> bases, internal algorithms, or other protected implementation
> components.

------------------------------------------------------------------------

## Intended Users

CISO-CSFF is designed for professionals and organizations involved in
cybersecurity and information-security governance, including:

-   Chief Information Security Officers --- CISOs;
-   information-security managers;
-   cybersecurity teams;
-   GRC professionals;
-   risk managers;
-   security consultants;
-   internal audit teams;
-   public and private organizations;
-   research and educational institutions.

------------------------------------------------------------------------

## Software as a Service

CISO-CSFF is provided as a **web-based SaaS platform**.

Users interact with the cybersecurity assessment environment through a
web interface while proprietary inference models and computational
methods remain protected within the service infrastructure.

No local installation or access to the CISO-CSFF source code is required
for normal platform use.

------------------------------------------------------------------------

## Current Status

  Item                          Status
  ----------------------------- --------------------------
  **Product Type**              SaaS
  **Platform**                  Web
  **Development Stage**         Pre-commercial
  **Current Availability**      Controlled testing
  **Commercial Availability**   Planned for October 2026
  **Software Registration**     INPI BR512026005357-9
  **Computational Method**      Patent application filed

------------------------------------------------------------------------

## Public Repository Policy

This repository is intentionally focused on **public product and
scientific documentation**.

It may contain:

-   product documentation;
-   conceptual architecture diagrams;
-   public screenshots;
-   demonstration videos;
-   scientific publications and references;
-   methodological descriptions at an appropriate public level;
-   public release information.

It does **not** distribute:

-   application source code;
-   proprietary fuzzy models;
-   fuzzy rule bases;
-   inference files;
-   internal APIs;
-   infrastructure configuration;
-   deployment procedures;
-   security credentials;
-   confidential internal technical documentation.

------------------------------------------------------------------------

## Source Code and Licensing

CISO-CSFF is **not an open-source project**.

No source-code license is granted through this repository. Access to the
software is provided through the official SaaS platform under the
applicable commercial terms.

Scientific publications and third-party standards or frameworks
referenced by this project remain subject to their respective rights and
licensing conditions.

------------------------------------------------------------------------

## Security

Security vulnerabilities or suspected security issues should not be
publicly disclosed through GitHub Issues.

A responsible security-disclosure channel will be provided through the
official CISO-CSFF contact channels.

------------------------------------------------------------------------

## Documentation

Additional public documentation can be organized in the `docs/`
directory:

``` text
docs/
├── overview.md
├── methodology.md
├── scientific-validation.md
├── cis-controls.md
├── iso-27002.md
├── hybrid-model.md
├── lgpd.md
├── intellectual-property.md
└── faq.md
```

------------------------------------------------------------------------

## Commercial Availability

CISO-CSFF is currently undergoing controlled testing and preparation for
commercial availability.

**Commercial release is planned for October 2026.**

Information regarding SaaS subscriptions, institutional plans,
demonstrations, pilot projects, partnerships, and commercial access will
be announced through the official project channels.

------------------------------------------------------------------------

## Contact

For institutional partnerships, research collaboration, technology
transfer, pilot projects, and commercial inquiries, please use the
official CISO-CSFF contact channels.

------------------------------------------------------------------------

## CISO-CSFF

### From Security Maturity to Intelligent Cybersecurity Risk Assessment

**Hierarchical Fuzzy Logic · CIS Controls v8.1 · ISO/IEC 27002:2022 ·
Cybersecurity Risk · Decision Support**

------------------------------------------------------------------------

© 2026 Universidade do Estado de Mato Grosso --- UNEMAT. CISO-CSFF. All
rights reserved.
