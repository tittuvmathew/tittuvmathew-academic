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
  email: tittu.v.mathew@alumni.iitm.ac.in
  phone: 647 787 6069
  address:
    street: 9 Sumac Street
    city: Barrie
    region: ON
    postcode: 'L4N 9R8'
    country: Canada
    country_code: CA
  #coordinates:
    #latitude: '37.4275'
    #longitude: '-122.1697'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday to Friday 09:00 to 17:00'
    #- 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.us/j/9614975026?pwd=ejZJOGdseFJocjIrUDBVRU1pa1FOQT09'

design:
  columns: '2'
---
