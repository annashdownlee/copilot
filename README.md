## Welcome to Copilot

### Practitioners
{% for person in site.data.practitioners %}
  - {{person.name}} ({{person.state}}) <img src="{{person.image_url}}" height="42" width="42">

{% endfor %}
