---
layout: default
---

# Check Point Training Labs

<a class="cta" href="lab-preparation/">
  <strong>Lab preparation checklist</strong>
  <span>Start here: work through this before the first lab, whatever your course.</span>
</a>

## Courses

<p class="lead">Course-specific resources, including lab topology maps.</p>

<div class="course-grid">
{% for c in site.data.courses %}
  <a class="course-card" href="{{ c.slug }}/"><strong>{{ c.code }}</strong>{% if c.name != "" %}<span>{{ c.name }}</span>{% endif %}</a>
{% endfor %}
</div>

<p class="muted">General help: <a href="common/">Skillable registration, keyboard, timezone and navigation</a>.</p>
