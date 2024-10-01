---
type: PageLayout
title: Home
colors: colors-a
sections:
  - type: CtaSection
    title: 'Hello, my name is Williams Ozserttas a 42 Student.'
    text: |+


    actions: []
    colors: colors-c
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
        borderStyle: dashed
      title:
        textAlign: center
      text:
        textAlign: center
      actions:
        justifyContent: center
  - type: HeroSection
    title: About me
    subtitle: >-
      I am 28 years old currently preparing for a Digital Architect title at 42
      School.
    actions:
      - type: Button
        label: View Resume
        altText: /
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/me.jpg
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-c
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderColor: border-secondary
      title:
        textAlign: left
        fontWeight: 400
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    text: >
      I have been passionate about computers and technology since I was young, I
      like to learn new things and also to pass them on.

      I am looking for a 6-month internship in Paris as a developer.
  - type: LabelsSection
    title: Skills
    subtitle: ''
    items:
      - type: Label
        label: Linux
        url: /
      - type: Label
        label: MacOS
        url: ''
      - type: Label
        label: Windows
        url: ''
      - type: Label
        label: Bash/Shell
        url: ''
      - type: Label
        label: C/C++
        url: ''
      - type: Label
        label: HTML/CSS
        url: ''
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: JavaScript
        url: ''
      - type: Label
        label: Arduino
        url: ''
      - type: Label
        label: Django
        url: ''
      - type: Label
        label: Next.js
        url: ''
      - type: Label
        label: PostgreSQL
        url: ''
      - type: Label
        label: Docker
        url: ''
      - type: Label
        label: Docker-compose
        url: ''
      - type: Label
        label: GitHub
        url: ''
      - type: Label
        label: Visual Studio Code
        url: ''
    colors: colors-c
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
---
