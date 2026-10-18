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
        I am passionate about exploring how data-driven insights can transform educational practices and improve student outcomes.

        Since 2013, I have also been actively involved in mobile application development, specializing in both Android and cross-platform solutions. As an entrepreneur and freelancer, I have created applications for a wide range of sectors, gaining experience in project management, user experience design, and adapting technology to solve real-world problems — especially within educational settings.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
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
