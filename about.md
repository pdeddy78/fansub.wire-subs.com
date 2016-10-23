---
layout: page
title: About
---

<p class="message">
  Hi!
</p>


## Staff

Some fun facts about the setup of this project:
<ul>
{% for staff in site.data.staff %}
  <li>
    [{{ staff.name }}](https://facebook.com/{{ staff.facebook }}) from <small>{{ staff.joined | date_to_string }}</small>
  </li>
{% endfor %}
</ul>

Have questions or suggestions? Feel free to [ask us on FB](https://facebook.com/WireSubs).

Thanks for coming!
