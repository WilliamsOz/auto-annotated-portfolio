---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
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
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: wide
        padding:
          - pt-3
          - pb-3
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 4
        borderStyle: solid
  - type: HeroSection
    title: About me
    subtitle: >-
      I am 28 years old currently preparing for a Digital Architect title at 42
      School.
    actions:
      - type: Button
        label: View Resume
        altText: /
        url: >-
          /https://media.licdn.com/dms/document/media/D4E1FAQFItFs4_-J1oQ/feedshare-document-pdf-analyzed/0/1719915715921?e=1728518400&v=beta&t=E5SiugJlHfpNjg3ERv5tZ4Rd4jHrvZIlD2L_c-RFqE8
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
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
