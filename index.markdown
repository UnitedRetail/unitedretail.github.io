---
layout: home
---
<div class="background">
  <div class="transbox">
    <h1>United Retail</h1>
    <h3>United Retail Datasets and Challenges for Detecting, Matching, and Reading in Retail Scene</h3>
  </div>
</div>
<br>
<div>
  <h2>News</h2>
  <ul>
    {% for news in site.data.news %}
      <li>
        <b>[{{ news.time }}]</b>
        {{ news.content }}
      </li>
    {% endfor %}
  </ul>
</div>

<div>
  <h2>Overview</h2>
    <p>This is Unitail Overview.</p>
</div>



<div>
  <h2>Citation</h2>
  <pre>
    <code>
      This is Citation example
    </code>
  </pre>
</div>