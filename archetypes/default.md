---
guid: "path to mp3"
title: "{{ replace .Name "-" " " | title }}"
link: "audio/Ep001.mp3"
description: "Welcome to Episode 1 - Lets Rock!"
pubDate: {{ .Date }}
length: 110
itunesAuthor: {{ .Site.email }}
itunesSummary: {{ .Site.itunesSummary }}
itunesImage: {{ .Site.itunesImage }}
draft: false
latest: false
epURL: "/"
episodeNumber: 001
---