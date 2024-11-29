---
title: "{{ replace .Name "-" " " | title }}"
description: "This is meta description"
date: {{ .Date }}
image: "images/{{ .Name }}.jpg"
alt: "Describe the image visually."
tags: ["tag"]
categories: ["categories"]
draft: true
type: "regular"
sitemapExclude: false
---
