---
layout: default
title: Activities
---

# News & Activities

Stay updated with the latest news, seminars, workshops, and events from the Software Engineering Lab.

---

## Latest Updates

{% assign sorted_activities = site.activities | sort: 'date' | reverse %}

{% if sorted_activities.size > 0 %}
  {% for activity in sorted_activities %}
  <div class="activity-item">
    <h3><a href="{{ activity.url | relative_url }}">{{ activity.title }}</a></h3>
    <p class="activity-date">📅 {{ activity.date | date: "%B %d, %Y" }}</p>
    <p>{{ activity.excerpt }}</p>
    <a href="{{ activity.url | relative_url }}" class="read-more">Read more →</a>
  </div>
  {% endfor %}
{% else %}
  <p><em>No activities posted yet. Check back soon!</em></p>
{% endif %}

---

## Categories

- 🎓 Seminars & Workshops
- 📰 Lab News
- 🏆 Awards & Achievements
- 📚 Publications & Releases
- 🤝 Collaborations
- 📢 Announcements

---

## How to Submit News

To share lab news, seminars, or achievements, please:

1. Email [Salman@uohyd.ac.in](mailto:Salman@uohyd.ac.in) with details
2. Include: title, date, description, and any relevant links
3. We'll post it to this page

---

## Archive

*Activity posts will appear automatically in reverse chronological order*

