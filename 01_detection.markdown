---
layout: page
title: Unitail-Det
permalink: /Unitail-Det/
brief: Detecting Products as Quadrilaterals
Image: All images are stored in 'JPG' format.  They can be used for academic purposes only.
Annos: Each product is annotated with with a quadrilateral (QUAD).
        A QUAD refers to 4 points with 8 degrees of freedom 
        (x1, y1, x2, y2, x3, y3, x4, y4)
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
  <h3>Image Source and Usage License</h3>
  <div class="Image">
    <p>{{ page.Image }}</p>
  </div>
</div>
<div>
  <h3>Annotations</h3>
  <div class="Annos">
    <p>{{ page.Annos }}</p>
  </div>
</div>
<div>
  <h3>Downloads</h3>
  <ul>
    {% for download in page.downloadsList %}
    <li>
      <h4>{{ download.description }} <br><a href="{{download.url}}">{{download.urlname}}</a></h4>
    </li>
    {% endfor %}
  </ul>
  <p>{{ page.downloads }}</p>
</div>
