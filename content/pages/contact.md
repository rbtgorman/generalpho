title: Contact & Location
slug: contact
seo:
  metaTitle: Contact & Location - General Phở Vietnamese Kitchen
  metaDescription: Find our Vietnamese food truck at Fort Knox, KY. Building 127 Gold Vault Road. Follow PX schedule. Visit us for authentic Vietnamese cuisine!
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
sections:
  - title:
      text: Find Us at Fort Knox
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Visit Our Food Truck
    text: >
      General Phở Vietnamese Kitchen operates at Fort Knox, Kentucky. 
      We are located near the PX and follow the PX schedule for our hours of operation. 
      Come visit us and become part of our Big Family!
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-32
          - pl-4
          - pb-32
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
      altText: Fort Knox location
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg

  - title:
      text: Location & Hours
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    items:
      - title: Our Location
        subtitle: Fort Knox, Kentucky
        text: >-
          Building 127 Gold Vault Road, Fort Knox, KY 40121
          
          
          We are located near the Post Exchange (PX) at Fort Knox.
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
          altText: Location
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
      - title: Hours of Operation
        subtitle: We Follow the PX Schedule
        text: >-
          Our food truck follows the Fort Knox Post Exchange (PX) operating schedule.
          
          
          When the PX is open, we are open. When there are post delays, check our Facebook.
          
          
          We close for winter months (typically mid-December through early spring).
          
          
          Holiday closures follow PX schedule.
          
          
          Please check our Facebook page for daily updates and any schedule changes!
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
          altText: Hours
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
      - title: Stay Connected
        subtitle: Follow Us on Social Media
        text: >-
          For daily updates, menu specials, and schedule changes, 
          follow us on Facebook and Instagram!
          
          
          Facebook: General Phở Vietnamese Kitchen
          
          
          Instagram: @generalphovietnamesekitchen
          
          
          We post updates about daily specials, weather-related closures, 
          holiday schedules, new menu items, and behind-the-scenes content.
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
          altText: Social Media
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-8
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection

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
      text: Important Information
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Before You Visit
    text: >
      Weather Conditions: We operate our food truck year-round when conditions permit. During extreme 
      cold weather, we may have adjusted hours or temporary closures for safety. 
      We typically close for the winter season (mid-December through early spring) 
      to prep for the next year and give our team a well-deserved break.
      
      
      Fort Knox Access: Please note that Fort Knox is an active military installation. Visitors will 
      need proper identification and may need to check in at the gate. If you have 
      questions about base access, please contact Fort Knox directly.
      
      
      Sold Out Items: Because we prepare everything fresh daily, popular items may sell out during 
      peak lunch hours. We recommend visiting earlier in the day for the full menu selection!
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

  - title:
      text: Get In Touch
      color: text-dark
      type: TitleBlock
    subtitle: Questions or Feedback?
    text: >
      Have questions about our menu, catering options, or special requests? 
      We would love to hear from you! Send us a message using the form below or 
      reach out to us on Facebook.
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
        - name: phone
          label: Phone
          hideLabel: true
          placeholder: Your phone number (optional)
          isRequired: false
          width: full
          type: TextFormControl
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
        label: Send Message
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Form
      color: text-primary
      type: Badge
    colors: bg-neutral-fg-dark
    type: GenericSection
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
