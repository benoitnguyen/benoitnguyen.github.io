---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% assign pubjl = site.publications | where: "iswp", false %} {% assign pubwp = site.publications | where: "iswp", true %}

<!---  
{% if author.googlescholar %}
% You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% include base_path %}
--->
<!--- 
### Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% for post in site.wp reversed %}
  {% include archive-single.html %}
{% endfor %}
--->

### Publications
***
{% for post in pubjl reversed%} {% include archive-single.html %} {% endfor %}

### Working papers
***
{% for post in pubwp reversed%} {% include archive-single.html %} {% endfor %}
