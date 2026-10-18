---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-10-18
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a slug in `data/authors/`)
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
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
      title: 'Research'
      subtitle: ''
      text: |-
        My primary research line centers on the **LARA framework** (Learning Analytics for Reactive Assistance) and **Leia 2.0**, an AI-powered pedagogical assistant for programming education, which I have studied with cohorts of engineering students in Colombia. I have also developed learning analytics infrastructure for pair programming research.

        Previously, as a researcher at Fundación Universitaria Konrad Lorenz and during my PhD at Universitat Pompeu Fabra, I studied computer-supported collaborative learning, flow experience and social media literacy.

        I am also a mobile and web applications developer, and have designed and built platforms for fintech, crowdfunding and educational services.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Recent Publications
      filters:
        folders:
          - publications
    design:
      view: citation
  # To show your latest blog posts here, uncomment this block once you
  # have published your first post in `content/blog/`.
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent Posts
  #     page_type: blog
  #     count: 5
  #     order: desc
  #   design:
  #     view: card
---
