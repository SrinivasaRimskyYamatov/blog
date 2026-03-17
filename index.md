---
layout: home
title: "Home"
---

# Rimsky Blog

色々やる技術系ブログ
<input type="text" id="search-input" placeholder="検索..." />
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
