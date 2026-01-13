---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Authentic Vietnamese Cuisine by a Retired Army Veteran
      color: text-dark
      type: TitleBlock
    subtitle: Serving Fort Knox with Love
    text: >
      General Phở Vietnamese Kitchen brings authentic Vietnamese flavors to Fort Knox, Kentucky. 
      Created by a retired Army veteran who understands the importance of good food and community, 
      we serve our Big Family with traditional Vietnamese dishes made with care and pride.
    actions:
      - label: View Menu
        altText: 'View our menu'
        url: /menu
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: Find Us
        altText: 'Find our location'
        url: /contact
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Link
    media:
      url: /images/generalpho.jpg
      altText: General Phở Vietnamese Kitchen
      elementId: ''
      type: ImageBlock
      styles:
        self:
          maxWidth: none
          width: 100%
          objectFit: contain
    badge:
      label: 100% Recommended
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
          - pl-4
          - pb-16
          - pr-4

  - type: FeaturedItemsSection
    title:
      text: What Makes Us Special
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Quality, Tradition, and Community
    items:
      - type: FeaturedItem
        title: Veteran Owned
        subtitle: Serving Those Who Serve
        text: >-
          Created by a retired Army veteran who brings military precision and dedication 
          to every dish. We understand the Fort Knox community because we are part of it.
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
          altText: Veteran owned business
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Authentic Vietnamese
        subtitle: Traditional Recipes
        text: >-
          From our signature Phở to fresh Bánh Mì sandwiches, every dish is prepared 
          using authentic Vietnamese recipes and the freshest ingredients available.
        image:
          url: /images/icon2.svg
          altText: Authentic Vietnamese cuisine
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
      - title: Food Truck Fresh
        subtitle: Made to Order
        text: >-
          Operating from our food truck at Fort Knox, we prepare each order fresh 
          just for you. Join our Big Family and taste the difference.
        image:
          url: /images/icon3.svg
          altText: Fresh food truck meals
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
        type: FeaturedItem
    actions:
      - label: Learn More About Us
        altText: 'Learn more about our story'
        url: /about
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: Our Values
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
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

  - type: GenericSection
    title:
      text: Our Signature Dishes
      color: text-dark
      type: TitleBlock
    subtitle: Fan Favorites from Our Menu
    text: >
      From steaming bowls of traditional Phở to crispy fresh Bánh Mì sandwiches, 
      our menu features authentic Vietnamese dishes that have made us a Fort Knox favorite.
    actions:
      - label: See Full Menu
        url: /menu
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    media:
      url: /images/hero2.svg
      altText: Vietnamese food dishes
      type: ImageBlock
    badge:
      label: Most Popular
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    elementId: ''

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
    subtitle: What Our Big Family Says
    items:
      - title: >-
          Best Vietnamese food at Fort Knox! The Bánh Mì is incredible and the Phở 
          is authentic and delicious.
        tagline: Customer Review
        subtitle: 'Fort Knox Community Member'
        text: >-
          The owner is incredibly friendly and you can taste the care that goes into 
          every dish. Highly recommend!
        image:
          url: /images/person-placeholder-light.png
          altText: Customer review
          styles:
            self:
              borderRadius: full
          type: ImageBlock
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
        type: FeaturedItem
      - title: >-
          As a veteran myself, I love supporting a fellow veteran's business. 
          The food is amazing and the service is always excellent.
        tagline: Customer Review
        subtitle: 'Retired Army Veteran'
        text: >-
          This is authentic Vietnamese cuisine done right. It reminds me of my time 
          overseas and brings back great memories.
        image:
          url: /images/person-placeholder-light.png
          altText: Veteran customer
          styles:
            self:
              borderRadius: full
          type: ImageBlock
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
        type: FeaturedItem
      - title: >-
          I stop by every week for lunch. The spring rolls are fresh, the portions 
          are generous, and the prices are great.
        tagline: Customer Review
        subtitle: 'Regular Customer'
        text: >-
          The owner makes everyone feel like family. It is more than just great food - 
          it is a great experience.
        image:
          url: /images/person-placeholder-light.png
          altText: Regular customer
          styles:
            self:
              borderRadius: full
          type: ImageBlock
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
      text: Visit Us at Fort Knox
      color: text-dark
      type: TitleBlock
    subtitle: Find us at the Fort Knox PX
    text: >
      We operate our food truck at Fort Knox, following the PX schedule. 
      Come join our Big Family and experience authentic Vietnamese cuisine 
      made with love by a veteran for veterans and the community.
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
          placeholder: Your message or questions
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
        label: Send Message
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Get In Touch
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: General Phở Vietnamese Kitchen - Authentic Vietnamese Food at Fort Knox
  metaDescription: Veteran-owned Vietnamese food truck at Fort Knox, KY serving authentic Phở, Bánh Mì, and traditional Vietnamese dishes. Join our Big Family today!
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---