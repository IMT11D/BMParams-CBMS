---
layout: default
title: 我的博客首页
---

# 欢迎来到我的博客 🌟

这是我的个人博客，用于**开源实践课程**作业。

---

## 📝 最新文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y年%m月%d日" }}
    </li>
  {% endfor %}
</ul>

---

## 📚 关于本站

- 使用 **Jekyll** 静态站点生成器
- 通过 **GitHub Actions** 自动部署
- 托管在 **GitHub Pages** 上
