## Welcome to Copilot

<img src="https://images.squarespace-cdn.com/content/5c869f61b10f25fb5feea9bc/1554402871368-LZGTUOS8PHABQBO3S6PV/Color+logo+-+no+background.png?format=1500w&content-type=image%2Fpng" height="42" width="42">

<div class="dropdown">
  <button onclick="myFunction()" class="dropbtn">Dropdown</button>
  <div id="myDropdown" class="dropdown-content">
    <input type="text" placeholder="Search.." id="myInput" onkeyup="filterFunction()">
    <a href="#about">About</a>
    <a href="#base">Base</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
    <a href="#custom">Custom</a>
    <a href="#support">Support</a>
    <a href="#tools">Tools</a>
  </div>
</div>

### Practitioners
{% for person in site.data.practitioners %}
  - {{person.name}} ({{person.state}}) <img src="{{person.image_url}}" height="42" width="42">

{% endfor %}
