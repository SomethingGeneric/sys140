# its-work
Notes and journals from ITS classes
<ul>
  {% for item in site.pages %}
    <li {% if page.url contains item.url %}class="active"{% endif %}><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
</ul>
