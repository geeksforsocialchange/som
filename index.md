---
---

<section>
  <div class="hero__wrapper">
    <div class="hero">
      <div class="content">
        <h1 class="hero__title narrow">In order to reach the truth, you have got to tell the truth.</h1>
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
    <p class="h2 narrow">Strength of our Mothers documents the lives of 23 white women in interracial relationships with African and Afro-Caribbean men from the 1940s to 2000. Each women's story is told in their own voice or by their children.</p>
    <p class="btn">
      <a href="#about">Learn more about the project</a>
    </p>
  </div>
  <br>
</section>

<hr>

<section id="women">
  <div class="content">
    <br>
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
  <br><br>
</section>

<section>
  <div class="theme-2">
    <div class="content content--padding">
      <h2 class="narrow">Every picture tells a story. Here are the families' images captured over the years full of memories.</h2>
      {% include youtube.html id='YeWn7wzLJTk' %}
    </div>
    <br>
  </div>
</section>

<section id="launch">
  <div class="theme-3">
    <div class="content content--padding">
      <h1>The launch</h1>
    </div>
  </div>

  <div class="content">
    <p class="h2 narrow">Held at HOME on May 19th 2019, 140 family members joined us for the launch event.</p>

    <div class="photos">
      <img src="/assets/launch/launch1.jpg">
      <img src="/assets/launch/launch2.jpg">
      <img src="/assets/launch/launch3.jpg">
    </div>
    <br>
    <p class="narrow">The event was an afternoon of performances of poetry, dance and song and a unique one-act play scripted verbatim from all the interviews bringing the lives of the mothers live to the stage for a one-off unique performance now captured on film.</p>
    <br>
    <div class="photos">
      <img src="/assets/launch/launch4.jpg">
      <img src="/assets/launch/launch5.jpg">
      <img src="/assets/launch/launch6.jpg">
    </div>
    <br>
    <div class="narrow center">
      <!-- {% include youtube.html id='R5jIoLnL_nE' %} -->
      <h3>Launch video coming soon!</h3>
    </div>
    <br>
  </div>
</section>

<section id="book">
  <div class="theme-3">
    <div class="content content--padding">
      <h1>The book</h1>
    </div>
  </div>

  <div class="content">
    <br>
    <blockquote class="x-narrow">
      <p>This collection of stories is about love.</p>

      <p>It is also about hidden lives, sometimes painful, sometimes heart-breaking, always important. The oral histories of relationships across the divides of race and celebrates the ways in which women sustain and support their families over time.</p>

      <p>Like all hidden histories, these stories represent living knowledge that can inform future generations and can help us think differently about the experiences of children from interracial relationships.</p>
    </blockquote>
    <cite>Edited review by Kate Pahl<br> MMU Professor of Arts and Literacy</cite>
    <br><br>
    {% include book.html %}

    <p class="h2 no-bottom-margin">Strength of Our Mothers</p>
    <p class="center"><strong>ISBN</strong> 978-1-78972-129-4</p>

    <p class="btn">
      <a href="/assets/strength-of-our-mothers.pdf">Download the PDF</a>
    </p>

    <br>

    <p class="x-narrow">
      <strong>Hard copies can only be collected in person from:</strong><br>
      <br>
      Ahmed Iqbal Ullah Race Relations Resource Centre <br>
      Lower Ground Floor<br>
      Central Library<br>
      St Peter’s Square<br>
      Manchester<br>
      M2 5PD<br>
      <br>
      By post email <a href="mailto:contact@ourmothers.org">contact@ourmothers.org</a>
    </p>
  </div>
</section>

<br><br><br>
<hr>

<section id="about">
  <div class="content">
    <br>
    <h1 class="h2">Background on the project</h1>

    <p class="narrow">SOM does not fictionalise life but tells it just as we live it. Sometimes it is cruel and heart-breaking but even then, families pull on through. In many cases hardship and heartache makes the bond of family stronger, especially when Mothers stepped away from the relationship into single parenthood. Fathers too became the sole carer of their children when mothers left because they couldn’t or didn’t want to stay in the home.</p>

    <p class="narrow">Strength of Our Mothers a 2017-2019 partnership project led by National Black Arts Alliance, supported by the Heritage Lottery Fund.</p>

    <p class="narrow">NBAA is the UK’s largest network of Black artists established in 1985 it exists to combat negative attitudes to Black arts and culture. Its heritage work in social history contributes to debates around migration, interracial marriage, and class to challenge racist narratives.</p>

    <br><br>

    <p class="btn">
      <a href="#women">Back to the women</a>
    </p>
  </div>
</section>
