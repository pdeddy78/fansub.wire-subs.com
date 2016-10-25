---
layout: page
title: About
---

<p class="message">
  Hi!
</p>
<div class="hero">
<img src="{{ site.baseurl }}/public/img/baka.jpg">
</div>

## Staff

Some fun facts about the setup of this project:
<ul>
{% for staff in site.data.staff %}
  <li>
	{{ staff.name }}
    from <small>{{ staff.joined }}</small>
  </li>
{% endfor %}
</ul>

Have questions or suggestions? Feel free to [ask us on FB](https://facebook.com/WireSubs).

Thanks for coming!
