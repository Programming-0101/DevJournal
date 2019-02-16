# Articles

Here's my current list of articles. These are base off of {{site.baseurl }}.

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{site.baseurl}}{{ page.url }}">{{ page.title }}</a>
      <pre>
      {{ page }}
      </pre>
    </li>
  {% endfor %}
</ul>
