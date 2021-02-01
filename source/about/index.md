---
title: about
keywords: 关于
layout: "about"
comments: false
photos: https://cdn.jsdelivr.net/gh/FengYJ120/CDN/MyBlog/img/banner/about.jpg
date: 2021-01-18 21:50:10
---
<!-- https://www.bootcdn.cn/botui/ -->
<link href="https://cdn.bootcss.com/botui/0.3.9/botui-theme-default.css" rel="stylesheet">
<link href="https://cdn.bootcss.com/botui/0.3.9/botui.min.css" rel="stylesheet">

{% raw %}
<!-- 因为vue和botui更新导至bug,现将对话移至js下的botui中配置 -->
<div class="entry-content">
  <div class="moe-cungudafa" style="text-align:center; font-size: 50px; margin-bottom: 20px;">ZEROのBlog</div>
  <div id="hello-cungudafa" class="popcontainer" style="min-height: 300px; padding: 2px 6px 4px; background-color: rgb(36, 200, 255); border-radius: 10px;">
    <center>
    <p>
    </p>
    <h1>模块开发中，敬请期待</h1>    
    <p>
    </p>
    </center>
    <bot-ui></botui>
  </div>
</div>
<script src="/js/botui.js"></script>
<script>
 bot_ui_ini()
</script>
{% endraw %}