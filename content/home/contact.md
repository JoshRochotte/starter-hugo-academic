---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 180

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
  email: josh.rochotte@rutgers.edu
 # phone: 888 888 88 88
 # address:
  #  street: 450 Serra Mall
   # city: Stanford
   # region: CA
   # postcode: '94305'
   # country: United States
   # country_code: US
  office_hours:
    - 'Evenings 5:00pm to 10:00pm'
  appointment_url: 'https://calendly.com/joshrochotte'
  contact_links:
   #- icon: twitter
     # icon_pack: fab
     # name: DM Me
     # link: 'https://twitter.com/Twitter'
    #- icon: video
     # icon_pack: fas
     # name: Zoom Me
     # link: 'https://zoom.com'

design:
  columns: '2'
---
