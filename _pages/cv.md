---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<p class="academic-actions">
  <a class="btn btn--primary" href="/files/cv_yang_yan.pdf">Download CV as PDF</a>
  <a class="btn" href="mailto:y.yan@zju.edu.cn">Contact</a>
</p>

## Contact

**Yang Yan**<br>
Ph.D. Candidate, Zhejiang University / Westlake University<br>
AI for Science | Computer Vision | Representation Learning | Structural Biology<br>
Email: [y.yan@zju.edu.cn](mailto:y.yan@zju.edu.cn), [yanyang92@westlake.edu.cn](mailto:yanyang92@westlake.edu.cn)<br>
GitHub: [github.com/yanyang1998](https://github.com/yanyang1998)<br>
Google Scholar: [profile](https://scholar.google.com/citations?user=33_VlgwAAAAJ&hl=zh-CN)<br>
ORCID: [0000-0002-3306-3863](https://orcid.org/0000-0002-3306-3863)<br>
X: [@yangyan511018](https://twitter.com/yangyan511018)

## Research Profile

AI-for-science Ph.D. candidate building foundation models and open-source ML systems for cryo-electron microscopy. First author of a *Nature Methods* study introducing **Cryo-IEF**, a foundation model for cryo-EM particle processing, pretrained on approximately **65.3M particle images** and transferred to structural classification, pose-aware clustering, particle-quality ranking, and automated reconstruction. Current work extends this research through **CryoDECO**, a foundation-prior ab initio reconstruction framework for compositional and conformational heterogeneity.

## Education

<div class="academic-timeline">
  <article>
    <span>2023-Present</span>
    <h3>Ph.D. Candidate in Computer Science</h3>
    <p>Zhejiang University / Westlake University</p>
    <p>Joint Ph.D. program supervised by Prof. Fajie Yuan and Prof. Huaizong Shen. Research: foundation models for cryo-EM image processing, automated workflows, and heterogeneity analysis.</p>
  </article>
  <article>
    <span>2020-2023</span>
    <h3>M.S. in Translational Medicine (Engineering)</h3>
    <p>Xiamen University</p>
    <p>National Institute of Diagnostics and Vaccine Development in Infectious Diseases, supervised by Prof. Ningshao Xia. Research: machine learning for medical image analysis.</p>
  </article>
  <article>
    <span>2016-2020</span>
    <h3>B.S. in Electrical Information Engineering</h3>
    <p>Northeastern University (Qinhuangdao)</p>
    <p>Research included machine-learning applications in localization.</p>
  </article>
</div>

## Selected Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Research Highlights

- **First cryo-EM foundation model:** introduced **Cryo-IEF**, a foundation model developed for cryo-EM particle processing and pretrained on approximately 65M particle images.
- **Automated reconstruction pipeline:** developed **CryoWizard**, a computational pipeline for single-particle cryo-EM reconstruction that streamlines data processing, particle ranking, and 3D structure determination.
- **Heterogeneous reconstruction:** developed **CryoDECO**, a foundation-prior model for heterogeneous cryo-EM reconstruction and panoramic analysis of structural mixtures.
- **Open-source Python package for cryo-EM data processing:** developed **cryodata**, a PyPI-installable data layer that converts CryoSPARC particle jobs into PyTorch-ready datasets.

## Research Software and Open Source

<div class="academic-projects">
  <article>
    <h3><a href="https://github.com/westlake-repl/Cryo-IEF">Cryo-IEF</a></h3>
    <p>Foundation model for cryo-EM particle processing, including PyTorch inference and downstream tooling for CryoRanker and CryoClustering.</p>
  </article>
  <article>
    <h3><a href="https://github.com/yanyang1998/CryoDECO">CryoDECO</a></h3>
    <p>Prior-guided heterogeneous reconstruction framework using Cryo-IEF representations to support compositional and conformational deconstruction.</p>
  </article>
  <article>
    <h3><a href="https://github.com/SMART-StructBio-AI/CryoWizard">CryoWizard</a></h3>
    <p>Automated single-particle cryo-EM reconstruction pipeline integrating CryoRanker with CryoSPARC.</p>
  </article>
  <article>
    <h3><a href="https://github.com/SMART-StructBio-AI/cryoief-data">cryodata</a></h3>
    <p>Reusable data layer for MRC/MRCS preprocessing, LMDB datasets, Fourier/Hartley features, balanced sampling, and metadata conversion.</p>
  </article>
</div>

## Technical Skills

- **ML / Vision:** self-supervised learning, representation learning, foundation models, clustering, autoencoders, generative/reconstruction models, image denoising.
- **Structural Biology:** single-particle cryo-EM, cryo-ET, CryoSPARC/RELION workflows, ChimeraX visualization, MRC/MRCS data formats.
- **Systems:** multiprocessing data pipelines, parallel GPU training and inference.

## Research Interests

My long-term research vision is to develop AI systems that understand molecular structure in its native, dynamic context. I am interested in structural world models that learn the latent laws of macromolecular identity, interaction, motion, and cellular context from large-scale cryo-EM/cryo-ET data, as well as agent-based structural-biology systems that autonomously plan reconstruction strategies and diagnose workflow failure modes.
