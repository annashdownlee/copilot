## Welcome to Copilot

<img src="https://images.squarespace-cdn.com/content/5c869f61b10f25fb5feea9bc/1554402871368-LZGTUOS8PHABQBO3S6PV/Color+logo+-+no+background.png?format=1500w&content-type=image%2Fpng" height="42" width="42">


### Practitioners
{% for person in site.data.practitioners %}
  - {{person.name}} ({{person.state}}) <img src="{{person.image_url}}" height="42" width="42">

{% endfor %}
