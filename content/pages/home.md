---
blocks:
  - tagline: oh for fuck's sake
    headline: headroom
    text: >-
      * Starter to make it quick and easy to get a new project idea up and
      running

      * Landing Page pulls content from content/pages/home.md,
        * components from components/blocks, and
        * puts them all together in pages/\[filename\].tsx, all based on a schema defined in .tina/schema.ts.
    actions:
      - label: Action
        type: button
        icon: true
        link: /posts
      - label: Posts(blog)
        type: link
        icon: true
        link: /posts
    image:
      src: >-
        http://res.cloudinary.com/ely-io/image/upload/v1575113491/illlustrations.co/svg/day65-city-road.svg
      alt: City Road
    color: tint
    _template: hero
  - items:
      - icon:
          color: teal
          style: float
          name: aperture
        title: Shoot In Style
        text: Describe one function to prototype here.
      - icon:
          color: red
          style: float
          name: code
        title: Developing
        text: >-
          Writing all kinds of code that means so much to a few people and a lot
          more computers and non-living digital products.
      - icon:
          color: primary
          style: float
          name: like
        title: This Is a Feature
        text: Vestibulum ante ipsum primis in faucibus orci luctus et ultrices.
    color: default
    _template: features
  - quote: Don't try to be different...
    author: ... own the fact that you already are.
    color: tint
    _template: testimonial
---

