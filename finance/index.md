---
layout: page
title: Personal Finance
permalink: /finance/
---

## 💸 Personal Finance

Welcome to my personal finance blog — a space where I explore:

- Budgeting and saving strategies
- Investment ideas and tools
- Financial independence & long-term planning
- Real-world experiences with money management

---

### 📚 Recent Posts

{% assign finance_posts = site.categories.finance %}

{% if finance_posts %}
  {% assign sorted_finance_posts = finance_posts | sort: 'date' | reverse %}
  {% for post in sorted_finance_posts %}
  - [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) <span style="color:#888;">{{ post.date | date: "%b %d, %Y" }}</span>
  {% endfor %}
{% else %}
  _No finance posts published yet — stay tuned!_
{% endif %}

---

Got a question about something financial or a tool you’d like reviewed? [Get in touch]({{ site.baseurl }}/contact/).
