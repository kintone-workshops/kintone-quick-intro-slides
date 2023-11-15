---
theme: /
favicon: ./kintone-graphics/KDP_favicon.png
layout: image
image: ./kintone-graphics/kintone-background-v2.svg
title: Quick Introduction to Kintone Kintone Web Database
exportFilename: kintone-quick-intro-slides
export:
  format: pdf
  timeout: 30000
  withToc: true
presenter: true
download: true
highlighter: prism
lineNumbers: false
monaco: dev
remoteAssets: true
selectable: true
record: true
routerMode: history
aspectRatio: 16/9
canvasWidth: 980
themeConfig:
  primary: '#008080'
  dark: '#038378'
  darker: '#076E65'
  darkest: '#065A53'
  light: '#10B5A7'
  lighter: '#0CCABA'
  lightest: '#06E5D2'
fonts:
  sans: Raleway
  serif: Raleway
  mono: Raleway
hideInToc: true
---

<div class="mb-4 top-15 left-45" style="text-align: right">
  <div class="text-7xl text-white text-opacity-100" style="font-weight: 600">
    Kintone Web Database
  </div>
  <div><br /></div>
  <div class="text-6xl text-white text-opacity-100" style="font-weight: 600">
    Your Project's Backend <mdi-database-cog/>
  </div>
  <div><br /><br /></div>
  <div
    class="text-2xl text-white text-opacity-100"
    style="font-weight: 600; line-height: 2"
  >
    <a href="https://kintone.dev/">Kintone Developer Program</a><mdi-book/>
  </div>
</div>

<div
  class="absolute bottom-15 right-12"
  style="
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
  "
>
  <div
    class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-60 flex justify-center items-center"
    align="center"
    style="flex: 1; padding-right: 20px"
  >
    <a
      href="https://ahandsel.github.io/kintone-quick-intro-slides/"
      target="_blank"
      alt="Intro to Kintone Slides"
    >
      Slides <mdi-presentation-play/>
    </a>
  </div>
  <div>
    <a
      href="https://ahandsel.github.io/kintone-quick-intro-slides/"
      target="_blank"
      alt="Intro to Kintone Slides"
    >
    <QRCode
      value="https://ahandsel.github.io/kintone-quick-intro-slides/"
      width="100"
      height="100"
      alt="QR Code for kintone-for-hackathon Slide Deck"
    />
    </a>
  </div>
</div>
<div class="absolute bottom-7 right-12">
  <div
    @click="$slidev.nav.next"
    class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-60 flex justify-center items-center"
  >
    Press Space for the next page →
  </div>
</div>


---
layout: image-right-bar
image: ./kintone-graphics/Animal_6_flip.png
hideInToc: true
---

## Table of Contents <mdi-table-of-contents/>

<toc />


---
layout: image-right-bar
image: ./kintone-graphics/Animal_6_flip.png
title: Overview <tabler-color-swatch/>
---

# Overview <tabler-color-swatch/>

<br>

### ① What is Kintone? <mdi-database-cog/>

‣ Kintone's Features

### ② How to Use Kintone? <mdi-school-outline/>

‣ Example Projects

### ③ How to Get Started? <mdi-pencil/>

‣ When the fun starts


---
layout: my-two-columns
title: What is Kintone? <mdi-database-cog/>
---

# What is Kintone? <mdi-database-cog/>

<br>

::left::

<div class="text-4xl top-1" style="font-weight:500;user-select:text;line-height: 1.6;" >
  Kintone is a <strong>low-code</strong> platform that allows you to <strong>build web databases</strong> easily & quickly! <mdi-tools/>
</div>


::right::

![Kintone exchanging data from a smartphone](/kintone-graphics/Fast_Database.png)


---
layout: my-two-columns
title: Your Project's Web Database <mdi-sitemap/>
---

# Your Project's Web Database <mdi-sitemap/>

<br>

::left::

<div class="text-4xl" style="font-weight:500;user-select:text;line-height: 1.6;" >
  Use Kintone to <strong>store</strong> incoming data or <strong>manage</strong> outgoing data!
</div>


::right::

![Kintone exchanging data from a smartphone](/kintone-graphics/Kintone_DataExchange.png)


---
layout: image-right
image: ./kintone-graphics/Traditional_Database.png
equal: true
---

# Traditional Databases <bx-sad/>

<br>

<div class="text-2xl" style="font-weight:500;user-select:text;line-height: 1.6;" >
  Needs a <strong>high-level understanding</strong> of databases
  <br><br>
  <strong>Servers</strong> need to be <strong>constantly running</strong> &amp; maintained to be accessed
</div>


---
layout: image-right
image: ./kintone-graphics/Build_App_Demo.gif
equal: true
---

# Kintone Databases <bx-happy />

<br>

<div class="text-2xl" style="font-weight:500;user-select:text;line-height: 1.6;" >
Databases are created with intuitive <strong>drag-&-drop</strong> GUI
<br><br>
<strong>No servers need</strong> to be set up by the user
</div>


---
layout: image-right-bar
image: ./kintone-graphics/Animal_6_flip.png
---

# How to Use Kintone? 🧐

<br>

## Access Kintone Database Data via

<br>

## ‣ Web Browser <gg-browser/>

<br>

## ‣ REST API <gg-database/>


---
layout: my-two-columns
title: Access Kintone DBs via the Browser <gg-browser/>
---

# Access Kintone DBs via the Browser <gg-browser/>

<br>

::left::

## Use the GUI to:

<br>

* #### Create & Edit Databases <mdi-database/>

<br>

* #### View/ Add/ Edit Records <mdi-folders/>

<br>

* #### Add JS Customizations <mdi-code/>

::right::

![Build a Kintone App from YOUR_SUBDOMAIN.kintone.com](/kintone-graphics/Kintone_From_Browser.png)


---
layout: image-center
image: ./kintone-graphics/Kintone_REST_API_Request.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via REST API <mdi-exchange/>
  <br><br>
</div>


---
layout: image-center
image: ./kintone-graphics/Kintone_REST_API_Response.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via REST API <mdi-exchange/>
  <br><br>
</div>


---
layout: image-center
image: ./kintone-graphics/Kintone_REST_API_Flow.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via REST API <mdi-exchange/>
  <br><br>
</div>

<!--
Let’s say you’ve made some databases in Kintone and added some data in.
You can make REST API calls from your App pointing to your Kintone environment, the Database ID you want to access and an API token for authentication to get your results.
You can call REST APIs from most languages, wether it be node.js, python, php, Ruby etc.
-->

---
layout: image-right
image: ./kintone-graphics/Example_Samurai.gif
equal: true
title: Example - IoT Samurai Swords <tabler-slice />
---

## IoT Samurai Swords <tabler-slice />
Created by [@RyBB](https://github.com/RyBB) - [Article](https://dev.to/will_yama/kintone-at-maker-faire-tokyo-2020-215k)

Users are challenged to slice their enemies as quickly as possible with a samurai sword!

* Sensor records the sword action speed
* Kintone hosts the game, scoreboard, & IoT data
* Doll's magnetic head falls off when the user wins


---
layout: image-right-bar
image: ./kintone-graphics/Example_flowerpot-bar.gif
title: Example - Hibotan / Flowerpot Project <mdi-robot-outline />
---

## Hibotan / Flowerpot Project <mdi-robot-outline />
Created by [Nobuyuki Furukawa](https://protopedia.net/prototyper/nobuyukifurukawa) - [ヒボたん](https://peraichi.com/landing_pages/view/hibotan)

* A moving flowerpot that uses **Kintone as the backend** to store sensor data.
* Sensors are attached to a [mbed microcontroller](https://os.mbed.com/handbook/mbed-Microcontrollers) & periodically send data to Kintone via Node.js.
* Node.js checks Kintone's sensor values over time and controls the motors of the flowerpot.
* The flowerpot moves to a sunnier place.

<!--
* Goal: Make attendees feel like super fast anime samurais
* Sword: magnet sensors to detect in & out motion speed
* doll with electric magnet to have its head fall off
* 2 M5Stick microcontrollers were used for sword & doll
* The score ranking displayed information stored in the Kintone App, where scores of participants were automatically recorded via REST API after they finished playing the game.
-->

---
layout: image-right
image: ./kintone-graphics/Example_SpaceInvaders.gif
equal: true
title: Example - Space Invaders <mdi-space-invaders />
---

## Space Invaders <mdi-space-invaders />

Created by [@will_yama](https://twitter.com/will_yama) & [@ahandsel](https://github.com/ahandsel/) - [Article](https://dev.to/will_yama/having-fun-with-phaser-io-games-web-databases-4f08)

Run a [Space Invaders game](https://phaser.io/examples/v2/games/invaders) on a Kintone App!

Game specifications (number of aliens, aliens' health, etc.) are specified as Kintone records.

High scores can also be stored in Kintone.


---
layout: image-right
equal: true
image: ./kintone-graphics/Kintone_New.png
title: Get your Kintone <mdi-server />
---

## Get your free Kintone Web Database <mdi-server />

<br>

#### Go to [Kintone.dev/new](https://Kintone.dev/new)!


Fill out the Developer License Registration form for your free Kintone Subdomain!

* ✅ Use Chrome or Firefox ( _NOT Safari_ )
* ⚡ Accept Cookies First
* 🚧 Only use lowercase, numbers, and hyphens (-) for subdomain names
* Ex: `weekend-hacker4life`


---
layout: image-right-bar
image: ./kintone-graphics/Animal_3_flip.png
title: Where to get help? <mdi-help-circle/>
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Where to get help? <mdi-help-circle/>
</div>

<br>

Here are some resources to help you use Kintone as your project's database!

| <mdi-home/>     | [kintone.dev](https://kintone.dev/)                                          | Read API Docs & Tutorials |
| --------------- | ---------------------------------------------------------------------------- | ------------------------- |
| <mdi-lifebuoy/> | [forum.kintone.dev](https://forum.kintone.dev/)                              | Post Questions            |
| <mdi-youtube/>  | [@KintoneDeveloperProgram](https://www.youtube.com/@KintoneDeveloperProgram) | Watch Tutorials           |


---
layout: image-right-bar
image: ./kintone-graphics/Animal_10_flip.png
---

# Thank You Gift! <mdi-rocket/>

<br>

### As a **Thank You** for using Kintone in your project, we are giving away some Kintone Swag!

<br><br>

<img src="/kintone-graphics/KDP_Swag.png" alt="Bottles, backpacks, PopSockets, & more!" style="width: 60%;">

