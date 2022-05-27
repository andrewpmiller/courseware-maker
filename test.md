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
{%- comment -%}
<pre>
Generated at: {{ site.time }}
</pre>
{%- endcomment -%}
