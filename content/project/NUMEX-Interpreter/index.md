---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NUMEX Interpreter"
summary: "A pure functional implementation of NUMEX (Number Expression Programming Language) written in Racket"
authors: []
tags: ["3"]
categories: []
date: 2020-08-19T04:47:57+04:30

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/Arashhs/NUMEX-Interpreter"

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

url_code: ""
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
__Example Command__:
```lisp
(eval-exp (with "f1" (lam "f1" "a" (with "x" (var "a") (lam "f2" "z" (plus (var "x") (num 1)))))
                               (with "f3" (lam "f3" "f" (with "x" (num 1729) (apply (var "f") (munit)))) 
                                     (apply (var "f3") (apply (var "f1") (num 1))))))
```

__Output__:
```
(num 2)
```