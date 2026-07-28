---
title: "Publications"
permalink: /publications/
layout: single
classes: wide
author_profile: true
---

<!--
  Generated content: this page renders _data/publications.yml, which is written
  by scripts/publish_web.py in the private resume-toolkit repo. To add or change
  a publication, edit profile/master_profile.md there and re-run the script —
  do not hand-edit the list here, it will be overwritten on the next sync.
-->

{% for section in site.data.publications.sections %}
## {{ section.title }}

{% for pub in section.items %}
### {{ pub.title }}

{{ pub.authors }} ({{ pub.year }}).  
{% if pub.status %}{{ pub.status }} {% endif %}{% if pub.venue %}*{{ pub.venue }}*{% endif %}{% if pub.detail %}, {{ pub.detail }}{% endif %}.  
{% if pub.award %}🏆 **{{ pub.award }}**  
{% endif %}{% if pub.doi_url %}🔗 [DOI: {{ pub.doi_id }}]({{ pub.doi_url }})  
{% endif %}
{% endfor %}
{% endfor %}

---

*Last updated {{ site.data.publications.generated | date: "%B %-d, %Y" }}. A full list is also in the [CV](/assets/CV_YuhangZhang.pdf).*
