---
layout: archive
title: ""
permalink: /etc/
author_profile: false
---

{% include base_path %}


<style>
/* Three columns: photos | text | photos. On narrow screens the text goes on top
   and the two photo columns sit side by side underneath. */
.etc-grid { display: grid; grid-template-columns: 1fr 2fr 1fr; gap: 24px; align-items: start; }
.etc-col { min-width: 0; }
.etc-grid img { display: block; width: 100%; height: auto; border-radius: 4px; margin-bottom: 16px; }
/* Click-to-zoom photos */
.etc-grid > .etc-col > img { cursor: zoom-in; }
#lightbox { position: fixed; inset: 0; background: rgba(0,0,0,.85); display: none; align-items: center; justify-content: center; z-index: 9999; cursor: zoom-out; }
#lightbox.on { display: flex; }
#lightbox img { max-width: 94vw; max-height: 94vh; width: auto; height: auto; border-radius: 4px; }
/* Resource list: small thumbnail instead of a bullet */
.resource-list { list-style: none; padding: 0; margin: 0; }
.resource-list li { display: flex; align-items: center; gap: 12px; margin-bottom: 12px; }
.etc-grid .resource-list img { width: 40px; height: 40px; object-fit: cover; margin: 0; border-radius: 6px; flex: none; }
@media (max-width: 800px) {
  .etc-grid { grid-template-columns: 1fr 1fr; }
  .etc-center { grid-column: 1 / -1; order: -1; }
}
</style>


<div class="etc-grid">

<!-- LEFT PHOTOS: copy a line to add a photo, delete a line to remove one.
     Put the image files in /images/etc/ -->
<div class="etc-col">
<img src="/images/photos/boy_in_tree.png" alt="boy in tree; somewhere in MAD">
<img src="/images/photos/water_tank_portrait.jpg" alt="water tank portrait; Oaxaca, MEX">
<img src="/images/photos/space_needle_portrait.jpg" alt="space needle portrait; Seattle, WA, USA">
<img src="/images/photos/diesel_fried_chicken.jpg" alt="disel fried chicken; somewhere in TX, USA">
<img src="/images/photos/car_and_tree.jpg" alt="car and tree; somewhere in NIC">
<img src="/images/photos/tacos_de_cabeza.jpg" alt="tacos de cabeza; Oaxaca, MEX">
<img src="/images/photos/guitar_and_strings.png" alt="guitar and strings; Cadiz, ESP">
<img src="/images/photos/rolling_still_life.jpg" alt="bike trip, still life; somewhere in PA, USA">
<img src="/images/photos/self_portrait.jpg" alt="self portrait; Tucson, AZ, USA">
</div>

<!-- CENTER TEXT (markdown works in here) -->
<div class="etc-col etc-center" markdown="1">

The rest of my life
======
In my free time, I love to run and hike, play soccer (very poorly), play with my family, naturalize and birdwatch, read books, listen to music, cook and eat, and generally explore and experience the world.

I've been fortunate to live and work in many places throughout my life. Adventure and happenstance have played very important formative roles in my life. The photos here attempt to capture a few of the many meaningful moments.



-----------------------

### Language learning

I am also passionate about the mind-opening experience of language learning. I've learned Spanish, Japanese, French, Portuguese, and others, to varying degrees, at varying points in my life.

Japanese, in particular, has been a long, slow, complicated process. Since I've been asked many times, here a curated list of my favorite resources:


<ul class="resource-list">
<li> <img src="/images/kanji_study_logo.png" alt=""> <span><strong><a href="https://play.google.com/store/apps/details?id=com.mindtwisted.kanjistudy">Kanji Study app</a></strong>: Phenomenal dictionary and study app (for Android). (Bonus: Add tegaki keyboard to your phone so you can directly search new kanji by drawing. Good fun.)</span> </li>
<li> <img src="/images/tae_kim_book_cover.png" alt=""> <span><strong><a href="https://www.guidetojapanese.org/grammar_guide.pdf">Tae Kim's Japanese grammar guide</a></strong>: I read this cover to cover multiple times when I first started learning Japanese. Quick, practical framework for understanding how the language is put together.</span> </li>
<li> <img src="/images/japanese_short_stories_cover.png" alt=""> <span><strong><a href="https://www.penguin.com.au/books/short-stories-in-japanese-9780143118336">Japanese short stories in parallel text</a></strong>: I stumbled upon this book while waiting for a bus in Fukuoka. It remains the most fun and useful resource I've found for learning to parse and understand Japanese syntax in context.</span> </li>
<li> <img src="/images/suiran_logo.png" alt=""> <span><strong><a href="https://erthward.github.io/suiran">Suiran</a></strong>: Over the years, I've never found a simple thing I've wanted: a minimalist app that behaves as closely as possible to actual paper flashcards. So I finally made it. (***NOTE***: If you plan to use this then contact me for details... And so I can make sure we don't overload my free Deno proxy that it currently depends on!)</span> </li>




<!-- Click-to-zoom: click a photo to enlarge it; click anywhere or press Esc to close.
     Optional: add data-full="/images/etc/big-version.jpg" to an <img> to show a larger file when zoomed. -->
<div id="lightbox"><img alt=""></div>
<script>
(function () {
  var lb = document.getElementById('lightbox');
  var big = lb.querySelector('img');
  document.querySelectorAll('.etc-grid > .etc-col > img').forEach(function (img) {
    img.addEventListener('click', function () {
      big.src = img.getAttribute('data-full') || img.src;
      big.alt = img.alt;
      lb.classList.add('on');
    });
  });
  lb.addEventListener('click', function () { lb.classList.remove('on'); });
  document.addEventListener('keydown', function (e) { if (e.key === 'Escape') lb.classList.remove('on'); });
})();
</script>





