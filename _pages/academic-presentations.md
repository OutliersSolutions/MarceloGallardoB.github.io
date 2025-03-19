---
layout: pages
title: "Academic Presentations"
permalink: /academic-presentation/
---
{% include publications.html %}

<style>
  .content-academic-presentations {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    text-align: left;
  }
  .content-academic-presentations h2 {
    margin-bottom: 25px;
  }
  .presentation-item {
    margin-bottom: 20px;
  }
  .presentation-item p {
    margin: 5px 0;
  }
  details {
    margin-top: 10px;
  }
  summary {
    cursor: pointer;
  }
  a {
    text-decoration: none;
    color: inherit;
  }
</style>

<div class="content-academic-presentations">
  <h2>Academic Presentations</h2>

  <div class="presentation-item">
    <p style="color: #003d90"><strong>Optimal Transport and Some Other Mathematical Models with Applications in Economics</strong></p>
    <p><em>For ADEEM Winter School</em></p>
    <p><a href="{{ '/files/books-and-papers/adeem.pdf' | relative_url }}" target="_blank">Certification</a></p>
    <details>
      <summary>
        Summary | <a style="color: #003d90" href="{{ '/files/books-and-papers/slides_ot.pdf' | relative_url }}" target="_blank">Slides</a>
      </summary>
      <p>
        Seminar for the Winter School 2023 organized by the Association of Students and Alumni of Mathematics and the Association of Physics Students of PUCP.<br>
        Based on Alfred Galichon's book, <em>Optimal Transport Methods in Economics</em>, and his co-authored paper <em>SISTA: Learning Optimal Transport Costs Under Sparsity Constraints</em>.
      </p>
    </details>
  </div>

  <div class="presentation-item">
    <p style="color: #003d90">
      <strong>
        On the Conference Paper 
        <a href="https://eml.berkeley.edu/~fechenique/published/sperner.pdf" target="_blank">
          Finding a Walrasian Equilibrium is Easy for a Fixed Number of Agents
        </a>
        by 
        <a href="https://eml.berkeley.edu/~fechenique/index.html" target="_blank">F. Echenique</a>
        and 
        <a href="https://adamwierman.com/" target="_blank">A. Wierman</a>
      </strong>
    </p>
    <p><em>For Numerical Analysis, Mathematics PUCP</em></p>
    <details>
      <summary>
        Summary | <a style="color: #003d90" href="{{ '/files/books-and-papers/walrasian_equilibrium_echenique_wierman.pdf' | relative_url }}" target="_blank">Slides</a>
      </summary>
      <p>
        As part of the midterm assignment for the course <em>Numerical Analysis (2024-2)</em>, I presented the article <em>Finding a Walrasian Equilibrium is Easy for a Finite Number of Agents</em> by Federico Echenique and Adam Wierman.<br>
        The article introduces an algorithm that computes, in polynomial time with respect to the number of goods and a parameter epsilon, an epsilon-Walrasian equilibrium.<br>
        In my presentation, I delved into some of the technical details and provided a comprehensive introduction for those unfamiliar with general equilibrium theory.<br>
        I also proposed some insights on one of the lemmas discussed in the article.
      </p>
    </details>
  </div>
</div>
