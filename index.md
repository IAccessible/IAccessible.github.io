---
layout: splash
author_profile: false

# Hero section
header:
  overlay_image: /assets/images/hero-technical-accessibility.jpg
  overlay_filter: 0.5
excerpt: "Experts with lived disability experience lead accessibility audits, research, and remediation—validating AI-enabled accessibility workflows."
intro:
  - title: "Accessibility outcomes driven by lived disability experience"
    excerpt: "Experts with lived disability experience lead accessibility audits, research, and remediation—validating AI-enabled accessibility workflows."
    actions:
      - label: "View our services"
        url: "/products"
      - label: "See case studies"
        url: "/case-studies/"

# Services section - 2x2 grid
services_grid:
  - image_path: /assets/images/services/audits.jpg
    alt: "Accessibility Audits"
    featuretitle: "Accessibility Audits"
    url: "/assessment"
    excerpt: "WCAG 2.2, Section 508, and EN 301 549 audits conducted by experts with lived disability experience, using real assistive-technology workflows."
  - image_path: /assets/images/services/research.jpg
    alt: "Usability Research & Design Reviews"
    featuretitle: "Usability Research & Design Reviews"
    url: "/user-research"
    excerpt: "Research and design-phase evaluations with people with disabilities to identify real-world barriers and prevent issues before development."
  - image_path: /assets/images/services/training.jpg
    alt: "Training & Enablement"
    featuretitle: "Training & Enablement"
    url: "/trainings"
    excerpt: "Role-based accessibility training for designers, developers, QA, and product leaders, grounded in hands-on assistive-technology use."
  - image_path: /assets/images/services/documents.jpg
    alt: "PDF & Document Accessibility Remediation"
    featuretitle: "PDF & Document Accessibility Remediation"
    url: "/assessment"
    excerpt: "Accessible PDFs and Office documents remediated by experts with lived disability experience and validated using real screen readers."

# Case studies
customers:
  - image_path: "assets/images/microsoft-logo.PNG"
    image_width: '124'
    image_height: '121'
    alt: "microsoft logo"
    featuretitle: "IAccessible Helps Compass Group Enhance Accessibility in Microsoft Cafes"
    url: "case-studies/microsoft"
    btn_label: "Microsoft case study"
    excerpt: |
      IAccessible is partnering with Compass Group USA to improve the accessibility of their innovations in Microsoft cafes and dining facilities. From vending machines to the Rammon vending car, we are helping Compass Group gather valuable feedback from real users with disabilities to ensure their innovations are ready for deployment and meet the needs of all employees.
---

<div id="main">

<!-- Services Section -->
{% include feature_row id="services_grid" rowtitle="Our Services" %}

<!-- AI Validation Capability Section -->
<div style="padding: 60px 5%; background-color: #f8f9fa;">
  <h2 style="text-align: center; margin-bottom: 20px;">Expert Validation for AI-Driven Accessibility</h2>
  <p style="text-align: center; font-size: 1.125rem; margin-bottom: 40px; max-width: 900px; margin-left: auto; margin-right: auto;">AI can accelerate accessibility workflows. Lived-experience experts ensure those results actually work for users.</p>
  <ul style="max-width: 900px; margin: 0 auto; font-size: 1.0625rem; line-height: 1.8;">
    <li>Validate AI-generated accessibility findings against real assistive-technology workflows</li>
    <li>Confirm whether AI-suggested fixes actually resolve user barriers</li>
    <li>Identify false positives and missed issues automation cannot detect</li>
    <li>Deliver legally defensible, human-verified accessibility outcomes</li>
  </ul>
</div>

<!-- Case Studies Section -->
{% include feature_row id="customers" rowtitle="Our Customers" %}

<!-- Customer Logos -->
<figure class="third" style="padding: 12px 16px;">
  <div class="archive__item-body_11_div">
    <img src="/assets/images/racloop.jpg" alt="Racloop technologies" />
    <p class="archive__item-body_11_p" style="font-size: 18px;font-weight: 600;">Racloop</p>
  </div>
  <div class="archive__item-body_11_div">
    <Our Story Section -->
<h2 class="archive__item-body_8_h1">Join us to empower people with disabilities</h2>
<div class="archive__item-body_8_div">
  <div> 
    <img src="./assets/images/story.jpg" alt="" class="archive__item-body_8_div_img">
  </div>
  <div class="mrt">
    <p class="archive__item-body_8_div_p">
      Our mission is to help companies build accessible and inclusive products through the power of design, reviews, testing, and training by users with disabilities. We do this by collaborating with non-profit organizations across the world to train and hire people with various kinds of disabilities. Besides being trained experts in accessibility testing and design, they have a lifetime of experience as users of accessibility products and solutions for their day-to-day living.
    </p>
    <a href="/about-us" style="text-decoration: none;">
      <p class="archive__item-body_9_P" style="font-size: 18px;">Our Story</p>
    </a>
  </div>
</div>

<!-- img src="/assets/images/compass-group-logo.PNG" alt="Compass Group logo" />
    <p class="archive__item-body_11_p" style="font-size: 18px;font-weight: 600;">Compass Group USA</p>
  </div>
  <div class="archive__item-body_11_div">
    <img src="/assets/images/Adobe_logo.png" alt="Adobe" />
    <p class="archive__item-body_11_p" style="font-size: 18px;font-weight: 600;">Adobe</p>
  </div>
</figure>

<!-- Announcements Section (conditional) -->
{% if site.data.announcements %}
  {% assign current_announcements = site.data.announcements | where: "is_current", true %}
  {% if current_announcements.size > 0 %}
  <div style="padding: 40px 5%; background-color: #fff3cd; border-top: 3px solid #ffc107;">
    <h2 style="margin-bottom: 20px;">Latest Updates</h2>
    {% for announcement in current_announcements %}
    <div style="margin-bottom: 15px;">
      <h3 style="margin-bottom: 5px;"><a href="{{ announcement.url }}">{{ announcement.title }}</a></h3>
      <p style="color: #666; font-size: 0.9rem;">{{ announcement.date | date: "%B %d, %Y" }}</p>
    </div>
    {% endfor %}
    <p style="margin-top: 20px;"><a href="/news/">View all news and updates</a></p>
  </div>
  {% endif %}
{% endif %}

</div>