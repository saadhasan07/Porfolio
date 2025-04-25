---
# Leave the homepage title empty to use the site title
title: Saad Hasan
role: DevOps & Cloud Engineer | Certified Scrum Master
organizations:
  - name: Techstarter GmbH
    url: 'https://www.techstarter.de'
interests:
  - Cloud Automation
  - CI/CD Pipelines
  - Infrastructure as Code
  - Agile & Scrum
  - Scalable Systems
  - Web Application Development
education:
  - course: Expert in Cloud and Web Development
    institution: Techstarter GmbH, Hamburg
    year: 2023-2024
  - course: Bachelor of Commerce
    institution: Dhadabhoy University, Karachi
    year: 2014
skills:
  - AWS
  - Azure
  - Docker
  - Kubernetes
  - Terraform
  - Jenkins
  - GitHub Actions
  - Prometheus
  - Grafana
  - React.js
  - Node.js
  - Python
  - TypeScript
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: Recent Projects
      filters:
        folders:
          - project
    design:
      view: card
      columns: '2'
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---

I am a passionate DevOps & Cloud Engineer and Certified Scrum Master with a strong background in automating cloud deployments, building CI/CD pipelines, and implementing infrastructure as code. I thrive on solving complex challenges and delivering scalable, reliable solutions using AWS, Azure, Docker, and Kubernetes. My experience spans full-stack web development, cloud-native architectures, and Agile team facilitation.

I believe in continuous improvement—both for technology and teams. My mission is to bridge the gap between development and operations, enabling organizations to innovate faster and more securely. I enjoy collaborating with diverse teams, mentoring others, and keeping up with the latest in cloud and DevOps practices.

When I'm not coding or automating workflows, you'll find me playing football, swimming, or exploring new tech trends. Let's connect and build something amazing together!
