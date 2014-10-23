---
layout: default
title: Sample Slide Me page
byline: Just another byline
leadingpath: .
---

{% capture slide %}
## Slidedown

Single-document Markdown presentation decks

{% endcapture %}{% include slide-section %}


{% capture slide %}
## Simplicity

Markdown and a few special `{ % include % }` is all you need
{% endcapture %}{% include slide-section %}

{% capture slide %}
## Table of contents

Automatically built table of contents makes browsing easy
{% endcapture %}{% include slide-section %}


{% capture slide %}
## Responsive

Based on [Bootstrap](https://getbootstrap.com) for the ultimate in responsive layout
{% endcapture %}{% include slide-section %}


{% capture slide %}
## Notes

Add notes directly below slides for resources and reference
{% endcapture %}{% include slide-section %}

### Slide mode toggle

Hide notes and resources during presentation mode.
