---
title: Generative Biology
keywords:
- Artificial Intelligence
- Generative AI
- Machine Learning
- Biology
lang: en-US
date-meta: '2024-06-14'
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
  <meta name="dc.date" content="2024-06-14" />
  <meta name="citation_publication_date" content="2024-06-14" />
  <meta property="article:published_time" content="2024-06-14" />
  <meta name="dc.modified" content="2024-06-14T23:39:12+00:00" />
  <meta property="article:modified_time" content="2024-06-14T23:39:12+00:00" />
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
  <link rel="alternate" type="text/html" href="https://In-Vivo-Group.github.io/generative-biology/v/ed59f48b4d1c906078678ba96f24f79bd41bae99/" />
  <meta name="manubot_html_url_versioned" content="https://In-Vivo-Group.github.io/generative-biology/v/ed59f48b4d1c906078678ba96f24f79bd41bae99/" />
  <meta name="manubot_pdf_url_versioned" content="https://In-Vivo-Group.github.io/generative-biology/v/ed59f48b4d1c906078678ba96f24f79bd41bae99/manuscript.pdf" />
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
([permalink](https://In-Vivo-Group.github.io/generative-biology/v/ed59f48b4d1c906078678ba96f24f79bd41bae99/))
was automatically generated
from [In-Vivo-Group/generative-biology@ed59f48](https://github.com/In-Vivo-Group/generative-biology/tree/ed59f48b4d1c906078678ba96f24f79bd41bae99)
on June 14, 2024.
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


# Computers, Algorithms and the Internet

## 1950s and 1960s: Early computers and algorithms

Computers were used in the early 1950s for population genetics calculations [@url:https://pubmed.ncbi.nlm.nih.gov/4859964]. Notably, the inception of computational modeling in biology dates to the origins of computer science itself. British mathematician and logician Alan Turing, often referred to as “the father of computing”, used primitive computers to implement a model of biological morphogenesis (the emergence of pattern and shape in living organisms) in 1952 [@url:https://royalsocietypublishing.org/doi/10.1098/rstb.1952.0012]. At about the same time, a computer called MANIAC was used for measuring speculative genetic codes; it  was originally built for weaponry research at the Los Alamos National Laboratory in New Mexico [@url:https://link.springer.com/article/10.1007/BF02628301].

Computers were used for the study of protein structure by the 1960s, and other increasingly diverse analyses. These developments marked the rise of the computational biology field, stemming from research focused on protein crystallography, in which scientists found computers indispensable for carrying out laborious Fourier analyses to determine the three-dimensional structure of proteins [@url:https://pubmed.ncbi.nlm.nih.gov/13517261; @url:https://pubmed.ncbi.nlm.nih.gov/18990802].

In addition to advances in determination of protein structures through crystallography, the first sequence of protein, insulin, was published [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1198157; @url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1198158]. More efficient protein sequencing methods, such as the Edman degradation technique [@url:https://pubmed.ncbi.nlm.nih.gov/18134557], enabled sequencing 15 different proteins over a decade [@url:https://pubmed.ncbi.nlm.nih.gov/11252753]. COMPROTEIN, one of the first bioinformatics softwares developed in the early 1960s, was designed to overcome the limitations of Edman sequencing [@url:https://www.semanticscholar.org/paper/Comprotein%3A-a-computer-program-to-aid-primary-Dayhoff-Ledley/5c73ddc7e6e3e142736210c8a2e71cc6e647bc41]. In an effort to simplify the handling of protein sequence data for the COMPROTEIN software, a one-letter amino acid code was developed [@url:https://febs.onlinelibrary.wiley.com/toc/14321033/5/2]. This one-letter code was first used in the Atlas of Protein Sequence and Structure [@url:https://pubmed.ncbi.nlm.nih.gov/20665074], the first biological sequence database, laying the groundwork for paleogenetic studies.

Development of methods to compare protein sequences followed. The Needleman-Wunsch algorithm [@url:https://pubmed.ncbi.nlm.nih.gov/5420325], the first dynamic programming algorithm developed for pairwise protein sequence alignments, was introduced in the 1970s. Multiple sequence alignment (MSA) algorithms followed in the early 1980s. Progressive sequence alignment was introduced by Feng and Doolittle in 1987 [@url:https://pubmed.ncbi.nlm.nih.gov/3118049]. The MSA software CLUSTAL, a simplification of the Feng-Doolittle algorithm [@url:https://pubmed.ncbi.nlm.nih.gov/3243435] was developed in 1988. It is still used and maintained to this day [@url:https://pubmed.ncbi.nlm.nih.gov/24170397].

## 1970s: From protein to DNA analysis

The deciphering of all 64 triplet codons of the genetic code in 196817 fueled a desire to efficiently determine the sequence of DNA that existed into the 1970s. This desire led to the development of  cost-efficient DNA sequencing methods, such as the Maxam-Gilbert and Sanger sequencing techniques in the mid-1970s [@url:https://pubmed.ncbi.nlm.nih.gov/265521; @url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1198157; @url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1198158]. With this new ability to generate DNA sequence data, a paradigm shift from protein analysis to DNA analysis occurred in the late 1970s. Concurrently, concerns over recombinant DNA research led to safety protocols established during the 1975 Asilomar conference [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC432675].

New DNA sequencing techniques resulted in significantly more data to be analyzed, a task at which computation could help. The first software dedicated to analyzing Sanger sequencing reads was published in 1979 [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC327874]. DNA sequences began to be utilized in phylogenetic inference with pioneering methods like maximum likelihood for inferring phylogenetic trees from DNA sequences [@url:https://pubmed.ncbi.nlm.nih.gov/7288891]. Several bioinformatics tools and statistical methods were developed following this work. The adoption of Bayesian statistics in molecular phylogeny in the 1990s was inspired by this [@url:https://pubmed.ncbi.nlm.nih.gov/8703097] and is still commonly used in biology today [@url:https://pubmed.ncbi.nlm.nih.gov/28983516]. Yet, numerous computational limitations needed to be overcome during the latter half of the 1970s to expand the utilization of computing in the life sciences, especially in DNA analysis. The subsequent decade proved instrumental in addressing these challenges.

![**Figure 1**: The history of parallel advancements in computing and the life sciences: A timeline of major milestones.](https://github.com/samadon1/generative-biology/assets/56901167/4d765e41-8a46-4eb8-9b45-c206e0ab22e3)

## 1980s: Simultaneous advances in computing and biology

Parallel advancements in biology and computing propelled bioinformatics forward during the 1980s and 1990s. Molecular techniques like gene targeting and amplification, using enzymes like restriction endonucleases and DNA ligases, laid the groundwork for genetic engineering [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC432675]. The polymerase chain reaction (PCR) transformed gene amplification, while innovations like Taq polymerase and thermal cyclers optimized the process [@url:https://www.nobelprize.org/prizes/chemistry/1993/mullis/lecture].

Computing accessibility surged with microcomputers like the Commodore PET, Apple II, and Tandy TRS-80, along with bioinformatics software like the GCG software suite [@url:https://pubmed.ncbi.nlm.nih.gov/6546423] and DNASTAR [@url:https://link.springer.com/protocol/10.1385/1-59259-192-2:71], another sequence manipulation suite capable of assembling and analyzing Sanger sequencing data. Other sequence manipulation suites were developed to run on CP/M, Apple II, and Macintosh computers [@url:https://pubmed.ncbi.nlm.nih.gov/6320099] in the years 1984 and 1985. Free code copies of this software were offered on demand by some developers. This propelled an upcoming software-sharing movement in the programming world [@url:https://www.gnu.org/gnu/manifesto.en.html; @url:https://www.researchgate.net/publication/221307757_The_Free_Software_Movement_and_the_GNULinux_Operating_System].

The free software movement, led by the GNU project, promoted open-source bioinformatics tools. Major sequence databases (EMBL, GenBank, DDBJ) standardized data formatting and enabled global sharing. Bioinformatics journals, like CABIOS, which is now known as Bioinformatics (Oxford, England) accentuated computational methods' importance. Desktop workstations with Unix-like systems and scripting languages aided bioinformatics analyses, and scripting languages simplified tool development.

## 1990s: The genomics era and web-based bioinformatics

The genomics era began in the mid-1990s with the complete sequencing of the Haemophilus influenzae genome [@url:https://pubmed.ncbi.nlm.nih.gov/7542800], initiating genome-scale analyses. This milestone was followed by the publication of the human genome at the beginning of the 21st century, which served as the definitive catalyst for the genomic era [@url:https://pubmed.ncbi.nlm.nih.gov/11181995]. This transformative event  spurred the design and development of several specialized Perl-based software to assemble whole-genome sequencing reads: PHRAP [@url:https://pubmed.ncbi.nlm.nih.gov/9521923], Celera Assembler [@url:https://pubmed.ncbi.nlm.nih.gov/10731133] among others. 

Tim Berners-Lee's pioneering work at CERN in the early 1990s resulted in the World Wide Web, transforming global communication and ushering in an era of unprecedented access to information. With the advent of the internet, researchers gained a powerful platform to share and access vast amounts of biological data efficiently. This facilitated collaborative efforts in biology and genomics, leading to the establishment of foundational databases such as the EMBL Nucleotide Sequence Data Library [@url:https://pubmed.ncbi.nlm.nih.gov/8332519] and the GenBank database became the responsibility of the NCBI [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3531190] in 1992. Also, the famous NCBI website came online in 1994, featuring the efficient pairwise alignment tool BLAST [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC441573]. After that, the world saw the birth of major databases we still rely on today: Genomes (1995), PubMed (1997), and Human Genome (1999) [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC29859; @url:https://pubmed.ncbi.nlm.nih.gov; @url:https://academic.oup.com/nar/article/26/1/94/2379498].

The proliferation of web-based resources transformed access to bioinformatics tools, democratizing their availability and usability for researchers worldwide. Through the development of web platforms, bioinformatics tools became more user-friendly and accessible. This shift enabled researchers to interact with sophisticated analytical tools without needing extensive computational expertise or access to specialized hardware. Consequently, the widespread adoption of web-based bioinformatics resources facilitated broader participation in genomic and molecular research, accelerating scientific discovery and collaboration on a global scale. Graphical web servers emerged as a convenient alternative to traditional UNIX-based systems, simplifying data analysis without the need for complex installations. The continued relevance of servers for scientific purposes is exemplified by the AlphaFold Server which uses the latest AlphaFold 3 model [@url:Abramson, J. et al. Accurate structure prediction of biomolecular interactions with AlphaFold 3. Nature 1–3 (2024) doi:10.1038/s41586-024-07487-w], released in 2024, to provide highly accurate biomolecular structure predictions in a unified platform. 

The internet facilitated the dissemination of scientific research through online publications, challenging traditional print-based methods. Early initiatives like BLEND [@url:https://www.tandfonline.com/doi/abs/10.1080/00140138208924954] paved the way for internet-based scientific publishing by shedding insights into the potentials and obstacles associated with using the internet for scientific publications. This study paved the way for leveraging the Internet for both data set storage and dissemination, leading up to the establishment of preprint servers like arXiv (est. 1991) [@url:https://arxiv.org] and bioRxiv (est. 2013) [@url:https://www.biorxiv.org] which changed the way scientific findings are shared and accessed. These platforms democratized access to scientific knowledge by enabling researchers to share their work rapidly and openly, facilitating interdisciplinary collaborations and the cross-pollination of ideas.

The experimental determination of the first three-dimensional structure of a protein, specifically, myoglobin, occurred in 1958 via X-ray diffraction [@url:https://pubmed.ncbi.nlm.nih.gov/13517261]. However,  earlier groundwork by Pauling and Corey with the publication of two articles in 1951 that reported the prediction of α-helices and β-sheets [@url:https://pubmed.ncbi.nlm.nih.gov/16578412] laid the foundation for predicting protein structures. Similar to advances in other biological sciences, the utilization of computers has made it feasible to conduct calculations aimed at predicting the secondary and tertiary structure of proteins, with varying levels of confidence. This capability has been notably enhanced by the development of fold recognition algorithms, also known as threading algorithms [@url:https://pubmed.ncbi.nlm.nih.gov/28040746; @url:https://archive.org/details/computationalmet0000unse_u4q5]. However, proteins are dynamic entities, requiring advanced biophysical models to describe their interactions and movements accurately. Force fields have been formulated to describe the interactions among atoms, enabling the introduction of tools for modeling the molecular dynamics of proteins during the 1990s [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4655909]. Used to study the behavior and interactions of atoms and molecules over time, molecular dynamics simulations calculate the positions and velocities of atoms based on physical principles. Despite the theoretical advancements and availability of tools, executing molecular dynamics simulations remained challenging in practice due to the substantial computational resources they demanded.

Graphical processing Units (GPUs) have made molecular dynamics more accessible [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3673555], with applications extending to other bioinformatics fields requiring intensive computation. However, the internet's role in data dissemination, coupled with increasing computational power, has led to the proliferation of 'Big Data' in bioinformatics.

## 2000-2010: High-throughput sequencing and big data

Second-generation sequencing technologies democratized high-throughput bioinformatics. For example '454' pyrosequencing, a high-throughput DNA sequencing technique played a significant role in advancing genomics research by enabling rapid and cost-effective sequencing of DNA samples, particularly for applications such as whole-genome sequencing [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7122948], but computational challenges arose with increased data volumes. Decreasing sequencing costs resulted in more data being generated, emphasizing data organization and accessibility. Specialized repositories and standardization efforts were needed to ensure data interoperability. High-performance computing adaptation became vital to address the increased amounts of data within bioinformatics projects. The surge in bioinformatics projects, accompanied by a vast influx of data, prompted adjustments from funding bodies to accommodate the demand for high-performance computing resources and collaborative initiatives. 

While basic computer setups suffice for some projects, others demand complex infrastructures and substantial expertise. Government-sponsored entities like [Compute Canada](https://computecanada.ca/), [New York State’s High-Performance Computing Program](https://esd.ny.gov/doing-business-ny/new-york-state-high-performance-computing-program), [The European Technology Platform for High-Performance Computing](https://www.etp4hpc.eu/), and [National Center for High-Performance Computing](https://www.nchc.org.tw/?langid=2) served researchers' computational needs. Companies like Amazon, Microsoft, and Google, among many others, offer bioinformatics and life sciences services, emphasizing the field's importance.

### **Table 1.** Organizations providing High-Performance Computing Resources for Bioinformatics and Life Sciences
| Organization | Computing Resources |
|--------------|---------------------|
| **Compute Canada** | Provides high-performance computing resources and support services to researchers and innovators across Canada. They offer supercomputers, cloud platforms, data storage, and training programs to advance scientific research and innovation in various fields. |
| **New York State’s High-Performance Computing Program** | Provides researchers, businesses, and educational institutions with access to high-performance computing (HPC) resources and expertise to support their computational research and development efforts. |
| **The European Technology Platform for High-Performance Computing** | Fosters collaboration among industry, research, and academic stakeholders to advance high-performance computing (HPC) technology in Europe. |
| **National Center for High-Performance Computing** | Facility for high-performance computing (HPC) resources including large-scale computational science and engineering, cluster and grid computing, middleware development, visualization and virtual reality, data storage, networking, and HPC-related training. |
| **National Center for Supercomputing Applications** | Offers high-performance computing resources such as the Blue Waters supercomputer, provides advanced data storage solutions, data analysis, and visualization tools, and supports interdisciplinary research in fields such as astrophysics, climate modeling, and genomics. |
| **Oak Ridge Leadership Computing Facility** | Provides supercomputing resources, such as the Summit supercomputer, for scientific research, offers support services including software development, data storage, and visualization, and facilitates research in various fields including climate science, biology, and materials science. |
| **Swiss National Supercomputing Centre** | Provides high-performance computing systems including the Piz Daint supercomputer, offers cloud computing services, data management, and user support, and facilitates scientific research in areas such as climate modeling, physics, and life sciences. |
| **Barcelona Supercomputing Center** | Provides access to MareNostrum, one of the most powerful supercomputers in Europe, offers resources for high-performance computing, data storage, and computational sciences, and supports research in fields including bioinformatics, computational biology, and engineering. |
| **Japan's RIKEN Center for Computational Science** | Houses the Fugaku supercomputer, one of the world's fastest supercomputers, provides resources for computational science, data processing, and artificial intelligence, and supports research in fields such as life sciences, materials science, and disaster prevention. |
| **National Supercomputing Centre Singapore** | Provides high-performance computing resources and support services, offers data storage, cloud computing, and software development services, and supports research in fields including bioinformatics, environmental modeling, and smart cities. |


Community computing platforms democratized participation and expanded bioinformatics research's reach. Platforms like BOINC [@url:https://link.springer.com/article/10.1007/s10723-019-09497-9] enabled broad participation in bioinformatics. Experts can submit computing tasks to BOINC, while non-experts and science enthusiasts can volunteer their computer resources to process these tasks. Several life sciences projects are available through BOINC, including protein-ligand docking, malaria simulations, and protein folding [@url:https://link.springer.com/article/10.1007/s10723-019-09497-9].

## 2010-Today: The present and future

The integration of computers into biology has ushered in a new era of research possibilities, allowing for increasingly complex studies. While before, the focus was on individual genes or proteins, advancements today enable the analysis of entire genomes or proteomes [@url:https://pubmed.ncbi.nlm.nih.gov/18761469]. This shift toward a holistic approach in biology is evident in disciplines like genomics, proteomics, and glycomics, which have limited interconnection between them.

The next leap at the intersection of computing and the life sciences lies in modeling entire living organisms and their environments simultaneously, integrating all molecular categories. This has already been achieved in a whole cell model of Mycoplasma genitalium, in which all its genes, products and their known metabolic interactions have been reconstructed [@url:https://pubmed.ncbi.nlm.nih.gov/22817898]. Driven by advancements in measurement techniques, improved computational performance and artificial intelligence (AI) techniques, whole-cell modeling is increasingly becoming realistic and feasible. In contrast to traditional bottom-up approaches relying on molecular interaction networks, a predictive model has been developed for genome-wide phenotypes of budding yeast using deep learning [@url:https://www.nature.com/articles/nmeth.4627]. The main applications of whole-cell modeling have been in producing useful substances and discovering drugs, such as antimicrobials [@url:https://pubmed.ncbi.nlm.nih.gov/26471224; @url:https://pubmed.ncbi.nlm.nih.gov/24556244; @url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7426639; @url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3856890] since whole-cell modeling was first directed toward unicellular organisms. Meanwhile, models of cultured human cells have also been developed, which have found applications in cell differentiation and medical research [@url:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5966287]. The possibility of modeling entire multicellular organisms may not be far off, considering the rapid pace of technological and computational advancements like artificial intelligence (AI) .





# Artificial Intelligence (AI)

Artificial intelligence (AI) refers to a set of tools, techniques and paradigms that enable computers to mimic human behavior and either replicate the decision-making process typically performed by humans or exceed human performance in solving complex tasks independently or with minimal human intervention [@url:https://www.researchgate.net/publication/30874496_Artificial_Intelligence_A_Modern_Approach]. AI is concerned with a variety of central problems, including knowledge representation, reasoning, learning, planning, perception, and communication. It also refers to a variety of tools and methods, including case-based reasoning, rule-based systems, genetic algorithms, fuzzy models, and multi-agent systems [@url:https://www.researchgate.net/publication/223020409_Chen_CM_Intelligent_Web-based_Learning_System_with_Personalized_Learning_Path_Guidance_Computers_Education_512_787-814]. Early AI research focused primarily on hard-coded statements in formal languages, which a computer can then automatically reason about based on logical inference rules. These computer systems known as expert systems, excelled in specific domains but lacked adaptability. Over time, AI has evolved to include a variety of approaches, each with its own strengths and weaknesses. For instance, expert systems are highly accurate within narrow fields but struggle with tasks outside their programmed knowledge. In contrast, machine learning algorithms can generalize from data and adapt to new situations, though they require large datasets and extensive training. Other AI techniques, such as deep learning, neural networks, and natural language processing also offer their own unique advantages and challenges. 

## Expert systems
Expert systems are a type of artificial intelligence (AI) that aims to replicate the decision-making capabilities of human experts in specific domains. They are made of a knowledge base containing domain-specific facts, rules, and heuristics, and an inference engine that applies logical reasoning to this knowledge to draw conclusions or make decisions [@url:https://ieeexplore.ieee.org/document/1145205]. Users are typically able to input queries and receive advice or recommendations through a simplified user interface. The primary user action, which involves pointing and clicking, is known as selecting [@url:https://www.semanticscholar.org/paper/On-Interface-Requirements-for-Expert-Systems-Wexelblat/291bffa7fec4fafff62462d015dd86c466273d4c]. 

An expert system for chemical analysis was developed in 1965 by AI researcher Edward Feigenbaum and geneticist Joshua Lederberg. This system was originally known as Heuristic DENDRAL and later as DENDRAL [@url:https://stacks.stanford.edu/file/druid:pj337tr4694/pj337tr4694.pdf]. DENDRAL was developed to analyze molecular structures, particularly those containing elements like carbon, hydrogen, and nitrogen, based on spectrographic data. It proposed molecular structures for the compounds, with accuracy comparable to that of expert chemists.

Edward Shortliffe’s work on MYCIN [@url:https://www.sciencedirect.com/science/article/abs/pii/S0020737378800492] began in 1972 at Stanford University. MYCIN, an expert system, was designed to assist physicians in diagnosing and selecting therapies for patients with bacterial infections, particularly patients with meningitis. It used a rule-based system that analyzed patient symptoms and medical history to suggest appropriate antibiotic treatments. MYCIN exhibited proficiency equivalent to infectious disease doctors.

However, despite their capabilities, the paradigm faces several limitations as humans generally struggle to explicitly articulate all their tacit knowledge that is required to perform complex tasks [@url:https://www.researchgate.net/publication/235028224_The_Applicability_and_Limitations_of_Expert_System_Shells], leading to challenges such as difficulty in extrapolation, handling out-of-distribution data, managing uncertainty, and addressing biases. These limitations arise because expert systems heavily rely on predefined rules and knowledge encoded by humans. Consequently, the involvement of humans in specifying these parameters is essential but can also introduce limitations due to human cognitive constraints and biases. In contrast, machine learning algorithms overcome some of these limitations by learning from data, and making them more adaptable without relying heavily on explicit human guidance.

## Machine learning and Deep learning

Machine learning (ML) is a subset of AI that focuses on the development of algorithms and statistical models that enable computers to perform tasks without being explicitly programmed to do so [@url:https://pubmed.ncbi.nlm.nih.gov/37468046]. It involves the use of data and algorithms to imitate the way humans learn, gradually improving the system's performance on a specific task over time through iterative learning processes. Machine learning is effective for tasks such as classification, regression, and clustering, particularly when they involve high-dimensional data. These algorithms analyze data, identify patterns, and make predictions or decisions without being explicitly programmed for each task.

Based on the given problem and the available data, there are many potential model and training paradigms, three of the most prominent types of ML being: supervised learning [@url:https://link.springer.com/article/10.1007/s10994-019-05855-6], unsupervised learning [@url: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5765025; @url:https://ieeexplore.ieee.org/document/9072123], and reinforcement learning [@url:https://ieeexplore.ieee.org/document/8716527]. The goal of machine learning is to develop an output model that can make predictions or decisions based on input data. In supervised learning, the model is trained on a labeled dataset, where each training example is paired with an output label. A label is the desired output or result for a given piece of data. For example, in an image recognition task, labels could be the names of objects in the images (e.g., "cat," "dog," "car"). In a spam detection task, emails could be labeled as "spam" or "not spam.". The goal is to learn a mapping from inputs to outputs. Unsupervised learning involves training a model on data without labeled responses. The goal is to uncover patterns or structures within the data. In reinforcement learning, an agent learns to make decisions by interacting with an environment. The agent receives feedback in the form of rewards or penalties based on its actions and learns to maximize cumulative rewards over time.

Depending on the learning task, the field offers various classes of ML algorithms, each of them coming in multiple specifications and variants, including regression models, instance-based algorithms, decision trees, Bayesian methods, and artificial neural networks, among others.

Artificial neural networks (ANNs) span all three major types of machine learning. ANNs are inspired by biological systems and consist of interconnected processing units called neurons, with connections akin to synapses in the human brain. Signals are processed based on thresholds set by activation functions, and organized into layers for input, hidden, and output layers. Shallow machine learning encompasses simpler ANNs and other algorithms, often being more interpretable than deep neural networks. Deep neural networks, which have multiple hidden layers, perform complex calculations to automatically discover patterns in data. This ability is known as deep learning64. Deep learning excels with large, high-dimensional data like text, images, and videos, while shallow learning may outperform with low-dimensional data or limited training data. Time series, image, and text data present various application domains.

![**Figure 2**: Relationship between statistics, artificial intelligence, expert systems, machine learning, deep learning and large language models.](https://github.com/samadon1/generative-biology/assets/56901167/e0b9341b-b745-4511-af3f-13466f8a96b9)

Automated model building in machine learning involves using input data for pattern identification relevant to the learning task. Shallow machine learning relies on  predefined features such as pixel values in images or word frequencies in text. For example, in image classification, shallow learning might rely on handcrafted features like color histograms or edge detectors. In contrast, deep learning can operate directly on high-dimensional raw input data, such as the raw pixel values of an image or the sequence of words in text. It automatically learns features at multiple levels of abstraction, allowing it to capture patterns in the data without the need for manual feature engineering. For instance, in image classification with deep learning, the model learns to detect edges, shapes, and textures from raw pixel data, resulting in improved accuracy [@url:https://www.sciencedirect.com/science/article/pii/S2666165921000041].

Deep learning architectures often combine both aspects into end-to-end systems or extract features for use in other learning subsystems. Various deep learning architectures have emerged, including convolutional neural networks (CNNs) [@url:https://arxiv.org/abs/1511.08458], recurrent neural networks (RNNs) [@url:https://arxiv.org/abs/1912.05911], distributed representations [@url:https://link.springer.com/article/10.1007/BF00114844], autoencoders [@url:https://arxiv.org/abs/2003.05991], generative adversarial neural networks (GANs) [@url:https://arxiv.org/abs/1406.2661], among others. CNNs excel in computer vision and speech recognition tasks, learning hierarchical features essential for image recognition. RNNs specialize in sequential data structures like time-series data and natural language processing (NLP), addressing the challenges of vanishing gradients through advanced mechanisms like long short-term memory (LSTM) networks [@url:https://pubmed.ncbi.nlm.nih.gov/35855771]. Distributed representations, such as word embeddings, play a crucial role in NLP tasks by projecting language entities into numerical representations, preserving semantic relationships between words. Autoencoders provide dense feature representations and are applied for unsupervised feature learning, dimensionality reduction, and anomaly detection. GANs, belonging to generative models, learn probability distributions over training data to generate new data samples, using a generator-discriminator framework in a non-cooperative game setting.

## Generative AI and Transformers

Generative AI (GenAI) analyzes vast amounts of data, looking for patterns and relationships, then uses these insights to create fresh, new content that mimics the original data [@url:https://www.sciencedirect.com/science/article/pii/S2543925124000020]. It does this by leveraging machine learning models, especially unsupervised and semi-supervised algorithms. There are three popular techniques for implementing Generative AI: Generative Adversarial Networks (GANs), Variational Autoencoders (VAEs), and Transformers.

Variational Autoencoders (VAEs) [@url:https://arxiv.org/abs/1312.6114] first introduced by Diederik P. Kingma et al. in 2013 are generative models in unsupervised machine learning that generate new data similar to the input data. They consist of an encoder that compresses the input data into a lower-dimensional latent space by producing parameters for a probability distribution (mean and variance). The decoder reconstructs the data from this latent representation. The loss function, which combines reconstruction loss and regularization loss (KL Divergence), ensures the output data is both accurate and diverse. VAEs are used in applications like image generation, data imputation, anomaly detection, offering a flexible framework for generating and understanding data despite some challenges in balancing the loss components and achieving high-quality outputs [@url:https://www.researchgate.net/publication/377955158_Autoencoders_and_their_applications_in_machine_learning_a_survey; @url:https://www.biorxiv.org/content/10.1101/433763v5; @url:https://www.researchgate.net/publication/322870935_A_New_Dimension_of_Breast_Cancer_Epigenetics_-_Applications_of_Variational_Autoencoders_with_DNA_Methylation].

In 2014, GANs [@url:https://arxiv.org/abs/1406.2661] were proposed by researchers at the University of Montreal. GANs use two models that work in tandem: One learns to generate a target output (like an image) and the other learns to discriminate true data from the generator’s output. The generator tries to fool the discriminator, and in the process learns to make more realistic outputs. The image generator StyleGAN [@url:https://arxiv.org/abs/1812.04948] is based on these types of models.  

Diffusion models [@url:https://arxiv.org/abs/2006.11239] were introduced a year later by researchers at Stanford University and the University of California at Berkeley. By iteratively refining their output, these models learn to generate new data samples that resemble samples in a training dataset and have been used to create realistic-looking images. A diffusion model is at the heart of the text-to-image generation system Stable Diffusion [@url:https://arxiv.org/abs/2112.10752].

Recurrent neural networks (RNNs) and their variants like long short-term memory (LSTM) networks are commonly used for sequential data processing tasks. However, these models suffer from limitations such as vanishing gradients and inefficiency in parallelization. Transformers revolutionized the field with the ability to capture long-range dependencies in sequential data efficiently and was first reported in the seminal 2017 paper, "Attention is All You Need" [@url:https://arxiv.org/abs/1706.03762]. The introduction of transformers, with their superior performance and scalability, initiated a departure from RNNs. Transformers were used to train the large language models (LLMs) that power ChatGPT [@url:https://openai.com/index/chatgpt].

The transformer architecture consists of an encoder and a decoder, each with multiple layers of self-attention and feedforward neural networks. The self-attention mechanism enables the model to assess the significance of a piece of data, such as a word in a sentence, based on that word’s relations with other words in the sentence. To preserve the ordering of the words and the meaning of the sentence, the transformer incorporates positional bias to maintain the relative positions of words within a sentence. 

The transformer encoder-decoder architecture performs well at tasks like language translation. In a language translation task, the model transforms a sentence by encoding inputs from one language and then decoding outputs in another. The encoder processes the input sentence and creates a fixed-size vector representation, which the decoder then uses to generate the output sentence. The encoder-decoder employs both self-attention and cross-attention mechanisms, where self-attention is applied to the decoder's inputs, and cross-attention focuses on the encoder's output.

A prominent example of the transformer encoder-decoder architecture is Google's T5 (Text-to-Text Transfer Transformer) [@url:https://arxiv.org/abs/1910.10683], introduced in 2019. T5 can be fine-tuned for various NLP tasks, including language translation, question answering, and summarization.Real-world applications of the transformer encoder-decoder architecture include Google Translate, which utilizes the T5 model for translating text between languages, and Facebook’s M2M-10080, a multilingual machine translation model capable of translating among 100 different languages.

![**Figure 3**: The encoder-decoder structure of the Transformer architecture. Adapted from “Attention Is All You Need” **Encoder-only models**: Ideal for tasks requiring a deep understanding of the input, such as sentence classification and named entity recognition. **Decoder-only models**: Suited for generative tasks like text generation. **Encoder-decoder models (or sequence-to-sequence models)**: Best for generative tasks that depend on an input, such as translation or summarization.
](https://github.com/samadon1/generative-biology/assets/56901167/0b812bd8-b2a8-48b6-9768-e2f447114bf6)

### Transformer Encoder

The transformer encoder architecture is used for tasks such as text classification, where the goal is to categorize a piece of text into predefined categories. Text classification tasks include determining the sentiment  of a piece of text, determining the topic and detecting if the text is spam. The encoder processes a sequence of tokens and produces a fixed-size vector representation of the entire sequence, which is then used for classification. The most notable transformer encoder model is BERT (Bidirectional Encoder Representations from Transformers) [@url:https://arxiv.org/abs/1810.04805], introduced by Google in 2018. BERT is pre-trained on large text datasets and can be fine-tuned for a wide range of NLP tasks.

Unlike the encoder-decoder architecture, the transformer encoder focuses solely on the input sequence without generating an output sequence and instead the output is a classification task. It uses the self-attention mechanism to identify the most relevant parts of the input for the given task. Real-world applications of the transformer encoder architecture include sentiment analysis, where models classify reviews as positive or negative, and email spam detection, where models classify emails as spam or not.

### Transformer Decoder

The transformer decoder architecture is tailored for tasks like language generation, where the model creates a sequence of words based on an input prompt or context. The decoder takes a fixed-size vector representation of the context and generates a sequence of words one at a time, with each word depending on the previously generated words. A well-known transformer decoder model is GPT-3 (Generative Pre-trained Transformer 3) [@url:https://arxiv.org/abs/2005.14165], introduced by OpenAI in 2020. GPT-3 is a large language model capable of generating human-like text across various styles and genres. ChatGPT, which is based on the GPT-3 model, was officially launched by OpenAI in November 2020.  It was a significant milestone in the development of large language models (LLMs), characterized by its ability to generate human-like text across various styles and genres. Real-world applications of the transformer decoder architecture include text generation, where models generate stories or articles based on a given prompt, and chatbots, where models create natural and engaging responses to user inputs.

### Large Language Models (LLMs)
Large language models are machine learning models that can comprehend and generate human language text. In the life sciences, LLMs such as GPT (Generative Pre-trained Transformer) and BERT, have revolutionized natural language processing, enabling researchers to extract insights from vast repositories of biomedical literature, accelerate drug discovery, and personalize patient care [@url:https://arxiv.org/abs/2311.05112].

Large language models use transformer models and are trained using massive datasets — hence, large. This enables them to recognize, translate, predict, or generate text or other content. They are composed of multiple neural network layers – recurrent layers, feedforward layers, embedding layers, and attention layers work in tandem to process the input text and generate output content.

There are three main kinds of large language models:

- **Generic or raw language models** predict the next word based on the language in the training data. These language models perform information retrieval tasks.
- **Instruction-tuned language models** are trained to predict responses to the instructions given in the input. This allows them to perform sentiment analysis, or to generate text or code.
- **Dialog-tuned language models** are trained to have a dialog by predicting the next response. Think of chatbots or conversational AI.

Before functioning, LLMs undergo two crucial processes: training and fine-tuning. They are pre-trained on massive textual datasets from sources like Wikipedia and GitHub, comprising trillions of words to form a foundation model or a pre-trained model. This unsupervised learning stage allows the model to understand word meanings, relationships, and contextual distinctions, such as discerning whether "right" means "correct" or the opposite of "left.". To perform specific tasks, pretrained models undergo fine-tuning, which tailors them to particular activities like translation. This process optimizes task-specific performance. A related method, prompt-tuning, trains the model using few-shot or zero-shot prompting. Few-shot prompting provides examples to teach the model how to respond, while zero-shot prompting directly instructs the model on the task without examples.

LLMs serve various purposes:

- **Information retrieval**: Used by search engines like Google and Bing to produce and communicate answers conversationally.
- **Sentiment analysis**: Used to evaluate the sentiment of textual data.
- **Text generation**: Powers generative AI, such as ChatGPT, to create text based on prompts.
- **Code generation**: Similar to text generation, LLMs can generate code by recognizing patterns.
- **Chatbots and conversational AI**: Facilitate customer service interactions by interpreting and responding to customer queries.


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

- Background on the role of DNA as a carrier of genetic information  
- Promise of generative models to advance DNA research
- Scope focused on the latest advances in DNA prediction and design

## Sequence Modeling

### Transformer architectures for modeling DNA sequences
The HyenaDNA paper introduces a new genomic foundation model called HyenaDNA that can process DNA sequences at single nucleotide resolution with ultralong context lengths up to 1 million base pairs - a 500x increase over previous transformer models. HyenaDNA uses a parameter-efficient convolutional architecture that allows it to scale subquadratically with sequence length, enabling the use of full genome-scale context. On a range of regulatory genomics prediction tasks, HyenaDNA matches or exceeds the performance of previous state-of-the-art models while using 1500x fewer parameters and 3200x less pretraining data. HyenaDNA also demonstrates the ability to perform challenging species classification using the full mutational profile visible at 1 million base pairs of context. The authors explore new training techniques to enable ultralong sequence modeling as well as prompt-based tuning methods for rapidly adapting to new tasks without updating pre-trained weights @doi:10.48550/arXiv.2306.15794.

### Pretraining on large genomic datasets
### Applications in variant calling and annotation

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

### Challenges in predicting long-range chromatin interactions
The development of transformer architectures like HyenaDNA that can leverage genome-scale context creates new opportunities for understanding long-range chromatin interactions, gene regulation, and intercellular networks. However, significant challenges remain in improving model accuracy and uncertainty quantification. Hybrid physics- and data-driven approaches may help address these gaps. Safety considerations around synthetic genome design also warrant further research to ensure responsible innovation as these generative capabilities advance. Overall, the future looks bright for generative models that can capture both local mutations and global patterns critical to biology @doi:10.48550/arXiv.2306.15794.

### Responsible design of synthetic genomes
### Ethical considerations for human genome editing


# Generative AI for Autonomous Experimentation 

## Introduction

- Promise of generative models to accelerate scientific discovery
- Rise of autonomous labs and robotics for automated experimentation
- Overview of generative AI's role in self-driving research 

## Closed-Loop Systems

- Integrating computational hypothesis generation with robotic wet lab testing
- Reinforcement learning pipelines for autonomous optimization
- Case studies in materials science, drug discovery

## Automated Experiment Design

- Using generative models to design novel compounds, genes
- Leveraging simulations to predict experimental outcomes
- Robotic execution of designed experiments 

## Adaptive Sampling

- Active learning to iteratively select most informative experiments 
- Bayesian optimization powered by neural networks
- Applications in probing molecular design spaces

## Real-Time Learning

- Deploying models on lab edge devices 
- Online learning from experimental data streams
- Improving models and experiment plans on-the-fly

## Outlook

- Key challenges around model accuracy and integration
- The future of data-driven, self-driving laboratories
- Risks of full automation and need for human oversight

## Conclusion

- Generative AI as a powerful tool for autonomous experimentation
- Accelerating discovery alongside human researchers
- Responsible implementation will maximize benefit


# Generative AI and the Biosecurity Landscape

## Introduction

- Background on biosecurity threats from natural, accidental, and intentional pathogens
- Rise of generative AI as a dual use technology for biodefense and misuse 

## Enhanced Risks

- Automated bioweapon design with generative models
- Relatively low computing needs to generate dangerous agents
- Challenges detecting artificially generated sequences/organisms

## Enhanced Response Capabilities

- Generative models for vaccine and therapeutic design
- High-throughput testing of countermeasures with synthetic data
- AI for early detection of emergent pathogens and outbreaks

## Recommendations

- Increased oversight for generative model development/release
- Expanding biosecurity legislation and regulations 
- Fostering open research and global cooperation  

## Outlook

- Trajectory toward increasingly powerful generative biological capabilities  
- Need for preventative ethics research and guidance
- Maintaining public trust and avoiding overreaction 

## Conclusion

- Balancing generative AI's benefits and risks in biology
- Importance of thoughtful governance and responsible innovation
- Staying ahead of the curve on biosecurity


# Policy Responses to Generative AI in Biology

## Introduction

- Background on rise of powerful generative models for biology
- Overview of risks like bioweapons, environmental damage
- Need for governance to ensure responsible development

## Self-Governance by Developers

- Voluntary guidelines on ethical AI by corporations  
- Limiting access to certain capabilities like human editing
- Issues with self-regulation and transparency 

## Governmental Regulations 

- New biosecurity regulations on certain AI technologies
- Restrictions on use of synthetic biology IP
- Challenges with fast pace of technology change

## International Governance

- Proposals for global observatory to monitor risks
- Treaties restricting development of bioweapons  
- Difficulty achieving consensus and compliance

## Public Deliberation and Ethics

- Activities to involve broader stakeholders 
- Gathering public attitudes on acceptable uses of generative bio AI
- Informing policy with deliberative democracy   

## Outlook

- Likely increase in debate and policy activity in this space
- Balancing innovation and security will be a key challenge
- Importance of thoughtful multidisciplinary discourse

## Conclusion

- No easy policy solutions, but inaction also carries risks
- Policy should enable innovation but promote responsible use
- This will require sustained public deliberation and coordination


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

