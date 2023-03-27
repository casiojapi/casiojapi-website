---
title: "foto"
date: 2023-02-06T10:37:03-03:00
draft: false
---

<div class="image-gallery">
{{ range $index, $image := readDir "static/images" }}
  <img src="{{ "images/" | relURL }}{{ $image.Name }}" alt="Image {{ $index }}">
{{ end }}
</div>

<div> <p>TESTESTTSETESTETSETTSETS</p>
</div>
<link rel="stylesheet" href="/css/gallery.css">