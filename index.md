---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<script
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript">
</script>

 <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}\{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>