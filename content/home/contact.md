---
# An instance of the Contact widget.
widget: contact

# Activate this widget? true/false
active: false

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: formspree
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: brandon.thurgood@outlook.com
  phone: ''
  address:
    street: ''
    city: ''
    region: ''
    postcode: ''
    country: ''
    country_code: ''
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: ''
  office_hours: []
  appointment_url: ''
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/BrandonsDefiant/'
    - icon: skype
      icon_pack: fab
      name: Skype Me
      link: 'https://join.skype.com/invite/dWdUil43IKua'

design:
  columns: '2'
---
