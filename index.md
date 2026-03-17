---
layout: home
title: "Home"
---

## Rimsky Blog

技術系のブログ

---

## 🔍 検索

<input type="text" id="search-input" placeholder="記事を検索..." style="width:100%;padding:10px;border-radius:10px;border:none;background:#161b22;color:#fff;" />

<ul id="results"></ul>

<script src="https://unpkg.com/simple-jekyll-search/dest/simple-jekyll-search.min.js"></script>

<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results'),
  json: '/search.json',
  searchResultTemplate: '<li style="margin:10px 0;"><a href="{url}">{title}</a></li>',
  noResultsText: '見つからない'
});
</script>

---

## 📝 最新記事

{% for post in site.posts %}
<div class="post">
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
</div>
{% endfor %}
