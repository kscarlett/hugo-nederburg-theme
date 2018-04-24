---
date: {{ .Date }}
title: "{{ replace .Name "-" " " | title }}"
slug: "{{ .Name }}"
govanity: "remove if empty"
aliases: [
    "/test/log",
    "/test/cli",
]
image: "img/image.jpg"
showonlyimage: false
categories: [""Project"]
keywords: ["{{ .Name }}"]
topics: ["{{ .Name }}"]
tags: ["{{ .Name }}"]
draft: true
---