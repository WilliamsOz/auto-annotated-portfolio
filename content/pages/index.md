---
type: PageLayout
title: Home
colors: colors-a
sections:
  - type: CtaSection
    title: 'Hello, my name is Williams Ozserttas a 42 Student.'
    text: |+


    actions: []
    colors: colors-d
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
        url: /images/cv.pdf
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
    colors: colors-d
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-40
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
      - type: Label
        label: Vim
        url: ''
      - type: Label
        label: Adobe Illustrator
        url: ''
      - type: Label
        label: Microsoft Office
        url: ''
      - type: Label
        label: Notion
        url: ''
      - type: Label
        label: Trello
        url: ''
    colors: colors-d
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: true
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
---
