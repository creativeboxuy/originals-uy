---
layout: home
title: Inicio
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/hero-web-originals-02-b.jpg
    background_image_opacity: 65
    content: |
      # Sos original, tu ropa también.

      Llevá siempre con vos tus prendas cómodas y originales.
    actions:
      - title: Ver prendas
        url: /store
        arrow: true
        style: primary
  - type: featured_products_section
    section_id: best_sellers_section
    title: Lo más vendido
    icon: true
    light_title: true
    featured_products:
      - content/pages/products/plant1.md
      - content/pages/products/plant3.md
      - content/pages/products/plant5.md
      - content/pages/products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - content/pages/category/bigplants.md
      - content/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Experiencias originales
    testimonials:
      - author:
          name: Julian Martin
          location: 'Montevideo, Uruguay'
        text: >-
          Creative Box. Agencia de marketing y producción digital.
      - author:
          name: Major Payne
          location: 'VA, USA'
        text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.
  - type: promotion_section
    section_id: promotion_section
    title: Que no falte en tu ropero ;)
    subtitle: Prendas desde $899 que van bien con todo!
    image: images/parker-burchfield-tvG4WvjgsEY-unsplash.jpeg
    cta:
      title: Llevate las tuyas
      url: /store
      style: secondary
      arrow: true
seo:
  title: Planty Theme
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Planty Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Planty Theme
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
---
