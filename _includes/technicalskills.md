| Skill | Tech |
| ---- | ---- |
{% assign skills = site.data.skills.technical | sort: "title" -%}
{% for skill in skills -%}
{{skill.title}} | {{skill.tech}}
{%endfor%}
