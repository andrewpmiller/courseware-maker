---
layout: default
permalink: /course.xml
---
{%- assign course = site.data.gym-000 -%}
<course url_name="course" org="GYM" course="{{ course.course_ID | slice: -3,3 }}"/>
