---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-10-20
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: cta-image-paragraph
    content:
      items:
        -
          name: "Introduction"
          description: "Quick Intro with Image"
          title: "The Hugo Blox Theme — **typewired**"
          text: "[**typewired**](https://www.typewired.com) is a customized Hugo Blox theme created by Shaun Assam. **typewired** was derived from the Hugo Blox Academic CV with the addition of the Documentation templates."
          image: "typewired-logo.png"
          button:
            text: "Get the theme from GitHub"
            url: "https://github.com/shaunassam/typewired-template"
    design:
      background:
        color: "#2e2e2e"
        text_color_light: true
        spacing:
          padding: ["0", "0", "0", "0"]
          columns: "2"
        css_style: "color: #fdfcfc;"
  - block: collection
    id: posts
    content:
      title: Recent Posts
      filters:
        folders:
          - /
          - stories
          - articles
          - blog
          - docs
          - projects
        featured_only: false
      count: 6
    design:
      view: article-grid
      columns: 3
---
