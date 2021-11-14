---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: IAccessible
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "./assets/images/sample1.png"
  actions:
    - label: "Contact Us"
      url: "contact-us"
#  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Aaccessibility driven by people with disabilities!"
intro: 
  - title : "People with disabilities power accessibility in your products"
    excerpt: 'Leading organizations use IAccessible to connect to people with disabilities for accessibility testing, training, and design reviews.'
    
clients:
  - image_path : "./assets/images/accessibility.png"
    alt : "Eskalera Inc"
    title : "Eskalera Inc"
  - image_path : "./assets/images/racloop.jpg"
    alt : "Racloop technologies"
    title : "Racloop technologies"
  - image_path : "./assets/images/voice_analytics.png"
    alt : "Saksham"
    title : "Saksham"

skill:
  - title : 'Our skills and experience'
    excerpt: >
      IAccessible is a social enterprise with years of experience connecting product makers to people with disabilities to drive accessibility in Web and mobile applications.  
      
      We collaborate with non-profits across the world to train and hire people with various kinds of disabilities. Besides being trained experts in accessibility testing and design, these people have a lifetime of experience as  users of accessibility products and solutions for their day-to-day living.

services:
  - image_path : "assets/materials/images2.jpg"
    title: "Accessibility Testing"
    url: "testing"
    btn_label : "Learn more about testing"
    excerpt: |
      We are a team of expert assistive technology users with lived experience of disabilities. We test Web and mobile applications against WCAG 2.1 & section 508 for accessibility compliance.
  - image_path : "assets/materials/images2.jpg"
    url: "trainings"
    btn_label : "Learn more about trainings"
    title: Trainings
    excerpt: |
      We conduct workshops and hands-on trainings on how to create accessible Web and mobile applications. The trainings are customized to your specific needs and meet the learners where they are.  
  - image_path : "assets/materials/images2.jpg"
    url: "design"
    btn_label : "Learn more about design review"
    title: Design Review
    excerpt: |
      Did you know, you can prevent over 60% of accessibility bugs by considering accessibility during the design of your applications?  
      Build an accessible and usable   product  right the first time and save costly bug fixes later.


author_profile: false
---
{% include feature_row id="intro" type="center" %}
{% include gallery id="clients" %}
{% include feature_row id="skill" type="center" %}
{% include feature_row id="services" %}