---
title: >-
  ¿Deseas una mente abierta para conectar puntos y desarrollar tecnología como
  catalizadora de un mundo más humano?
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      Muchas gracias por tu interés en trabajar juntos.


      Te respondo en un plazo de 24 horas. Por favor, rellene el siguiente
      formulario de contacto.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre completo
        default_value: Escribe tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Correo electrónico
        default_value: Escribe tu correo electrónico
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: 'Por favor, seleccione'
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: 'Tu mensaje, sé breve. '
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario almacena la información que he enviado
          para que puedan ponerse en contacto conmigo.
    submit_label: Enviar
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
