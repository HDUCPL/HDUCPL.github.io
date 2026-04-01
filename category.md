---
layout: categories
title: "文章分类"
permalink: /categories/
author_profile: true
---


<script>
  // 智能路由：如果发现用户点击了特定分类，自动跳转到精美页面
  window.onload = function() {
    var hash = window.location.hash;
    if (hash === "#科研成果" || window.location.pathname.includes("科研成果")) {
      window.location.href = "{{ '/research/' | relative_url }}";
    } else if (hash === "#最新动态" || window.location.pathname.includes("最新动态")) {
      window.location.href = "{{ '/news/' | relative_url }}";
    }
  };
</script>