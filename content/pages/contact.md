---
title: Contact us
sections:
  - type: HeroSection
    title: Contact
    text: >
      Let’s build something great together.

      Complete our contact form or send us an email at
      [email@example.com](mailto:email@email.com) .
    feature:
      type: FormBlock
      action: /.netlify/functions/submission_created
      elementId: contact-form
      submitLabel: Contact
      fields:
        - type: TextFormControl
          label: Name
          placeholder: Your name
          width: full
        - type: EmailFormControl
          label: Email
          placeholder: Your email
          width: full
        - name: message
          label: Message
          placeholder: Your Message
          isRequired: false
          width: full
          type: TextareaFormControl
        - type: CheckboxFormControl
          label: Sign me up to receive updates
          width: full
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
