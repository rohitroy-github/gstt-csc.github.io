---
title: Policy
order: 4
image:
---

<!-- Resources -->
<table class="table table-hover">
  <thead>
    <tr>
      <th scope="col">Resource</th>
      <th scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
  {% for resource in site.data.resources.policy %}
  <tr>
    <td>{% if resource.link %}<a href="{{ resource.link }}">{{ resource.name }}</a>{% else %} {{ resource.name }}{% endif %}</td>
    <td>{{ resource.description }}</td>
  </tr>
{% endfor %}
  </tbody>
</table>
<!-- Resources -->