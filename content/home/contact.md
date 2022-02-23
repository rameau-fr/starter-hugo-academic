---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: rameau-fr@gmail.com
  address:
    street: N1 building, KAIST
    city: Daejeon
    postcode: '34141'
    country: Korea
    country_code: KR
  coordinates:
    latitude: '36.374160524017974'
    longitude: '127.36582737044516'
  directions: Enter N1 Building  and go to room #212
  office_hours:
    - 'Monday-Friday 09:00 to 18:00'

design:
  columns: '2'
---
