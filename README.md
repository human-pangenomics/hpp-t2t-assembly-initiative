
<img src="images/pangenome_art.png" alt="Figure 1: overview diagram" width="100%" style="max-height: 100px; object-fit: cover;" />


# Human Pangenome Project (HPP) T2T Assembly Initiative

## Welcome

We are excited to welcome you as part of this international effort to co-develop a globally representative, telomere-to-telomere (T2T) pangenome resource. This task team operates under the umbrella of the Human Pangenome Project (HPP), a GA4GH Driver Project committed to building equitable and inclusive reference systems that serve all populations. Our shared objective is to create 'best-in-class' assembly standards, methods, and reference materials, beginning with a project leveraging well-characterized 1000 Genomes (1000G) cell lines. These lines provide a unique opportunity to initiate collaboration across diverse partners under a common consent framework and to produce a foundational T2T resource that is open, reusable, and globally impactful.

**Why this matters now:** As we look ahead to a coordinated community release of the next global human pangenome reference in Summer 2026, this task team plays a critical role in aligning international efforts. This international initiative builds upon the momentum of the NIH-funded Human Pangenome Reference Consortium (HPRC), which has led the release of high-quality phased assemblies from over 200 individuals and continues to generate a growing set of open T2T assemblies. The target release ("Release 3", to acknowledge the building from prior HPRC Releases) will include at least 350 assemblies from the Human Pangenome Reference Consortium (HPRC), 65 assemblies from the Human Genome Structural Variation Consortium (HGSVC), and contributions from international collaborators.

This GitHub site serves as our central hub for project updates, timelines, and shared documentation. We invite you to join us by completing the interest form and contributing to the collaborative planning now underway.

📋 [Link to Collaboration Guidelines]

## Project Timeline

![Figure 1: overview diagram](images/timeline.png)

### Overview

| Milestone | Date |
|-----------|------|
| **Official Launch of the Task Team** | August 2025 |
| **Next versioned release of assembly method** | Dec 2025 |
| **Sequence Production Data Submission Deadline** | Jan 2026 |
| **T2T Assembly Completion and Upload** | March 2026 |
| **Quality assessment and genome annotation** | May 2026 |
| **Public Announcement of HPP-International-Data Release** | Summer 2026 (Estimated Timeline July) |

### Important Notes

If you are developing or using an alternative assembly method that you believe could enhance the current standard workflow, we encourage you to participate in the [Working Group Name] calls. Contributors are welcome to present benchmarking results (particularly against HG002) and propose improvements for group discussion. Promising approaches, as determined by the working group, may be considered for integration into the standard assembly workflow. Please note that consideration of very different data production recipes (e.g., an all ONT workflow) can be discussed but is not being considered for Summer 2026 assembly release goals.

Please reference the 1000G table of cell lines to avoid duplicating production efforts. All sequencing projects for this task team must be logged by **Oct 1, 2025** with production plans.

## HPP-Assembly Initiative Virtual Meetings

We will support a series of working group meetings for this initiative, as listed below. Calls for task team will rotate to accommodate different time zones of participating members. All calls will be recorded and available for review. Please contact [###] to be added to the calendar invites:

- **T2T Consortium Meetings** to discuss assembly methods and workflow (Sept-Dec)
  - [LINK TO MEETING SCHEDULE]
- **Focused HPP Task Team Meetings** (HPP Sequencing and assembly production)
  - [LINK TO MEETING SCHEDULE]

## 1000 Genomes Cell Lines

The 1000 Genomes Project (1000G) cell lines are a foundational resource for advancing the goals of the Human Pangenome Project (HPP), as they represent individuals from globally diverse populations and are linked to deeply characterized genomic data, including high-coverage short-read sequencing, structural variant catalogs, and ancestry annotations. These lines provide a consistent, renewable, and consented framework that supports open data sharing and global collaboration. Under the terms of the original 1000G consent, these samples are approved for broad use in genomic research, including the development of reference resources. This makes them ideal for enabling reproducible and scalable long-read sequencing efforts across international partners. 

The 1000G lymphoblastoid cell lines are publicly available through the Coriell Institute for Medical Research and can be ordered here: https://catalog.coriell.org/1KG.

To support coordination across international partners, we will provide a prioritized list of 1000G cell lines for T2T assembly (2389 unrelated individuals that were used in the MaxVar evaluation) by the Human Pangenome Reference Consortium (HPRC) Population Sampling and Representation (PSR) Working Group. HPRC Ranking or prioritized lines were based on the 'MaxDiv' algorithm, a greedy optimization approach that maximizes representation of common alleles (allele frequency >1%) as defined in the 1000G variant call sets. The list also includes annotation of lines that have prior data production through the HPRC or HGSVC, and excludes close family members in trios to avoid redundancy. This prioritization enables equitable sampling and efficient integration of new assemblies into the evolving global pangenome reference. This table will be updated/versioned regularly as teams share information about production efforts. Please contact Karen Miga or Ann McCartney to confirm your interests in data generation as soon as possible (and by the latest: **Oct 1, 2025**).

🔗 [LINK TO TABLE OF 1000G CELL LINES]

We also welcome teams interested in contributing T2T genomes from samples outside of the 1000 Genomes Project. If you are considering such contributions, we encourage you to connect with Dr. Ann McCartney and Dr. Heather Lawson, who are leading coordination efforts in this space. In collaboration with the HPP and the GA4GH Regulatory and Ethics Work Stream (REWS), they are helping to develop a Pangenome Consent Toolkit, a community-driven resource aimed at defining core consent language to support open data sharing and open access for this initiative. The HPRC Consent used for prospective recruitment can be referenced here. This work will help ensure ethical alignment and transparency as we build a globally representative pangenome resource.

## Data Generation Expectations

To meet the goals of the July 2026 Release 3, we ask that all teams contributing sequencing data to this initiative complete data generation by **January 1, 2026**. Raw data should be uploaded to the HPRC/HPP Data Portal to allow centralized coordination and support for bulk assembly production through March 2026. While we welcome T2T assembly submissions from international teams, HPRC production centers will also generate assemblies locally as a default to ensure consistency and timely integration.

### Required Data Types

| Technology | Platform/Kit | Coverage | Read Length/Notes |
|------------|--------------|----------|-------------------|
| **PacBio HiFi** | Revio<br/>2 SMRT Cells<br/>+kinetics and methylation | ~60× | HiFi reads with ~20 kb insert sizes; high accuracy long reads ideal for primary assembly and polishing<br/>[Link to protocol or notes] |
| **Oxford Nanopore Ultra-Long (UL)** | R1041<br/>>sup@v5.0.0<br/>5mCG_5hmCG | ~30x (100kb+) | Ultra-long Read lengths are defined as >100 kb; recommended FC, chemistry, and base-calling to support error correction<br/>[Link to protocol or notes] |
| **Hi-C** | Dovetail Omni-C (preferred) | ~30× | For scaffolding; Arima, PoreC or other kits/protocols also acceptable based on partner preference<br/>[Link to protocol or notes] |

### Optional Data Types

- **Fiber-seq Protocol** (upstream treatment of cells prior to long-read sequencing, ~50-60x Coverage)
  - [Link to protocol or notes]
- **Kinnex long-read RNA-seq** for gene annotation (Standard HPRC/HGSVC Protocol: 10M Cells)
  - [Link to protocol or notes]

### Option for HPRC-partnership to support data generation

To support this collaborative effort, the HPRC production centers can assist with generating high-quality sequencing data for selected samples. This includes PacBio HiFi (Revio), Oxford Nanopore ultra-long reads (R10 chemistry), and Hi-C scaffolding data using Dovetail Omni-C or compatible kits. Teams interested in contributing T2T assemblies but lacking local sequencing capacity are encouraged to reach out, data generation can be coordinated through the HPRC production network, with Rockefeller University (HPRC Production Center and Vertebrate Genomes Lab) serving as a central hub. This shared infrastructure ensures that all participants have access to the standardized, high-coverage datasets necessary for robust and reproducible T2T genome assembly.

## Benchmark Assembly Data – HG002

This task team will work together to refine and advance T2T assembly methods and workflows in preparation for the upcoming release planned for Summer 2026. From August through December, we invite all members to participate in our regular T2T development calls, co-hosted by Adam Phillippy and Karen Miga, which will focus on method optimization, coordination, and establishment of a community-wide production plan. If you are developing new tools, pipelines, or strategies for T2T assembly, we encourage you to contribute and join the discussion. As a shared benchmark, we recommend evaluating methods using the T2T-HG002 "Q100" benchmark genome and associated GQC software (data linked below).

We are planning to finalize our assembly production plans by **Dec 2025**, and we welcome analysis and reporting of tools/methods submission from any team until **Nov 15, 2025**. Please let Adam Phillippy and Karen Miga know if you would like to propose improvements or modifications to the assembly workflow by **Oct 1, 2025** to ensure we can prioritize time on our group call for open discussion.

**HG002-Q100 Assembly:** https://github.com/marbl/HG002

### HG002 Benchmark Data

| Technology | Platform/Kit | Coverage | Data Links |
|------------|--------------|----------|------------|
| **PacBio HiFi** | Revio<br/>2 SMRT Cells<br/>+kinetics and methylation | ~60× | [Link to data] |
| **Oxford Nanopore Ultra-Long (UL)** | R1041<br/>>sup@v5.0.0<br/>5mCG_5hmCG | ~30x (100kb+) | [Link to data] |
| **Hi-C** | Dovetail Omni-C | ~30× | [Link to data] |

## Resources

- 📚 Assembly Pipeline Documentation
- ✅ Quality Control Standards
- 📤 HPRC/HPP Data Submission Portal
- 📅 Meeting Calendar
- 📧 Contact Information
- 📋 Data Use Best Practices
- 🌍 Population Descriptor Best Practices

## Contact

- **Project Coordinators:** [Names and emails]
- **Technical Support:** [Email]
- **Data Submission:** [Email]

## Contributing International Teams

[Enter here]

---

**GitHub Repository:** https://github.com/human-pangenomics/hpp-t2t-assembly-initiative

*This proposal is hosted as a README on a GitHub repo to allow easy sharing and referencing. The final version will mirror this document.*
