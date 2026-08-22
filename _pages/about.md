---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<section class="page__content" style="max-width: 760px; margin: auto; font-size: 1.1rem; line-height: 1.8;">
  <h1 style="font-size: 2.4rem; font-weight: 700;">Hi, I'm Kelsey 👋</h1>

  <p>
    I’m currently a <strong>postdoctoral researcher in geospatial AI</strong>, holding a joint appointment at 
    Arizona State University under 
    <a href="https://hannah-rae.github.io/" target="_blank">Hannah Kerner</a> and the 
    University of Cape Town at the Climate Risk Lab with 
    <a href="https://acdi.uct.ac.za/contacts/christopher-trisos" target="_blank">Chris Trisos</a>.
    I completed my PhD at the <a href="https://www.ox.ac.uk/" target="_blank">University of Oxford</a> as part of 
    <a href="https://oatml.cs.ox.ac.uk/" target="_blank">OATML</a>, supervised by Professor Yarin Gal in the Autonomous Intelligent Machines and Systems Doctoral Training Program.
  </p>

  <p>
    
  </p>

  <p>
    My research is rooted in building AI tools for Earth Sciences that support scientific understanding. I have worked with NASA, ESA, and UNICEF on building AI tools to support climate modeling, disaster preparedness and humanitarian capacity building.
  </p>

  <p>
    Prior to my PhD, I was a Space Systems Engineer in Satellite Operations at Planet, operating the world's largest EO constellation! I completed my Masters in Electrical and Computer Engineering and the University of Western Ontario and my Bachelors in Aerospace Engineering: Space Systems Design at Carleton University.
  </p>

  <h2 style="font-size: 1.6rem; font-weight: 700; margin-top: 2.5rem; padding-bottom: 0.4rem; border-bottom: 1px solid var(--global-border-color);">News 📣</h2>

  <ul class="news-list">
    {% for item in site.data.news %}
      <li class="news-item">
        <span class="news-date">{{ item.date }}</span>
        <span class="news-text">{{ item.text }}</span>
      </li>
    {% endfor %}
  </ul>
</section>

<style>
  .news-list {
    list-style: none;
    margin: 1.2rem 0 0;
    padding: 0;
  }

  .news-item {
    display: flex;
    align-items: baseline;
    gap: 1rem;
    padding: 0.6rem 0;
    border-bottom: 1px solid var(--global-border-color);
  }

  .news-item:last-child {
    border-bottom: none;
  }

  .news-date {
    flex: 0 0 9.5rem;
    font-size: 0.85em;
    font-weight: 700;
    letter-spacing: 0.02em;
    text-transform: uppercase;
    color: var(--global-text-color);
    opacity: 0.8;
  }

  .news-text {
    flex: 1 1 auto;
  }

  @media (max-width: 600px) {
    .news-item {
      display: block;
    }

    .news-date {
      display: block;
      margin-bottom: 0.15rem;
    }
  }
</style>
