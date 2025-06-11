<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ふじみ | ナレーター ポートフォリオ</title>
  <link href="https://fonts.googleapis.com/css2?family=Zen+Maru+Gothic:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Zen Maru Gothic', sans-serif;
      margin: 0;
      padding: 0;
      background: #ffffff;
      color: #333;
    }
    header {
      background: #ffffff;
      color: #333;
      padding: 50px 20px;
      text-align: center;
      box-shadow: 0 3px 8px rgba(0,0,0,0.1);
      border-bottom-left-radius: 30px;
      border-bottom-right-radius: 30px;
    }
    nav {
      margin-top: 20px;
    }
    nav a {
      margin: 0 15px;
      color: #333;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ff9966;
    }
    section {
      max-width: 900px;
      margin: 60px auto;
      padding: 40px 30px;
      background: #ffffff;
      border-radius: 20px;
      box-shadow: 0 6px 12px rgba(0,0,0,0.08);
    }
    h1, h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    h2 {
      color: #ff9966;
    }
    .intro {
      text-align: center;
      font-size: 1.2em;
      margin-bottom: 40px;
    }
    .profile-photo {
      display: block;
      margin: 20px auto;
      border-radius: 50%;
      width: 160px;
      height: 160px;
      object-fit: cover;
      box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    }
    .audio-sample {
      margin: 30px 0;
    }
    audio {
      width: 100%;
    }
    footer {
      background: #ffffff;
      color: #999;
      text-align: center;
      padding: 20px;
      margin-top: 80px;
      font-size: 0.9em;
      border-top: 1px solid #ddd;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li {
      margin: 8px 0;
    }
    a.email, a.sns {
      color: #ff9966;
      text-decoration: none;
      font-weight: bold;
    }
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
      section {
        margin: 20px 10px;
        padding: 20px 15px;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>ふじみ Official Website</h1>
  <nav>
    <a href="#profile">プロフィール</a>
    <a href="#samples">作品紹介</a>
    <a href="#contact">お問い合わせ</a>
  </nav>
</header>

<section id="top">
  <h2>「声で心を動かすナレーター」</h2>
  <p class="intro">CM・企業VP・ドキュメンタリーなど幅広いジャンルで活動中です。</p>
</section>

<section id="profile">
  <h2>プロフィール</h2>
  <img src="your-photo.jpg" alt="プロフィール写真" class="profile-photo">
  <p>ナレーター歴○年。柔らかく落ち着いた声質を活かし、企業VP・CM・Web動画・教材ナレーションなど多数担当。自宅録音環境も完備し、迅速な納品が可能です。</p>

  <h3>使用機材</h3>
  <ul>
    <li>マイク：○○○</li>
    <li>オーディオインターフェース：○○○</li>
    <li>録音環境：防音ブース完備</li>
  </ul>
</section>

<section id="samples">
  <h2>作品紹介</h2>

  <div class="audio-sample">
    <h3>CMナレーション</h3>
    <audio controls>
      <source src="sample-cm.mp3" type="audio/mpeg">
      お使いのブラウザはaudioタグに対応していません。
    </audio>
  </div>

  <div class="audio-sample">
    <h3>企業VP</h3>
    <audio controls>
      <source src="sample-vp.mp3" type="audio/mpeg">
      お使いのブラウザはaudioタグに対応していません。
    </audio>
  </div>

  <div class="audio-sample">
    <h3>教材ナレーション</h3>
    <audio controls>
      <source
