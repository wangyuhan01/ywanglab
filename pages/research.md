---
layout: default
title: Research
---

## Research
<div class="research-container">
  <div class="research-description">
      <p>Cells are the fundamental units of tissues and organs. Diverse cell types are spatially organized to produce complex functions, and their identities and states are dynamic. They are modulated by environmental cues and physiological demand. They can also be reprogrammed by targeted transcriptional or circuit-level perturbations. The Y. Wang Lab studies how cellular diversity generates coordinated physiology. We develop and adapt molecular tools to map and perturb cell types in their native context across scales. With a focus on the brain-pancreas axis, we aim to link cellular state and circuit architecture to energy homeostasis and metabolic regulation, with the goal of ultimately translating these insights to prevent and treat metabolic diseases.</p>
  </div>
</div>

<style>
  .Lab-Publications {
  margin-top: 25px;   /* space above the first item */
}
  /* Container: vertical space between items */
  .Lab-Publications {
    display: grid;
    gap: 22px; /* space between articles */
  }

  /* Row: image left, text right */
  .Lab-Publications > article {
    display: flex;
    align-items: flex-start;
    column-gap: 18px; /* space between image and text */
    padding-bottom: 8px;
    border-bottom: 1px solid #eee;
  }
  .Lab-Publications > article:last-child { border-bottom: 0; }

  /* Thumbnail sizing (choose ONE of the two height rules) */
  .Lab-Publications > article > img {
    flex: 0 0 140px;
    width: 140px;
    /* Option A: square thumbs (consistent look) */
    height: 140px; object-fit: cover;
    /* Option B: natural aspect ratio — uncomment next line and remove height above */
    /* height: auto; */
    display: block; max-width: none; border-radius: 8px;
  }

  /* Text column */
  .Lab-Publications > article > .text { flex: 1; min-width: 0; }

  /* Smaller title */
  .Lab-Publications .text h3 {
    font-size: 1.1rem;       /* tweak to 0.95–1.1rem as you like */
    line-height: 1.3;
    margin: 0 0 0.3rem;
    font-weight: 600;
  }

  /* Optional: make links a touch subtler */
  .Lab-Publications .text a { text-decoration: underline; }
</style>


<div class="Lab-Publications">
  <article>
    <img src="{{ '/imgs/research/q1.jpg' | relative_url }}" alt="CEA" loading="lazy" >
    <div class="text">
      <h3>1. What defines a cell type?</h3>
      <p>Recent advances in single-cell RNA-seq and spatial omics have revealed far greater cellular diversity than previously recognized. Why does this diversity exist? And do molecularly defined cell types each govern specific functions? Molecular diversity alone only partially captures cellular properties, and it is still unclear which molecular features truly define a cell type. To address this challenge, we will integrate methods that co-measure molecular identity and functional outputs to construct a more complete, mechanistic definition of cell types.</p>
    </div>
  </article>
  <article>
    <img src="{{ '/imgs/research/q2.avif' | relative_url }}" alt="CEA" loading="lazy" >
    <div class="text">
      <h3>2. How are cell types modulated by external cues? </h3>
      <p>Most molecular cell-type definitions are snapshots, yet gene expression and cellular states are dynamic and shaped by environmental cues and physiological demands. How do external cues remodel cell types, their gene expression and their functions? We will engineer molecular tools to capture state dynamics within molecularly defined cell types, linking recent activity, hormonal/nutritional context, and other environmental signals to shifts in cell state and function.</p>
    </div>
  </article>
  <article>
    <img src="{{ '/imgs/research/q3_V2.avif' | relative_url }}" alt="CEA" loading="lazy" >
    <div class="text">
      <h3>3. How does the brain communicate with peripheral organs to regulate metabolic homeostasis? </h3>
      <p>We will focus on molecularly defined neuronal subtypes involved in energy homeostasis. Using cell type-specific approaches, we will map afferent and efferent connectivity and perturb activity to establish causal links between defined neural circuits and metabolic outputs. We aim to clarify how the brain communicates with peripheral organs, in particular the pancreas, to exert top-down control of metabolic function.</p>
    </div>
  </article>
</div>