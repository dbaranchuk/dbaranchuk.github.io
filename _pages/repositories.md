---
layout: page
permalink: /repositories/
title: Code
description:
nav: true
nav_order: 4
---

<p class="repo-intro">
  Open-source releases accompanying the papers above. More at
  <a href="https://github.com/dbaranchuk">github.com/dbaranchuk</a>.
</p>

<div class="repo-grid">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repo=repo %}
  {% endfor %}
</div>
