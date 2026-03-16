---
layout: null
permalink: /about/
title: About The Daily Scout
---
<!DOCTYPE html>
<html lang="en">
<head>
  {% include head.html %}
  <title>{{ page.title }} | {{ site.title }}</title>
  <meta name="description" content="About The Daily Scout — honest product roundups for smart shoppers.">
  {% seo %}
</head>
<body>
  <header class="site-header">
    <div class="container">
      <a href="{{ site.baseurl }}/" class="site-title">{{ site.title }}</a>
      <nav>
        <a href="{{ site.baseurl }}/">Home</a>
        <a href="{{ site.baseurl }}/about/">About</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <div class="page">
      <h1 class="page-title">About The Daily Scout</h1>
      <div class="post-content">
        <p>We test, compare, and rank products so you don't have to scroll through thousands of Amazon reviews. Every recommendation on this site comes from hands-on research and real-world testing.</p>

        <h3>What we cover</h3>
        <p>Home office gear, tech accessories, productivity tools, and everyday essentials — the stuff that actually makes your life better, not just your feed look cooler.</p>

        <h3>How we make money</h3>
        <p>Some links on this site are affiliate links to Amazon. If you buy something through our links, we earn a small commission at no extra cost to you. This keeps the site running and the reviews honest — we only recommend products we'd actually use ourselves.</p>

        <h3>Our promise</h3>
        <ul>
          <li>No sponsored posts disguised as reviews</li>
          <li>No filler products to pad a list</li>
          <li>No clickbait — just straight answers</li>
        </ul>
      </div>
    </div>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>&copy; {{ site.time | date: "%Y" }} {{ site.title }}. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
