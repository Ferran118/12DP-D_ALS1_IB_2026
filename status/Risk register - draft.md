# Risk register — ALS1 (12DP-D)

## Methodology

- **Likelihood (L)** and **Impact (I)** are each scored from 1 (low) to 3 (high).
- **Risk score: S = L × I** (range 1–9).
- **Category:** 1–2 Low · 3–5 Medium · 6–9 High.
- **Status:** Open (not yet occurred) · Monitoring (signs detected, being watched) · Occurred (contingency activated) · Closed · Withdrawn.

## Risk matrix

| ID | Risk | Type | L | I | S | Category | We have realized because… | Contingency plan | Related task | Owner | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|
| R1 | Using terms we don't understand or including GenAI errors or hallucinations | Scientific | 2 | 3 | 6 | High | SOD1 literature uses highly specialized terminology and the IB GenAI policy makes us liable for any GenAI-generated content. | Each section is cross-read by the other members, who must be able to understand and explain it. GenAI is only used for wording and formatting, outside GitHub, and its output is always checked manually. | 3.4.3 | Luz | Monitoring |
| R2 | Tight schedule: deadline | Team & planning | 2 | 3 | 6 | High | The final deadline on Atenea is Monday 26/10 at 22:00, and only two working days remain after the 22/10 retrospective. | Content freeze on 21/10; 22–23/10 for integration and review only; 26/10 kept exclusively as a buffer. | 1.4.1 | Ferran | Occurred |
| R3 | Uneven contribution | Team & planning | 2 | 3 | 6 | High | Our first Gantt draft assigned several tasks to "All". | Every task has a single owner and a balanced workload; each member commits their own work at least twice a week. Tasks are reassigned early if someone falls behind. | 1.4.1 | Ferran | Occurred |
| R4 | "Niche awareness" at the oral presentation | Team & planning | 2 | 3 | 6 | High | Our analysis tasks are split by specialization, each owned by a single member, while the rubric assesses every member's understanding of the whole project. | Short weekly sync where each member explains their progress to the rest; each section is cross-read by a different member; everyone reads the full report before the presentation; a rehearsal with questions about other members' sections. | 4.1.1 | Noa | Open |
| R5 | Mismatch between different sources leads to wrong positions in alignments and structures | Scientific | 3 | 2 | 6 | High | The same SOD1 mutation is named A4V in the classic literature but p.Ala5Val in ClinVar. | Before any analysis, define a single numbering convention in Methods and build a mapping table between sources. | 2.1.2 | Leyre | Occurred |
| R6 | Trying to analyse too much information (e.g. too many variants) | Scientific | 3 | 2 | 6 | High | ClinVar lists 194 SOD1 variants classified as pathogenic or likely pathogenic (consulted 08/10), far more than we can analyse. | Select 2–3 representative variants using explicit criteria by a fixed date (14/10); anything outside that scope is left for the Discussion as future work. | 2.1.2 | Leyre | Closed |
| R7 | Format errors in the submissions | Technical & format | 2 | 2 | 4 | Medium | The Formal Requirements and the BMC template impose many formal rules. | Build a checklist from the Formal Requirements and the BMC template (repo name, mandatory folders, .md report, word limits…) and review it before each delivery. Agree an approximate word budget per section from the start. Check the word count on 21/10. | 3.4.5 | Luz | Open |
| R8 | Technical problems with Git files or GitHub | Technical & format | 2 | 2 | 4 | Medium | Our repository did not meet some formal rules yet (it was named ALS1 and had no report/ folder). | Small and frequent commits. Upload deliverables at least 2 h before the deadline. | 1.1.2 | Leyre | Monitoring |
| R9 | Gantt and Status not kept up to date | Team & planning | 2 | 2 | 4 | Medium | Our first versions of the Gantt and of the Project Status had empty fields and outdated dates. | One owner updates the Project Status and the live Gantt every Monday and Thursday with real dates, status and notes; each member reports their progress at each meeting. | 1.4.1 | Ferran | Monitoring |
| R10 | ~~Distant species make the comparison hard to interpret~~ | Scientific | 1 | 2 | 2 | Low | ~~The project requires comparing human SOD1 with at least two other species, and the candidates range from close mammals to very distant organisms with much less similar sequences.~~ | ~~Choose species with a clear biological or experimental justification. If the distant species alignment is not informative, replace it with an intermediate one and explain the choice in Methods.~~ | 2.2.1 | Noa | Withdrawn |
| R11 | Online tools unavailable or slow close to the deadline | Technical & format | 1 | 2 | 2 | Low | The tools we need (BLAST, multiple sequence alignment servers) are shared public services with job queues, used by all groups in the same weeks. | Run all analyses early, well before the content freeze; save every output (files + screenshots, with date and tool version). | 2.2.2 | Noa | Closed |
| R12 | Retrieving the wrong homolog (a paralog or an unrelated database entry) | Scientific | 1 | 3 | 3 | Medium | Our bibliography and README initially contained entries for unrelated proteins taken from the class examples (TTR, serum albumin), which had to be removed on 06–09/10. | Use curated RefSeq entries (NM_/NP_), check that the gene name in the record is SOD1, and confirm that the human SOD1 protein is the best BLASTp hit when the ortholog is used as the query. | 2.2.1 | Noa | Open |

## Update log

### 21/10/2026

| ID | Status | Update |
|---|---|---|
| R1 | Monitoring |  |
| R2 | Occurred | The 21/10 content freeze was missed. Contingency applied: writing sprint on 21–23/10; 26/10 kept as a buffer (deadline 22:00). |
| R3 | Occurred | Commit counts differ widely between members. Action: each owner writes and commits their own section in small commits. |
| R4 | Open | |
| R5 | Occurred | Drafts used both A4V (legacy) and p.Ala5Val (HGVS). Contingency applied: HGVS numbering fixed, with a legacy/PDB equivalence table (task 2.1.2). |
| R6 | Closed | Only the variant in the course FASTA file must be analysed. Scope reduced to that variant (c.14C>T, p.Ala5Val, legacy A4V); other variants are left for the Discussion as future work. Specific Objectives 2 and 3 updated accordingly. |
| R7 | Open |  |
| R8 | Monitoring | Partly materialised: one branch not yet merged and some files stored in the wrong folders. Action: merge the branch through a pull request and reorganize folders. Following lecturer feedback, the live Gantt and this register are kept in Markdown so that changes are tracked by Git rather than re-uploaded as binary files. |
| R9 | Monitoring | Three non-matching versions of the live Gantt and an outdated Status header. Action: a single live Gantt and Status in Markdown, updated by their owner. |
| R10 | Withdrawn | Following lecturer feedback, differences between species are an expected scientific outcome, not a risk: they are what allows conserved functional regions to be identified. Replaced by R12. |
| R11 | Closed | All online analyses completed and outputs saved. |
| R12 | Open | New risk added after the R10 review. |
