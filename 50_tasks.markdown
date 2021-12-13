---
layout: page
title: Tasks
permalink: /tasks/
---
<hr>
<br>
{% for task in site.data.tasks %}
<div>
  <h2>{{ task.name }}</h2>
  <p>{{ task.content }}</p>
</div>
{% endfor %}
