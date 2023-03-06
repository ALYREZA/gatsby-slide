---
theme: apple-basic
layout: intro
drawings:
  persist: false
  enabled: true
# page transition
transition: slide-left
---

# Wordpress to Gatsby
<img style="width: 300px" src="/assets/img/gatsby.gif" />
<div class="absolute bottom-10">
  <span class="font-700">
    by Alyreza
  </span>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: intro
transition: slide-up
---
# how Wordpress works

---
layout: intro-image
image: '/assets/img/wp.webp'
---

---
layout: fact
---

# what Gastby does

---
layout: intro-image
preload: false
image: '/assets/img/wp.webp'
---

<img v-motion
      :initial="{ x: 800, y: 2000 }"
      :enter="{ x: 400,y: 130, scale: 1.3 ,opacity: 1, transition: { delay: 300, duration: 2000 } }"
      class="absolute top-0 left-0 right-0 bottom-0"  style="width: 200px; height: 200px;" src="/assets/img/gatsby.svg" />

---
layout: image-right
image: '/assets/img/headless.png'
---

<h2>what does <mark>Headless</mark> mean</h2>
<br />
<blockquote>
A headless application is a software program which runs without an inbuilt graphical user interface (GUI) and provides a specific functionality to your application or website. It uses API to connect to the frontend solution and send the data to be presented on the frontend layer.
</blockquote>

---
layout: fact
transition: slide-up
---

# why Gastby


---
layout: fact
---

<h2>It's in our DNA to be fast.</h2>
<br />
<div>
  <div>
    <h1>50%</h1>
    <h2>Faster Page Load Speed vs. competitors</h2>
  </div>
  <div>
    <h1>20 x</h1>
    <h2>Faster Build Times vs. competitors</h2>
  </div>
  <div>
    <h1>2 x</h1>
    <h2>SEO Boost vs. competitors</h2>
  </div>
</div>