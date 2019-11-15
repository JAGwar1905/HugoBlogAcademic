---
title: Docker on CentOS 8
summary: Docker on CentOS 8.
tags:
- Docker
- DevOps
- Web Development

date: "2019-11-11T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Docker
  focal_point: Smart

#links:
#- icon: facebook
#  icon_pack: fab
#  name: Follow
#  url: https://www.facebook.com/jasongray85

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

# SET UP THE REPOSITORY

$ sudo yum install -y yum-utils \
   device-mapper-persistent-data \
   lvm2

$ sudo yum-config-manager \
    --add-repo \
    https://download.docker.com/linux/centos/docker-ce.repo


# INSTALL DOCKER ENGINE - COMMUNITY

$ sudo yum install docker-ce docker-ce-cli containerd.io


