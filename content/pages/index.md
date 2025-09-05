---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Guilty Games
      color: text-light
      type: TitleBlock
    subtitle: Vision & Mission
    text: >
      At Guilty Games, we seek to create novel experiences that captivate
      players and leave an impact on the world. As a teaching studio, our
      mission extends beyond game development, as we're dedicated to fostering
      an inclusive space for people to learn and grow, while supporting each
      other along the way. Ready to join us? Let's play.
    actions:
      - label: Steam
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - type: Button
        label: Discord
        altText: ''
        url: 'https://discord.gg/hmjrNCJyTa'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    media:
      url: /images/Logo_GG.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Est 2024
      color: text-neutral
      type: Badge
    elementId: ''
    colors: bg-dark-fg-light
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - title:
      text: Games
      color: text-light
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - title: Snowball's Chance In Hell
        tagline: This is the tagline
        subtitle: December 2025
        text: |
          Fall 2025
        image:
          url: /images/SCIH.png
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Made of Clay
        tagline: This is the tagline
        subtitle: July 2026
        text: |
          Summer 2026
        image:
          url: /images/MoC.png
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Project Z
        tagline: This is the tagline
        subtitle: July 2028
        text: |
          Summer 2028
        image:
          url: /images/ProjectZ.png
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - type: FeaturedItemsSection
    title:
      text: What we do
      color: text-light
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Games
        subtitle: ''
        text: |
          ...
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
        tagline: ''
      - title: Game Consulting
        subtitle: ''
        text: |
          ...
        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
        tagline: ''
      - type: FeaturedItem
        title: Indie Solutions
        subtitle: ''
        text: |
          ...
        image:
          type: ImageBlock
          url: /images/icon1.svg
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
    actions: []
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: two-col-grid
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title: Divider
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - subtitle: ...
    images:
      - altText: Empathy logo
        type: ImageBlock
      - url: /images/knight lvl2 F.png
        altText: Contentful logo
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Sanity logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-dark-fg-light
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - title: Divider
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
