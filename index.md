---
layout: default
title: Home
---

# Welcome to Software Engineering Lab

<div class="hero-section">
  <img src="{{ site.baseurl }}/assets/images/selablogo.png" alt="SE Lab Logo" class="hero-logo">
  <div class="hero-text">
    <h1>{{ site.lab_name }}</h1>
    <p class="subtitle">{{ site.school }}, {{ site.university }}</p>
  </div>
</div>

## About Our Lab

The Software Engineering Lab at the School of Computer and Information Sciences, University of Hyderabad, conducts research in software engineering methodologies, practices, and tools.

Our research focuses on improving software quality, development processes, and modern software engineering challenges.

---

## Research Areas

- **Software Quality & Testing**
- **Software Process & Methodologies**
- **DevOps & Continuous Integration**
- **Software Maintenance & Evolution**
- **Software Security**

*[Add more research themes as needed]*

---

## Latest News & Activities

{% assign sorted_activities = site.activities | sort: 'date' | reverse %}
{% for activity in sorted_activities limit: 5 %}
<div class="activity-card">
  <h3><a href="{{ activity.url | relative_url }}">{{ activity.title }}</a></h3>
  <p class="date">{{ activity.date | date: "%B %d, %Y" }}</p>
  <p>{{ activity.excerpt }}</p>
</div>
{% endfor %}

[View all activities →]({{ site.baseurl }}/activities)

---

## Quick Links

- 📚 [Research]({{ site.baseurl }}/research)
- 📄 [Publications]({{ site.baseurl }}/publications)
- 👥 [Team Members]({{ site.baseurl }}/members)
- 📧 [Contact Us]({{ site.baseurl }}/contact)

