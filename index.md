---
layout: home
title: "Rimsky Blog | 技術ブログ・プログラミング記録"
description: "Rimsky Blogではプログラミングや技術に関する学習記録や解説を発信しています。"
---

## Rimsky Blog

このサイトでは、プログラミングや技術に関する情報を発信しています。

## 内容
- プログラミング学習記録
- 技術解説
- 開発メモ

## このブログについて
Rimsky Blogは、日々の学習や開発で得た知識をまとめた技術ブログです。
初心者にも分かりやすく解説することを目指しています。
## 🔍 検索

<input type="text" id="search-input" placeholder="記事を検索..."
style="width:100%;padding:10px;border-radius:10px;border:none;background:#161b22;color:#fff;" />

<ul id="results"></ul>

<script src="https://unpkg.com/simple-jekyll-search/dest/simple-jekyll-search.min.js"></script>

<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results'),
  json: '/search.json',
  searchResultTemplate: '<li><a href="{url}">{title}</a></li>',
  noResultsText: '見つからない'
});
</script>

---

## 📝 記事一覧

{% for post in site.posts %}
<div class="post">
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
</div>
{% endfor %}
