---
title: Phase 3
phase: 3
published: true
---

{% assign topics = site.data.phase3.topics | reverse | where: "published", "true" %}
{% assign demos = site.data.phase3.demos %}
{% assign projects = site.data.phase3.projects %}

{% for topic in topics %}
{{ topic.date | date: "%B %-d" }}
: {% if topic.page %} [{{ topic.title }}]({% link {{topic.page}} %}){% else %} {{topic.title}} {% endif %}
: {% if topic.post_today %} [Post]({% link posts.md %}){: .label .post-label } {% endif %}[Project]({{ projects[topic.project_name].url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .project-label } {% if topic.code_demo %} [Demo]({{ demos[topic.code_demo].url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .code-demo-label } {% endif %}
{% endfor %}
