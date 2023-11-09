---
# Leave the homepage title empty to use the site title
title: ''
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
  - block: portfolio
    id: publication
    content:
      title: Journal Articles
      filters:
        folders:
          - publication
      design:
        columns: '1'
        view: citation
  - block: portfolio
    id: paper
    content:
      title: Working Papers
    filters:
        folders:
          - paper
      design:
        columns: '1'
        view: compact
  - block: portfolio
    id: project
    content:
      title: Works in Progress
      filters:
        folders:
          - project
    design:
      columns: '1'
      view: list
---
