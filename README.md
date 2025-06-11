<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>○○ ○○ | ナレーター ポートフォリオ</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Noto Sans JP', sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #111;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    nav {
      margin-top: 20px;
    }
    nav a {
      margin: 0 15px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #f39c12;
    }
    section {
      max-width: 900px;
      margin: 60px auto;
      padding: 0 20px;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    h1, h2 {
      text-align: center;
      margin-bottom: 20px;
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
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    }
    .audio-sample {
      margin: 30px 0;
    }
    audio {
      width: 100%;
    }
    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 80px;
      font-size: 0.9em;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li {
      margin: 8px 0;
    }
    a.email, a.sns {
      color: #f39c12;
      text-decoration: none;
    }
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>○○ ○○ Official Website</h1>
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
      <source src="sample-edu.mp3" type="audio/mpeg">
      お使いのブラウザはaudioタグに対応していません。
    </audio>
  </div>
</section>

<section id="contact">
  <h2>お問い合わせ</h2>
  <p>お仕事のご依頼・ご相談は下記よりお気軽にご連絡ください。</p>
  <ul>
    <li>📧 メールアドレス：<a href="mailto:yourmail@example.com" class="email">yourmail@example.com</a></li>
    <li>📱 SNS：
      <a href="https://twitter.com/yourname" target="_blank" class="sns">Twitter</a> /
      <a href="https://instagram.com/yourname" target="_blank" class="sns">Instagram</a>
    </li>
  </ul>
</section>

<footer>
  <p>&copy; 2025 ○○ ○○ All Rights Reserved.</p>
</footer>

</body>
</html>
