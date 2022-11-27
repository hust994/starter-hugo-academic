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
  email: 3025883327@qq.com
  phone: 13167131846
  address:
    street: 1037 Luoyu Road, Huazhong University of Science and Technology
    city: Wuhan
    region: Hubei
    postcode: '430074'
    country: CHINA
    country_code: CHN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: None
  office_hours:
    - 'Monday to Friday 14:00 to 17:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
