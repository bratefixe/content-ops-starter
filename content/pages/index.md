---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: 'Connecting your brand with sports, games, music and entertainment'
      color: text-dark
      type: TitleBlock
    subtitle: A new media model
    text: >+
      Our mission is to align brand expectations with the experiences of sports
      and entertainment through strong and secure partnerships.

    actions: []
    media:
      url: /images/S.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
      styles:
        self:
          borderColor: border-neutral
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: ImageGallerySection
    subtitle: Our customers
    images:
      - type: ImageBlock
        altText: Empathy logo
        elementId: ''
      - type: ImageBlock
        altText: Wellster logo
        elementId: ''
      - type: ImageBlock
        url: /images/2.png
        altText: Vise logo
        elementId: ''
      - type: ImageBlock
        url: /images/1.png
        altText: Telus logo
        elementId: ''
      - type: ImageBlock
        url: /images/3.png
        altText: Contentful logo
        elementId: ''
      - type: ImageBlock
        url: /images/4.png
        altText: Sanity logo
        elementId: ''
      - type: ImageBlock
        altText: Rangle logo
        elementId: ''
    elementId: ''
    motion: static
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Send your project to connect it with amazing experiences
      color: text-dark
      type: TitleBlock
    subtitle: Let us help
    text: >+

      We will help your brand connect with brands that share values aligned with
      your goals.

    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
isDraft: false
---
