---
title: Formats
subtitle: Aggregating all the registries
---

Search
------

<script src="{{ site.baseurl }}/assets/js/jekyll-search.js"></script>

<div class="input-group">
  <span class="input-group-addon">File extension</span>
  <input type="text" class="search form-control" placeholder="*.ext" id="ext-search"/>
</div>

<ul id="ext-results" class="results">
</ul>

<script>
JekyllSearch.init({
    searchInput: document.getElementById("ext-search"),
    searchResults: document.getElementById("ext-results"),
    searchResultsHeader: "<ul>",
    searchResultsFooter: "</ul><p>Showing {limit} out of {total} matching results.</p>",
    jsonFile: "{{ site.baseurl }}/formats/search.json",
    template: "<li><a href='{url}' title='{desc}'>{title}</a></li>",
    fuzzy: false,
    limit: 20
});
</script>

<!--
Based on <https://github.com/christian-fei/Simple-Jekyll-Search>
-->