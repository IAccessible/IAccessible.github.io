---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: IAccessible
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: "./assets/images/heroImage.png"
  actions:
    - label: "Contact Us"
      url: "contact-us"
#  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "People with disabilities power accessibility in your products"
intro: 
  - title : "People with disabilities power accessibility in your products"
    excerpt: 'Leading organizations use IAccessible to connect to people with disabilities for accessibility testing, training, and design reviews.'
    
clients:
  - image_path : "./assets/images/accessibility.png"
    alt : "Eskalera Inc"
    title : "Eskalera Inc"
    image_caption : "Eskalera Inc"
    excerpt: |
      Accessibility assessment for line of business apps
  - image_path : "./assets/images/racloop.jpg"
    alt : "Racloop technologies"
    title : "Racloop technologies"
    excerpt: |
      Trained Developers on accessibility
  - image_path : "./assets/images/voice_analytics.png"
    alt : "Saksham"
    title : "Saksham"
    excerpt: |
      Accessible ebook publishing 

goal:
  - title : 'Join us to empower people with disabilities'
    excerpt: >
      Our mission is to help companies build accessible and inclusive products through the power of design, reviews, testing, and training by users with disabilities. We do this by collaborating with non-profit organizations across the world to train and hire people with various kinds of disabilities. Besides being trained experts in accessibility testing and design, they have a lifetime of experience as users of accessibility products and solutions for their day-to-day living.

services:
  - image_path : "assets/materials/images2.jpg"
    title: "Start accessibility assessment"
    url: "assessment"
    btn_label : "Learn more about Assessments"
    excerpt: |
      Use a team of expert assistive technology users with lived experience of disabilities to assess your web and mobile applications against WCAG 2.1 & section 508 standards for compliance.
  - image_path : "assets/materials/images2.jpg"
    url: "design"
    btn_label : "Learn more about design reviews"
    title: Design accessible experiences
    excerpt: |
      Did you know, you can prevent over 60% of accessibility bugs by considering accessibility during the design of your applications?  
      Build an accessible and usable   product  right the first time and save costly bug fixes later.
  - image_path : "assets/materials/images2.jpg"
    url: "trainings"
    btn_label : "Learn more about trainings"
    title: Become accessibility experts
    excerpt: |
      Sign-up for our workshops and hands-on training on how to create accessible web and mobile applications. We customize them to your specific needs and meet the learners where they are.

author_profile: false
---


<!-- {% include feature_row id="intro" type="center" %} -->

{% include feature_row id="services" %}
{% include feature_row id="goal" type="center" %}
{% include gallery  id="clients"   layout="third" caption="our clients" %}
<!-- {%include banner.html%} -->
