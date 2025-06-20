---
permalink: /
# title: "This is Qingeng Jin's academic page."
layout: archive
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<h1> This is Jin's academic page. </h1>
Welcome to my academic page, feel free to explore!
<br/>
<br/>

{% include base_path %}
{% for post in site.posts %}
  <hr style="border: none; border-top: 1px solid #eee; width: 90%; margin: 24px 0;" />
  {% include archive-single.html %}
{% endfor %}

