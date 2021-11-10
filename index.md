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
    excerpt: 'leading organizations use IAccessible  to connect to people with disabilities for  accessibility testing, training, and design.'
    
clients:
  - image_path : "./assets/images/accessibility.png"
    alt : "Eskalera Inc"
    title : "Eskalera Inc"
  - image_path : "./assets/images/opus-green.svg"
    alt : "Racloop technologies"
    title : "Racloop technologies"
  - image_path : "./assets/images/voice_analytics.png"
    alt : "Saksham"
    title : "Saksham"

skill:
  - title : 'Our skills and experience'
    excerpt: >
      IAccessible is  a social enterprise with years of experience connecting product makers to people with disabilities to drive accessibility in Web and mobile applications.  
      
      We collaborate with non-profits across the world to train and hire people with various kinds of disabilities. Besides being trained experts in accessibility testing and design, these people have a lifetime of experience as  users of accessibility products and solutions for their day-to-day living.

services:
  - image_path : "assets/materials/images2.jpg"
    title: "Accessibility Testing"
    url: "web-accessibility-testing"
    btn_label : "Learn more about testing"
    excerpt: |
      Our certified experts are people with disabilities having  lived experience of using various assistive technologies to:
      * comprehensively test your rich Internet applications,  Web sites, and mobile IOS and Android apps  for accessibility and compliance to W3C accessibility guidelines AKA WCAG 2.1, section 508 or ADA compliance.
      * Test and remediate documents, such as PDF, word, or power point presentations, for accessibility.
      * Author Accessibility Conformance Reports (ACR) and VPATs.  
      
  - title: Trainings
    excerpt: |
      We conduct workshops and hands-on trainings on how to create accessible Web and mobile applications:  
      * Half day Sensitization workshop: Specially useful for people involved in product and platform strategy and usability decisions. This workshop provides an overview of the accessibility problem helping learners understand what are disabilities, how do people with disabilities access computers and software, what is the need to build accessible and inclusive solutions - pragmatic reasons and legislations, what does it take to build accessible Web applications -- costs and technologies involved and so on.  
      * 3 day Comprehensive Web accessibility training: This training helps Web developers, designers, and architects understand how to develop and test accessible Rich Internet applications that comply with the W3C accessibility guidelines.  
      * 1 day accessibility testing primer: Targetted primarily for the quality assurance engineers, this training helps learn the tools and techniques to test if a Web application is accessible and meets the various W3C guidelines compliance or other legal requirements, such as section 508 or ADA etc.  

author_profile: false
---
{% include feature_row id="intro" %}
{% include gallery id="clients" caption="our clients" %}
{% include feature_row id="skill" %}
{% include feature_row id="services" %}