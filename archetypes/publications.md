---
title: "{{ replace .Name \"-\" \" \" | title }}"
date: {{ .Date }}
draft: true

# --- Academic Metadata ---
authors: "Daniel J. Gomez, et al."
journal: ""
doi: ""
external_link: ""

# --- Stanford/Snyder Lab Context ---
lab: "Snyder Lab"
institution: "Stanford Genetics"
consortia: [] # e.g., ["HuBMAP", "HTAN", "MoTrPAC"]

# --- Computational Stack (Stanford Focus) ---
spatial_modules: [] # e.g., ["MaxFuse", "Squidpy", "LIANA+", "SPACEc"]
spatial_tech: []    # e.g., ["Xenium", "Visium", "CODEX"]
analysis_modality: "Spatial Multi-omics"

# --- [CRITICAL] Safety Net ---
tags: ["SPACEc", "Stanford Genetics", "Spatial Biology"]
summary: ""
---

## Computational Workflow
This project utilized SPACEc, LIANA+, and NiCo for:
- [ ] Spatial clustering
- [ ] Cell-type deconvolution
- [ ] Ligand-receptor interaction mapping
