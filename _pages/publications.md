---
layout: page
permalink: /publications/
title: Publications
description: Peer-reviewed publications
nav: true
nav_order: 1
---

<div class="publications publications-badge-list publications-clean-list">
  {% for group in site.data.publications %}
    <section class="publication-year-group">
      <h2 class="bibliography publication-year-heading">{{ group.year }}</h2>
      <div class="publication-year-rule"></div>
      <ol class="bibliography publication-items">
        {% for pub in group.items %}
          <li class="publication-item">
            <div class="pub-entry-clean">
              <div class="pub-badge-wrap">
                <span class="pub-venue-badge">{{ pub.abbr }}</span>
              </div>
              <div class="pub-content-wrap">
                <div class="title"><a href="{{ pub.link }}" target="_blank" rel="noopener noreferrer">{{ pub.title }}</a></div>
                <div class="author">{{ pub.authors }}</div>
                <div class="periodical"><em>{{ pub.journal }}</em>, {{ pub.year }}</div>
                <div class="links pub-links">
                  {% if pub.abstract %}
                    <details class="pub-abstract">
                      <summary class="btn btn-sm z-depth-0" aria-label="Show abstract for {{ pub.title }}">ABS</summary>
                      <div class="pub-abstract-content">
                        <strong>Abstract</strong>
                        <p>{{ pub.abstract }}</p>
                      </div>
                    </details>
                  {% endif %}
                  {% if pub.bib %}<a class="btn btn-sm z-depth-0" href="{{ pub.bib | relative_url }}" target="_blank" rel="noopener noreferrer">BIB</a>{% endif %}
                  {% if pub.doi %}<a class="btn btn-sm z-depth-0" href="https://doi.org/{{ pub.doi }}" target="_blank" rel="noopener noreferrer">DOI</a>{% endif %}
                  {% if pub.pdf %}<a class="btn btn-sm z-depth-0" href="{{ pub.pdf }}" target="_blank" rel="noopener noreferrer">PDF</a>{% endif %}
                  {% if pub.doi %}<span class="dimensions-inline"><span class="__dimensions_badge_embed__" data-doi="{{ pub.doi }}" data-style="small_circle"></span></span>{% endif %}
                </div>
              </div>
            </div>
          </li>
        {% endfor %}
      </ol>
    </section>
  {% endfor %}
</div>

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
