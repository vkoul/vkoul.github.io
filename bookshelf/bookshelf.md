---
layout: page
title: "Bookshelf"
permalink: /bookshelf/
---
Below is a list of books I have read, with links to my notes and summaries on each one.

{% for summary in site.summaries %}
- {{ summary.date | date: "%b '%y" }} [{{ summary.title }}]({{ summary.url }})
{% endfor %}