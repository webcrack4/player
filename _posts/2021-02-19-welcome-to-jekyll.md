---
layout: post
title: 'Welcome to Jekyll!'
date: 2021-02-19 23:17:16 +0000
categories: jekyll update
---

{% assign mp3_files = site.static_files | where: "mp3", true %}
{%- for mp3 in mp3_files -%}
  {{ mp3.path }}
{%- endfor -%}
