---
layout: page
title: Evaluation
permalink: /evaluation/
---
<hr>
<br>
{% for task in site.data.tasks %}
<div>
  <h2>{{ task.name }} Server</h2>
  <p>{{ task.server }}</p>
</div>
{% endfor %}

<h2>Leaderboard</h2>
<h4>Task1</h4>
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Name1</td>
      <td>Date1</td>
    </tr>
  </tbody>
</table>
