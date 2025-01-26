---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
   {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship

<!-- Note:
1. To control the right margin of publications page, you can go to _sass/_archive.scss. Find .list__item, and adjust the @include breakpoint($x-large) {
    padding-right: 5em; }. -->