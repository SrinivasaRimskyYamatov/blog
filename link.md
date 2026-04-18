---
layout: page
title: "Link"
---

<style>
.link-container {
  display: grid;
  gap: 14px;
  max-width: 500px;
  margin: 0 auto;
}

.link-card {
  display: flex;
  align-items: center;
  padding: 14px 18px;
  border-radius: 14px;
  text-decoration: none;
  color: #eee;
  font-weight: 500;
  background: #1e1e1e;
  border: 1px solid #2a2a2a;
  transition: 0.2s;
}

.link-card:hover {
  transform: translateY(-2px);
  background: #2a2a2a;
}

/* 控えめアクセント */
.home:hover { border-color: #4CAF50; }
.youtube:hover { border-color: #ff5555; }
.note:hover { border-color: #41C9B4; }
.github:hover { border-color: #888; }

.icon {
  margin-right: 12px;
}

.icon img {
  width: 22px;
  height: 22px;
  object-fit: contain;
}

.desc {
  font-size: 12px;
  opacity: 0.6;
}
</style>

<div class="link-container"> <a class="link-card home" href="http://home.rimsky.f5.si">
      <span class="icon">
        <img src="https://raw.githubusercontent.com/SrinivasaRimskyYamatov/blogimages/main/newtf.png">
      </span>
      <div>
        Home<br>
        <span class="desc">ホームページ</span>
      </div>
    </a>

  <a class="link-card youtube" href="https://youtube.com/channel/UCwAyGE_6uz7BBU2qr5dF5lw?si=GVfhuCMuIwFaIHKY">
    <span class="icon">▶️</span>
    <div>
      YouTube<br>
      <span class="desc">動画投稿（予定）</span>
    </div>
  </a>

  <a class="link-card note" href="https://note.com/rimsky_2672">
    <span class="icon">📝</span>
    <div>
      Note<br>
      <span class="desc">機械語とか</span>
    </div>
  </a>

  <a class="link-card github" href="https://github.com/SrinivasaRimskyYamatov">
    <span class="icon"><img src="https://raw.githubusercontent.com/SrinivasaRimskyYamatov/blogimages/main/github.png"></span>
    <div>
      GitHub<br>
      <span class="desc">コード公開</span>
    </div>
  </a>

</div>
