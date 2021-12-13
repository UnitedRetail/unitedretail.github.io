---
layout: page
title: People
permalink: /people/
---
<hr>
<br>
<table class="people">
  <tr>
  {% for person in site.data.people %}
    {% assign remainder = forloop.index | modulo:3 %}
    <td>
      <a href="{{ person.url }}" target="_blank">
        <img src="{{site.baseurl}}/assets/images/people/{{ person.picture }}">
      </a>
      <h4>{{ person.name }}</h4>
      <p>{{ person.title }}</p>
    </td>
    {% if remainder == 0 %}
      </tr>
      <tr>
    {% endif %}
  {% endfor %}
  </tr>
</table>

