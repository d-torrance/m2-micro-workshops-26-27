---
title: Macaulay2 Micro-Workshops
subtitle: A series of short, focused workshops for Macaulay2 users and developers, 2026–27
---

A **micro-workshop** is a small, tightly scoped gathering built around a single theme in
[Macaulay2](https://macaulay2.com). The "micro" refers to the size and the scope rather
than the length — a workshop may well run a full week — with only a handful of
participants working on one narrowly defined set of problems.

Projects lean toward the **internals of Macaulay2**: the C++ engine, the interpreter,
the build system, and the infrastructure the rest of the system rests on, rather than
mathematics implemented at the package level.

Over 2026 and 2027 we are running a series of these at several host institutions. If you
are interested in taking part, get in touch with the [organizers](#organizers).

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

<h2 id="organizers">Organizers</h2>

The series is organized by [Mike Stillman](https://pi.math.cornell.edu/~mike) (Cornell
University) and [Doug Torrance](https://d-torrance.github.io) (Georgia Institute of
Technology). Individual workshops also have local hosts, listed on each workshop's page.
