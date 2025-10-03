---
layout: default
title: News
---

## Lab News

<style>
  /* ===== Spacing tuned tighter than Publications ===== */
  .Lab-News {
    margin-top: 16px;                  /* less top space */
    display: grid;
    gap: 12px;                         /* less space between items (was 22px) */
  }

  /* Row: image left, text right */
  .Lab-News > article {
    display: flex;
    align-items: flex-start;
    column-gap: 12px;                  /* tighter than 18px */
    padding-bottom: 6px;               /* thinner divider padding */
    border-bottom: 1px solid #eee;
  }
  .Lab-News > article:last-child { border-bottom: 0; }

  /* Thumbnail: slightly smaller to reduce visual bulk */
  .Lab-News > article > img {
    flex: 0 0 160px;                   /* narrower than 190/210 */
    width: 170px;
    height: 150px;                     /* keep square/cropped look */
    object-fit: cover;
    display: block;
    max-width: none;
    border-radius: 8px;
  }

  /* Text column */
  .Lab-News > article > .text { flex: 1; min-width: 0; }

  .Lab-News .text h3 {
    font-size: 1.0rem;                 /* slightly smaller title */
    line-height: 1.3;
    margin: 0 0 0.25rem;
    font-weight: 600;
  }

  /* Optional date badge */
  .Lab-News .meta {
    font-size: 0.9rem;
    color: #64748b;                    /* slate-ish */
    margin-bottom: 0.35rem;
  }

  /* Links subtle but visible */
  .Lab-News .text a { text-decoration: underline; }

  /* Items with no image: keep columns aligned */
  .Lab-News > article.no-image::before {
    content: "";
    display: block;
    flex: 0 0 170px;                   /* match image width */
  }

  /* ===== Mobile: stack image above text, keep things compact ===== */
  @media (max-width: 700px) {
    .Lab-News > article {
      flex-direction: column;
      row-gap: 8px;
      column-gap: 0;
      padding-bottom: 10px;
    }
/* Thumbnail: consistent 4:3 box, smaller than now */
/* Thumbnail: keep aspect ratio, cap height */
.Lab-News > article > img {
  flex: 0 0 240px;   /* column width */
  width: 240px;
  max-height: 110px; /* cap tall images */
  height: auto;      /* preserve aspect ratio */
  object-fit: contain;
  display: block;
  background: #f6f7f8; /* optional letterbox backdrop */
  border-radius: 8px;
}
    .Lab-News > article.no-image::before { display: none; }
  }
</style>

<div class="Lab-News">

  <!-- Example item -->
   <article>
    <img src="{{ '/imgs/news/new_lab.JPEG' | relative_url }}" alt="Hello, new lab" loading="lazy">
    <div class="text">
      <div class="meta">Sep 2025</div>
      <h3>A New Home!</h3>
      <p>We are now fully settled into our new, bright lab space and look forward to exciting science in the new lab!</p>
    </div>
  </article>

  <article>
    <img src="{{ '/imgs/news/old_lab.JPG' | relative_url }}" alt="Bye old Lab" loading="lazy">
    <div class="text">
      <div class="meta">June 2025</div>
      <h3>(Almost) Packed for the Lab Move.</h3>
      <p>Our lab space renovation is wrapping up, and we are moving from our temporary home on Kinzelberg Hall’s 2nd floor to the 3rd. We will miss these bright orange colors!</p>
    </div>
  </article>

  <article>
    <img src="{{ '/imgs/news/pccw.png' | relative_url }}" alt="pccw" loading="lazy">
    <div class="text">
      <div class="meta">May 2025</div>
      <h3>Affinito-Stewart Grant!</h3>
      <p>Thrilled to receive grant support from Cornell PCCW to launch a pilot project in the lab.</p>
    </div>
  </article>

  <!-- Example item with link -->
  <!-- <article>
    <img src="{{ '/imgs/news/grant.jpg' | relative_url }}" alt="Grant award" loading="lazy">
    <div class="text">
      <div class="meta">May 2025</div>
      <h3>New award to map brain→pancreas control points</h3>
      <p>Thrilled to receive support from .
        <a href="https://example.org/press-release">Press release</a>.
      </p>
    </div>
  </article> -->

 <!-- Example without image -->
  <!-- <article class="no-image">
    <div class="text">
      <div class="meta">May 2025</div>
      <h3>Affinito-Stewart Grant!</h3>
      <p>Thrilled to receive grant support from Cornell PCCW to launch a pilot project in the lab.</p>
    </div>
  </article> -->

  <!-- Example without image -->
  <article class="no-image">
    <div class="text">
      <div class="meta">Jan. 2024</div>
      <h3>Welcome to the Y. Wang lab. </h3>
      <p>The Y. Wang Lab has opened its doors on the 2nd floor of Kinzelberg Hall.</p>
    </div>
  </article>

  <!-- Duplicate <article> blocks as needed -->
</div>