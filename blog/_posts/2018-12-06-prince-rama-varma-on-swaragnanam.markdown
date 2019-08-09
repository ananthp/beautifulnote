---
title: Prince Rama Varma on Swara Gnanam
layout: post

class_col_app_logo: "col-xs-offset-4 col-xs-4 col-md-offset-0 col-md-1"
class_col_app_text: "appinfo col-xs-12 col-md-6"
class_col_play_badge: "col-xs-offset-3 col-xs-6 col-md-offset-1 col-md-3"

sadhakam_screenshots: [
  '/images/screenshot-sadhakam-srg-question.png',
  '/images/screenshot-sadhakam-srg-answer.png'
]
sadhakam_screenshot_alts: [
  'a challenge in sadhakam app sa-ri-ga exercise',
  'answer to the challenge in sadhakam app'
]

redirect_from: /blog/2018/12/06/prince-rama-varma-on-swaragyanam
---

Prince Rama Varma, an eminent carnatic musician and teacher, points out a shortcoming in swara gnanam that's common even among advanced carnatic musicians. He also explains why it is common in our traditional raga-by-raga learning process:

<div class="embed-responsive embed-responsive-16by9 mb-3">
<iframe class='embed-responsive-item' src="https://www.youtube-nocookie.com/embed/AivQgaKwEfo?start=606" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

Excerpts from his talk:

> 10:06 "We (Carnatic musicians) are always trained to identify swarams of one raga only."
>
> 11:45 "Many carnatic musicians I myself know, they would be qualified to give a Ragam-Tanam-Pallavi in Todi correctly. But if we just ask them to sing Prati Madhyamam, immediately, they have to think a little bit. If someone asks you your name, you don't have to hesitate, you'll tell immediately. Like that we have to know all the 12 notes, not just the notes of one raga."
>
> 12:37 "Like a keyboard, in our throat, in our ear, in our brain, all 12 notes have to be fixed."

<script type="application/ld+json">
{% for screenshot in page.sadhakam_screenshots %}
{
    "@context": "http://schema.org/",
    "@type": "MobileApplication",
    "name": "Sadhakam: Carnatic Swara Gnanam Practice",
    "url": "{{ site.sadhakam_app_link }}",
    "applicationCategory": "Education",
    "operatingSystem": "Android",
    "screenshot": "{{ screenshot | absolute_url }}"
},
{% endfor %}
</script>

This is exactly why we built <a {{ site.new_tab }} href='{{ site.sadhakam_app_link }}'>Sadhakam: Carnatic Swara Gnanam Practice</a> (Android app). It has direct swaram centric exercises that will help you fix all the swarasthanas <em>in your throat, ear and brain</em> as Prince Rama Varma advices.

<figure>
<div class='row'>
  {% for i in (0..1) %}
  <div class='col-md py-3'>
    <a {{ site.new_tab }} href='{{ site.sadhakam_app_link }}'>
    <img class='img-fluid' src="{{ page.sadhakam_screenshots[i] }}" alt="{{ page.sadhakam_screenshot_alts[i] }}" />
    </a>
  </div>
  {% endfor %}
</div>

<figcaption>Sadhakam app in action: In a swaram quiz, the app has played a sequence and the user should guess the swarasthanams. Then the app shows whether he/she guessed it right or wrong. It also shows the correct answer to help the user learn the correct swarasthanams.</figcaption>
</figure>
