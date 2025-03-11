---
type: PageLayout
title: About
colors: colors-c
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: "<div style=\"text-align: left\">**HEY, I’M TESSA.**</div>\n\nREALITY STAR, MODEL, AND VEGAN ACTIVIST.\n\nBORN AND RAISED IN THE WORLD, AND THAT’S WHERE I’M BASED.**LEGENDARY EX-GNTM, EX-THIS, EX-THAT—BUT ALWAYS 100% ME.**\n\nWHEN I’M NOT IN FRONT OF THE CAMERA OR FIGHTING FOR ANIMAL RIGHTS,\n\n[I’M PROBABLY ENJOYING A PLANT-BASED FEAST.CHECK OUT MY JOURNEY **@TESSA.BERGMEIER**](https://www.instagram.com/tessa.bergmeier/?hl=de).\U0001F525✨\n"
    media:
      type: ImageBlock
      url: /images/15319150_10153993151081937_1623194486861022717_n.jpg
      altText: Hero image
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
    type: HeroSection
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: true
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        self:
          textAlign: center
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: center
  - type: TextSection
    title: IMPRESSUM & DISCLAIMER
    text: >-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
      Sed ut perspiciatis undeomnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
    colors: colors-f
    variant: variant-a
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        textAlign: left
socialImage: /images/15319150_10153993151081937_1623194486861022717_n.jpg
---
