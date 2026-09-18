---
layout: archive
# title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  <p>
    You can also find my articles on
    <u><a href="{{ author.googlescholar }}">my Google Scholar profile</a></u>.
  </p>
{% endif %}

{% include base_path %}

<style>
.pub-entry {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  margin: 1.8rem 0 2.4rem 0;
}

.pub-thumb {
  flex: 0 0 150px;
  width: 150px;
}

.pub-thumb img {
  width: 150px;
  height: 130px;
  object-fit: contain;
  display: block;
}

.pub-text {
  flex: 1;
  min-width: 0;
}

.pub-text p {
  margin: 0;
}

.pub-links {
  margin-top: 0.45rem !important;
}

.equal-note {
  font-size: 0.9em;
  margin-top: -0.5rem;
  margin-bottom: 1.5rem;
}

@media (max-width: 700px) {
  .pub-entry {
    align-items: flex-start;
    gap: 1rem;
  }

  .pub-thumb {
    flex: 0 0 120px;
    width: 120px;
  }

  .pub-thumb img {
    width: 120px;
    height: 104px;
  }
}

@media (max-width: 500px) {
  .pub-entry {
    display: block;
  }

  .pub-thumb {
    width: 150px;
    margin-bottom: 0.8rem;
  }

  .pub-thumb img {
    width: 150px;
    height: 130px;
  }
}
</style>


Publications
====

<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://arxiv.org/pdf/2511.19166"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_pstat.png' | relative_url }}"
           alt="P-StaT framework">
    </a>
  </div>

  <div class="pub-text">
    <p>
      <strong>Samantha Dies</strong>, Courtney Maynard, Germans Savcisens,
      and Tina Eliassi-Rad.
      <em>Epistemic Familiarity is Associated With Belief Stability in Large Language Models.</em>
      <em>Findings of the Association for Computational Linguistics: EMNLP</em> (2026),
      forthcoming.
    </p>
    <p class="pub-links">
      [<a href="https://arxiv.org/pdf/2511.19166"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>


<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://link.springer.com/article/10.1140/epjds/s13688-026-00638-1"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_faculty_hiring.png' | relative_url }}"
           alt="Temporal coauthorship network modeling pipeline">
    </a>
  </div>

  <div class="pub-text">
    <p>
      <strong>Samantha Dies</strong>, David Liu, and Tina Eliassi-Rad.
      <em>Forecasting Faculty Placement from Patterns in Co-authorship Networks.</em>
      <em>EPJ Data Science</em> (2026).
    </p>
    <p class="pub-links">
      [<a href="https://link.springer.com/article/10.1140/epjds/s13688-026-00638-1"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>


<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://www.nature.com/articles/s42005-025-02445-y"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_hyperjustice.png' | relative_url }}"
           alt="Higher-order interactions and information access">
    </a>
  </div>

  <div class="pub-text">
    <p>
      Moritz Laber*, <strong>Samantha Dies*</strong>, Joseph Ehlert*,
      Brennan Klein, and Tina Eliassi-Rad.
      <em>Effects of higher-order interactions and homophily on information access inequality.</em>
      <em>Communications Physics</em> (2026).
    </p>
    <p class="pub-links">
      [<a href="https://www.nature.com/articles/s42005-025-02445-y"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>


<p class="equal-note">* Equal contribution.</p>


Preprints
====

<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://arxiv.org/pdf/2607.27512"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_coevolve.png' | relative_url }}"
           alt="Belief coevolution in a network of large language models">
    </a>
  </div>

  <div class="pub-text">
    <p>
      Germans Savcisens, <strong>Samantha Dies</strong>, Courtney Maynard,
      and Tina Eliassi-Rad.
      <em>Belief Coevolution in a Social Network of Generalist and Specialist Large Language Models</em>
      (2026).
    </p>
    <p class="pub-links">
      [<a href="https://arxiv.org/pdf/2607.27512"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>


<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://arxiv.org/pdf/2409.02002"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_ethics.png' | relative_url }}"
           alt="Coauthorship and citation networks in complexity science ethics">
    </a>
  </div>

  <div class="pub-text">
    <p>
      Olumide Adisa, Enio Alterman Blay, Yasaman Asgari, Gabriele Di Bona,
      <strong>Samantha Dies</strong>, Ana Maria Jaramillo, Paulo H. Resende,
      and Ana Maria de Sousa Leitao.
      <em>The Overlooked Need for Ethics in Complexity Science: Why it Matters</em>
      (2024).
    </p>
    <p class="pub-links">
      [<a href="https://arxiv.org/pdf/2409.02002"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>
