---
title: Family plans
date: 2019-01-23 20:23:00 +11:00
header: Join the Gnibl club
subheader: Select your preferences and find the Gnibl membership most suited to your
  team.
small box:
  name: Small
  image: "/uploads/starter-box.png"
  cost:
    single box: 32
    monthly: 29
  number of snacks: 10
medium box:
  name: Medium
  image: "/uploads/starter-box.png"
  cost:
    single box: 54
    monthly: 49
  number of snacks: 20
family box:
  name: Family
  image: "/uploads/small-box.png"
  cost:
    single box: 76
    monthly: 69
  number of snacks: 30
size selection:
  lead: How many snacks?
  breakpoints:
  - snacks: 10
    box: small box
  - snacks: 20
    box: medium box
  - snacks: 30
    box: family box
frequency selection:
  lead: 'Select your delivery frequency:'
  options:
  - single box
  - monthly
value props:
- value: "$9 Flat Shipping. (We are unable to ship to WA)"
  image: "/uploads/truck.svg"
cta: Sign up now
layout: default
---

<main class="pricing fixed-header dotted-bg">
<div class="desktop">
<div class="table"></div>
{% include pricing2_sections/calculator.md %}
{% include pricing2_sections/boxes.md %}
</div>
{% include pricing2_sections/mobile-section.md %}
  {% include pricing2_sections/quote-modal.md %}
</main>
