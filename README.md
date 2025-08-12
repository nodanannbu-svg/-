:root {
  --blue: #0b4f6c;
  --accent: #ffd97d;
  --bg: #f7fbfc;
  --muted: #5b6b73;
  --maxw: 1100px;
  font-family: "Noto Sans JP", sans-serif;
}

* { box-sizing: border-box; margin: 0; padding: 0; }
body { background: var(--bg); color: var(--blue); line-height: 1.6; }
a { color: var(--blue); text-decoration: none; }
a:hover { text-decoration: underline; }

/* 共通レイアウト */
header {
  background: #fff;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}
.navbar {
  max-width: var(--maxw);
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 20px;
}
.navbar h1 { font-size: 20px; }
.navbar ul {
  list-style: none;
  display: flex;
  gap: 18px;
}
.navbar li { font-size: 14px; }

/* ヒーロー画像 */
.hero {
  position: relative;
  height: 380px;
  overflow: hidden;
}
.hero img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.hero-text {
  position: absolute;
  bottom: 20px;
  left: 30px;
  background: rgba(0,0,0,0.5);
  color: #fff;
  padding: 12px 18px;
  border-radius: 8px;
  font-size: 18px;
}

/* メインコンテンツ */
.container {
  max-width: var(--maxw);
  margin: 30px auto;
  padding: 0 20px;
}
section { margin-bottom: 40px; }
h2 { margin-bottom: 10px; }

/* 部活動カード */
.club-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 18px;
}
.club {
  background: #fff;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}
.club img {
  width: 100%;
  height: 140px;
  object-fit: cover;
}
.club h3 { padding: 10px; font-size: 16px; }
.club p { padding: 0 10px 10px; font-size: 14px; color: var(--muted); }

/* フッター */
footer {
  background: #f1f8fb;
  padding: 14px 20px;
  text-align: center;
  font-size: 13px;
  color: var(--muted);
}
<!doctype html>
<html lang="ja">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>県立ゲッター高等専門学校</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="navbar">
    <h1>県立ゲッター高等専門学校</h1>
    <ul>
      <li><a href="index.html">ホーム</a></li>
      <li><a href="admission.html">入学案内</a></li>
      <li><a href="access.html">アクセス</a></li>
      <li><a href="staff.html">教員紹介</a></li>
      <li><a href="apply.html">募集要項</a></li>
    </ul>
  </div>
</header>

<div class="hero">
  <img src="https://images.unsplash.com/photo-1503676260728-1c00da094a0b" alt="学校外観">
  <div class="hero-text">未来を創る学びの場</div>
</div>

<div class="container">
  <section>
    <h2>学校紹介</h2>
    <p>県立ゲッター高等専門学校は、校長ダイアン・ゴンザレスのもと、全日制で9クラスを擁する専門教育機関です。マーチングバンド部は全国大会で2年連続金賞を受賞。新設された野球部をはじめ、陸上部、鉄道研究部、料理部など多彩な部活動があります。</p>
  </section>

  <section>
    <h2>部活動紹介</h2>
    <div class="club-list">
      <div class="club">
        <img src="https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4" alt="マーチングバンド部">
        <h3>マーチングバンド部</h3>
        <p>全国大会2年連続金賞の実力派。美しい演奏と迫力のパフォーマンス。</p>
      </div>
      <div class="club">
        <img src="https://images.unsplash.com/photo-1507842217343-583bb7270b66" alt="野球部">
        <h3>野球部</h3>
        <p>新設ながら日々練習に励み、地区大会優勝を目指しています。</p>
      </div>
      <div class="club">
        <img src="https://images.unsplash.com/photo-1517649763962-0c623066013b" alt="陸上部">
        <h3>陸上部</h3>
        <p>短距離から長距離、跳躍まで幅広く活動し、多くの大会で好成績。</p>
      </div>
      <div class="club">
        <img src="https://images.unsplash.com/photo-1533142266415-ac591a4c3b9b" alt="鉄道研究部">
        <h3>鉄道研究部</h3>
        <p>模型作りから路線研究まで鉄道愛にあふれる部員たちが集います。</p>
      </div>
      <div class="club">
        <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836" alt="料理部">
        <h3>料理部</h3>
        <p>和洋中ジャンル問わず料理を探求し、文化祭では長蛇の列。</p>
      </div>
    </div>
  </section>
</div>

<footer>
  © 県立ゲッター高等専門学校 ｜ 提供：<a href="https://gptjp.net/">gptjp.net</a>
</footer>

</body>
</html>
:root {
  --blue: #0b4f6c;
  --accent: #ffd97d;
  --bg: #f7fbfc;
  --muted: #5b6b73;
  --maxw: 1100px;
  font-family: "Noto Sans JP", sans-serif;
}

* { box-sizing: border-box; margin: 0; padding: 0; }
body { background: var(--bg); color: var(--blue); line-height: 1.6; }
a { color: var(--blue); text-decoration: none; }
a:hover { text-decoration: underline; }

header {
  background: #fff;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}
.navbar {
  max-width: var(--maxw);
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 20px;
}
.navbar h1 { font-size: 20px; }
.navbar ul {
  list-style: none;
  display: flex;
  gap: 18px;
}
.navbar li { font-size: 14px; }

.hero { position: relative; height: 380px; overflow: hidden; }
.hero img { width: 100%; height: 100%; object-fit: cover; }
.hero-text {
  position: absolute; bottom: 20px; left: 30px;
  background: rgba(0,0,0,0.5); color: #fff;
  padding: 12px 18px; border-radius: 8px; font-size: 18px;
}

.container { max-width: var(--maxw); margin: 30px auto; padding: 0 20px; }
section { margin-bottom: 40px; }
h2 { margin-bottom: 10px; }

.club-list {
  display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 18px;
}
.club {
  background: #fff; border-radius: 10px; overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}
.club img { width: 100%; height: 140px; object-fit: cover; }
.club h3 { padding: 10px; font-size: 16px; }
.club p { padding: 0 10px 10px; font-size: 14px; color: var(--muted); }

footer {
  background: #f1f8fb; padding: 14px 20px;
  text-align: center; font-size: 13px; color: var(--muted);
}
<!doctype html>
<html lang="ja">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>県立ゲッター高等専門学校</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <div class="navbar">
    <h1>県立ゲッター高等専門学校</h1>
    <ul>
      <li><a href="index.html">ホーム</a></li>
      <li><a href="admission.html">入学案内</a></li>
      <li><a href="access.html">アクセス</a></li>
      <li><a href="staff.html">教員紹介</a></li>
      <li><a href="apply.html">募集要項</a></li>
    </ul>
  </div>
</header>

<div class="hero">
  <img src="https://images.unsplash.com/photo-1503676260728-1c00da094a0b" alt="学校外観">
  <div class="hero-text">未来を創る学びの場</div>
</div>

<div class="container">
  <section>
    <h2>学校紹介</h2>
    <p>県立ゲッター高等専門学校は、校長ダイアン・ゴンザレスのもと、全日制で9クラスを擁する専門教育機関です。マーチングバンド部は全国大会で2年連続金賞を受賞。新設された野球部をはじめ、陸上部、鉄道研究部、料理部など多彩な部活動があります。</p>
  </section>

  <section>
    <h2>部活動紹介</h2>
    <div class="club-list">
      <div class="club">
        <img src="https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4" alt="マーチングバンド部">
        <h3>マーチングバンド部</h3>
        <p>全国大会2年連続金賞の実力派。美しい演奏と迫力のパフォーマンス。</p>
      </div>
      <div class="club">
        <img src="https://images.unsplash.com/photo-1507842217343-583bb7270b66" alt="野球部">
        <h3>野球部</h3>
        <p>新設ながら日々練習に励み、地区大会優勝を目指しています。</p>
      </div>
      <div class="club">
        <img src="https://images.unsplash.com/photo-1517649763962-0c623066013b" alt="陸上部">
        <h3>陸上部</h3>
        <p>短距離から長距離、跳躍まで幅広く活動し、多くの大会で好成績。</p>
      </div>
      <div class="club">
        <img src="https://images.unsplash.com/photo-1533142266415-ac591a4c3b9b" alt="鉄道研究部">
        <h3>鉄道研究部</h3>
        <p>模型作りから路線研究まで鉄道愛にあふれる部員たちが集います。</p>
      </div>
      <div class="club">
        <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836" alt="料理部">
        <h3>料理部</h3>
        <p>和洋中ジャンル問わず料理を探求し、文化祭では長蛇の列。</p>
      </div>
    </div>
  </section>
</div>

<footer>
  © 県立ゲッター高等専門学校 ｜ 提供：<a href="https://gptjp.net/">gptjp.net</a>
</footer>
</body>
</html>
<!doctype html>
<html lang="ja">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>入学案内 - 県立ゲッター高等専門学校</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <div class="navbar">
    <h1>県立ゲッター高等専門学校</h1>
    <ul>
      <li><a href="index.html">ホーム</a></li>
      <li><a href="admission.html">入学案内</a></li>
      <li><a href="access.html">アクセス</a></li>
      <li><a href="staff.html">教員紹介</a></li>
      <li><a href="apply.html">募集要項</a></li>
    </ul>
  </div>
</header>

<div class="hero">
  <img src="https://images.unsplash.com/photo-1523240795612-9a054b0db644" alt="入学説明">
  <div class="hero-text">入学案内</div>
</div>

<div class="container">
  <section>
    <h2>入学までの流れ</h2>
    <ol>
      <li>学校説明会に参加</li>
      <li>願書の提出</li>
      <li>筆記試験・面接</li>
      <li>合格発表</li>
      <li>入学手続き</li>
    </ol>
  </section>

  <section>
    <h2>学校説明会日程</h2>
    <p>2025年4月・7月・10月に予定。詳細はお問い合わせください。</p>
  </section>
</div>

<footer>
  © 県立ゲッター高等専門学校 ｜ 提供：<a href="https://gptjp.net/">gptjp.net</a>
</footer>
</body>
</html>
<!doctype html>
<html lang="ja">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>アクセス - 県立ゲッター高等専門学校</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <div class="navbar">
    <h1>県立ゲッター高等専門学校</h1>
    <ul>
      <li><a href="index.html">ホーム</a></li>
      <li><a href="admission.html">入学案内</a></li>
      <li><a href="access.html">アクセス</a></li>
      <li><a href="staff.html">教員紹介</a></li>
      <li><a href="apply.html">募集要項</a></li>
    </ul>
  </div>
</header>

<div class="hero">
  <img src="https://images.unsplash.com/photo-1486308510493-aa64833634ef" alt="アクセス案内">
  <div class="hero-text">アクセス</div>
</div>

<div class="container">
  <section>
    <h2>所在地</h2>
    <p>〒000-0000　〇〇県〇〇市〇〇町1-2-3</p>
  </section>

  <section>
    <h2>交通アクセス</h2>
    <ul>
      <li>JR〇〇駅から徒歩10分</li>
      <li>〇〇バス「〇〇高校前」下車すぐ</li>
    </ul>
  </section>

  <section>
    <h2>地図</h2>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3..."
      width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
  </section>
</div>

<footer>
  © 県立ゲッター高等専門学校 ｜ 提供：<a href="https://gptjp.net/">gptjp.net</a>
</footer>
</body>
</html>
