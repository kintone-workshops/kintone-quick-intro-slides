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
addons:
  - '@katzumi/slidev-addon-qrcode'
---

<div class="mb-4 top-15 left-45" style="text-align: right">
  <div class="text-7xl text-white text-opacity-100" style="font-weight: 600">
    Kintone Web Database
  </div>
  <div><br/></div>
  <div class="text-6xl text-white text-opacity-100" style="font-weight: 600">
    Your Project's Backend <mdi-database-cog/>
  </div>
  <div><br/></div>
  <div
    class="text-2xl text-white text-opacity-100"
    style="font-weight: 600; line-height: 2"
  >
    <a href="https://kintone.dev/">Kintone Developer Program<mdi-book/></a>
  <br>
  </div>
  <div
    class="text-2xl text-white text-opacity-100"
    style="font-weight: 450; line-height: 2"
  >
    <a href="https://kintone-workshops.github.io/kintone-quick-intro-slides/">Slides <mdi-presentation-play/></a>
    <br>
    <a href="https://github.com/kintone-workshops/kintone-quick-intro-slides ">Code <mdi-language-markdown
/></a>
  </div>
</div>

<div
  class="absolute bottom-13 right-9"
  style="
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
  "
>
  <div>
    <a
      href="https://kintone-workshops.github.io/kintone-quick-intro-slides/"
      target="_blank"
      alt="Intro to Kintone Slides"
    >
    <QRCode
      value="https://kintone-workshops.github.io/kintone-quick-intro-slides/"
      width="100"
      height="100"
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

<!--
kintoneウェブデータベース  
プロジェクトのバックエンド  
kintone開発者プログラム  
-->

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

<!--
概要  
①kintoneとは何ですか？  
‣ kintoneの特徴  
②kintoneの使い方は？  
‣ プロジェクト例  
③どうやって始めればいいの？  
‣ 楽しいことが始まるとき
-->

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

<!--
キントーンとは何ですか？

kintone は、Web データベースを簡単かつ素早く構築できるローコード プラットフォームです。

スマートフォンからデータをやりとりするkintone
-->

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

<!--
プロジェクトの Web データベース

あなたの作るアプリのデータ管理にはkintoneを使ってみてください。

kintoneを使って受信データの保存や送信データの管理をしましょう！

スマートフォンからデータをやりとりするkintone
-->

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

<!--
従来のデータベース

データベースについての高度な理解が必要

サーバーにアクセスするには、サーバーを常に実行および維持する必要があります
-->

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

<!--
kintoneデータベース

データベースは直感的なドラッグ＆ドロップ GUI で作成されます

ユーザーがサーバーをセットアップする必要はありません
-->

---
layout: image-right-bar
image: ./kintone-graphics/Animal_6_flip.png
---

# How to Use Kintone? <mdi-school-outline/>

<br>

## Access Kintone Database Data via

<br>

## ‣ Web Browser <gg-browser/>

<br>

## ‣ REST API <gg-database/>

<!--
kintoneの使い方は？

kintone データベースのデータにアクセスするには
‣ ウェブブラウザ
‣ REST API
-->

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

<!--
ブラウザからkintone DBにアクセス

GUI を使用して次のことを行います。

データベースの作成と編集

レコードの表示/追加/編集

JSカスタマイズの追加
YOUR_SUBDOMAIN.kintone.com から kintone アプリを構築する
-->

---
layout: image-center
image: ./kintone-graphics/Kintone_REST_API_Request.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via REST API <mdi-exchange/>
  <br><br>
</div>

<!--
REST API経由でkintone DBにアクセス

とはいえ、RESTAPIってなに？と思いますよね。そこでまずは普段みなさんが使っていそうなアプリを参考にRESTAPIを紹介します。皆さんYouTubeって見ますか？トップページを表示するときに動画のコンテンツがどのように表示されているかというと、DBに保存されている動画データを取得してページに表示しています。このリクエストの仕組みをRESTAPIが担っています。
-->

---
layout: image-center
image: ./kintone-graphics/Kintone_REST_API_Response.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via REST API <mdi-exchange/>
  <br><br>
</div>

<!--
REST API経由でkintone DBにアクセス
このリクエストとレスポンスの仕組みをRESTAPIが担っています。
-->

---
layout: image-center
image: ./kintone-graphics/Kintone_REST_API_Flow.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via REST API <mdi-exchange/>
  <br><br>
</div>

<!--
Kintoneでいくつかのデータベースを作成し、そこにデータを追加したとします。
アプリから REST API 呼び出しを実行して、Kintone 環境、アクセスするデータベース ID、結果を取得するための認証用の API トークンを指定できます。
Node.js、Python、php、Ruby など、ほとんどの言語から REST API を呼び出すことができます。
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

<!--
IoTサムライソード

剣の抜き差しの速さを競うゲームです。
このようにIOTと連携することもできます。

ユーザーはサムライソードでできるだけ早く敵を斬ることに挑戦します!
- センサーが剣の動作速度を記録
- Kintone はゲーム、スコアボード、IoT データをホストします
- ユーザーが勝つと人形の磁気ヘッドが落ちる
-->

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
緋牡丹・植木鉢プロジェクト
お花や植物の管理ってたまに面等くさいですよね。そんな課題を解決してくれるのがこの作品です。
ロボットは温度や湿度データを取得してkintoneに登録しています。
登録されたデータはkintoneに登録してデータのグラフ表示も簡単です。

- kintoneをバックエンドとしてセンサーデータを保存する移動式植木鉢。
- センサーはmbedマイコンに接続されており、Node.js経由でKintoneに定期的にデータを送信します。
- Node.jsはkintoneのセンサー値を経時的にチェックし、植木鉢のモーターを制御します。
- 植木鉢は日当たりの良い場所に移動します。
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

<!--
スペースインベーダーズ

kintoneアプリでスペースインベーダーゲームを動かしてみよう！JSのカスタマイズができるので、画面上のカスタマイズが自由にできます。

ゲームの仕様（エイリアンの数やエイリアンの健康状態など）をkintoneのレコードとして指定します。

ハイスコ​​アはkintoneに保存することもできます。
-->

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

<!--
無料の Kintone Web データベースを入手する方法

kintone.dev/new にアクセスしてください。

無料の Kintone サブドメインの開発者ライセンス登録フォームに記入してください。

- ✅ Chrome または Firefox を使用してください (Safari ではありません)
- ⚡ 最初に Cookie を受け入れます
- 🚧 サブドメイン名には小文字、数字、ハイフン (-) のみを使用してください
- 例: 週末-hacker4life
-->

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

<!--
どこで助けが得られますか?

プロジェクトのデータベースとして kintone を使用するのに役立つリソースをいくつか紹介します。
- kintone.dev API ドキュメントとチュートリアルを読む
- forum.kintone.dev 質問を投稿する
- @KintoneDeveloperProgram チュートリアルを見る
ではみなさんのkintoneを使用した作品をお待ちしています
-->

---
layout: image-right-bar
image: ./kintone-graphics/Animal_10_flip.png
---

# Thank You Gift! <mdi-rocket/>

<br>

### As a **Thank You** for using Kintone in your project, we are giving away some Kintone Swag!

<br><br>

<img src="/kintone-graphics/KDP_Swag.png" alt="Bottles, backpacks, PopSockets, & more!" style="width: 60%;">

<!--
ありがとうギフト！

プロジェクトでkintoneをご利用いただいたことに感謝を込めて、kintoneグッズをプレゼントいたします！

ボトル、バックパック、ポップソケットなど！
-->
