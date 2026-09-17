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
  gap: 1.4rem;
  margin: 1.5rem 0 2.1rem 0;
}

.pub-thumb {
  flex: 0 0 170px;
}

.pub-thumb img {
  width: 170px;
  height: 115px;
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
  margin-top: 0.4rem !important;
}

.equal-note {
  font-size: 0.9em;
}

@media (max-width: 700px) {
  .pub-entry {
    align-items: flex-start;
    gap: 1rem;
  }

  .pub-thumb {
    flex: 0 0 125px;
  }

  .pub-thumb img {
    width: 125px;
    height: 90px;
  }
}

@media (max-width: 500px) {
  .pub-entry {
    display: block;
  }

  .pub-thumb {
    margin-bottom: 0.8rem;
  }

  .pub-thumb img {
    width: 170px;
    height: 115px;
  }
}
</style>


Publications
====

<div class="pub-entry">

  <div class="pub-thumb">
    <a href="PSTAT_LINK">
      <img src="{{ '/images/fig_pstat.png' | relative_url }}"
           alt="P-StaT framework">
    </a>
  </div>

  <div class="pub-text">
    <p>
      <strong>Samantha Dies</strong>, Courtney Maynard, Germans Savcisens,
      and Tina Eliassi-Rad.
      <em>Epistemic Familiarity is Associated With Belief Stability in Large Language Models.</em>
      <em>Findings of the Association for Computational Linguistics: EMNLP 2026</em>,
      forthcoming.
    </p>
    <p class="pub-links">
      [<a href="PSTAT_LINK">png</a>]
    </p>
  </div>

</div>


<div class="pub-entry">

  <div class="pub-thumb">
    <a href="HYPERJUSTICE_LINK">
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
      [<a href="HYPERJUSTICE_LINK">png</a>]
    </p>
  </div>

</div>


<div class="pub-entry">

  <div class="pub-thumb">
    <a href="FACULTY_HIRING_LINK">
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
      [<a href="FACULTY_HIRING_LINK">png</a>]
    </p>
  </div>

</div>

<p class="equal-note">* Equal contribution.</p>


Preprints
====

<div class="pub-entry">

  <div class="pub-thumb">
    <a href="COEVOLVE_LINK">
      <img src="{{ '/images/fig_coevolve.png' | relative_url }}"
           alt="Belief coevolution in a network of large language models">
    </a>
  </div>

  <div class="pub-text">
    <p>
      Germans Savcisens, <strong>Samantha Dies</strong>, Courtney Maynard,
      and Tina Eliassi-Rad.
      <em>Belief Coevolution in a Social Network of Generalist and Specialist Large Language Models.</em>
    </p>
    <p class="pub-links">
      [<a href="COEVOLVE_LINK">png</a>]
    </p>
  </div>

</div>


<div class="pub-entry">

  <div class="pub-thumb">
    <a href="ETHICS_LINK">
      <img src="{{ '/images/fig_ethics.png' | relative_url }}"
           alt="Coauthorship and citation networks in complexity science ethics">
    </a>
  </div>

  <div class="pub-text">
    <p>
      Olumide Adisa, Enio Alterman Blay, Yasaman Asgari, Gabriele Di Bona,
      <strong>Samantha Dies</strong>, Ana Maria Jaramillo, Paulo H. Resende,
      and Ana Maria de Sousa Leitao.
      <em>The Overlooked Need for Ethics in Complexity Science: Why it Matters.</em>
      (2024).
    </p>
    <p class="pub-links">
      [<a href="ETHICS_LINK">png</a>]
    </p>
  </div>

</div>
