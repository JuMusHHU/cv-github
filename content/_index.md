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
        I am currently Acting Professor of English Language and Linguistics at Heinrich Heine University Düsseldorf. My research investigates language production and processing, with a particular interest in how linguistic knowledge emerges from experience and how different types of information interact during language use.
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
        My work examines written language production and the relationship between writing and speech, including the interaction of phonological, orthographic, and morphological information across modalities. I also work on empirical pragmatics and, more recently, multimodal communication. Methodologically, I combine experimental, corpus-based, and quantitative approaches.
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
