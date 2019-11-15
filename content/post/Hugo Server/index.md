---
title: Hugo Server
summary: Getting the Hugo Server to do what I want it to do.
tags:
- Hugo
- Web Development

date: "2019-11-11T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Hugo Server
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


# Getting the Hugo Server to do what I want it to do. 

- Home Ip 192.168.1.15
- hugo server --bind "192.168.1.15" -p 80 

- Work Ip 192.168.254.108
- hugo server --bind "192.168.254.108" -p 80 


- --bind string            
interface to which the server will bind (default "127.0.0.1")

- -p, --port int               
port on which the server will listen (default 1313)

- --gc                     
enable to run some cleanup tasks (remove unused cache files) after the build


# Creating new post and project

- hugo new post/pagename/index.md
- hugo new project/pagename/index.md

Not using the right template?

More to come...


