---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from: 
  - /publication/
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<style>
  .pub-box {
      display: block;
      width: 100%;
      border: 2px solid #ccc; /* 边框颜色和粗细 */
      border-radius: 10px; /* 圆角半径 */
      margin: 15px 0;
      padding: 10px; /* 内边距 */
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      background-color: #f9f9f9;
      font-size: 14px; /* Adjust font size */
      line-height: 1.2; /* Adjust line height */
    }
  .pub-box h3 {
    margin-top: 0;
    font-size: 16px; /* Adjust font size for heading */
    line-height: 1.2; /* Adjust line height for heading */
  }
</style>

<body>
  <div class="pub-box">
    <h3>Fast-scBatch: Batch Effect Correction Using Neural Network-Driven Distance Matrix Adjustment</h3>
    <p><b>DOI: </b><a href="https://doi.org/10.1145/3698587.3701383">https://doi.org/10.1145/3698587.3701383</p>
    <p><b>Citation: </b>Chen, F., Tian, L., Fei, T., & Yu, T. (2024, November). Fast-scBatch: Batch Effect Correction Using Neural Network-Driven Distance Matrix Adjustment. In Proceedings of the 15th ACM International Conference on Bioinformatics, Computational Biology and Health Informatics (pp. 1-6).</p>
  </div>
</body>

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
