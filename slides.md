---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /start.jpeg
# some information about your slides (markdown enabled)
title: Verwebte Klänge
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
hideInToc: true
---

# Verwebte Klänge

Eine Intervention im Brücke Museum<br/>
von Moritz Hüper und Magda-Lena Prokopiev

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/hueper/verwebte-klaenge" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>


---
layoutClass: gap-16
hideInToc: true
---

# Inhalt

<Toc text-sm minDepth="1" maxDepth="2" />


---
transition: slide-up
layout: center
class: text-center
---

# Hintergrund

---
transition: slide-up
layout: two-cols
layoutClass: gap-16
level: 2
---

# Ausstellung

Lise Gujer. Eine neue Art zu malen

<v-clicks>

- **Begegnung mit Kirchner (1922)**  
- **Themen:** Schweizer Bergwelt, Tiere, Menschen, Tanz  
- **Eigene Schaffensphase ab 1950er-Jahren:** Weiterentwicklung über Kirchners Vorlagen hinaus  
- **Über 30 Wirkereien & Kirchners Vorzeichnungen**  
- **Fokus:** Gujers Autorinnenschaft in den Vordergrund stellen und ihren Platz in der Geschichte des Expressionismus anerkennen  
- **Erste umfassende Präsentation seit über 20 Jahren**  

</v-clicks>

::right::

![](/Ausstellungsansicht_Lise_Gujer_03.jpg)

---
transition: slide-up
layout: two-cols
layoutClass: gap-16
level: 2
---

# Seminar

<v-clicks>

- November 2024 - Februar 2025
- Kooperation mit der Kuratorin für Outreach, Daniela Bystron
- 1 Treffen in Hildesheim 
- 3 Treffen in Berlin
- Weitere Besprechungen online
- 14 Teilnehmer*innen aus BA und MA
- 5 Interventionen / Vermittlungsangebote

</v-clicks>

::right::

<div class="flex justify-center">
  <img src="/signal-2025-03-27-100630.jpeg" class="max-h-120 shadow-lg">
</div>

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
level: 2
---

# Motivation

<v-clicks>

- Wirkereien keine bloßen Reproduktionen, sondern **Übersetzung** in andere Materialität
- Notwendigkeit, Farben und Formen zu **abstrahieren** - bei gleichzeitigem Erhalt von Kirchners expressivem Stil
- **Beschränkung der Technik** – Rasterstruktur, begrenzte Farbmischung, Materialwiderstände

</v-clicks>

<v-clicks>

&rarr; Übersetzungsleistung von einem kontinuierlichem Medium zu einem diskreten (= Digitalisierung)

&rarr; Darstellung des enormen Arbeitsaufwandes schwierig und unterrepräsentiert.

</v-clicks>

::right::

<div class="flex justify-center">
  <img src="/uebersetzung-am-webstuhl.jpeg" class="max-h-120 shadow-lg">
</div>

---
transition: slide-up
layout: center
class: text-center
---

# Produktion

Vermittlung des Herstellungsprozesses einer Webarbeit auf auditiver Ebene.

---
transition: slide-up
level: 2
---

# Material

<v-clicks>

- Audiodatei
- Geräusche von Webstühlen, Menschenstimmen wie Gespräche und Summen Geschirr und ggf. Berggeräusche, wie bspw. Kühe, Vögel, Alpenhorn, etc.
- Platzierung des Klangs in Davos
- Found Footage, Sound aus Youtube-Videos
- Nutzung von [yt-dlp](https://github.com/yt-dlp/yt-dlp) und [ffmpeg](https://ffmpeg.org/), um Material als Audiodateien zu beschaffen
- [Audacity](https://www.audacityteam.org/) zur Bearbeitung des Materials

</v-clicks>

---
transition: slide-up
level: 2
---

# Prototyp


<video controls width="800">
  <source src="/prototyp.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---
transition: slide-up
layout: two-cols
layoutClass: gap-16
level: 2
---

# Zusammenarbeit

<v-clicks>

- Erstellung des Prototyps und Vorstellung in Gruppe via Telegram
- Assoziatives Hin- und Herschicken von Klangmöglichkeiten
- Beschaffung des Materials durch Moritz
- Komposition von Magda-Lena
- gemeinsame Feedbackloops und Korrekturen

</v-clicks>

::right::

![](/2025-03-27-17-11-12.png)

---
transition: slide-up
layout: two-cols
layoutClass: gap-16
layout: center
class: text-center
---

# Präsentation

---
transition: slide-up
layout: center
class: text-center
level: 2
---

# Sound

<audio controls>
  <source src="/verwebte-klaenge.mp3" type="audio/mpeg">
</audio>

<div class="flex justify-center">
  <img src="/headphones.jpeg" class="max-h-100 shadow-lg">
</div>

---
transition: slide-up
level: 2
---

# Ausstellungsansicht 1

<div class="flex justify-center">
  <img src="/praesentation-2.jpg" class="max-h-100 shadow-lg">
</div>

---
transition: slide-up
level: 2
---

# Ausstellungsansicht 2

<div class="flex justify-center">
  <img src="/praesentation-1.jpg" class="max-h-100 shadow-lg">
</div>

---
transition: slide-up
level: 2
layout: center
class: text-center
---

# Danke 👋

<div class="flex justify-center">
  <img src="/Ausstellungsansicht_Lise_Gujer_03.jpg" class="max-h-100 shadow-lg">
</div>