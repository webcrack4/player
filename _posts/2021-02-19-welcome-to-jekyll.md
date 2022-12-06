---
layout: post
title: 'Welcome to Jekyll!'
date: 2021-02-19 23:17:16 +0000
categories: jekyll update
---

{% assign mp3_files = site.static_files | where: "mp3", true %}
{%- for mp3 in mp3_files -%}
  https://jsd.cdn.zzko.cn/gh/webcrack4/player@main{{ mp3.path }}
{%- endfor -%}
