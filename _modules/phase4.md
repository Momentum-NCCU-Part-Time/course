---
title: Agile Development
phase: 3
published: true
---

{% assign topics = site.data.phase4.topics | reverse | where: "published", "true" %}
{% assign demos = site.data.phase4.demos %}
{% assign projects = site.data.phase4.projects %}

{% for topic in topics %}
{{ topic.date | date: "%B %-d" }}
: {% if topic.page %} [{{ topic.title }}]({% link {{topic.page}} %}){% else %} {{topic.title}} {% endif %}
: {% if topic.post_today %} [Post]({% link posts.md %}){: .label .post-label } {% endif %}{% if topic.project %}[Project]({{ projects[topic.project].url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .project-label } {% endif %}{% if topic.code_demo %} [Demo]({{ demos[topic.code_demo].url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .code-demo-label } {% endif %}
{% endfor %}
