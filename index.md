---
---

<div class="hero__wrapper">
  <div class="hero">
    <div class="content">
      <h1 class="hero__title narrow">SoM explores the extrodinary stories of white women in interracial relationships from 1940-2000. These previously ignored histories give a fresh insight into our social attitudes to race relations in the UK.</h1>
      <!-- <a href="/our-story" class="hero__btn btn">Our story</a> -->
    </div>
  </div>
</div>
<div class="hero__caption">
  <div class="content">
    <div class="hero__caption-text">
      <strong>Photo:</strong> Mrs Ada next to her husband Alfred Lawrence (Anya) in his circus outfit in the 1930s.<br> Courtesy of their daughter Coca Clarke.
    </div>
  </div>
</div>
<div class="content">
  <h2 class="narrow">We are still gathering interviews for the 2018 launch. Below are some of the women whose chapters have been completed.</h2>
</div>
<hr>
<div class="content">
  <ul class="women reset">
    {% for woman in site.data.women %}
      <li class="woman">
        <h3 class="woman__name">{{ woman.name }}</h3>
        <div class="woman__dob">{{ woman.dob }}</div>
        <img src="/assets/women/{{ woman.photo }}" class="woman__photo" alt="A photo of {{ woman.name }}">
        <div class="woman__caption">{{ woman.caption }}</div>
      </li>
    {% endfor %}
  </ul>
</div>
