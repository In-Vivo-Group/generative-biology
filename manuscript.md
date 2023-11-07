---
title: Generative Biology
keywords:
- Artificial Intelligence
- Generative AI
- Machine Learning
- Biology
lang: en-US
date-meta: '2023-11-07'
author-meta:
- Alexander J. Titus
- Matthew E. Walsh
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Generative Biology" />
  <meta name="citation_title" content="Generative Biology" />
  <meta property="og:title" content="Generative Biology" />
  <meta property="twitter:title" content="Generative Biology" />
  <meta name="dc.date" content="2023-11-07" />
  <meta name="citation_publication_date" content="2023-11-07" />
  <meta property="article:published_time" content="2023-11-07" />
  <meta name="dc.modified" content="2023-11-07T00:49:40+00:00" />
  <meta property="article:modified_time" content="2023-11-07T00:49:40+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Alexander J. Titus" />
  <meta name="citation_author_institution" content="In Vivo Group, Washington, DC, USA" />
  <meta name="citation_author_institution" content="International Computer Science Institute, Berkeley, CA, USA" />
  <meta name="citation_author_orcid" content="0000-0002-0145-9564" />
  <meta name="citation_author" content="Matthew E. Walsh" />
  <meta name="citation_author_institution" content="Center for Health Security, Johns Hopkins Bloomberg School of Public Health, Baltimore, MD, USA" />
  <meta name="citation_author_institution" content="Department of Environmental Health and Engineering, Johns Hopkins Bloomberg School of Public Health, Baltimore, MD, USA" />
  <meta name="citation_author_orcid" content="0000-0003-1514-7761" />
  <link rel="canonical" href="https://In-Vivo-Group.github.io/generative-biology/" />
  <meta property="og:url" content="https://In-Vivo-Group.github.io/generative-biology/" />
  <meta property="twitter:url" content="https://In-Vivo-Group.github.io/generative-biology/" />
  <meta name="citation_fulltext_html_url" content="https://In-Vivo-Group.github.io/generative-biology/" />
  <meta name="citation_pdf_url" content="https://In-Vivo-Group.github.io/generative-biology/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://In-Vivo-Group.github.io/generative-biology/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://In-Vivo-Group.github.io/generative-biology/v/8f12a68cc2b661911c9e6273616a1fc48f1c404f/" />
  <meta name="manubot_html_url_versioned" content="https://In-Vivo-Group.github.io/generative-biology/v/8f12a68cc2b661911c9e6273616a1fc48f1c404f/" />
  <meta name="manubot_pdf_url_versioned" content="https://In-Vivo-Group.github.io/generative-biology/v/8f12a68cc2b661911c9e6273616a1fc48f1c404f/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://In-Vivo-Group.github.io/generative-biology/v/8f12a68cc2b661911c9e6273616a1fc48f1c404f/))
was automatically generated
from [In-Vivo-Group/generative-biology@8f12a68](https://github.com/In-Vivo-Group/generative-biology/tree/8f12a68cc2b661911c9e6273616a1fc48f1c404f)
on November 7, 2023.
</em></small>



## Authors



+ **Alexander J. Titus**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-0145-9564](https://orcid.org/0000-0002-0145-9564)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [alexandertitus](https://github.com/alexandertitus)
    <br>
  <small>
     In Vivo Group, Washington, DC, USA; International Computer Science Institute, Berkeley, CA, USA
     · Funded by Grant TBD
  </small>

+ **Matthew E. Walsh**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-1514-7761](https://orcid.org/0000-0003-1514-7761)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [mwalsh52](https://github.com/mwalsh52)
    <br>
  <small>
     Center for Health Security, Johns Hopkins Bloomberg School of Public Health, Baltimore, MD, USA; Department of Environmental Health and Engineering, Johns Hopkins Bloomberg School of Public Health, Baltimore, MD, USA
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/In-Vivo-Group/generative-biology/issues)
or email to
Alexander J. Titus \<publications@theinvivogroup.com\>.


:::


## Abstract {.page_break_before}

The rapid pace of progress in generative artificial intelligence (AI) techniques like deep learning, reinforcement learning, and transformer neural networks is transforming the life sciences and biomedicine. This living review paper provides an updatable, comprehensive overview and analysis of the latest literature on generative biology – the application of cutting-edge generative AI methods to accelerate insights and innovation across the life sciences and healthcare. All authors are welcome to contribute to this review via pull requests. 

The review synthesizes key developments in using generative models for de novo biomedical discovery, design, and decision support. It examines techniques and applications including deep learning on omics data for personalized medicine, generative chemistry for drug development, protein structure prediction for molecular engineering, image synthesis for pathology, language models for clinical decision support, robotic simulation for prosthetics, and generative networks for cell programming. 

The review highlights representative studies and benchmarks in each area while contextualizing progress, limitations, emerging best practices, and directions for future work. It also discusses social and ethical challenges raised by generative biology applications, such as compounding bias, system opacity, and dual-use risks, alongside proposed solutions.

As a living review, this paper will be continually updated as the field rapidly advances to provide researchers and practitioners with an up-to-date reference on the state of the art in employing generative AI to accelerate biomedicine for the collective good.


# Executive Summary {.page_break_before}

The goal with be a 2 page TL;DR of the review after v1 is complete. Need more content.


# Introduction

This is the start of the Generative Biology living review!


# Recent Advances in Generative AI

## Introduction

Brief background on rise of generative models like GPT-3, DALL-E, AlphaFold, etc. Summary of scope and goals of chapter focused on key advances in last 1-2 years.

## Transformer-Based Language Models

### GPT-3 and Foundation Models

- Overview of GPT-3 architecture and self-supervised training on massive text corpus 
- Discussion of GPT-3 capabilities and limits, including few-shot learning
- Concept of foundation models as basis for many downstream applications

### Other Notable Models

- Summary of other major transformer language models like Google's PaLM, DeepMind's Gopher, Meta's OPT, Anthropic's Claude etc.
- Comparison of model sizes, architectures, training approaches
- Benchmarking of models on various NLP tasks

## Multimodal Generative Models

### DALL-E 2 and Text-to-Image Generation

- Explain DALL-E 2 architecture and training methodology
- Discuss capabilities in text-to-image generation 
- Issues around bias, appropriate use cases

### Other Multimodal Models

- Overview of models like Imagen, Parti, Flamingo for text-to-image
- Discussion of video generation models like Googles Imagen Video
- Models for text to 3D shapes, text to music etc.

## Outlook

- Key challenges and limitations of current generative models
- Likely future advances building on these models
- Broader societal impact of widely available generative models


# Advances in Generative AI for Proteins

## Introduction

- Background on proteins as key molecular machines in biology
- Promise of generative AI to accelerate protein discovery and engineering
- Overview of scope covering recent advances in last 1-2 years

## Structure Prediction

- AlphaFold2 as a breakthrough method for structure prediction
- Novel model architecture and training methodology 
- Examples of new biological insights from predicted structures

## Function Prediction

- Using predicted structures to infer protein functions
- Structure-based identification of catalytic and binding sites
- Case studies of novel enzyme functions discovered

## Designing Novel Proteins

- Generative models for designing functional protein sequences
- Leveraging structural constraints for optimized protein engineering
- Applications in industrial enzymes, therapeutics, biomaterials

## Interaction Prediction

- Modeling protein-protein interactions with graph networks
- Structure-based prediction of protein-drug bindings
- Applications in drug discovery and toxicity screening

## Outlook 

- Challenges and next steps in improving accuracy 
- Hybrid physics- and data-driven approaches
- Ethical considerations in synthetic protein design


# Advances in Generative AI for RNA 

## Introduction

- Background on key roles of RNA in biology 
- Promise of generative models to advance RNA research
- Scope focused on latest advances in RNA prediction and design

## Structure Prediction

- Transformer-based prediction of RNA folding
- Novel architectures for incorporating chemical constraints
- Improved accuracy on complex structures like ribosomes

## Function Prediction 

- Inferring RNA functions from sequence and structure
- Identifying motifs, domains, and atomic binding sites
- Applications in understanding long noncoding RNAs

## Interaction Prediction

- Graph neural networks for RNA-protein interactions
- Structure-augmented modeling of splice sites
- Predicting RNA base editing targets 

## Design of RNA Therapeutics

- Generative models for optimizing siRNA, antisense design
- Reinforcement learning for chemical modification patterns
- Progress in computational RNA-targeted drug design

## Outlook

- Key challenges in prediction of long RNA structures
- Design of RNA for self-assembly and scaffolding
- Ethical use of synthetic RNA technologies


# Advances in Generative AI for DNA

## Introduction

- Background on role of DNA as carrier of genetic information  
- Promise of generative models to advance DNA research
- Scope focused on latest advances in DNA prediction and design

## Sequence Modeling

- Transformer architectures for modeling DNA sequences
- Pretraining on large genomic datasets
- Applications in variant calling and annotation

## Regulation Prediction

- Graph neural networks for modeling 3D genome architecture
- Predicting enhancer-promoter interactions and expression
- Design of synthetic promoters and enhancers

## Genome Editing

- Generative models for CRISPR guide design
- Contextual prediction of on-target editing efficacy  
- Modeling of off-target effects during optimization

## DNA Data Generation

- Variational autoencoders for realistic DNA sequences
- Generating paired genomic-transcriptomic data
- Applications in training genome interpretation models

## Outlook  

- Challenges in predicting long-range chromatin interactions
- Responsible design of synthetic genomes
- Ethical considerations for human genome editing


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

