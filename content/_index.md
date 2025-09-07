---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-08-29
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:

  - block: resume-biography-3-custom
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: DOWNLOAD CV
        url: uploads/Hellstern_Michael_CV.pdf
    design:
      css_class: light
      background:
        color: white

  - block: sidetitle
    id: news
    content:
      title: News
      title_link_folder: news
      # Choose how many pages you would like to display (0 = all pages)
      count: 6
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
      filters:
        folders:
          - news
      archive:
        text: "See all news"
    design:
      titlewidth: 1/4
      contentwidth: 3/4
      css_class: light
      # Choose a layout view
      view: news
      background:
        color: "rgb(247, 247, 247)"

  - block: sidetitle
    id: pubs
    content:
      count: 5
      title: Publications
      title_link_folder: publications
      text: ""
      filters:
        folders:
          - publications
      archive:
        text: "See all publications"
    design:
      view: citation
      titlewidth: 1/4
      contentwidth: 3/4
      css_class: light

  - block: sidetitle
    id: talks
    content:
      title: Talks
      title_link_folder: talks
      filters:
        folders:
          - talks
      archive:
        text: "See all talks"
    design:
      view: talk
      titlewidth: 1/4
      contentwidth: 3/4
      css_class: light
      background:
        color: "rgb(247, 247, 247)"
---
