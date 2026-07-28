---
title: "Curriculum Vitae"
permalink: /cv/
layout: single
classes: wide
author_profile: true
---

<!--
  Generated content: this page renders _data/cv.yml, which is written by
  scripts/publish_web.py in the private resume-toolkit repo. To change anything
  below, edit profile/master_profile.md there and re-run the script — hand edits
  here are overwritten on the next sync.
-->

[Download full CV (PDF)](/assets/CV_YuhangZhang.pdf){: .btn .btn--primary }

## Education

{% for e in site.data.cv.education %}
**{{ e.degree }}**  
{{ e.institution }}{% if e.location %}, {{ e.location }}{% endif %} · {{ e.period }}  
{% if e.advisor %}Advisor: {{ e.advisor }}  
{% endif %}{% if e.dissertation %}Dissertation: *{{ e.dissertation }}*  
{% endif %}{% if e.thesis %}Thesis: *{{ e.thesis }}*  
{% endif %}
{% endfor %}

## Awards & Honors

{% for a in site.data.cv.awards %}- {{ a }}
{% endfor %}

## Academic Service

{% for group in site.data.cv.service %}
### {{ group.title }}

{% for item in group.items %}- {{ item.text }}
{% if item.sub %}{% for s in item.sub %}  - {{ s }}
{% endfor %}{% endif %}{% endfor %}
{% endfor %}

## Conference Presentations

Presentations without published proceedings. Peer-reviewed papers are on the
[Publications](/publications/) page.

{% for p in site.data.cv.presentations %}- "{{ p.title }}"
{% for v in p.venues %}  - {{ v }}
{% endfor %}{% endfor %}

---

*Last updated {{ site.data.cv.generated | date: "%B %-d, %Y" }}.*
