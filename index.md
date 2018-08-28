---
---

<div class="hero">
  <h1 class="hero__title">SoM explores the extrodinary stories of white women in interracial relationships from 1940-2000. These previously ignored histories give a fresh insight into our social attitudes to race relations in the UK.</h1>

  <a href="/our-story" class="hero__btn btn">Our story</a>

  <div class="hero__caption">
    <strong>Photo:</strong> Mrs Ada next to her husband Alfred Lawrence (Anya) in his circus outfit in the 1930s.<br>
    Courtesy of their daughter Coca Clarke.
  </div>
</div>

<h2>We are still gathering interviews for the 2018 launch. Below are some of the women whose chapters have been completed.</h2>

<hr>

<ul class="women">
  {% for woman in site.data.women %}
    <li class="woman">
      <h3 class="woman__name">{{ woman.name }}</h3>
      <p class="woman__dob">{{ woman.dob }}</p>
      <p class="woman__caption">{{ woman.caption }}</p>
    </li>
  {% endfor %}
</ul>
