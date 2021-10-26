---
title: About us
sections:
  - type: HeroSection
    title: Our story
    text: >
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus vel
      venenatis augue. Suspendisse tincidunt, nibh eget sodales eleifend, lectus
      magna elementum lorem, ut bibendum tellus turpis quis risus. Vivamus
      sagittis enim est, et semper lectus hendrerit ut.


      In sollicitudin imperdiet turpis quis accumsan. Pellentesque euismod
      turpis et nisi fermentum accumsan.
    feature:
      type: ImageBlock
      url: /images/about.jpg
      altText: About us
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - elementId: ''
    variant: variant-a
    colors: colors-a
    backgroundWidth: full
    title: The Team
    subtitle: An optional subtitle of the section
    actions: []
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/dianne-ameter.json
      - content/data/team/hilary-ouse.json
      - content/data/team/person-evcrq76qa.json
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPeopleSection
  - elementId: ''
    colors: colors-a
    backgroundWidth: full
    title: Testimonials
    subtitle: What our customers say about us
    testimonials:
      - quote: >-
          It’s great to see someone taking action while still maintaining a
          sustainable fish supply to home cooks.
        name: Isabelle Parks
        title: Head chef at The Cook
        image:
          type: ImageBlock
          url: /images/isabelle-parks.jpg
          altText: Photo of Isabelle Parks
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: col
          quote:
            textAlign: center
          name:
            fontWeight: 400
            fontStyle: normal
            textAlign: center
          title:
            fontWeight: 400
            fontStyle: normal
            textAlign: center
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
    type: TestimonialsSection
layout: PageLayout
---
