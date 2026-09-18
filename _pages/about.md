---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.selected-work {
  margin-top: 2.5rem;
}

.selected-work-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
  margin-top: 1.3rem;
}

.work-card {
  text-align: left;
}

.work-card img {
  width: 100%;
  aspect-ratio: 15 / 13;
  object-fit: contain;
  display: block;
  margin-bottom: 0.8rem;
}

.work-title {
  font-weight: 700;
  line-height: 1.35;
  margin-bottom: 0.35rem;
}

.work-meta {
  font-size: 0.95em;
  color: #666;
  margin-bottom: 0.35rem;
}

.work-link {
  font-size: 0.95em;
}

.all-publications {
  margin-top: 1.5rem;
}

@media (max-width: 800px) {
  .selected-work-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }

  .work-card {
    max-width: 450px;
  }
}
</style>


I am a fifth-year computer science Ph.D. candidate at Northeastern University in [Khoury College](https://www.khoury.northeastern.edu/) affiliated with the [Network Science Institute](https://www.networkscienceinstitute.org/). I received my M.S. in Computer Science from Northeastern University en route to the Ph.D. in 2026. I am advised by [Professor Tina Eliassi-Rad](http://eliassi.org/). My research lies at the intersection of machine learning, network science, and AI ethics, with a current focus on characterizing the structure, stability, and reliability of beliefs in large language models and how they change across semantic and social contexts.

I graduated from Georgetown University in 2022 with a B.S. in Mathematics and Computer Science with a minor in Spanish. As an undergraduate, I was advised by [Professor Lisa Singh](https://people.cs.georgetown.edu/~singh/) as a research scholar at the McCourt School of Public Policy's [Massive Data Institute](https://mdi.georgetown.edu/).


<div class="selected-work">

<h2>Selected Work</h2>

<div class="selected-work-grid">

  <div class="work-card">
    <a href="https://arxiv.org/pdf/2511.19166"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_pstat.png' | relative_url }}"
           alt="P-StaT framework">
    </a>

    <div class="work-title">
      Epistemic Familiarity is Associated With Belief Stability in Large Language Models
    </div>

    <div class="work-meta">
      Findings of the Association for Computational Linguistics: EMNLP, 2026
    </div>

    <div class="work-link">
      [<a href="https://arxiv.org/pdf/2511.19166"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </div>
  </div>


  <div class="work-card">
    <a href="https://link.springer.com/article/10.1140/epjds/s13688-026-00638-1"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_faculty_hiring.png' | relative_url }}"
           alt="Temporal coauthorship network modeling pipeline">
    </a>

    <div class="work-title">
      Forecasting Faculty Placement from Patterns in Co-authorship Networks
    </div>

    <div class="work-meta">
      EPJ Data Science, 2026
    </div>

    <div class="work-link">
      [<a href="https://link.springer.com/article/10.1140/epjds/s13688-026-00638-1"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </div>
  </div>


  <div class="work-card">
    <a href="https://www.nature.com/articles/s42005-025-02445-y"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_hyperjustice.png' | relative_url }}"
           alt="Higher-order interactions and information access">
    </a>

    <div class="work-title">
      Effects of Higher-Order Interactions and Homophily on Information Access Inequality
    </div>

    <div class="work-meta">
      Communications Physics, 2026
    </div>

    <div class="work-link">
      [<a href="https://www.nature.com/articles/s42005-025-02445-y"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </div>
  </div>

</div>

<div class="all-publications">
  <a href="{{ '/publications/' | relative_url }}">View all publications →</a>
</div>

</div>
