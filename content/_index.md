---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
seo:
  title: 'René Lobo-Quintero, PhD – AI in Education & Learning Analytics Researcher'
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

        At Fundación Universitaria Konrad Lorenz I developed **Konrad Think-Pair-Share**, an AI-enhanced collaborative learning platform, to study how AI scaffolding affects students' creative thinking. During my PhD at Universitat Pompeu Fabra I studied computer-supported collaborative learning, flow experience and social media literacy.
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
  - block: markdown
    id: collaborate
    content:
      title: Invite me
      text: |-
        I welcome invitations to contribute as:

        - **Peer reviewer** for journals and conferences in learning analytics, AI in education, CSCL and educational technology
        - **Evaluator** of research projects, grant proposals and master's or doctoral theses
        - **Invited speaker or keynote** at conferences, seminars and institutional events
        - **Workshop facilitator** on generative AI in the classroom, learning analytics and collaborative learning design

        **Topics:** AI-assisted programming education · learning analytics · generative AI and chatbots in teaching · Think-Pair-Share and collaborative learning scripts · gamification and motivation · social media literacy.

        Talks in **Spanish or English**, in person (Bogotá, Colombia) or online.

        *Disponible como evaluador de artículos, proyectos y tesis, jurado y conferencista invitado en inteligencia artificial en educación, analítica del aprendizaje y aprendizaje colaborativo.*

        [Send an invitation](mailto:raloboq@udistrital.edu.co?subject=Invitation%20%E2%80%93%20renelobo.com)
    design:
      columns: '1'
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        📧 [raloboq@udistrital.edu.co](mailto:raloboq@udistrital.edu.co)

        🏛️ Ingeniería de Sistemas  
        Universidad Distrital Francisco José de Caldas, Bogotá, Colombia

        🆔 ORCID [0000-0003-2989-5357](https://orcid.org/0000-0003-2989-5357) · [Google Scholar](https://scholar.google.com/citations?user=jv3umq0AAAAJ)
    design:
      columns: '1'
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
