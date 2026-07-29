---
title: Macaulay2 Micro-Workshops
subtitle: A series of short, focused workshops for Macaulay2 users and developers, 2026–27
---

A **micro-workshop** is a short, focused gathering — typically a long weekend — built
around a single theme in [Macaulay2](https://macaulay2.com). Each one brings together a
small group of users and developers to write code, improve packages, and work on
documentation, with plenty of time set aside for collaboration.

Over 2026 and 2027 we are running a series of these at several host institutions. They
are open to anyone interested in Macaulay2; no prior experience contributing to the
system is required, though some familiarity with the language is helpful.

<h2 id="workshops">Workshops</h2>

{% assign workshops = site.workshops | sort: "order" %}
<ul class="workshop-list">
{% for w in workshops %}
  <li class="workshop-card">
    <h3><a href="{{ w.url | relative_url }}">{{ w.title }}</a></h3>
    <p class="workshop-meta">{{ w.date_display }} &middot; {{ w.location }}</p>
    <p class="workshop-blurb">{{ w.blurb }}</p>
  </li>
{% endfor %}
</ul>

## Contact

Questions about the series are welcome — see the [organizers]({{ '/organizers' | relative_url }}) page.
