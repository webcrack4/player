---
layout: post
title: 'Welcome to Jekyll!'
date: 2021-02-19 23:17:16 +0000
categories: jekyll update
---

{% assign mp3_files = site.static_files | where: "mp3", true %}
{%- for mp3 in mp3_files -%}
  https://jsd.cdn.zzko.cn/gh/webcrack4/player@main{{ mp3.path }} <br />
{%- endfor -%}

<audio src="https://jsd.cdn.zzko.cn/gh/webcrack4/player@main/assets/mp3/Bittersweet%20(Movie%20Version)%20-%20%E5%B7%9D%E6%B4%A5%E6%98%8E%E6%97%A5%E9%A6%99%E3%80%81%E5%86%85%E8%97%A4%E7%A7%80%E4%B8%80%E9%83%8E%E3%80%81%E5%B1%B1%E5%8F%A3%E8%B2%B4%E4%B9%9F%E3%80%81%E9%9D%92%E6%9C%A8%E7%9E%AD.mp3" preload="none" controls="controls"/>
