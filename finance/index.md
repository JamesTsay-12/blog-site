---
layout: page
title: Personal Finance
permalink: /finance/
---

## 💸 Personal Finance

Welcome to my personal finance blog — a space where I explore:

- Investment ideas and tools  
- Financial independence & long-term planning  
- Psychology and Philosophy of Investing
- Budgeting and saving strategies
    
My aim here is to provide perspectives that are objective and data-driven, while being open to different points of view. I add references to back up the articles so you can decide yourself the validity of the conclusions.  Please take these blogs as food for thought instead of prescriptive financial advice. Hopefully there are some useful perspectives shared here.


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

Disclaimer: I am not a financial advisor, CPA, or licensed professional. All content on this blog is for informational and educational purposes only and does not constitute financial, investment, or legal advice. Please consult with a qualified professional for personalized advice.
