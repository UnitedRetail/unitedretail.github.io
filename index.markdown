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
        <br>
        All images and their associated annotations in Unitail can be used for academic purposes only.
    </p>
</div>

<img src='./assets/images/fig-unitailoverview.jpg'>


<div>
  <h2>Citation</h2>
  <pre>
    <code>
        @InProceedings{Chen2022unitail,
        author = {Chen, Fangyi and Zhang, Han and Li, Zaiwang and Dou, Jiachen and Mo, Shentong and Chen, Hao and Zhang, Yongxin and Ahmed, Uzair and Zhu, Chenchen and Savvides, Marios},
        title = {Unitail: Detecting, Reading, and Matching in Retail Scene},
        journal = {European Conference on Computer Vision},
        year = {2022}
        }
    </code>
  </pre>
</div>