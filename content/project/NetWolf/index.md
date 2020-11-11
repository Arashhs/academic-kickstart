---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NetWolf"
summary: "A Peer-to-Peer file sharing application implemented in Python"
authors: []
tags: ["1"]
categories: []
date: 2020-08-18T06:27:44+04:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Arashhs/NetWolf"
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
NetWolf is a P2P torrent-like network application written in Python for the final project of my Computer Networks Course with the following capabilities:
* Discovering clusters and maintaining a cluster list at each node by periodically sending a UDP customized DISCOVERY message
* Sharing files between nodes by sending a UDP customized GET message (which includes the file names), waiting for the answer, and selecting the best node (fastest response), and then establishing a TCP connection for transmitting the file

Application in action: (Click to open in full size on a new tab)
<a href="gif.gif" target="_blank">
![NetWolf © Arash Hajisafi](gif.gif)
</a>
