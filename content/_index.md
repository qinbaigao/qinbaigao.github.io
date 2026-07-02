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
      headings:
        about: About
        education: Education
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
    id: internships
    content:
      title: 实习经历
      text: |
        <div class="internship-list">
          <div class="internship-item">
            <div>
              <div class="internship-company">阿里巴巴</div>
              <div class="internship-team">千问 C 端事业群 · 千问算法 · 大模型训练及应用</div>
            </div>
            <div class="internship-time">2026.07 - 至今</div>
          </div>
          <div class="internship-item">
            <div>
              <div class="internship-company">蚂蚁集团</div>
              <div class="internship-team">财保技术部 · 多模态推理算法组 · VLM 隐空间推理</div>
            </div>
            <div class="internship-time">2026.03 - 2026.07</div>
          </div>
          <div class="internship-item">
            <div>
              <div class="internship-company">美团 AI</div>
              <div class="internship-team">视觉智能部 · AutoML 算法组 · YOLOv6 开发</div>
            </div>
            <div class="internship-time">2022.04 - 2022.07</div>
          </div>
        </div>
    design:
      spacing:
        padding: ["1rem", "0", "1rem", "0"]
  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
      sort_by: Weight
      sort_ascending: true
    design:
      view: publication-detail
      show_date: false
      show_read_time: false
---
