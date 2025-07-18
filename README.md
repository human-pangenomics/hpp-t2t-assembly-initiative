
<img src="images/pangenome_art.png" alt="Figure 1: overview diagram" width="100%" />

# Human Pangenome Project (HPP) T2T Assembly Initiative

## Welcome  
We are excited to welcome you as part of this international effort to co-develop a globally representative, telomere-to-telomere (T2T) pangenome resource. This task team operates under the umbrella of the Human Pangenome Project (HPP), a GA4GH Driver Project committed to building equitable and inclusive reference systems that serve all populations.

Our shared objective is to create **best-in-class** assembly standards, methods, and reference materials, beginning with a project leveraging well-characterized 1000 Genomes (1000G) cell lines. These lines provide a unique opportunity to initiate collaboration across diverse partners under a common consent framework, and to produce a foundational T2T resource that is open, reusable, and globally impactful.

**Why this matters now:**  
As we look ahead to a coordinated community release of the next global human pangenome reference in **Summer 2026**, this task team plays a critical role in aligning international efforts. The target release will include:

- **350 assemblies** from the Human Pangenome Reference Consortium (HPRC)  
- **65 assemblies** from the Human Genome Structural Variation Consortium (HGSVC)  
- **New contributions** from international collaborators  

Together, we have the opportunity to shape this reference by co-producing assemblies, establishing reproducible pipelines, and advancing a new era of comparative human genomics. This GitHub site serves as our central hub for project updates, timelines, and shared documentation. We invite you to join us by completing the interest form, and contributing to the collaborative planning now underway.

[Link to Collaboration Guidelines]

---

## Project Timeline

### Overview  

![Figure 1: overview diagram](images/timeline.png)

### Important Tentative Dates

| Milestone                                                   | Date                     |
|-------------------------------------------------------------|--------------------------|
| Official Launch of the Task Team                            | August 2025              |
| Next versioned release of assembly method                   | December 2025            |
| — Submit assembly workflows for consideration               | by **October 1, 2025**   |
| Sequence Production Data Submission Deadline                | January 2026             |
| — Log all sequencing projects by **October 1, 2025**        |                          |
| T2T Assembly Completion and Upload                          | March 2026               |
| Quality Assessment & Genome Annotation                      | May 2026                 |
| Public Announcement of HPP-International Data Release       | Summer 2026 (est. July)  |

---

## HPP-Assembly Initiative Virtual Meetings

We will support a series of working group meetings. Calls will rotate across time zones, will be recorded, and available for review. Please contact **[NAME/EMAIL]** to be added to calendar invites.

1. **T2T Consortium Meetings** (assembly methods & workflows)  
   Sept – Dec 2025  
   [LINK TO MEETING SCHEDULE]

2. **Focused Task Team: Sequence Data Production**  
   Sept – Dec 2025  
   [LINK TO MEETING SCHEDULE]

3. **Focused Task Team: HPP Assembly Production**  
   Jan – July 2026  
   [LINK TO MEETING SCHEDULE]

---

## 1000 Genomes Cell Lines

The 1000 Genomes Project (1000G) cell lines represent individuals from globally diverse populations with deeply characterized genomic data. Under the original 1000G consent, these samples are approved for broad use in genomic research.

- **Source:** Coriell Institute for Medical Research  
- **Catalog:** https://catalog.coriell.org/1KG  

To coordinate efforts, we’ll maintain a **prioritized, rank-ordered list** of 1000G cell lines (by HPRC PSR Working Group, using the “MaxDiv” algorithm). This list excludes close family members to avoid redundancy and will be updated regularly.

[LINK TO TABLE OF 1000G CELL LINES]

---

## Contributions Beyond 1000G

We also welcome teams interested in contributing T2T genomes from samples outside the 1000 Genomes Project. Please connect with:

- **Dr. Ann McCartney**  
- **Dr. Heather Lawson**  

They lead coordination in collaboration with the GA4GH Regulatory and Ethics Work Stream (REWS) on a **Pangenome Consent Toolkit**.

---

## Data Generation Expectations

To meet the July 2026 Release 3 goals:

- **Deadline for data generation:** January 1, 2026  
- **Upload raw data to:** HPRC/HPP Data Portal  
- **Centralized assembly production:** through March 2026  

HPRC production centers will generate assemblies locally as default; international submissions are welcome.

---

## Technology Platforms & Coverage

| Platform / Kit                       | Coverage            | Notes & Links                              |
|--------------------------------------|---------------------|--------------------------------------------|
| **PacBio HiFi (Revio)**              | ~60× (2 SMRT Cells) | HiFi reads ~20 kb; ideal for primary assembly & polishing<br>[Protocol/notes] |
| **Oxford Nanopore Ultra-Long (UL)**  | ~30× (100 kb+)      | R10 chemistry + latest basecalling<br>[Protocol/notes] |
| **Hi-C (Dovetail Omni-C preferred)** | ~30×                | For scaffolding; Arima or others acceptable<br>[Protocol/notes] |

**Optional data types:**

- **FiberSeq Protocol** (~50–60×)  
- **Kinnex RNA-seq** (10 M cells)  

---

## Option for HPRC-Partnership Data Generation

HPRC production centers (e.g., Rockefeller University led by Erich Jarvis) can assist teams lacking local sequencing capacity:

- **PacBio HiFi (Revio)**  
- **ONT Ultra-Long (R10)**  
- **Hi-C Scaffolding (Omni-C)**  

Contact **[Email]** to coordinate.

---

## Benchmark Assembly Data – HG002

From August–December 2025, we’ll refine T2T assembly methods via regular calls (co-hosted by Adam Phillippy & Karen Miga). Methods will be benchmarked on **HG002-Q100**:

- **Assembly repository:** https://github.com/marbl/HG002  
- **Datasets & reference assembly:** provided in repo  

**HG002-Q100 Platform Coverage**:

| Platform                    | Coverage   | Data Link                         |
|-----------------------------|------------|-----------------------------------|
| PacBio HiFi (Revio)         | ~60×       | [Link to data]                    |
| Oxford Nanopore UL (R10)    | ~30×       | [Link to data]                    |
| Hi-C (Omni-C)               | ~30×       | [Link to data]                    |

Submit new tools/pipelines by **Oct 1, 2025** for discussion; analysis & reporting accepted until **Nov 15, 2025**.

---

## Resources

- **Assembly Pipeline Documentation**  
- **Quality Control Standards**  
- **HPRC/HPP Data Submission Portal**  
- **Meeting Calendar**  

---

## Contact

- **Project Coordinators:** [Names & emails]  
- **Technical Support:** [Email]  
- **Data Submission:** [Email]  

---

## Contributing International Teams

We welcome contributions from all international partners. Please reach out to the coordination leads to get involved!
