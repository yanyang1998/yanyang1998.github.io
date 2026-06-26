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
  <!-- <h1>Building AI systems that help reveal molecular structure from cryo-EM data.</h1> -->
  <p class="academic-lede">I develop foundation models, automated workflows, and open-source tools that help structural biologists recover 3D molecular structures from noisy cryo-EM images, making high-resolution biological discovery more scalable, reproducible, and accessible.</p>
  <p class="academic-actions">
    <a class="btn btn--primary" href="/files/cv_yang_yan.pdf">Download CV</a>
    <a class="btn" href="mailto:y.yan@zju.edu.cn">Email</a>
    <a class="btn" href="https://github.com/yanyang1998">GitHub</a>
  </p>
</section>

## Research Profile

Structural biology seeks to understand life at the molecular level: how proteins, complexes, and molecular machines are shaped, how they move, and how their structures explain biological function, interactions, and disease mechanisms. Cryo-electron microscopy (cryo-EM) has become one of the central technologies for this goal because it can image biomolecules close to their native states and support high-resolution 3D structure determination.

The computational challenge is that cryo-EM data are not direct 3D structures. A typical experiment produces large collections of extremely noisy 2D particle images. The same molecule may appear in many orientations, adopt multiple conformations, or coexist with other molecular species. Turning these data into reliable structural insight often requires expert decisions across particle selection, classification, heterogeneity analysis, and reconstruction.

I am a PhD candidate in computer science, jointly trained at Zhejiang University and Westlake University. My research uses self-supervised learning and foundation models to learn transferable representations of cryo-EM particles. These representations support particle-quality ranking, structural classification, pose clustering, heterogeneity analysis, and automated reconstruction.

My recent work introduced **Cryo-IEF**, a foundation model for cryo-EM particle processing pretrained on approximately 65 million particle images. This direction is extended by **CryoDECO**, which uses foundation-model priors to analyze compositional and conformational heterogeneity. I also build practical software systems, including **CryoWizard** and **cryodata**, that turn these models into reusable tools for cryo-EM workflows.

## Research Vision

My long-term goal is to build AI systems that make structural biology more automated, data-driven, and capable of resolving molecular structures and dynamics in native-like contexts. Rather than treating structure determination as a sequence of isolated manual steps, I am interested in models that can learn from large-scale cryo-EM and cryo-ET data, transfer across datasets, and assist scientists in reasoning about molecular state.

Building on the CryoDECO idea that foundation-model priors can reduce the circular dependency between classification and reconstruction, I am interested in **adaptive manifold intelligence**: models that infer the intrinsic degrees of freedom of a sample, choose appropriate latent capacity, and move beyond static structure determination toward continuous maps of biological state space. I am also interested in agent-based structural-biology systems that plan reconstruction strategies, diagnose failure modes, select data-processing actions, and connect imaging data with biochemical and multimodal biological evidence.

The broader goal is **panoramic structural biology**: moving from single purified targets toward AI-guided discovery of molecular machines, transient interactions, and conformational dynamics directly from complex native mixtures.

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
    <p>Introduced Cryo-IEF to learn transferable representations from large-scale, noisy cryo-EM particles, providing a foundation for downstream structural analysis.</p>
  </article>
  <article>
    <h3>Automated Reconstruction</h3>
    <p>Developed CryoWizard to reduce expert intervention in single-particle cryo-EM workflows and make structure determination more reproducible.</p>
  </article>
  <article>
    <h3>Heterogeneous Reconstruction</h3>
    <p>Developed CryoDECO for samples that are not a single static structure, using foundation-model priors to resolve compositional and conformational heterogeneity.</p>
  </article>
  <article>
    <h3>Open-Source Python Package</h3>
    <p>Built cryodata as reusable infrastructure that brings cryo-EM particle data into PyTorch-ready workflows for training, inference, and reproducible analysis.</p>
  </article>
</div>

## Featured Software

<div class="academic-projects">
  <article>
    <h3><a href="https://github.com/westlake-repl/Cryo-IEF">Cryo-IEF</a></h3>
    <p>Addresses the difficulty of interpreting noisy cryo-EM particles by learning general-purpose representations for quality assessment, classification, clustering, and reconstruction workflows.</p>
  </article>
  <article>
    <h3><a href="https://github.com/yanyang1998/CryoDECO">CryoDECO</a></h3>
    <p>Tackles structural heterogeneity by using Cryo-IEF priors to guide ab initio reconstruction and separate compositional or conformational states.</p>
  </article>
  <article>
    <h3><a href="https://github.com/SMART-StructBio-AI/cryoief-data">cryodata</a></h3>
    <p>Provides the data infrastructure needed to move cryoSPARC particle jobs, MRC/MRCS stacks, and metadata into reproducible PyTorch-ready datasets.</p>
  </article>
  <article>
    <h3><a href="https://github.com/SMART-StructBio-AI/CryoWizard">CryoWizard</a></h3>
    <p>Automates expert-heavy cryo-EM processing by integrating particle ranking and CryoSPARC workflows into an end-to-end reconstruction pipeline.</p>
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

<!-- ## Professional Profiles

<p class="academic-actions">
  <a class="btn" href="https://github.com/yanyang1998">GitHub</a>
  <a class="btn" href="https://scholar.google.com/citations?user=33_VlgwAAAAJ&hl=zh-CN">Google Scholar</a>
  <a class="btn" href="https://orcid.org/0000-0002-3306-3863">ORCID</a>
  <a class="btn" href="https://twitter.com/yangyan511018">X</a>
</p> -->
