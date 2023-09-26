---
title: Generative Biology
keywords:
- Artificial Intelligence
- Generative AI
- Machine Learning
- Biology
lang: en-US
date-meta: '2023-09-26'
author-meta:
- Alexander J. Titus
- Your Name
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
  <meta name="dc.date" content="2023-09-26" />
  <meta name="citation_publication_date" content="2023-09-26" />
  <meta property="article:published_time" content="2023-09-26" />
  <meta name="dc.modified" content="2023-09-26T11:07:32+00:00" />
  <meta property="article:modified_time" content="2023-09-26T11:07:32+00:00" />
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
  <meta name="citation_author" content="Your Name" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://In-Vivo-Group.github.io/generative-biology/" />
  <meta property="og:url" content="https://In-Vivo-Group.github.io/generative-biology/" />
  <meta property="twitter:url" content="https://In-Vivo-Group.github.io/generative-biology/" />
  <meta name="citation_fulltext_html_url" content="https://In-Vivo-Group.github.io/generative-biology/" />
  <meta name="citation_pdf_url" content="https://In-Vivo-Group.github.io/generative-biology/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://In-Vivo-Group.github.io/generative-biology/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://In-Vivo-Group.github.io/generative-biology/v/0936377f86edb296a827a777a5bd6f689ac3fb65/" />
  <meta name="manubot_html_url_versioned" content="https://In-Vivo-Group.github.io/generative-biology/v/0936377f86edb296a827a777a5bd6f689ac3fb65/" />
  <meta name="manubot_pdf_url_versioned" content="https://In-Vivo-Group.github.io/generative-biology/v/0936377f86edb296a827a777a5bd6f689ac3fb65/manuscript.pdf" />
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
([permalink](https://In-Vivo-Group.github.io/generative-biology/v/0936377f86edb296a827a777a5bd6f689ac3fb65/))
was automatically generated
from [In-Vivo-Group/generative-biology@0936377](https://github.com/In-Vivo-Group/generative-biology/tree/0936377f86edb296a827a777a5bd6f689ac3fb65)
on September 26, 2023.
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

+ **Your Name**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [TBD](https://github.com/TBD)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
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

The goal with be a 2 page TL;DR of the review after v1 is complete.


# Introduction

This is the start of the Generative Biology living review!


# Science

This will be the bulk of the review, focusing on the technical progress across generative biology and emerging applications of deep learning in the life sciences (@doi:10.1371/journal.pcbi.1009803).


# Security

Generative biology poses opportunities and risks to national and biosecurity, and this section will highlight relevant advances across these domains. 


# Policy

Science doesn't happen in a vacuum, and the authors are active in science and technology policy as well as foundational research. This section will highlight relevant policy movement in generative biology.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

