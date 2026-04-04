---
layout: page
title: "Projects"
---
{% include social-links.html %}
{% include darkmode-toggle.html %}

# Cancer-associated Fibroblast (CAF) Heterogeneity
## 1. Emerging Inflammatory CAF (iCAF) upon neoadjuvant chemotherapy (NAC)
By integrating multiple public single-cell RNAseq datasets from muscle-invasive bladder cancer (MIBC) patients that received NAC, I was able to characterize the major subclusters of CAFs that emerge and could potentially contribute to NAC resistance. In brief, I identified 4 major classes: iCAF, myofibroblastic fibroblasts (myCAF), Hybrid i/myCAF and double-negative CAF (DNCAF) which can be easily sorted out using flow cytometry with two generic markers: &alpha;SMA and IL6.
![Fig1](/assets/dimplot.png){: style="width:300px; display:block; margin: 20px auto 0px auto;"}
<div style="text-align: center; ">Four major CAF clusters in MIBC after NAC</div>

![Fig2](/assets/dotplot_acta2_il6.png){: style="width:300px; display:block; margin: 20px auto 0px auto;"}
<div style="text-align: center; ">Four CAF clusters with distinct &alpha;SMA (ACTA2) and IL6 expression</div>
Other than conventionally known iCAF and myCAF, our team discovered a hybrid population of CAF with distinct markers. More importantly, using computational deconvolution algorithm EPIC on gene expression matrix of a NAC cohort (SWOG), we found that high proportion of these hybrid CAFs are significantly enriched post-NAC and are associated with worse survival in patients. 

![Fig3](/assets/dotplot_markers.png){: style="width:300px; display:block; margin: 20px auto 0px auto;"}
<div style="text-align: center; ">Hybrid CAF showing distinct markers from iCAF and myCAF</div>

![Fig4](/assets/hybrid_swog.png){: style="width:300px; display:block; margin: 20px auto 0px auto;"}
<div style="text-align: center; ">Significantly higher proportion of Hybrid CAF in post-NAC samples</div>

![Fig4](/assets/hybrid_swog_surv.png){: style="width:300px; display:block; margin: 20px auto 0px auto;"}
<div style="text-align: center; ">Significantly worse survival for MIBC patients with high Hybrid CAF proportion</div>

Read our published [paper](https://www.science.org/doi/10.1126/sciadv.adt8697) in **Science Advances** for more info!

## 2. Pre-Muscle-Invasive Cancer Associated Fibroblast Heterogeneity and Niche in Tumor Microenvironment
Approximately 25% of non-muscle invasive bladder cancer (NMIBC) patients progressed in aggressive muscle invasive form (MIBC). This ongoing project aims to characterize the role of CAF in shaping the tumor microenvironment and priming malignant urothelial cells for infiltration into the muscle layer with single-nuclues RNAseq and spatial transcriptomics (10X Genomics Xenium) technology.
![Fig1](/assets/uro_xenium.png){: style="width:600px; display:block; margin: 20px auto 0px auto;"}
<div style="text-align: center; ">Different composition of urothelial cell types in non-progressor (left) and progressor (right). White color indicates muscle layer.</div>

![Fig1](/assets/PNP_trajectories.png){: style="width:300px; display:block; margin: 20px auto 0px auto;"}
<div style="text-align: center; ">Distinct CAF trajectories between non-progressor (top) and progressor (bottom). </div>

![Fig1](/assets/spatial_cci.png){: style="width:600px; display:block; margin: 20px auto 0px auto;"}
<div style="text-align: center; ">Distinct spatial cell-cell interaction niches that could contribute to muscle invasion of urothelial cells.</div>

# Repurposing Drugs Targeting KMT2A-AFF1 Fusion Protein via In Silico Drug Screening
Deep-learning modeling of KMT2A-AFF1 fusion proteins and 3D structure validation using AlphaFold2 and Schrödinger Maestro.

# HMRIBladdeR (R Package)
An internal R package for evaluating bladder-cancer gene signatures and survival correlations. It provides a one-liner code that provides prognostic of a gene or gene signature of interest.
Bladder cancer datasets include TCGA-BLCA/TCGA-KIRC, SWOG (NAC cohort), IMvigor210 (ICI cohort) and Lars et al. cohort (early-staged NMIBC cohort).
[🔗 Email me to get a token for installation!](mailto:winstonhyh@live.com)
