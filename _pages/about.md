---
permalink: /
title: "Yang Yan"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section class="academic-hero">
  <p class="academic-kicker">AI for Science | Computer Vision | Representation Learning | Structural Biology</p>
  <!-- <h1>Ph.D. candidate building foundation models for cryo-electron microscopy.</h1> -->
  <!-- <p class="academic-lede">I develop AI systems and open-source tools that make cryo-EM particle processing, heterogeneity analysis, and structure determination more automated, scalable, and reproducible.</p> -->
  <p class="academic-actions">
    <a class="btn btn--primary" href="/files/cv_yang_yan.pdf">Download CV</a>
    <a class="btn" href="mailto:y.yan@zju.edu.cn">Email</a>
    <a class="btn" href="https://github.com/yanyang1998">GitHub</a>
  </p>
</section>

## Research Profile

I am a Ph.D. candidate in Computer Science in a joint program at Zhejiang University and Westlake University, supervised by Prof. Fajie Yuan and Prof. Huaizong Shen. My research focuses on foundation models and practical machine-learning systems for single-particle cryo-EM, with an emphasis on representation learning, particle-quality ranking, clustering, and automated reconstruction.

My recent work introduced **Cryo-IEF**, a foundation model for cryo-EM particle processing pretrained on approximately 65 million particle images and transferred to structural classification, pose-aware clustering, particle-quality ranking, and automated reconstruction. Current work extends this direction through **CryoDECO**, a foundation-prior framework for compositional and conformational heterogeneity.

## Research Vision

My long-term research vision is to develop AI systems that understand molecular structure in its native, dynamic context. Building on the CryoDECO idea that foundation-model priors can break the circular dependency between classification and reconstruction, I am interested in next-generation structural world models that learn the latent laws of macromolecular identity, interaction, motion, and cellular context from large-scale cryo-EM/cryo-ET data.

A central direction is **adaptive manifold intelligence**: models that infer the intrinsic degrees of freedom of a sample, choose appropriate latent capacity, and move beyond static structure determination toward continuous maps of biological state space. I am also interested in agent-based structural-biology systems that autonomously plan reconstruction strategies, diagnose failure modes, select data-processing actions, and connect imaging data with biochemical and multimodal biological evidence.

The broader goal is **panoramic structural biology**: replacing single-target, purification-heavy workflows with AI-guided discovery of molecular machines, transient interactions, and conformational dynamics directly from complex native mixtures.

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

<div class="academic-list">
  <article>
    <h3>A comprehensive foundation model for cryo-EM image processing</h3>
    <p><strong>Yang Yan</strong>, Shiqi Fan, Fajie Yuan, Huaizong Shen. <em>Nature Methods</em>, 23(1), 88-95, 2026. DOI: <a href="https://doi.org/10.1038/s41592-025-02916-8">10.1038/s41592-025-02916-8</a>.</p>
  </article>
  <article>
    <h3>Artificial intelligence foundation model automates cryo-EM structure determination</h3>
    <p><strong>Yang Yan</strong>, Huaizong Shen. <em>Nature Methods Research Briefing</em>, 23, 26-27, 2026. DOI: <a href="https://doi.org/10.1038/s41592-025-02917-7">10.1038/s41592-025-02917-7</a>.</p>
  </article>
  <article>
    <h3>CryoDECO: Deconstructing Extreme Compositional and Conformational Heterogeneity in Cryo-EM via Foundation Model Priors</h3>
    <p><strong>Yang Yan</strong>, Yanwanyu Xi, Shiqi Fan, Yifei Wang, Ziyun Tang, Fajie Yuan, Huaizong Shen. LangTaoSha Preprint Server, 2026. DOI: <a href="https://doi.org/10.65215/LTSpreprints.2025.12.30.000075">10.65215/LTSpreprints.2025.12.30.000075</a>.</p>
  </article>
</div>

[View all publications](/publications/){: .btn}

## Research Highlights

<div class="academic-card-grid">
  <article>
    <h3>Cryo-EM Foundation Models</h3>
    <p>Introduced Cryo-IEF as a foundation-model paradigm for automated cryo-EM particle analysis.</p>
  </article>
  <article>
    <h3>Automated Reconstruction</h3>
    <p>Developed CryoWizard, a fully automated computational pipeline for single-particle cryo-EM reconstruction.</p>
  </article>
  <article>
    <h3>Heterogeneous Reconstruction</h3>
    <p>Developed CryoDECO to combine foundation-model priors with ab initio reconstruction for complex compositional and conformational heterogeneity.</p>
  </article>
  <article>
    <h3>Open Scientific ML Infrastructure</h3>
    <p>Built cryodata, a reusable PyTorch-ready data layer for CryoSPARC particle outputs, MRC/MRCS preprocessing, LMDB datasets, and metadata conversion.</p>
  </article>
</div>

## Featured Software

<div class="academic-projects">
  <article>
    <h3><a href="https://github.com/westlake-repl/Cryo-IEF">Cryo-IEF</a></h3>
    <p>Foundation model ecosystem for cryo-EM particle processing, including downstream tooling for CryoRanker and CryoClustering.</p>
  </article>
  <article>
    <h3><a href="https://github.com/yanyang1998/CryoDECO">CryoDECO</a></h3>
    <p>Foundation-prior framework for heterogeneous cryo-EM reconstruction and compositional/conformational deconstruction.</p>
  </article>
  <article>
    <h3><a href="https://github.com/SMART-StructBio-AI/cryoief-data">cryodata</a></h3>
    <p>Open-source data-processing package that turns CryoSPARC particle jobs into reproducible PyTorch-ready datasets.</p>
  </article>
  <article>
    <h3><a href="https://github.com/SMART-StructBio-AI/CryoWizard">CryoWizard</a></h3>
    <p>End-to-end automated single-particle cryo-EM reconstruction pipeline integrating particle ranking and CryoSPARC workflows.</p>
  </article>
</div>

[View projects](/projects/){: .btn}

## Posters

<div class="academic-card-grid">
  <article>
    <h3>Cryo-IEF Poster</h3>
    <p>Foundation models for cryo-EM particle processing.</p>
    <p><a href="/files/Cryo_IEF_poster.pdf">Open poster PDF</a></p>
  </article>
  <article>
    <h3>CryoDECO Poster</h3>
    <p>Foundation-prior reconstruction for extreme cryo-EM heterogeneity.</p>
    <p><a href="/files/CryoDECO_poster.pdf">Open poster PDF</a></p>
  </article>
</div>

## Professional Profiles

<p class="academic-actions">
  <a class="btn" href="https://github.com/yanyang1998">GitHub</a>
  <a class="btn" href="https://scholar.google.com/citations?user=33_VlgwAAAAJ&hl=zh-CN">Google Scholar</a>
  <a class="btn" href="https://orcid.org/0000-0002-3306-3863">ORCID</a>
  <a class="btn" href="https://twitter.com/yangyan511018">X</a>
</p>
