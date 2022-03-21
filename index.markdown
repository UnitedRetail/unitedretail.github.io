---
layout: home
---
<div class="background">
  <div class="transbox">
    <h1>Unitail</h1>
    <h3>The United Retail Datasets and Challenges for Detecting, Reading, and Matching in Retail Scene</h3>
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
    <p>The United Retail Datasets (Unitail) is a large-scale benchmark of 
        basic visual tasks on products that challenges algorithms for detecting, 
        reading, and matching. It offers the Unitial-Det, with 1.8M quadrilateral-shaped 
        instances annotated; and the Unitial-OCR, containing 1454 product categories, 30k 
        text regions, and 21k transcriptions to enable robust reading on products and 
        motivate enhanced product matching.  
    </p>
</div>

<img src='./assets/images/fig-unitailoverview.jpg'>


<div>
  <h2>Citation</h2>
  <pre>
    <code>
    </code>
  </pre>
</div>