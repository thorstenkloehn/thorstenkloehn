---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
draft: false
menu: 
  main:
    name: '{{ replace .File.ContentBaseName "-" " " | title }}'
    url: "/"
    weight: 1
---
