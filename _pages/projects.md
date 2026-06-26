---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

These projects form a connected AI-for-cryo-EM ecosystem for turning noisy particle data into molecular structure discovery. Together, they cover the data infrastructure, foundation-model representations, heterogeneous reconstruction methods, and automated workflows needed to make cryo-EM analysis more scalable and reproducible.

<div class="academic-projects academic-projects--large">
  <article>
    <h2><a href="https://github.com/westlake-repl/Cryo-IEF">Cryo-IEF</a></h2>
    <p class="academic-meta">Foundation model for cryo-EM particle processing</p>
    <p>Cryo-EM particle images are noisy, heterogeneous, and difficult to interpret one by one. Designed and released the Cryo-IEF ecosystem, pretrained on approximately 65 million cryo-EM particle images to learn transferable representations for structural classification, pose clustering, particle-quality assessment, and automated reconstruction workflows.</p>
    <p><a class="btn" href="https://github.com/westlake-repl/Cryo-IEF">Repository</a></p>
  </article>

  <article>
    <h2><a href="https://github.com/yanyang1998/CryoDECO">CryoDECO</a></h2>
    <p class="academic-meta">Foundation-prior reconstruction for cryo-EM heterogeneity</p>
    <p>Real biological samples often contain multiple molecular species or continuous conformational motion rather than a single static structure. Developed a prior-guided heterogeneous reconstruction framework that uses Cryo-IEF representations to reduce random ab initio initialization and disentangle compositional classification from 3D reconstruction.</p>
    <p><a class="btn" href="https://github.com/yanyang1998/CryoDECO">Repository</a></p>
  </article>

  <article>
    <h2><a href="https://github.com/SMART-StructBio-AI/cryoief-data">cryodata</a></h2>
    <p class="academic-meta">Reusable data layer for scientific machine learning in cryo-EM</p>
    <p>Deep learning methods can only become useful in cryo-EM when experimental data and metadata can be moved reliably into training and inference workflows. Created the open-source data-processing layer used by Cryo-IEF, CryoDECO, and CryoWizard, with support for MRC/MRCS preprocessing, LMDB-backed datasets, Fourier/Hartley feature generation, balanced sampling, data loading, and CryoSPARC-to-RELION metadata conversion.</p>
    <p><a class="btn" href="https://github.com/SMART-StructBio-AI/cryoief-data">Repository</a></p>
  </article>

  <article>
    <h2><a href="https://github.com/SMART-StructBio-AI/CryoWizard">CryoWizard</a></h2>
    <p class="academic-meta">Automated single-particle cryo-EM reconstruction pipeline</p>
    <p>Cryo-EM structure determination traditionally requires many expert choices across data-processing stages. Built and extended an end-to-end computational pipeline integrating CryoRanker with CryoSPARC, streamlining processing from raw movies, micrographs, or particles to high-resolution 3D volumes through command-line, web, and browser-extension interfaces.</p>
    <p><a class="btn" href="https://github.com/SMART-StructBio-AI/CryoWizard">Repository</a></p>
  </article>
</div>

## GitHub Profile

For additional public repositories and contributions, see <a href="https://github.com/yanyang1998">github.com/yanyang1998</a>.
