---
title: Contact us
sections:
  - type: HeroSection
    title: Contact
    text: >
      Let’s build something great together.

      Complete our contact form or send us an email at
      [email@example.com](mailto:email@email.com) .


      ## Our offices


      ### San Francisco


      1234 Some St.

      San Francisco, CA 12345

      1-234-556-7890

      Get directions →



      ### New York


      1234 Some St.

      New York, NY 12345

      1-234-556-7890

      Get directions →
    feature:
      type: FormBlock
      action: /.netlify/functions/submission_created
      elementId: contact-form
      submitLabel: Send Message
      fields:
        - type: TextFormControl
          label: Name
          placeholder: Your name
          width: full
        - type: EmailFormControl
          label: Email
          placeholder: Your email
          width: full
        - name: Services
          label: What services are you looking for?
          defaultValue: Please select...
          options:
            - Branding
            - Design
            - Digital
          isRequired: false
          width: full
          type: SelectFormControl
        - name: message
          label: Message
          placeholder: Your Message
          isRequired: false
          width: full
          type: TextareaFormControl
        - type: CheckboxFormControl
          label: >-
            I understand that this form is storing my submitted information so I
            can be contacted.
          width: full
          name: checkbox
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
        flexDirection: row
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
layout: PageLayout
---
