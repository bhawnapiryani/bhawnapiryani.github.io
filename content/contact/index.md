---
title: "Contact"
type: widget_page
---
---
widget: contact
headless: true
active: true
weight: 10

title: "Contact"
subtitle: ""

# Contact details
email:
  - bhawna.piryani@uibk.ac.at
  - bhawna.piryani@gmail.com
address:
  street: ""
  city: "Innsbruck"
  region: "Tyrol State"
  country: "Austria"

# Map
map:
  service: google
  api_key: ""  # optional if you use the default embed
  latitude: 47.2692
  longitude: 11.4041
  zoom: 13

# Contact form
form:
  netlify: false  # set true if you use Netlify forms
  action: "mailto:bhawna.piryani@uibk.ac.at"
  fields:
    - name: "name"
      label: "Your Name"
      type: "text"
      required: true
    - name: "email"
      label: "Your Email"
      type: "email"
      required: true
    - name: "subject"
      label: "Subject"
      type: "text"
      required: true
    - name: "message"
      label: "Message"
      type: "textarea"
      required: true
  submit_label: "Send Message"

design:
  columns: "2"
---

