---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

These projects are open-source research systems and infrastructure for cryo-EM particle processing, representation learning, automated reconstruction, and heterogeneous structure analysis.

<div class="academic-projects academic-projects--large">
  <article>
    <h2><a href="https://github.com/westlake-repl/Cryo-IEF">Cryo-IEF</a></h2>
    <p class="academic-meta">Foundation model for cryo-EM particle processing</p>
    <p>Designed and released the Cryo-IEF ecosystem, pretrained on approximately 65 million cryo-EM particle images. The project supports representation learning and downstream tools for CryoRanker and CryoClustering, enabling structural classification, pose clustering, particle-quality assessment, and automated reconstruction workflows.</p>
    <p><a class="btn" href="https://github.com/westlake-repl/Cryo-IEF">Repository</a></p>
  </article>

  <article>
    <h2><a href="https://github.com/yanyang1998/CryoDECO">CryoDECO</a></h2>
    <p class="academic-meta">Foundation-prior reconstruction for cryo-EM heterogeneity</p>
    <p>Developed a prior-guided heterogeneous reconstruction framework that uses Cryo-IEF representations to reduce random ab initio initialization and disentangle compositional classification from 3D reconstruction.</p>
    <p><a class="btn" href="https://github.com/yanyang1998/CryoDECO">Repository</a></p>
  </article>

  <article>
    <h2><a href="https://github.com/SMART-StructBio-AI/cryoief-data">cryodata</a></h2>
    <p class="academic-meta">Reusable data layer for scientific machine learning in cryo-EM</p>
    <p>Created the open-source data-processing layer used by Cryo-IEF, CryoDECO, and CryoWizard. The package converts CryoSPARC particle jobs into PyTorch-ready datasets and supports MRC/MRCS preprocessing, LMDB-backed datasets, Fourier/Hartley feature generation, balanced sampling, data loading, and CryoSPARC-to-RELION metadata conversion.</p>
    <p><a class="btn" href="https://github.com/SMART-StructBio-AI/cryoief-data">Repository</a></p>
  </article>

  <article>
    <h2><a href="https://github.com/SMART-StructBio-AI/CryoWizard">CryoWizard</a></h2>
    <p class="academic-meta">Automated single-particle cryo-EM reconstruction pipeline</p>
    <p>Built and extended an end-to-end computational pipeline integrating CryoRanker with CryoSPARC. CryoWizard streamlines processing from raw movies, micrographs, or particles to high-resolution 3D volumes through command-line, web, and browser-extension interfaces.</p>
    <p><a class="btn" href="https://github.com/SMART-StructBio-AI/CryoWizard">Repository</a></p>
  </article>
</div>

## GitHub Profile

For additional public repositories and contributions, see <a href="https://github.com/yanyang1998">github.com/yanyang1998</a>.

