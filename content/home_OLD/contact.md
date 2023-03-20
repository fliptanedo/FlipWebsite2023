---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 200

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: false
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: test@example.org
  phone: x26168
  # Physics Building, Office 3054 on the third floor
  address:
    street: 900 University Ave.
    city: Riverside
    region: CA
    postcode: '92521'
    country: United States
    country_code: US
  # coordinates:
  #   latitude: '33.974480'
  #   longitude: '-117.325415'
  directions: Physics Building, Office 3054 on the third floor
  office_hours:
    - 'Office hours by appointment'
  # appointment_url: 'https://calendly.com'
  contact_links:
    # - icon: twitter
    #   icon_pack: fab
    #   name: DM Me
    #   link: 'https://twitter.com/Twitter'
    # - icon: video
    #   icon_pack: fas
    #   name: Zoom Me
    #   link: 'https://zoom.com'

design:
  # columns: '2'
  columns: '2'
---
