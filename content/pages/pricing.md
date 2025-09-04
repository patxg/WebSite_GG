---
title: About
slug: pricing
sections:
  - title:
      text: About
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Who we are
    plans: []
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Game Development Philosophy
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Gameplay First
        subtitle: Mechanics Dictate Experience
        text: |+
          *   We prioritize tight, responsive gameplay over flashy gimmicks.

          *   Every mechanic serves a purpose. No wasted systems.

          *   Player agency, mastery, and discovery are key.



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
        tagline: ''
      - type: FeaturedItem
        title: Iterative Design
        subtitle: 'Ship Small, Build Big'
        text: >+
          *   Our modular, scalable development ensures we test early and refine
          continuously.


          *   We prototype core mechanics first before adding complexity.


          *   We embrace fail-fast learning—bad ideas get scrapped quickly.



        image:
          type: ImageBlock
          altText: Featured icon two
          elementId: ''
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
      - type: FeaturedItem
        title: 200%
        subtitle: Faster
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
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
    actions:
      - type: Button
        label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    badge:
      type: Badge
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
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
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
