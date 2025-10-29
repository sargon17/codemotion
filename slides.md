---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.varesenews.it%2Fphotogallery_new%2Fimages%2F2021%2F03%2Fgenerica-2020-1206431.610x431.jpg&f=1&nofb=1&ipt=3c8ea3d14ff6ff38a9c7290d5bc65054d590620eb6b8c536791c59b211270d0a
# some information about your slides (markdown enabled)
title: Una giornata a spasso per Busto Arsizio
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 35min
---

# Una giornata a spasso per Busto Arsizio

<div  class="mt-12 py-1">
 feat <span class="text-orange-500 font-bold italic"> Valerio Lamberti </span> & <span class="text-orange-500 font-bold italic">Mykhaylo Tymofyeyev</span>
</div>

<!--<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>-->

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

<!--## transition: fade-out-->

# Cose da sapere su Busto Arsizio

<div class="flex ">
  <div class="w-full">
    <p v-click>
      Busto Arsizio è un comune italiano di 84 332 abitanti della provincia di Varese in Lombardia.
    </p>
    <br>
    <p v-click="2" >
      è un posto bellissimo che ispira vita e felicità
    </p>
    <p v-click="3" class="text-orange-500 font-bold italic z-1000 top-20 relative">
      ed, a quanto pare, ha anche tanto da offrire
    </p>
  </div>

<img
v-click="1"
class="w-full"
src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwips.plug.it%2Fcips%2Fnotizie.virgilio.it%2Fcms%2F2025%2F04%2Fbusto-arsizio.jpg&f=1&nofb=1&ipt=ac342ad1c0f1f396a1e8a54b177e199ed5225eda880dc0c8a086da19241ec670"
alt=""
/>
<img
v-click
class="w-100 absolute top-10 right-10 rotate-12"
src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.varesenews.it%2Fphotogallery_new%2Fimages%2F2011%2F05%2Fgiro-d-italia-2011-saronno-busto-arsizio-202729.jpg&f=1&nofb=1&ipt=4c0e92878b4264da66a879a31cba176527552492ff1db9d750113d79ba759389"
alt=""
/>
<img
v-click
class="w-100 absolute bottom-10 right-1/4 -rotate-8"
src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.sportface.it%2Fwp-content%2Fuploads%2F2024%2F12%2FBusto-Arsizio.jpg&f=1&nofb=1&ipt=70fe0ae8e7c413f72559a116a324a4ba1eb371887d98e99e44cd80a5626ba998"
alt=""
/>

</div>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<!--
Here is another comment.
-->

---

### ora che abbiamo la vostra attenzione...

---

# Cosa è successo a Busto Arsizio il 14 e 15 Ottobre?

<div class="relative">
  <img
  v-click
  class="shadow-xl"
  src="/img-1.png"
  alt=""
  />
  <img
  v-click
  class="absolute inset-0 rotate-3 shadow-xl"
  src="/img-2.png"
  alt=""
  />
  <img
  v-click
  class="absolute -rotate-2 inset-0 shadow-xl"
  src="/img-3.png"
  alt=""
  />
  <img
  v-click
  class="absolute inset-0 rotate-2 shadow-xl"
  src="/img-5.png"
  alt=""
  />

</div>

---

## ma anche questo...

<div class="relative min-h-[70vh]">
  <img
    v-click
    class="absolute top-[0%] left-[6%] w-[33%] rotate-6 shadow-xl"
    src="/codemotion/1.JPG"
    alt=""
  />
  <img
    v-click
    class="absolute top-[18%] left-[2%] w-[30%] -rotate-3 shadow-lg"
    src="/codemotion/2.JPG"
    alt=""
  />
  <img
    v-click
    class="absolute top-[14%] right-[28%] w-[28%] rotate-12 shadow-lg"
    src="/codemotion/3.JPG"
    alt=""
  />
  <img
    v-click
    class="absolute bottom-[32%] right-[18%] w-[24%] -rotate-6 shadow-xl"
    src="/codemotion/4.JPG"
    alt=""
  />
  <img
    v-click
    class="absolute top-[-10%] right-[8%] w-[29%] rotate-9 shadow-lg"
    src="/codemotion/6.JPG"
    alt=""
  />
  <img
    v-click
    class="absolute top-[14%] left-[32%] w-[29%] -rotate-8 shadow-xl"
    src="/codemotion/7.JPG"
    alt=""
  />
  <img
    v-click
    class="absolute top-[-12%] right-[46%] w-[28%] rotate-3 shadow-lg"
    src="/codemotion/8.JPG"
    alt=""
  />
  <img
    v-click
    class="absolute top-[28%] right-[0%] w-[50%] rotate-12 shadow-xl"
    src="/codemotion/9.JPG"
    alt=""
  />
  <img
    v-click
    class="absolute top-[-6%] left-[8%] w-[38%] -rotate-2 shadow-lg"
    src="/codemotion/11.JPG"
    alt=""
  />
  <img
    v-click
    class="absolute top-[-15%] left-[20%] w-[54%] rotate-8 shadow"
    src="/codemotion/12.PNG"
    alt=""
  />
  <img
    v-click
    class="absolute top-[-8%] right-[5%] w-[36%] -rotate-6 shadow-xl"
    src="/codemotion/13.JPG"
    alt=""
  />
  <video
    class="absolute top-1/3 left-1/2 w-[33%] rotate-6 shadow-2xl rotate-1 shadow-2xl rounded-xl transform -translate-x-1/2 -translate-y-1/2"
    controls
    v-click
    muted
    autoplay
    loop
  >
    <source src="/codemotion/5-1.mov" type="video/mp4">
    Your browser does not support the video tag.
  </video>

<p class="absolute top-1/4 left-1/2 -translate-x-1/2 text-orange-500 font-bold italic text-8xl text-nowrap" v-click>
  Nerd Ovunque
</p>
</div>
