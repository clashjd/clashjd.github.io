---
layout: default
title: Clash使用教程 | Windows、macOS、Android、iOS全平台配置指南
description: 免费获取Clash最新使用教程！涵盖Windows、macOS、Android、iOS等全平台配置指南，包含Clash for Windows、Clash Verge、手机端设置及免费节点分享。简单易懂，助您快速上手，畅享网络自由！
keywords: "Clash使用教程,Clash for Windows配置,macOS Clash教程,Android Clash设置,iOS Clash指南,Clash Verge教程,Clash免费节点,Clash代理设置,Clash手机端配置,Clash电脑端教程,Clash全平台指南
"
permalink: /post/
---

<div class="container">
  <h1>📘 使用教程文章列表</h1>
  <ul>
    {% for post in site.categories.tutorials %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span>（{{ post.date | date: '%Y-%m-%d' }}）</span>
      </li>
    {% endfor %}
  </ul>
</div>
