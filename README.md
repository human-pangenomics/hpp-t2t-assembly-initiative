
<div style="width: 100%; height: 200px; overflow: hidden;">
  <img src="images/pangenome_art_crop.png" alt="Figure 1: overview diagram" style="width: 100%; height: auto; min-height: 200px; object-fit: cover;" />
</div>

# Human Pangenome Project (HPP) T2T Assembly Initiative

## Welcome

We are excited to welcome you as part of this international effort to co-develop a globally representative, telomere-to-telomere (T2T) pangenome resource. This task team operates under the umbrella of the Human Pangenome Project (HPP), a GA4GH Driver Project committed to building equitable and inclusive reference systems that serve all populations. Our shared objective is to create ‘best-in-class’ assembly standards, methods, and reference materials, beginning with a project leveraging well-characterized 1000 Genomes (1000G) cell lines. These lines provide a unique opportunity to initiate collaboration across diverse partners under a common consent framework and to produce a foundational T2T resource that is open, reusable, and globally impactful.

**Why this matters now:** As we look ahead to a coordinated community release of the next global human pangenome reference in mid-year 2026, this task team plays a critical role in aligning international efforts. This international initiative builds upon the momentum of the NIH-funded Human Pangenome Reference Consortium (HPRC), which has led the release of high-quality phased assemblies from over 200 individuals and continues to generate a growing set of open T2T assemblies. The target release (“Release 3”, to acknowledge the building from prior HPRC Releases) will include at least 350 assemblies from the Human Pangenome Reference Consortium (HPRC), 65 assemblies from the Human Genome Structural Variation Consortium (HGSVC), and contributions from international collaborators.

This GitHub site serves as our central hub for project updates, timelines, and shared documentation. We invite you to join us by completing the interest form and contributing to the collaborative planning now underway.

---

<div style="border:1px solid #cccccc; padding:16px; border-radius:6px;">

## IMPORTANT TENTATIVE DATES

*Updated as we move forward as a team*

**Official Launch of the Task Team:** September 2025

**Next versioned release of assembly method:** Early Quarter 2026  

If you are developing or using an alternative assembly method that you believe could enhance the current standard workflow, we encourage you to participate in the T2T Consortium Assembly Working Group calls. Contributors are welcome to present benchmarking results (particularly against HG002) and propose improvements for group discussion. Promising approaches may be considered for integration into the standard assembly workflow. Please note that consideration of very different data production recipes (e.g., an all ONT workflow) can be discussed, but is not being considered for mid-year 2026 assembly release goals.

**Sequence Production Data Submission Deadline:** Alignment with goals to have assemblies uploaded by mid-year 2026  

Please reference the 1000G table of cell lines to avoid duplicating production efforts.

**T2T Assembly Completion and Upload:** Alignment with goals to have assemblies uploaded by mid-year 2026

**Quality assessment and genome annotation:** Alignment with goals to have assemblies uploaded by mid-year 2026

**Public Announcement of HPP-International-Data Release:** mid-year 2026

</div>

---

## HPP-Assembly Initiative Virtual Meetings

We will support a series of working group meetings for this initiative, as listed below. Calls for the task team will rotate to accommodate different time zones of participating members. All calls will be recorded and available for review.

### Onboarding

We are hosting two identical introductory calls to coordinate our efforts. To contribute to this initiative, it is expected that you attend one of these sessions (or arrange an individual meeting). Please join at the time that best fits your schedule:

**29-Sept-2025 – Onboarding – HPP 1000G T2T-Assembly Task Team Recordings:**  
https://wustl.box.com/s/ihcj4bizlg688e3vxe8yp38xj4oxcnhm

**2-Oct-2025 – Onboarding – HPP 1000G T2T-Assembly Task Team Recordings:**  
https://wustl.box.com/s/74yz0tuzvouw42kkno8unv91jboowx6l

### T2T–HPP Task Team Meetings

T2T–HPP Task Team meetings scheduled before the end of the year. To accommodate international time zones, we will offer two sessions covering the same material; you are welcome to attend whichever is most convenient:

**HPP-T2T Assembly Task Team:** Monday, Dec 8 at 7:00 PM EST | 12:00 AM UTC  
https://wustl.box.com/s/n5fxe3v89wahu5lavprdw3iplth5q6os

**HPP-T2T Assembly Task Team:** Thursday, Dec 11 at 10:00 AM EST | 3:00 PM UTC  
https://wustl.box.com/s/xmhxu4ffd0955bq2jgu4lhko1arqcdew

### Coriell Office Hours

These are informal, small-group opportunities to ask questions about cell lines, ordering and shipment logistics, and specific project plans. Please feel free to sign up for a time slot if you would also like a more detailed or tailored discussion:  
https://docs.google.com/forms/d/e/1FAIpQLSeZsAEQwnIgoHVb4NaefeYMLdhpHNLY8vPH3FwfdOZT_FyqOg/viewform

---

## T2T Working Group Calls

**Wednesday, Nov 19 11:00 AM EST | 4:00 PM UTC**  
Haoyu Cheng: “Hybrid assembly for population-scale high-quality/T2T genomes.”  
Recording: https://wustl.app.box.com/s/77rle8nkst0pgr5z1uq0l5bqt09llvt4/file/2051268174809

**Wednesday, Dec 3 11:00 AM EST | 4:00 PM UTC**  
Sergey Koren: “Update on HPRCv3 assembly recipe”  
Recording: http://wustl.app.box.com/s/wh8pjlmdrweetboj44pq5arzjc2auz7t/file/2064283122751

**Wednesday, Dec 17 11:00 AM EST | 4:00 PM UTC**  
DeKnot—Local haplotype-resolved assembly with k-syncmer-based multiplex De Bruijn graphs (Megan Le, Heng Li lab)

Planning for alternative protocols to test in January (e.g. ONT-only)

Zoom: https://wustl-hipaa.zoom.us/j/99084604526

---

## 1000 Genomes Cell Lines

The 1000 Genomes Project (1000G) cell lines are a foundational resource for advancing the goals of the Human Pangenome Project (HPP), as they represent individuals from globally diverse populations and are linked to deeply characterized genomic data, including high-coverage short-read sequencing, structural variant catalogs, and ancestry annotations. These lines provide a consistent, renewable, and consented framework that supports open data sharing and global collaboration. Under the terms of the original 1000G consent, these samples are approved for broad use in genomic research, including the development of reference resources. This makes them ideal for enabling reproducible and scalable long-read sequencing efforts across international partners.

The 1000G lymphoblastoid cell lines are publicly available through the Coriell Institute for Medical Research and can be ordered here:  
https://catalog.coriell.org/1KG

To support coordination across international partners, we will provide a prioritized list of 1000G cell lines for T2T assembly (2389 unrelated individuals that were used in the MaxVar evaluation) by the Human Pangenome Reference Consortium (HPRC) Population Sampling and Representation (PSR) Working Group. HPRC Ranking or prioritized lines were based on the 'MaxDiv' algorithm, a greedy optimization approach that maximizes representation of common alleles (allele frequency >1%) as defined in the 1000G variant call sets. The list also includes annotation of lines that have prior data production through the HPRC or HGSVC, and excludes close family members in trios to avoid redundancy. This prioritization enables equitable sampling and efficient integration of new assemblies into the evolving global pangenome reference.

This table will be updated/versioned regularly as teams share information about production efforts. Please contact Karen Miga or Ann McCartney to confirm your interest in data generation as soon as possible (with expectations of confirmation before Nov 15, 2025)

**LINK TO TABLE OF 1000G CELL LINES**

---

## Data Generation Expectations

To meet the goals of the July 2026 Release 3, we ask that all teams contributing sequencing data to be uploaded to the HPRC/HPP Data Portal to allow centralized coordination and support for bulk assembly production. While we welcome T2T assembly submissions from international teams, HPRC production centers will also generate assemblies locally as a default to ensure consistency and timely integration.

---

## Technology

| Technology | Platform / Kit | Coverage | Read Length / Notes |
|-----------|----------------|----------|---------------------|
| PacBio HiFi | Revio (2 SMRT Cells) | ~60× | HiFi reads with ~20 kb insert sizes; high accuracy long reads ideal for primary assembly and polishing |
| Oxford Nanopore Ultra-Long (UL) | R1041, >sup@v5.0.0, 5mCG_5hmCG | ~30× (100 kb+) | Ultra-long read lengths are defined as >100 kb |
| Hi-C | Dovetail Omni-C (optional) | ~30× | For scaffolding; Arima, PoreC or other kits acceptable |

Optional data types:  
- Fiber-seq Protocol (~50–60× coverage)  
- Kinnex long-read RNA-seq for gene annotation (10M cells)

---

## Benchmark Assembly Data – HG002

This task team will work together to refine and advance T2T assembly methods and workflows in preparation for the upcoming release planned for Summer 2026.

HG002-Q100 Assembly: https://github.com/marbl/HG002  

HG002 "Q100" benchmarking genome:  
https://www.biorxiv.org/content/10.1101/2025.09.21.677443v1


