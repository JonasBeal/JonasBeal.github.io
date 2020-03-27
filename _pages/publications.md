---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
 -->

You can also have a look at
<a href="https://scholar.google.fr/citations?user=iwIlGmUAAAAJ&hl=en">
    <i class="ai ai-google-scholar" aria-hidden="true"></i>Scholar
</a>

<h2  class="pubyear">Preprints</h2>
{% bibliography -f beal --query @unpublished%}

<h2  class="pubyear">Journal papers</h2>
{% bibliography -f beal --query @article%}

<h2  class="pubyear">Conference papers</h2>
{% bibliography -f beal --query @inproceedings%}

<h2  class="pubyear">Workshop papers</h2>
{% bibliography -f beal --query @misc%}
