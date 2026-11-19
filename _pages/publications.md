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

.wip-entry {
  margin: 1.25rem 0 1.7rem 0;
}

.wip-entry p {
  margin: 0;
}

.wip-note {
  font-size: 0.9em;
  color: #666;
  margin: 0.3rem 0 1.4rem 0;
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
<p class="equal-note">* Equal contribution.</p>

<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://doi.org/10.18653/2026.findings-emnlp.532"
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
      <em>Epistemic familiarity is associated with belief stability in large language models.</em>
      <em>Findings of the Association for Computational Linguistics: EMNLP 2026</em>,
      11150–11175 (2026).
    </p>
    <p class="pub-links">
      [<a href="https://doi.org/10.18653/2026.findings-emnlp.532"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>


<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://doi.org/10.1140/epjds/s13688-026-00638-1"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_faculty_hiring.png' | relative_url }}"
           alt="Temporal coauthorship network modeling pipeline">
    </a>
  </div>

  <div class="pub-text">
    <p>
      <strong>Samantha Dies</strong>, David M. Liu, and Tina Eliassi-Rad.
      <em>Forecasting faculty placement from patterns in coauthorship networks.</em>
      <em>EPJ Data Science</em>, 15, Article 41 (2026).
    </p>
    <p class="pub-links">
      [<a href="https://doi.org/10.1140/epjds/s13688-026-00638-1"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>


<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://doi.org/10.1038/s42005-025-02445-y"
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
      <em>Communications Physics</em>, 9, Article 13 (2026).
    </p>
    <p class="pub-links">
      [<a href="https://doi.org/10.1038/s42005-025-02445-y"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>


Preprints
====

<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://arxiv.org/abs/2609.34158"
       target="_blank"
       rel="noopener noreferrer">
      <img src="{{ '/images/fig_lockean_thesis.png' | relative_url }}"
           alt="Toward a graded measure of belief stability in large language models">
    </a>
  </div>

  <div class="pub-text">
    <p>
      <strong>Samantha Dies</strong>, Branden Fitelson,
      and Tina Eliassi-Rad.
      <em>Toward a graded measure of belief stability in large language models.</em>
      arXiv:2609.34158 (2026).
    </p>
    <p class="pub-links">
      [<a href="https://arxiv.org/abs/2609.34158"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>

<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://arxiv.org/abs/2607.27512"
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
      <em>Belief coevolution in a social network of generalist and specialist large language models.</em>
      arXiv:2607.27512 (2026).
    </p>
    <p class="pub-links">
      [<a href="https://arxiv.org/abs/2607.27512"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>

<div class="pub-entry">

  <div class="pub-thumb">
    <a href="https://arxiv.org/abs/2409.02002"
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
      <em>The overlooked need for ethics in complexity science: Why it matters.</em>
      arXiv:2409.02002 (2024).
    </p>
    <p class="pub-links">
      [<a href="https://arxiv.org/abs/2409.02002"
          target="_blank"
          rel="noopener noreferrer">paper</a>]
    </p>
  </div>

</div>
