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
<img src="/images/photos/water_tank_portrait.jpg" alt="water tank portrait; Oaxaca, MEX">
<img src="/images/photos/space_needle_portrait.jpg" alt="space needle portrait; Seattle, WA, USA">
<img src="/images/photos/boy_in_tree.png" alt="boy in tree; somewhere in MAD">
<img src="/images/photos/diesel_fried_chicken.jpg" alt="disel fried chicken; somewhere in TX, USA">
<img src="/images/photos/tacos_de_cabeza.jpg" alt="tacos de cabeza; Oaxaca, MEX">
<img src="/images/photos/car_and_tree.jpg" alt="car and tree; somewhere in NIC">
<img src="/images/photos/guitar_and_strings.png" alt="guitar and strings; Cadiz, ESP">
<img src="/images/photos/self_portrat.jpg" alt="self portrait; Tucson, AZ, USA">
</div>

<!-- CENTER TEXT (markdown works in here) -->
<div class="etc-col etc-center" markdown="1">

Other stuff I do
======
I've been fortunate to live and work in many places throughout. Adventure and happenstance have played formative roles in my life. The photos here capture a few of the many moments.

I love to run and hike, naturalize and birdwatch, read, cook, and generally explore and experience the world.

I am also passionate about the mind-opening experience of language learning. 
Japanese, in particular, has been a long, slow, revelatory process. For anyone who might be interested, here are a few curated resources:


<ul class="resource-list">
<li> <img src="/images/kanji_study_logo.png" alt=""> <span><strong><a href="https://play.google.com/store/apps/details?id=com.mindtwisted.kanjistudy">Kanji Study app</a></strong>: Phenomenal dictionary and study app (for Android). (Bonus: Add tegaki keyboard to your phone and you can draw kanji you don't know to search them. Good fun.)</span> </li>
<li> <img src="/images/tae_kim_book_cover.png" alt=""> <span><strong><a href="https://www.guidetojapanese.org/grammar_guide.pdf">Tae Kim's Japanese grammar guide</a></strong>: I read this cover to cover multiple times when I first started learning Japanese. Quick, practical framework for understanding how the language is put together.</span> </li>
<li> <img src="/images/suiran_logo.png" alt=""> <span><strong><a href="https://erthward.github.io/suiran">Suiran</a></strong>: For years, I've wanted but never found a minimalist app that behaves as closely as possible like actual paper flashcards. So I recently vibe-coded for the first time to make 翠嵐. It makes it super easy to add new vocab as it comes up in daily life, by searching in either either English or Japanese; review your running list; and quiz as much as you want, whenever you want, as long as you want. Vocab list and quiz data save locally in your browser cache, and it can be installed to your phone's homescreen from your browser so it looks and feels like a real app. (***NOTE***: If you plan to use this then please contact me so I can make sure it doesn't overload my free Deno proxy that it currently uses!)</span> </li>
<li> <img src="/images/japanese_short_stories_cover.png" alt=""> <span><strong><a href="https://www.penguin.com.au/books/short-stories-in-japanese-9780143118336">Michael Emmerich's Japanese short stories in parallel text</a></strong>: I stumbled upon this book while waiting for a bus in Fukuoka. It remains the most fun and useful resource I've found for learning to parse and understand Japanese syntax in context.</span> </li>


