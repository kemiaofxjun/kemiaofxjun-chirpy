---
layout: page
title: 微语
icon: fas fa-comments
order: 5
---

<head>
  <link rel="stylesheet" href="https://cdn.cbd.int/kemiaofxjun-cdn@1.0.3/css/qexo-talk/talk.css">
  <script src="https://cdn.cbd.int/kemiaofxjun-cdn@1.0.3/js/qexo-talk/talk.js"></script>
</head>

<div id="my-shouts-container"></div>

<script>
  myQexoShouts.init({
    el: "#my-shouts-container",
    avatar: "https://img.314926.xyz/images/2025/08/13/no-background-kemiaofxjun.webp",
    name: "克喵爱吃卤面",
    limit: 10,
    baseURL: "https://qexo.kemeow.top",
  }).catch(function(error) {
    console.error("加载过程中出现问题:", error);
  });
</script>
