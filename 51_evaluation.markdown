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
      <td>Fangyi Chen</td>
      <td>12/12/2021</td>
    </tr>
     <tr>
      <td>Fangyi Chen1234</td>
      <td>12/12/2021</td>
    </tr>
  </tbody>
</table>
