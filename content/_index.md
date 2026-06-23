---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: About
        education: Education
        interests: Research Interests
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
        I study 3D vision and generative 3D content creation, especially methods built around 3D Gaussian Splatting. My recent work explores native 3D Gaussian editing, robust 3D asset protection, image-to-3D generation, and agentic systems that can plan, revise, and execute complex editing instructions in 3D scenes.

        I also work on self-supervised representation learning for visual and skeleton-based understanding, including contrastive learning, action recognition, gait recognition, and efficient perception models.

        I am always interested in collaboration around 3D-AIGC, interactive content editing, and learning systems that connect perception, generation, and controllable creation.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
---
