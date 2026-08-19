---
title: ''
summary: ''
date: 2026-06-23
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |-
        I am an Acting Professor of English Language and Linguistics at HHU Düsseldorf. My research focuses on the intersection of psycholinguistics and pragmatics, specifically investigating (written) language production, perception, and the relation between speech and spelling.
      button:
        text: View University Profile
        url: https://www.anglistik3.hhu.de/en/faculty/staff/dr-julia-muschalik
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
      title: 'My Research'
      subtitle: ''
      text: |-
        My work explores how morphological structure affects the planning and execution of language, with a particular interest in typing and speech duration. I also investigate the pragmatics of threatening and conflictive illocutions.
    design:
      columns: '1'
  - block: content-collection
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
  - block: content-collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: content-collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: content-collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      subtitle: ''
      text: |-
        Since 2010, I have taught a wide range of BA- and MA-level courses on both micro- and macro-linguistic topics, as well as methodological developments and issues. I have successfully supervised a number of BA- and MA-theses.

        **Current courses (Summer 2026):**

        - Word-Formation
        - Examens- und Forschungskolloquium
        - First words and foreign accents: Learning a second language
        - Making meaning measurable: Experimental Pragmatics
        - Statistics for Beginners
        - Words don't mean things (people do)
    design:
      columns: '1'
---
