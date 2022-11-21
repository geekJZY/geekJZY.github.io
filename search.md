layout: default
permalink: /search/
title: "Search"
redirect_from:
  - /search.html
menu: main
---
<head>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="/css/style.css">
</head>
<div class = "container">
  Hello~~
  <div class = "row">
    <div class = "col-md-2">
        <br>
        <img src="/images/Time.png" >
    </div>
    <div class = "col-md-10">
     <!-- <article class = "post page">
        <header class = "post-header">
          <div id = "breadcrumbs">
            <a href="/">Home</a>/ Search
          </div>
          <h1 class="post-title">Search</h1>
        </header>
        <div class = "post-content">
          <h2 id="simple-site-search">Simple Site Search</h2>
          <div class = "row">
            <div class = "col-md-12">
              {% include search-lunr.html %}
            </div>
          </div>
        </div>
      </article>-->
      <header class = "post-header">
        <div id = "breadcrumbs">
          <a href="/">Home</a>/ Search
        </div>
        <h1 class="post-title">Search</h1>
      </header>
      <div class = "post-content">
        <h2 id="simple-site-search">Simple Site Search</h2>
        <div class = "row">
          <div class = "col-md-12">
            {% include search-lunr.html %}
          </div>
        </div>
      </div>
    </div>
  </div>
</div>