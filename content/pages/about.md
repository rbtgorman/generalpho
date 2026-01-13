---
title: About Us
slug: about
sections:
  - title:
      text: Our Story
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: From Service to Service
    text: >
      General Phở Vietnamese Kitchen was created by a retired Army veteran who wanted 
      to continue serving the community in a new way through authentic Vietnamese cuisine. 
      After years of military service, our founder brought the same dedication, precision, 
      and commitment to excellence to creating a food truck that serves the Fort Knox community 
      with pride and passion.
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: Vietnamese food background
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg

  - type: GenericSection
    title:
      text: Our Mission
      color: text-dark
      type: TitleBlock
    subtitle: Serving Our Big Family
    text: >
      We believe in more than just great food. We believe in building community. 
      That is why we call our customers our Big Family. Every bowl of Phở, 
      every Bánh Mì sandwich, is prepared with care and served with the same 
      dedication we learned in military service. We are proud to serve the Fort Knox 
      community and honored to be part of your daily lives.
    media:
      url: /images/hero2.svg
      altText: Vietnamese food
      type: ImageBlock
    badge:
      label: Veteran Owned
      color: text-primary
      type: Badge
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

  - type: GenericSection
    title:
      text: Why Vietnamese Cuisine?
      color: text-dark
      type: TitleBlock
    subtitle: A Connection to Heritage
    text: >
      Vietnamese food is about balance. The perfect harmony of flavors, textures, 
      and fresh ingredients. From the complex, slow-simmered broths of Phở to the 
      crispy-fresh combination of Bánh Mì sandwiches, every dish tells a story of 
      tradition, family, and craftsmanship. We are honored to share these authentic 
      flavors with Fort Knox.
    media:
      url: /images/hero3.svg
      altText: Traditional Vietnamese cooking
      type: ImageBlock
    badge:
      label: Authentic Recipes
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
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

  - title:
      text: What We Stand For
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Our Values
    items:
      - title: Quality First
        subtitle: Fresh Ingredients, Authentic Recipes
        text: >-
          We never compromise on quality. Every ingredient is chosen carefully, 
          and every dish is prepared using traditional Vietnamese cooking methods. 
          When you eat with us, you are getting the real thing.
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        image:
          url: /images/abstract-feature1.svg
          altText: Quality ingredients
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
      - title: Community Connection
        subtitle: Building Our Big Family
        text: >-
          We are not just a food truck. We are part of the Fort Knox community. 
          From active duty service members to veterans and families, everyone 
          is welcome at our window. This is your food truck.
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        image:
          url: /images/abstract-feature2.svg
          altText: Community
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
      - title: Service Excellence
        subtitle: Military Standards, Civilian Kindness
        text: >-
          Our founder's military background means we bring discipline and 
          precision to everything we do. But we also bring warmth, hospitality, 
          and a genuine desire to make your day better with great food.
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        image:
          url: /images/abstract-feature3.svg
          altText: Excellence
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-8
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection

  - title:
      text: Join Our Big Family
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: We Would Love to Serve You
    text: >
      Whether you are stationed at Fort Knox, work on post, or are visiting the area, 
      stop by our food truck and experience authentic Vietnamese cuisine made with 
      pride by a veteran for the community. We look forward to welcoming you!
    actions:
      - label: View Menu
        url: /menu
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
      - label: Find Us
        url: /contact
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        alignItems: center
        flexDirection: col
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection

seo:
  metaTitle: About Us - General Phở Vietnamese Kitchen
  metaDescription: Learn about our veteran-owned Vietnamese food truck at Fort Knox. Authentic cuisine, community values, and a Big Family welcome.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---