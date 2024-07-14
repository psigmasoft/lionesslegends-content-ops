---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Lioness Legends
      color: text-dark
      type: TitleBlock
    subtitle: UEFA Euro 2022 Champions!
    text: >
      Get the latest news, views and match results for the England Women's
      football team, the Lionesses.
    actions:
      - label: Latest news
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Results
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/lionesses-euros-in-blue.webp
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
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
  - posts:
      - content/pages/blog/case-study-3.md
      - content/pages/blog/track-the-right-analytics-for-your-business.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
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
  - type: GenericSection
    title:
      text: Match Highlights
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: ''
    text: |
      Watch the latest England Lionesses highlights here
    actions: []
    media:
      title: Title of the video
      url: 'https://youtu.be/7ifX_BV-1Yk?si=ProRD-t3Kyyzs8tE'
      autoplay: false
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
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
  - type: CarouselSection
    title: null
    subtitle: Lioness T-shirts
    items:
      - title: “Pink England T-shirt.”
        tagline: Pink Tee
        subtitle: ''
        text: |
          Lovely pink England Lionesses T-shirt
        image:
          url: >-
            /images/england-mono-logo-graphic-t-shirt-pink-womens_ss4_p-13346265+u-r3hubr7i7xpdbe661hen+v-ea29c580a8a3499ebee0868ca3877f14.avif
          altText: T-shirt
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Get in touch!
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Do you have any special memories of watching the lionesses?  We'd love to
      hear from you!
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
---
