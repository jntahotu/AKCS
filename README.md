# AKCS: ACORN Kicker Control System

Fermilab ACORN project repository for the redesign of the kicker control electronics. It holds the documents, hardware design, firmware design and software design for the AKCS. The first application is the Booster extraction kickers (MK04 to MK08).

The new design replaces the legacy CAMAC cards and NIM modules with one SoC-based board (FPGA plus Arm processor running an EPICS IOC) in its own chassis for each kicker. The candidate SoCs are the AMD Kria K26C, Altera Agilex 5 and Altera Arria 10.

> All documents are **Rev. 1.0 drafts for review**. Values marked TBD/TBC (in red in the documents) are not yet approved.

## Repository layout

| Folder | Contents |
|---|---|
| `docs/specs/` | Engineering specifications and requirements |
| `docs/plans/` | Quality assurance plan |
| `docs/analyses/` | Graded approach, FMEA, What-If and Prevention through Design (PtD) analyses |
| `docs/architecture/` | Hardware architecture block diagrams (Word, PowerPoint, PNG/SVG) |
| `docs/presentations/` | Review presentations |
| `references/` | Source documents: ACORN system descriptions and Fermilab Operations rookie books |
| `photos/west-gallery/` | Photos of the existing Booster extraction kicker equipment |
| `hardware/` | Board and chassis design (to come) |
| `firmware/` | FPGA firmware (to come) |
| `software/` | EPICS IOC and software (to come) |

## Document index

| Document | File |
|---|---|
| AKCS engineering specification and requirements, Rev. 1.1 | `docs/specs/ACORN KICKER SYSTEM SPEC DOC v1.1.docx` |
| Booster Extraction kicker subsystem specification | `docs/specs/ACORN Booster Extraction Kicker System Spec.docx` |
| Quality assurance plan | `docs/plans/ACORN Kicker Control System QA Plan.docx` |
| Engineering graded approach analysis | `docs/analyses/ACORN Booster Extraction Kicker Graded Approach Analysis.docx` |
| Failure modes and effects analysis (FMEA) | `docs/analyses/ACORN Booster Extraction Kicker FMEA.docx` |
| What-If analysis | `docs/analyses/ACORN Booster Extraction Kicker What-If Analysis.docx` |
| Prevention through Design assessment | `docs/analyses/ACORN Booster Extraction Kicker PtD Assessment.docx` |
| Hardware architecture block diagrams | `docs/architecture/` |
| Requirements and architecture presentation | `docs/presentations/ACORN Extraction Kicker Requirements and Architecture.pptx` |
| Development overview presentation | `docs/presentations/ACORN Extraction Kicker Development Overview.pptx` |

## Known open items

- The specifications, FMEA and block-diagram documents still describe one chassis per gallery. The current baseline (in the requirements and architecture presentation) is **one chassis and board per kicker**. The documents are to be updated.
- The as-found survey of legacy interfaces, timing-budget analysis and SoC trade study are pending.

## Author

J. Ntahoturi, Fermilab PPD / Electrical Engineering Department.
