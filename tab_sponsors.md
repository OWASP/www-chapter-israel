---

title: Sponsors
displaytext: Chapter sponsors
layout: null
tab: true
order: 4
tags: Israel

---

[AppSec Israel detailed sponsorship tiers and options can be found in AppSec IL site](https://appsecil.org/Sponsors)

### AppSec Israel Sponsors 

<img src="assets/images/Sponsors/AppsecIL-sponsors.png">

{% if site.data.sponsors.gold %}
### Gold Chapter Supporters  
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.gold %}
	  <span class="sponsor gold-sponsor">
		<a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		  {% if sponsor.image == %}
			<span>{{ sponsor.name }}</span>
		  {% else %} 
			<img src="assets/images/Sponsors/{{ sponsor.image }}">			
		  {% endif %}
		</a>
	  </span>
  {% endfor %}
</div>
{% endif %}

## Local sponsors

If you want to support our chapter, please contact [Ori Troyna](mailto:ori.troyna@owasp.org). 
