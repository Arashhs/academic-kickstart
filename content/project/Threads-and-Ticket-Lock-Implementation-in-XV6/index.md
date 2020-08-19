---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Threads and Ticket Lock Implementation in Xv6"
summary: "Implementing threads as well as ticket lock in Xv6's kernel"
authors: []
tags: ["1"]
categories: []
date: 2020-08-18T06:58:17+04:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "© Arash Hajisafi"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Arashhs/XV6-OS-Final-Project"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
I have implemented threads and ticket lock in Xv6 for the final project of my Operating Systems course
- Modified XV6 process allocation, execution, and termination implementations to add support
for threads so that each process can have multiple threads
- Modified scheduling algorithm to schedule threads
- Added Ticket Lock to the kernel