---
type: PageLayout
title: Privacy
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Unblock your team boost your time to production
      color: text-dark
    subtitle: Subtitle goes here
    text: >
      A Netlify website is a git repo that you own. Every code commit is
      instantly reflected in the visual editor and since every visual edit is a
      git commit, git workflows and collaboration just work.
    actions:
      - type: Button
        label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Link
        label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
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
  - type: ImageGallerySection
    subtitle: Award winning enterprises trust us
    images:
      - type: ImageBlock
        url: /images/empathy-logo.svg
        altText: Empathy logo
      - type: ImageBlock
        url: /images/wellster-logo.svg
        altText: Wellster logo
      - type: ImageBlock
        url: /images/vise-logo.svg
        altText: Vise logo
      - type: ImageBlock
        url: /images/telus-logo.svg
        altText: Telus logo
      - type: ImageBlock
        url: /images/contenful-logo.svg
        altText: Contentful logo
      - type: ImageBlock
        url: /images/sanity-logo.svg
        altText: Sanity logo
      - type: ImageBlock
        url: /images/rangle-logo.svg
        altText: Rangle logo
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - type: DividerSection
    title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
  - type: GenericSection
    title:
      type: TitleBlock
      text: Grow your business 10x faster
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: This is a subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
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
    badge:
      type: Badge
      label: Key Benefits
      color: text-primary
      styles:
        self:
          textAlign: center
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: Section with a video subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
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
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - type: GenericSection
    title:
      type: TitleBlock
      text: Social Media Management
      color: text-dark
    subtitle: Increase your reach
    text: >
      A service that helps businesses to manage their social media accounts and
      posts.
    actions:
      - type: Button
        label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/hero2.svg
      altText: Fun feature preview
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - type: CarouselSection
    subtitle: This is a subtitle
    items:
      - type: FeaturedItem
        title: >-
          “A designer knows he has achieved perfection not when there is nothing
          left to add, but when there is nothing left to take away.”
        tagline: Testimonial 1
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-neutralAlt-fg-dark
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
      - type: FeaturedItem
        title: >-
          “Quote from some important person goes right here. I love using
          Netlify.”
        tagline: Testimonial 2
        subtitle: 'Jane Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder-dark.png
          altText: Jane Doe
          styles:
            self:
              borderRadius: full
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
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
slug: /privacy
seo:
  type: Seo
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create
  socialImage: /images/main-hero.jpg
  metaTags: []
---
