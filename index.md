---

---

{% for collection in site.collections %}
  {% if collection.label != "posts" and collection.steop == false %}
  {{ collection.vo_name }}:
  <ul>
    {% for page in collection.docs %}
      <li><a href="{{ page.url | relative_url }}">{{ page.title }} - ({{ page.vortragender }} - {{ page.semester }})</a></li>
    {% endfor %}
  </ul>
  {% endif %}
{% endfor %}
SteOP Psychologie:
<ul>
<li><a href="{{ "steop" | relative_url }}">Module A1 und A2 (2020W)</a>
</li>
</ul>
