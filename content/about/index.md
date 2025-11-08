---
# Leave the homepage title empty to use the site title
title: 'About'
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '0rem'

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      #text: "For over 20 years I've been in the IT field administrating systems and supporting users. Now, I'm pivoting my career towards the role of Technical Writer to continue making technology easier for users."
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: "skills-bg-gradient dark:skills-bg-gradient"
      css_style: "padding: 2rem 1rem 0rem 1rem;"
      size: medium
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: skills
    content:
      title:
      username: admin
    design:
        css_class: "skills-bg-gradient dark:skills-bg-gradient"
        css_style: "padding-top: 3rem; padding-bottom: 4rem;"
---