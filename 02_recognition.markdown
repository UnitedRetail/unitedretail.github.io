---
layout: page
title: Unitail-OCR
permalink: /Unitail-OCR/
brief: Reading Enhanced Product Matching
description: The Unitail-OCR consists of an open-set gallery and a testing suite 
              that operate product matching inside.  
              All known categories are registered in the gallery. 
              In case of a query product, the matching algorithms find the top ranked category in the gallery.
              The gallery contains 1454 fine-grained and one-shot product categories. 
              Among these products, 10709 text regions and 7565 legible text transcriptions (words) are annotated. 
              This enables the gallery to act as the training source and the matching reference.
              <br><br>
              The testing suite contains four components
                <br>
                (1) 3012 products labeled with 18972 text regions for text detection.
                <br>
                (2) Among the pre-localized text regions, 13416 legible word-level transcriptions for text recognition.
                <br>
                (3) 10k product samples from the 1454 categories for general evaluation on product matching.
                <br>
                (4) From the 10k products, we select 2.4k fine-grained samples (visually similar for humans) for hard-example evaluation on product matching.

downloadsList:
- {
  description: "Unitail-OCR dataset",
  urlname: "Google Drive",
  url: "https://drive.google.com/file/d/1quJZdXXtzJ4VyprivwQIa3ldHCua_Ayq/view?usp=sharing"
  }
---
{% include datasetPage.html %}
