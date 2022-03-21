---
layout: page
title: Unitail-Det
permalink: /Unitail-Det/
brief: Detecting Products as Quadrilaterals
Image: Images are collected from two sources to support product detection.
        The training, validation, and origin-domain testing sets are collected 
        from the <a href="https://github.com/eg4000/SKU110K_CVPR19">SKU110k</a>.
        The cross-domain testing set is pictured from five chain stores. 
        <br><br>
        Each product is annotated with a quadrilateral style bounding box. It refers to 4 points 
        with 8 degrees of freedom (x1, y1, x2, y2, x3, y3, x4, y4).
        <br><br>
        <img src='../assets/images/det.jpg' >

downloadsList:
- {
  description: "In this demo site, we only provides a small group of demo images",
  urlname: "google drive",
  url: "https://drive.google.com/file/d/1hjpFtPA5rx8ydR6OW4OtMhWMzaDGZi15/view?usp=sharing"
  }
---

<h3>{{ page.brief }}</h3>
<hr>
<div>
  <h2>Description</h2>
  <div class="Image">
    <p>{{ page.Image }}</p>
  </div>
</div>
<div>
  <h2>Downloads</h2>
  <ul>
    {% for download in page.downloadsList %}
    <li>
      <h4>{{ download.description }} <br><a href="{{download.url}}">{{download.urlname}}</a></h4>
    </li>
    {% endfor %}
  </ul>
  <p>{{ page.downloads }}</p>
</div>
