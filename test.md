---
permalink: /test.html
layout: test
---
{% assign course = site.data.gym-000 %}

# {{ course.course_ID }}: {{ course.course_title }}

{% for lesson in course.course_outline %}
- {{ lesson.title }}
{% endfor %}

---

<pre>
Generated at: {{ site.time }}
</pre>
