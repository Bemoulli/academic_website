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
  email: renkangjun163@163.com
  # phone: 888 888 88 88
  address:
    street: 288, Liuhe Road
    city: Hangzhou
    region: Zhejiang Province
    postcode: '310023'
    country: P.R. China
    country_code: CHN
  coordinates:
    latitude: '120.2'
    longitude: '30.3'
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Workday 9:00 to 17:00 BeiJing time'
    - '工作日 北京时间 9:00 - 17:00 '
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
