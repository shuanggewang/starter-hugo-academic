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
  email: larrywan@usc.edu
  phone: (323) 600-3948
  address:
    street: 3584 S Figueroa St
    city: Los Angeles
    region: CA
    postcode: '90007'
    country: United States
    country_code: US


design:
  columns: '2'
---
