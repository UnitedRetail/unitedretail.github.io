---
layout: page
title: Unitail-Det
permalink: /Unitail-Det/
brief: Detecting Products as Quadrilaterals
Image: All images are stored in 'JPG' format.  They can be used for academic purposes only.

downloadsList:
- {
  description: "In this demo site, we only provides a small group of demo images",
  url: "https://github.com/eg4000/SKU110K_CVPR19"
  }
---

<h3>{{ page.brief }}</h3>
<hr>
<div>
  <h2>Image Source and Usage License</h2>
  <div class="Image">
    <p>{{ page.Image }}</p>
  </div>
</div>
<div>
  <h2>Downloads</h2>
  <ul>
    {% for download in page.downloadsList %}
    <li>
      <h4>{{ download.description }} <br><a href="{{download.url}}">{{download.url}}</a></h4>
    </li>
    {% endfor %}
  </ul>
  <p>{{ page.downloads }}</p>
</div>
