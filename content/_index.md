---
title: ''
summary: ''
date: 2026-06-23
type: landing

sections:
  - block: resume-biography-3
    content:
      username: julia
      text: |-
        I am an Acting Professor of English Language and Linguistics at HHU Düsseldorf. My research focuses on the intersection of psycholinguistics and pragmatics, specifically investigating (written) language production, perception, and the relation between speech and spelling.
      button:
        text: View University Profile
        url: https://www.anglistik3.hhu.de/team/detailseite-muschalik
      headings:
        about: 'About Me'
        education: 'Education'
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My work explores how morphological structure affects the planning and execution of language, with a particular interest in typing and speech duration. I also investigate the pragmatics of threatening and conflictive illocutions.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
