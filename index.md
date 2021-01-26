---

---

{% for collection in site.collections %}
  {% if collection.label != "posts"  %}
  {{ collection.vo_name }}:
  <ul>
    {% for page in collection.docs %}
      <li><a href="{{ page.url | relative_url }}">{{ page.title }} - ({{ page.date | date_to_string }} - {{ page.vortragender }})</a></li>
    {% endfor %}
  </ul>
  {% endif %}
{% endfor %}
