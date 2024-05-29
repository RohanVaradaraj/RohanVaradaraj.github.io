---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<div class="wordwrap">You can also find my articles on <a href="https://ui.adsabs.harvard.edu/search/filter_author_facet_hier_fq_author=OR&filter_author_facet_hier_fq_author=author_facet_hier%3A%221%2FVaradaraj%2C%20R%2FVaradaraj%2C%20Rohan%20G%22&filter_author_facet_hier_fq_author=author_facet_hier%3A%221%2FVaradaraj%2C%20R%2FVaradaraj%2C%20R%20%20G%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq=%7B!type%3Daqp%20v%3D%24fq_author%7D&fq_author=(author_facet_hier%3A%221%2FVaradaraj%2C%20R%2FVaradaraj%2C%20Rohan%20G%22%20OR%20author_facet_hier%3A%221%2FVaradaraj%2C%20R%2FVaradaraj%2C%20R%20%20G%22)&fq_database=(database%3Aastronomy%20OR%20database%3Aphysics)&q=%20author%3A%22Varadaraj%2C%20R.%20G.%22&sort=date%20desc%2C%20bibcode%20desc&p_=0"
">NASA ADS</a>.</div>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
