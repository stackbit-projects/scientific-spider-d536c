---
title: FAQ
layout: PageLayout
sections:
  - elementId: ''
    variant: variant-b
    colors: colors-f
    title: About us
    subtitle: Featured people section example
    actions: []
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/dianne-ameter.json
      - content/data/team/hilary-ouse.json
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPeopleSection
  - elementId: ''
    colors: colors-f
    title: Where did everyone go?
    text: >
      Learn how top tech companies have learned working remote using our
      product.
    actions:
      - type: Button
        label: Sign Up
        url: /
        style: secondary
      - type: Button
        label: Watch Video
        url: /
        style: link
        showIcon: true
        icon: arrowRight
    media:
      type: ImageBlock
      url: /images/hero-3.jpg
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-20
          - mb-20
          - ml-20
          - mr-20
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
---
