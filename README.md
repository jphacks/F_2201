# HackathonRunner
  
<img src="https://user-images.githubusercontent.com/79685987/197310366-d45ea75e-e970-441c-88f5-f57601a65ef6.jpg">

## 作品紹介動画
デモ動画: [https://www.youtube.com/watch?v=C4l_qvqyAOs](https://www.youtube.com/watch?v=C4l_qvqyAOs)

## 作品URL
作品URL: [https://infinite-citadel-53332.herokuapp.com](https://infinite-citadel-53332.herokuapp.com)

## 目次
- [製品概要](#anchor1)
    - [背景(製品開発のきっかけ、課題等）](#anchor2)
    - [製品説明（具体的な製品の説明）](#anchor3)
        - [診断機能](#anchor4)
        - [投稿機能](#anchor5)
        - [チームメンバー募集機能](#anchor6)
    - [特徴](#anchor7)
    - [解決出来ること](#anchor8)
    - [今後の展望](#anchor9)
    - [注力したこと](#anchor10)
- [開発技術](#anchor11)
    - [活用した技術](#anchor12)
        - [フレームワーク・ライブラリ・モジュール](#anchor13)
    - [独自技術](#anchor14)
        - [ハッカソンで開発した独自機能・技術](#anchor15)

<a id="anchor1"></a>

## 製品概要

ハッカソンに参加したい・参加する人たちを支援するためのWebアプリです！

GitHub: [https://github.com/Javaler/HackathonRunner](https://github.com/Javaler/HackathonRunner)

<a id="anchor2"></a>

### 背景(製品開発のきっかけ、課題等）

最近、日本でエンジニア不足が加速していると言われています。そのことも影響してか、ハッカソンの数が増えてきたり、オンラインでのハッカソンが増えてきたりと、ハッカソンがより身近に感じられるようになってきたのではないかなと思います。
しかし、それでもハードルのあるハッカソンはまだまだありますし、ハッカソン自体にも色々な不安があります。
そして、そんなハードルや不安から、なかなか参加には至らない人がまだまだたくさんいると思います。

例）

- 個人での参加も可能だが、チームでの参加を推奨しているハッカソン
- 複数人やチームでのみ応募可能なハッカソン
- 自分のレベルでもハッカソンに参加して大丈夫なのかという不安
- ハッカソンまでには何を準備して、ハッカソンではどう振る舞えば良いのかという不安

現に、我々のチームメンバー全員が、初ハッカソンまで上記であげたような不安を持っていました。
そこで我々は、そんなハードルや不安を軽減・解消し、ハッカソンに興味はあっても参加する勇気が持てずにいる人たちを、少しでも減らしたい、そんな思いからこの製品を開発しました。

<a id="anchor3"></a>

### 製品説明（具体的な製品の説明）

HackathonRunner には、ハッカソン参加の手助けになる3つの機能があります。
3つの機能によって、ユーザはハッカソンに参加しやすくなるだけでなく、継続してハッカソンに参加できるよになっています。

<a id="anchor4"></a>

#### 1. 診断機能

選択式の質問約10個に回答するだけで、ユーザーのハッカソンに対する技術レベルを診断し、下記のことを提案してくれる「診断機能」。ハッカソンに対する技術レベルはチャートで見られるように表示し、同じような技術レベルの人の投稿（どんなハッカソンに参加したかなどを含む）を取得・表示するための推薦システムは、[HackathonRunner-Analysis-API](JPHACKSリポジトリ内のディレクトリリンク)として実装しています。

- 同じようなレベルの人が参加したハッカソンの情報など
- ハッカソン当日までに何を準備しておけば良いか
- ハッカソン当日にどう振る舞えば良いか

<img src="https://user-images.githubusercontent.com/79685987/197223472-e6814061-015a-48e1-a347-02e690979ba6.mp4">

<a id="anchor5"></a>

#### 2. 投稿機能

ハッカソン参加後に、ユーザーがどんな技術レベルのときに、どんなハッカソンに参加し、どんな作品を開発したのかを投稿し、記録することができる「投稿機能」。これにより、ハッカソンでの活動・成長記録をつけられますし、診断機能の精度向上や開発した作品の宣伝にもなります。

<img src="https://user-images.githubusercontent.com/79685987/197227396-ac8907ca-91b9-480f-9b52-e4ebb2113861.mp4">

<a id="anchor6"></a>

#### 3. チームメンバー募集機能

開発仲間が少ない人や、開発仲間の都合が合わず、チームでの参加が難しい人でも、チームメンバーを募集して、事前にチームを組んで参加できるようになる「チームメンバー募集機能」。

<img src="https://user-images.githubusercontent.com/79685987/197318073-827d3bae-7763-48c1-9e3f-ac4df6ddc05c.mp4">

<a id="anchor7"></a>

### 特徴

- ハッカソンに対するユーザの技術レベルがわかる
- イベント情報サイトと比べると、ユーザ個人におすすめのハッカソンを知れる
- TwitterなどのSNSと比べると、ハッカソンに参加したい人だけが集める

<a id="anchor8"></a>

### 解決出来ること

背景でもあげましたが、下記のようなハッカソンに対するハードルや不安を軽減・解消するとともに、ハッカソンに興味があるにも関わらず、尻込みしている人たちを減少させることができます。

例）

- 個人での参加も可能だが、チームでの参加を推奨しているハッカソン
- 複数人やチームでのみ応募可能なハッカソン
- 自分のレベルでもハッカソンに参加して大丈夫なのかという不安
- ハッカソンまでには何を準備して、ハッカソンではどう振る舞えば良いのかという不安

<a id="anchor9"></a>

### 今後の展望

現状では、診断結果（診断機能を使用した結果）の中に表示されているハッカソンの情報は、他のユーザーの投稿に含まれているハッカソンの情報になっているので、情報が重複してしまうことがあるという点や、投稿されていないハッカソンはおすすめされないという点など、いくつかの問題があります。そこで、投稿とは別に、（投稿に含まれないハッカソンも含めて、）おすすめのハッカソンを表示する機能を追加したいと考えています。

また、投稿やチームメンバー募集の編集・削除機能を追加するために、ユーザーアカウント登録機能も実装しようと考えています。これによって、チームメンバー募集機能に、現在の募集採用人数を反映させることができます。

<a id="anchor10"></a>

### 注力したこと（こだわり等）

- 診断機能において、ユーザーのハッカソンに対する技術レベルを診断する基準および技術レベルを考慮した「ハッカソン当日までに何を準備しておけば良いか」、「ハッカソン当日にどう振る舞えば良いか」の提案内容

- 診断機能には類似ユーザーの投稿を推薦するために、ピアソンの積率相関係数を用いたアイテムベース協調フィルタリングを用いた推薦システムAPIを実装しました。 

- 上記の推薦システムを実装するにあたり、アプリケーションの実装に使用しているJavaより、Pythonの方が数値計算に適しているため、外部 API として別で実装し、アプリからそのAPI を叩いて取得するという構成にしました。

<a id="anchor11"></a>

## 開発技術

<a id="anchor12"></a>

### 活用した技術

<a id="anchor13"></a>

#### フレームワーク・ライブラリ・モジュール

- HackathonRunner
  - フロントエンド
    - HTML/CSS
    - JavaScript
    - Bootstrap
    - Chart.js
  - バックエンド
    - Spring Boot
    - Java
    - Maven
    - HackathonRunner-Analysis-API
  - インフラ
    - Heroku
    - Heroku Postgres
- HackathonRunner-Analysis-API
  - Django
  - Python
  - Heroku

<a id="anchor14"></a>

### 独自技術

<a id="anchor15"></a>

#### ハッカソンで開発した独自機能・技術

- チームメンバー募集機能
  - 募集の新規作成、一覧表示

