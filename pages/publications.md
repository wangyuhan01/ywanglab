---
layout: default
title: Publications
---
## Selected Publications

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
    flex: 0 0 190px;
    width: 210px;
    /* Option A: square thumbs (consistent look) */
    height: 200px; object-fit: cover;
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

  .Lab-Publications > article.no-image::before {
    content: "";
    display: block;
    flex: 0 0 200px;   /* same width as thumbnails */
  }
</style>

<div class="Lab-Publications">
  <article>
    <img src="{{ '/imgs/paper_cover/elife.jpg' | relative_url }}" alt="CEA" loading="lazy">
    <div class="text">
      <h3>Multimodal mapping of cell types and projections in the central nucleus of the amygdala</h3>
      <p>Wang Y, Krabbe S, Eddison M, Henry F, Lemire A, Korff W, Tillberg P, Luthi A, Sternson SM. Elife, 2023. <a href="https://elifesciences.org/articles/84262">Link</a>.</p>
    </div>
  </article>

  <article>
    <img src="{{ '/imgs/paper_cover/easi-fish.jpg' | relative_url }}" alt="EASI-FISH" loading="lazy">
    <div class="text">
      <h3>EASI-FISH for thick tissue defines lateral hypothalamus spatio-molecular organization</h3>
      <p>Wang Y, Eddison M, Fleishman G, Weigert M, Xu S, Wang T, Rokicki K, Goina C, Henry F, Lemire A, Schmidt Uwe, Yang H, Svoboda K, Myers E, Saalfeld S, Korff W, Sternson SM*, Tillberg P*. Cell, 2021. <a href="https://www.cell.com/cell/fulltext/S0092-8674(21)01339-8">Link</a>.</p>
    </div>
  </article>

  <article>
    <img src="{{ '/imgs/paper_cover/panc_duct.jpg' | relative_url }}" alt="CEA" loading="lazy">
    <div class="text">
      <h3>Long-term correction of diabetes in mice by in vivo reprogramming of pancreatic ducts</h3>
      <p>Wang Y, Dorrell C, Naugler WE, Heskett M, Spellman P, Li B, Galivo F, Haft A, Wakefield L, Grompe M. Molecular Therapy, 2018. <a href="https://elifesciences.org/articles/84262">Link</a>.</p>
    </div>
  </article>

  <article>
    <img src="{{ '/imgs/paper_cover/humanGBC.jpg' | relative_url }}" alt="EASI-FISH" loading="lazy">
    <div class="text">
      <h3>Reprogramming human gallbladder cells into insulin-producing β-like cells</h3>
      <p>Galivo F, Benedetti E, Wang Y, Schug J, Kaestner K, Grompe M. PloS ONE, 2017. <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0181812">Link</a>.</p>
    </div>
  </article>

  <article>
    <img src="{{ '/imgs/paper_cover/gbc.jpeg' | relative_url }}" alt="EASI-FISH" loading="lazy">
    <div class="text">
      <h3>Efficient generation of pancreatic β-like cells from the mouse gallbladder</h3>
      <p>Wang Y, Galivo F, Pelz C, Haft A, Lee J, Kim SK, Grompe M. Stem Cell Research, 2016 <a href="https://www.sciencedirect.com/science/article/pii/S1873506116301696?via%3Dihub">Link</a>.</p>
    </div>
  </article>

  <article>
    <img src="{{ '/imgs/paper_cover/cirrhosis.jpg' | relative_url }}" alt="EASI-FISH" loading="lazy">
    <div class="text">
      <h3>In vitro expansion of cirrhosis derived liver epithelial cells with defined small molecules</h3>
      <p>Li B, Wang Y, Pelz C, Moss J, Shemer R, Dor Y, Akkari YK, Canady PS, Naugler WE, Orloff S, Grompe M. Stem Cell Research, 2021. <a href="https://www.sciencedirect.com/science/article/pii/S1873506121003706">Link</a>.</p>
    </div>
  </article>

  <article class="no-image">
    <div class="text">
      <h3>The organoid-initiating cells in mouse pancreas and liver are phenotypically and functionally similar</h3>
      <p>Dorrell C, Tarlow B, Wang Y, Canaday PS, Haft A, Schug J, Streeter PR, Finegold MJ, Shenje LT, Kaestner KH, Grompe M. Stem Cell Research, 2014 <a href="https://www.sciencedirect.com/science/article/pii/S1873506114000877?via%3Dihub">Link</a>.</p>
    </div>
  </article>

  <article class="no-image">
    <div class="text">
      <h3>Generation of islet-like cells from mouse gall bladder by direct ex vivo reprogramming</h3>
      <p>Hickey RD, Galivo F, Schug J, Brehm MA, Haft A, Wang Y, Benedetti E, Gu G, Magnuson MA, Shultz LD, Lagasse E, Greiner DL, Kaestner KH, Grompe M. Stem Cell Research, 2013. <a href="https://www.sciencedirect.com/science/article/pii/S1873506113000226?via%3Dihub">Link</a>.</p>
    </div>
  </article>

  <!-- Duplicate <article> blocks as needed -->
</div>
