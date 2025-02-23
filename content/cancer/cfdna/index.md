---
title: Liquid Biopsy, 2022-2024
summary: 
date: 2024-08-23
authors:
  - admin
tags:
  - cancer
  - cfdna
  - liquid biopsy
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

My main and most recent project has been cfDNA liquid biopsy, on which I worked for two years at BostonGene. In this project, I developed a tumor-informed pipeline to monitor point mutations and indels in blood plasma from patients with hematologic and solid malignancies.

Cell-free DNA (cfDNA) in peripheral blood plasma is a promising tool for monitoring minimal residual disease (MRD) in hematologic and solid malignancies. Unlike conventional biopsies, cfDNA extraction is non-invasive and allows for rapid, repeated sampling to monitor disease progression over time. However, current assays are limited in scale by their detection of only a narrow range of mutations, the need for patient- and mutation-specific customization, and constant expert review.

**Our Approach:**  
We developed a novel, comprehensive cfDNA testing platform that targets 216 clinically actionable genes—including both exonic and intronic regions—to detect point mutations (SNVs/indels), structural variants, and microsatellite instability (MSI). Using deep sequencing (with a median exon coverage of over 2000×) and an in-house, tumor-informed variant calling algorithm, we established a limit of detection (LOD) of 0.05% variant allele frequency (VAF). Validation was carried out on plasma samples from 74 patients with various solid cancers, as well as on standard reference dilutions (Seraseq® and Twist cfDNA Pan-cancer Reference Standards) using triplicate experiments. In a case study of a follicular lymphoma (FL) patient, our assay detected clinically relevant mutations 14 months earlier than traditional blood cell mutation calling.

**Key Results:**

- Achieved an LOD > 0.05% VAF with sequencing depth >2000x.
- Sensitivity reached 93–97% and specificity 98–99%.
- High correlation between replicates (Pearson's r > 0.99, p < 0.0001) confirmed assay robustness for longitudinal monitoring.
- The assay successfully distinguished true somatic mutations from clonal hematopoiesis of indeterminate potential mutations and detected early disease relapse in an FL patient through analysis of five plasma samples collected over multiple years.

### My contributions:
- Developed code for the automated processing of patient samples to create a report with found biomarkers.
- Integrated and optimized pipelines for both indel and SNP detection, boosting sensitivity in ctDNA and WES data analyses.
- Validated germline and somatic mutation metrics to meet CLIA/CAP standards.

## Conference Talks:
<div style="text-align: center;">
          <img src="/images/lb_poster.jpeg" alt="Teaching Photo" style="width:15cm; height:auto;" />
</div>

You can find conference talks on:
- [A Novel Comprehensive Tumor-Informed Plasma cfDNA Assay to Monitor Minimal Residual Disease for Hematological and Solid Malignancies (ASH 2023)](https://ash.confex.com/ash/2023/webprogram/Paper174909.html)