# Website Improvement Plan

This plan combines:

- Recommendations based on the updated Introduction to IAccessible deck.
- Potential improvements reconstructed from the former `site-refresh` branch.

No earlier requirements document, detailed commit message, or pull request was
found for the `site-refresh` work. Changes should be reviewed and released
incrementally from the `homepage-incremental-updates` branch.

## Revised high-level recommendations

These recommendations align the website with IAccessible's brand voice,
customer expectations, and current direction. They define messaging and
content direction rather than final marketing copy.

### 1. Strengthen the homepage value proposition

The homepage already emphasizes lived experience, which is a strong unique
value proposition. It should also communicate the additional customer value
drivers identified in the updated deck:

- Actionable, developer-ready output.
- Shift-left efficiency.
- Real assistive-technology usability insight.
- Lower remediation costs.
- Better product outcomes.
- Expertise across design, research, and engineering.

Present these benefits in customer language rather than generic accessibility
messaging. People arriving on the site are not necessarily deciding whether
accessibility is important; many are comparing which vendor will produce
better results.

Positioning directions to develop later:

- We help teams fix the right issues, not every issue without regard to impact.
- We help prevent accessibility defects before they become expensive.
- We test with people who use real assistive-technology workflows so critical
  barriers are not missed.
- We deliver developer-ready remediation guidance that reduces churn and
  accelerates release cycles.

The final headline still needs to be developed. Do not use the previously
proposed "Accessibility outcomes driven by lived disability experience"
headline.

Retain this approved supporting line:

> Accessibility audits, research, training, and remediation led by experts who
> use assistive technology every day.

Potential homepage calls to action:

- Explore our services.
- Request a free assessment.

### 2. Add a "Problems We Solve" section

Add a concise "Problems We Solve" or "Why Teams Choose Us" section covering
customer challenges such as:

- Difficulty testing effectively with people who use real assistive
  technology.
- Uncertainty about which findings materially affect users.
- Difficulty making legally defensible accessibility decisions.
- Difficulty remediating issues correctly and consistently.
- Difficulty scaling accessibility across teams and releases.
- The limitations of automation-only testing.
- The much higher cost of fixing accessibility defects late.

This section should explain why a customer needs IAccessible specifically, not
why accessibility matters generally. Accurately articulating customer pain
helps prospects recognize that IAccessible understands their situation.

Verify and cite the "late fixes cost 10-100 times more" claim before publishing
it.

### 3. Promote the "Why IAccessible" differentiators

Add a prominent "Why IAccessible" block with the company's strongest
differentiators:

- Expertise grounded in lived disability experience.
- Actionable, prioritized findings.
- Developer-ready remediation guidance.
- Testing based on real assistive-technology workflows.
- Shift-left design reviews.
- High-impact outcomes and reduced defect churn.
- Proven experience with multiple enterprises.

This is the core business advantage and should be clear on the homepage. A
version of this block should also appear near the top of the services overview
page.

### 4. Expand service pages with updated language

Shift service content from merely describing what IAccessible offers to
explaining why its version of each service produces better results.

Use this pattern for each service block:

> Recognizable service name → customer-oriented sentence → concise explanation

Approved service-block copy:

#### Accessibility Audits & ACR/VPAT

**Find the accessibility issues that matter most.**

Our audits are led by experts with disabilities who manually test with the
assistive technologies they use every day. Get WCAG 2.2, ADA, Section 508, and
EN 301 549 assessments with prioritized, developer-ready findings, remediation
guidance, fix verification, and ACR/VPAT support.

#### Design & Usability Research

**Build accessibility in before you build the product.**

Bring people with disabilities into design reviews, prototype evaluations, and
usability research to uncover barriers early, validate the right solutions, and
reduce costly rework later in development.

#### Accessibility Training

**Build accessibility expertise across your organization.**

Equip designers, developers, QA, product managers, content authors, and leaders
with practical, role-specific skills taught by accessibility experts with
lived disability experience.

#### PDF & Document Remediation

**Make your documents accessible to everyone.**

Remediate PDFs, forms, Word documents, PowerPoint presentations, Excel files,
and other digital content for accessibility—from individual documents to
large-scale remediation programs.

The homepage should provide a concise overview of these four service pillars
and link each one to a dedicated destination.

Implementation details to verify:

- Update references from WCAG 2.1 to WCAG 2.2 where appropriate.
- Give each service a unique and correct destination.
- Make feature titles clickable when a destination is provided.
- Show a separate call-to-action button only when a button label is explicitly
  configured.
- Use image alternatives that describe the image rather than merely repeating
  the linked heading.

Potential files:

- `index.md`
- `_pages/products.md`
- `_pages/assessment.md`
- `_pages/user-research.md`
- `_pages/trainings.md`
- `_includes/feature_row`

### 5. Improve case studies and social proof

Use a consistent structure for customer stories:

1. Challenge.
2. What IAccessible did.
3. Impact.

Use measurable results where they can be verified, cited, and approved for
public use. Write concise, outcome-oriented titles consistent with the updated
deck.

Potential improvements:

- Feature a small number of strong case studies on the homepage.
- Link customer logos to the corresponding case studies where appropriate.
- Consider Microsoft, Adobe, Compass Group, and other publishable examples.
- Give logos useful alternative text and consistent presentation.
- Retain or remove older case studies intentionally rather than leaving
  commented definitions in the homepage source.

Potential files:

- `index.md`
- `_pages/case-studies/`

### 6. Add an "Our Approach" or "How We Work" section

Explain how IAccessible works with enterprise teams and integrates into their
product-development process.

Potential content:

- A high-level product-lifecycle graphic.
- Design reviews and prototype testing.
- Audits during development.
- Assistive-technology validation and fix verification.
- VPAT or Accessibility Conformance Report documentation.
- Training, analytics, and usability research.
- Fixed-scope, ongoing-consulting, and embedded-team engagement models.
- The dual-shore or other flexible delivery model, if appropriate for the
  public website.
- Clear expectations for project delivery, communication, and scaling.

This information can build enterprise buyer confidence and shorten the path to
engagement.

### 7. Elevate the lived-experience narrative

Present lived disability experience as the strategic reason IAccessible
produces stronger results, not as an incidental company attribute.

Explain concretely how lived experience:

- Reveals barriers that automated tools and compliance checklists miss.
- Improves the accuracy and context of findings.
- Helps teams prioritize issues based on real user impact.
- Produces more useful remediation guidance.
- Connects technical decisions to authentic assistive-technology use.

Place a concise version of this message near the top of the homepage and
develop it further in the company story. Review any claim that lived experience
makes a decision "legally defensible" before publication.

Potential files:

- `index.md`
- `_pages/about-us.md`

### 8. Keep the website as the visual style anchor

The website should govern the visual brand; the deck should follow it rather
than introducing a separate design language.

- Maintain the clean white, teal, and orange palette.
- Keep typography consistent with the website.
- Use subtle, clear iconography that matches the site.
- Keep photography and illustration styles consistent.
- Avoid visual treatments that do not match the established brand.
- Ensure new visual components meet contrast, reflow, zoom, keyboard, and
  screen-reader requirements.

## Additional potential improvements from `site-refresh`

The following ideas are not already covered by the revised recommendations.

### Add configurable announcements

- Add an announcements data file.
- Render a "Latest Updates" section only when at least one announcement has
  `is_current: true`.
- Include an announcement title, date, URL, and link to all news.
- Decide whether multiple current announcements should be supported.
- Keep example announcements disabled by default.

Potential files:

- `_data/announcements.yml`
- `index.md`

### Update footer messaging

Consider replacing the existing company description with:

> Enterprise accessibility services delivered by experts with lived disability
> experience.

Review the wording in the context of the complete footer before publishing.

Potential file:

- `_includes/footer.html`

### Consider AI accessibility validation messaging

AI validation can be a supporting capability but should not lead the homepage
unless it becomes a primary service.

Potential supporting points:

- Validate automated findings against real assistive-technology workflows.
- Confirm that suggested fixes resolve user barriers.
- Identify false positives and issues automation misses.
- Deliver human-verified accessibility results.

### Repair existing homepage markup before redesigning it

Validate and correct the current homepage structure before layering on new
content or layouts. The `site-refresh` draft contained malformed comments and
closing tags that should not be copied into production.

## Suggested incremental release order

1. Repair and validate existing homepage markup without changing content.
2. Finalize and publish the homepage value proposition.
3. Add the "Problems We Solve" section.
4. Add the "Why IAccessible" differentiators.
5. Update the homepage service overview.
6. Update each service page individually.
7. Improve one case study and establish the reusable case-study format.
8. Improve the homepage case-study and social-proof flow.
9. Elevate the lived-experience narrative.
10. Add the "Our Approach" section.
11. Update footer messaging.
12. Add configurable announcements.
13. Consider supporting AI validation content.

## Validation for every increment

- Preview the Jekyll site locally.
- Check desktop and mobile layouts.
- Navigate changed content using only a keyboard.
- Test headings, links, landmarks, and image alternatives with a screen reader.
- Check contrast, text resizing, zoom, and reflow.
- Confirm internal links work with the site's configured base URL.
- Verify, cite, and obtain approval for quantitative or customer-specific
  claims.
- Run the repository's available build and link checks.
- Keep each pull request focused on one recommendation where practical.
