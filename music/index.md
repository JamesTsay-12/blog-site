---
layout: page
title: Music
permalink: /music/
---

Welcome to my music blog! 🎵

In addition to all of my more conventional tastes in rock, blues, jazz, and classical music, I'm interested in film and video game soundtrack music and aspire to create different works in this area.  For now I've only posted things made in the distant past, but I'll add more new things as I progress.

Here I'll share:

- Songs I'm working on
- Favorite tracks
- Music production notes
- Instruments and gear I use

---

### 🎧 Listen on SoundCloud

<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay"
  src="https://w.soundcloud.com/player/?url=https%3A//soundcloud.com/james-tsay-857457878&color=%23ff5500&inverse=false&auto_play=false&show_user=true">
</iframe>

🔗 [**View all tracks on SoundCloud**](https://soundcloud.com/james-tsay-857457878)

---

### 🎧 Blog Posts

{% assign music_posts = site.categories.music %}

{% if music_posts %}
  {% assign sorted_music_posts = music_posts | sort: 'date' | reverse %}
  {% for post in sorted_music_posts %}
  - [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) <span style="color:#888;">{{ post.date | date: "%b %d, %Y" }}</span>
  {% endfor %}
{% else %}
  _No music posts found yet. Stay tuned!_
{% endif %}

Stay tuned for posts tagged with `music`!



