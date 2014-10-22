---
title: Formats
subtitle: Aggregating all the registries
---

<script src="{{ site.baseurl }}/assets/js/jekyll-search.js"></script>

<input type="text" class="search form-control" placeholder="Text input" id="search-this-page"/>

<ul id="search-results" class="results">
</ul>

<script>
JekyllSearch.init({
    searchInput: document.getElementById("search-this-page"),
    searchResults: document.getElementById("search-results"),
    jsonFile: "{{ site.baseurl }}/formats/search.json",
    template: "<li><a href='{url}' title='{desc}'>{title}</a></li>",
    fuzzy: false
});
</script>

Based on <https://github.com/christian-fei/Simple-Jekyll-Search>
