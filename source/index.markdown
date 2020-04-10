---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# How to contact me: #

* **Name**: {{ site.data.contactInfo.fullName }}
* **Email**: {{ site.data.contactInfo.email }}
* **Phone**: {{ site.data.contactInfo.phone }}
{% for link in site.data.contactInfo.links %}* **{{ link.name }}**: <{{link.url}}>
{% endfor %}
