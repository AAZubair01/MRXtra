# MRXtra

### AI-Assisted MRI Safety Screening, Workflow Decision Support, and Protocol Optimization

MRXtra is a **web-based, AI-assisted clinical decision-support platform** designed to strengthen MRI safety screening, workflow decision support, and patient-specific protocol optimization, particularly in resource-limited clinical environments.

The platform focuses on the **upstream MRI workflow**, where critical decisions concerning patient safety, contraindications, implants and devices, and acquisition protocols are made before image acquisition.

> **Clinical principle:** MRXtra provides decision support for qualified MRI professionals. It is not intended to replace professional clinical judgement.

## Platform Overview

MRXtra integrates three core functions:

- **MRI Safety Screening** — structured digital screening, adaptive questioning, deterministic evidence-based safety rules, contraindication flagging, and risk classification.
- **Protocol Decision Support** — patient- and risk-aware protocol suggestions informed by clinical indication, patient factors, safety classification, and acquisition considerations.
- **Structured MRI Workflow** — standardized digital documentation, action tracking, communication, audit trails, and workflow records.

The platform combines deterministic safety logic with AI-assisted functions while maintaining human oversight of clinical decisions.

## Clinical Feasibility Evaluation

MRXtra has undergone a **completed prospective single-centre pre-post clinical feasibility evaluation** in routine MRI practice at a Nigerian tertiary centre.

The study included **160 consecutive MRI patients**, comprising 80 patients screened using the existing paper-based workflow and 80 patients screened using MRXtra.

Selected findings included:

| Outcome | Baseline | MRXtra |
|---|---:|---:|
| Screening completeness | 53.8% | 96.3% |
| Contraindications detected | 2 | 15 |
| Median total workflow time | 105 min | 78 min |

Additional findings:

- Screening completeness: **p < 0.001**
- Contraindication detection: **p = 0.001**
- Total workflow time: **p < 0.001**
- Mean System Usability Scale score: **79.0/100** among five radiographers
- **80** protocol recommendations generated
- **70%** accepted without modification
- **20%** modified
- **10%** overridden
- Logged technical/workflow events were resolved **without patient harm**

These findings support clinical feasibility in the evaluated setting. As a single-centre, non-randomized pre-post study, external and multicentre validation is required before broader effectiveness claims are made.

## MRI Safety Rule-Engine Validation

The MRXtra MRI safety rule engine has also undergone expert evaluation, reported in an abstract accepted at **AMAI-MICCAI 2026**.

Key results:

- **42** evidence-based MRI safety rules
- **8** clinical domains
- **95.2%** rule correctness — Expert Rater 1
- **97.6%** rule correctness — Expert Rater 2
- **κ = 0.66** inter-rater agreement
- **7/7** evaluated life-threatening safety rules correctly classified by both raters
- **14/15** agreement across integrated patient scenarios
- Rules mapped to **ACR 2024 guidance**

The accepted abstract is available in the [`publications`](publications/) directory.

## Research Programme

The development and evaluation of MRXtra follow a staged clinical-translation pathway:

1. **Clinical co-design** — engage MRI clinicians, including radiographers and radiologists, to identify real workflow needs and co-design appropriate solutions.
2. **System development** — develop interpretable MRI safety, workflow, and protocol decision-support components.
3. **Expert validation** — evaluate the MRI safety rule engine using expert assessment and integrated clinical scenarios.
4. **Clinical feasibility evaluation** — prospectively evaluate the platform in routine MRI practice.
5. **External validation** — extend evaluation across institutions, scanners, patient populations, and clinical workflows.

## Health Equity Focus

MRXtra is designed around challenges encountered in resource-limited MRI environments, including variable workflow standardization, paper-based safety screening, limited specialist MRI safety support, and fragmented clinical documentation.

The project aims to support:

- standardized MRI safety screening;
- locally deployable decision support;
- structured and auditable MRI records;
- human oversight of clinical decisions;
- development of locally representative MRI workflow data; and
- scalable implementation across resource-constrained clinical settings.

## Funding and Acknowledgements

This project is supported by a **2026 MICCAI Society Award for the Advancement of Health Equity**.

We also thank **NordInsight (Denmark)** and **AIRA Africa** for their generous collaborative support.

## Research Team

MRXtra is being developed through multidisciplinary collaboration involving MRI radiographers, radiologists, imaging scientists and MRI physicists, software and AI researchers, health informatics specialists, and implementation researchers.

Authors associated with the AMAI-MICCAI 2026 accepted abstract include:

**Abdulrazaq A. Zubair, Musa Y. Dambele, M. Abba, Nafiu M. Muhammad, Abbas M. Rabiu, A. Muhammad, Zulyadaini A. Muhammad, M. Tarisiro, Musa M. Sani, M. Sidi, M. Yakubu, and Charles B. Delahunt.**

## Project Website

**MRXtra Project Website:**  
https://aazubair01.github.io/MRXtra/

## Contact

**Email**

- **PI:** aazubair01@gmail.com
- **CPI:** charles.delahunt@proton.me

**Phone:** +234 818 981 7182

## Publications

- **MRXtra: An AI-Assisted System for MRI Safety Screening, Workflow Decision Support, and Protocol Optimization in Resource-Limited Settings.** Accepted abstract, AMAI-MICCAI 2026. Conference publication forthcoming.
- **Clinical Feasibility of an Upstream AI-Assisted Decision Support System for MRI Safety Screening and Protocol Optimization in a Nigerian Tertiary Center.** Completed prospective single-centre clinical feasibility study; manuscript under revision.

## Disclaimer

MRXtra is a clinical decision-support platform under research and evaluation. It is **not intended to replace the judgement of qualified MRI professionals**, institutional MRI safety procedures, or applicable regulatory and professional guidance.

---

© 2026 MRXtra Project
