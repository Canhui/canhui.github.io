---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}





Some technical projects
======

* Throughput and Latency Modeling on a Local Cluster (Hong Kong Base) and an Alibaba Cloud Cluster (Guangzhou Base), 2020/01-2023/07

  * Hong Kong Baptist University

  * Output: Enclosed in my Ph.D. Thesis

    