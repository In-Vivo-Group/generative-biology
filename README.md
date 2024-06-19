# Computing in the Life Sciences: From Early Algorithms to Modern AI

<!-- usage note: edit the H1 title above to personalize the manuscript -->

[![arXiv](https://img.shields.io/badge/arXiv-2406.12108-brightgreen.svg)](https://arxiv.org/abs/2406.12108)
[![HTML Manuscript](https://img.shields.io/badge/manuscript-HTML-blue.svg)](https://in-vivo-group.github.io/generative-biology/)
[![PDF Manuscript](https://img.shields.io/badge/manuscript-PDF-blue.svg)](https://in-vivo-group.github.io/generative-biology/manuscript.pdf)
[![GitHub Actions Status](https://github.com/in-vivo-group/generative-biology/workflows/Manubot/badge.svg)](https://github.com/in-vivo-group/generative-biology/actions)

## Abstract

<!-- usage note: edit this section. -->

Computing in the life sciences has undergone a transformative evolution, from early computational models in the 1950s to the applications of artificial intelligence (AI) and machine learning (ML) seen today. This paper highlights key milestones and technological advancements through the historical development of computing in the life sciences.. The discussion includes the inception of computational models for biological processes, the advent of bioinformatics tools, and the integration of AI/ML in modern life sciences research. Attention is given to AI-enabled tools used in the life sciences, such as scientific large language models (Sci-LLMs) and bio-AI tools, examining their capabilities, limitations, and impact to biological risk. This paper seeks to clarify and establish essential terminology and concepts to ensure informed decision-making and effective communication across disciplines.

## Motivation

In today's rapidly evolving field of life sciences, technologies like Artificial Intelligence (AI) have become pivotal. However, their distinct roles and applications often blur in discussions, creating a need for clarity and understanding among stakeholders.

This paper aims to provide a comprehensive overview that delves into the historical roots, current applications, and future trajectories of computing technologies in life sciences. By demystifying key terms, outlining fundamental concepts, and tracing their developmental timelines, we seek to bridge the knowledge gap between practitioners and stakeholders. This foundational understanding is crucial for fostering an environment conducive to scientific innovation and achieving impactful public benefit outcomes.

Moreover, the review underscores significant studies and benchmarks within each technological domain. It contextualizes advancements while candidly addressing limitations, emerging best practices, and pivotal directions for future research. Beyond technical achievements, the paper delves into the pressing social and ethical challenges posed by applications of AI in the life sciences. These include issues of bias amplification, algorithmic opacity, and dual-use risks, which necessitate thoughtful consideration and proactive solutions.

## Contribution notes
Papers should be submitted for consideration as an [issue](https://github.com/In-Vivo-Group/generative-biology/issues). Issues should include as much detail as possible, but at a minimum, they should include the title of the paper and a link to the paper (preferably a DOI). An ideal issue will also include a 3-5 sentence summary of the main takeaway of the paper to make it easiest to include in the relevant sections of the review.

Contributions to this manuscript are welcome in the form of [pull requests](https://github.com/In-Vivo-Group/generative-biology/pulls). For any questions about this manuscript, submit an [issue](https://github.com/In-Vivo-Group/generative-biology/issues) with your question, or email **Alexander Titus** at [publications@theinvivogroup.com](mailto:titus@theinvivogroup.com).

# FAQ
<details>
<summary><b>Can I contribute?</b></summary>

Yes, everyone is welcome and encouraged to contribute to this manuscript. We welcome contributions from researchers, practitioners, and stakeholders in the life sciences community and beyond. Whether through insights, case studies, or ethical reflections, your input can enrich ongoing discussions and shape the future of AI in the life sciences. We ask that you do so through issues, pull requests, and engaging with the content thoughtfully. 


</details>
<details>
<summary><b>What do I do if I have a question?</b></summary>

Issues. Lots of issues. It's not that you have issues, but that we want to have issues. If you have questions, submit them so that we can track it and someone can help you. If we get the question enough, it will end up in these FAQs. Submit your issues!

</details>
<details>
<summary><b>Where can I find the latest version of this paper?</b></summary>
The latest version will soon be available on arXiv. Stay tuned for updates and access through this link.

</details>
<details>
<summary><b>What is Manubot?</b></summary>

Read everything on this README file below this question :-D

</details>

## Manubot

<!-- usage note: do not edit this section -->

Manubot is a system for writing scholarly manuscripts via GitHub.
Manubot automates citations and references, versions manuscripts using git, and enables collaborative writing via GitHub.
An [overview manuscript](https://greenelab.github.io/meta-review/ "Open collaborative writing with Manubot") presents the benefits of collaborative writing with Manubot and its unique features.
The [rootstock repository](https://git.io/fhQH1) is a general purpose template for creating new Manubot instances, as detailed in [`SETUP.md`](SETUP.md).
See [`USAGE.md`](USAGE.md) for documentation how to write a manuscript.

Please open [an issue](https://git.io/fhQHM) for questions related to Manubot usage, bug reports, or general inquiries.

### Repository directories & files

The directories are as follows:

+ [`content`](content) contains the manuscript source, which includes markdown files as well as inputs for citations and references.
  See [`USAGE.md`](USAGE.md) for more information.
+ [`output`](output) contains the outputs (generated files) from Manubot including the resulting manuscripts.
  You should not edit these files manually, because they will get overwritten.
+ [`webpage`](webpage) is a directory meant to be rendered as a static webpage for viewing the HTML manuscript.
+ [`build`](build) contains commands and tools for building the manuscript.
+ [`ci`](ci) contains files necessary for deployment via continuous integration.

### Local execution

The easiest way to run Manubot is to use [continuous integration](#continuous-integration) to rebuild the manuscript when the content changes.
If you want to build a Manubot manuscript locally, install the [conda](https://conda.io) environment as described in [`build`](build).
Then, you can build the manuscript on POSIX systems by running the following commands from this root directory.

```sh
# Activate the manubot conda environment (assumes conda version >= 4.4)
conda activate manubot

# Build the manuscript, saving outputs to the output directory
bash build/build.sh

# At this point, the HTML & PDF outputs will have been created. The remaining
# commands are for serving the webpage to view the HTML manuscript locally.
# This is required to view local images in the HTML output.

# Configure the webpage directory
manubot webpage

# You can now open the manuscript webpage/index.html in a web browser.
# Alternatively, open a local webserver at http://localhost:8000/ with the
# following commands.
cd webpage
python -m http.server
```

Sometimes it's helpful to monitor the content directory and automatically rebuild the manuscript when a change is detected.
The following command, while running, will trigger both the `build.sh` script and `manubot webpage` command upon content changes:

```sh
bash build/autobuild.sh
```

### Continuous Integration

Whenever a pull request is opened, CI (continuous integration) will test whether the changes break the build process to generate a formatted manuscript.
The build process aims to detect common errors, such as invalid citations.
If your pull request build fails, see the CI logs for the cause of failure and revise your pull request accordingly.

When a commit to the `main` branch occurs (for example, when a pull request is merged), CI builds the manuscript and writes the results to the [`gh-pages`](https://github.com/in-vivo-group/generative-biology/tree/gh-pages) and [`output`](https://github.com/in-vivo-group/generative-biology/tree/output) branches.
The `gh-pages` branch uses [GitHub Pages](https://pages.github.com/) to host the following URLs:

+ **HTML manuscript** at https://in-vivo-group.github.io/generative-biology/
+ **PDF manuscript** at https://in-vivo-group.github.io/generative-biology/manuscript.pdf

For continuous integration configuration details, see [`.github/workflows/manubot.yaml`](.github/workflows/manubot.yaml).

## License

<!--
usage note: edit this section to change the license of your manuscript or source code changes to this repository.
We encourage users to openly license their manuscripts, which is the default as specified below.
-->

[![License: CC BY 4.0](https://img.shields.io/badge/License%20All-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
[![License: CC0 1.0](https://img.shields.io/badge/License%20Parts-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Except when noted otherwise, the entirety of this repository is licensed under a CC BY 4.0 License ([`LICENSE.md`](LICENSE.md)), which allows reuse with attribution.
Please attribute by linking to https://github.com/in-vivo-group/generative-biology.

Since CC BY is not ideal for code and data, certain repository components are also released under the CC0 1.0 public domain dedication ([`LICENSE-CC0.md`](LICENSE-CC0.md)).
All files matched by the following glob patterns are dual licensed under CC BY 4.0 and CC0 1.0:

+ `*.sh`
+ `*.py`
+ `*.yml` / `*.yaml`
+ `*.json`
+ `*.bib`
+ `*.tsv`
+ `.gitignore`

All other files are only available under CC BY 4.0, including:

+ `*.md`
+ `*.html`
+ `*.pdf`
+ `*.docx`

Please open [an issue](https://github.com/in-vivo-group/generative-biology/issues) for any question related to licensing.
