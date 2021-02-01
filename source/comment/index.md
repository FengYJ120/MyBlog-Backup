---
title: comment
type: comment
layout: "comment"
photos: https://cdn.jsdelivr.net/gh/FengYJ120/CDN/MyBlog/img/banner/comment.jpg
date: 2021-01-18 21:48:46
---
<div class="poem-wrap">
    <div class="poem-border poem-left"></div>
    <div class="poem-border poem-right"></div>
    <h1>念两句诗</h1>
    <p id="poem">正在加载今日诗词....</p>
    <p id="info"></p>
</div>
<script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>
<script type="text/javascript">
    jinrishici.load(function(result) {
    var poem =  result.data.content;
    var info = "【"+result.data.origin.dynasty+"】"+ result.data.origin.author +"《" + result.data.origin.title + "》";
    document.getElementById("poem").value(poem);
    document.getElementById("info").value(info);
    })
</script>