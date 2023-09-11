---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Mekanism
---
Right now this site only contains the documentation for the computer exposed methods.

Select your Mekanism version below to see the details.
### Computer Methods
<ul>
{% for item in site.computer_data %}
    <li><a href="{{item.url}}">{{item.version}}</a></li>
{% endfor %}
</ul>
