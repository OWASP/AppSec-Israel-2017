---
---

## Sponsors

AppSec Israel Conference and Training are completely free to attend, thanks to the generous support of these sponsors! 

### Interested in becoming a sponsor for AppSecIL 2017? 

Whether you have a product to showcase, offering a service, or you are recruiting - sponsoring the OWASP AppSec Israel Conference gets you the right exposure.   
This year we are expecting over 700 attendees, including security professionals, developers, managers, and more.

Sponsorship also helps support the OWASP community, and ensures that we can keep on making our conferences better and better. Sponsorship fees are intended to cover the costs of the conference only. Since the conference is open to all and free of charge to attend, we need your support to enable us to put on a great conference.

We are now offering several tiers of premium sponsorship.   
There is also a cost-effective “Community Supporter” option for non-profits, government offices, small startups, and such.   
For more details on the available sponsorship options please see [Conference Sponsorships]({{ site.url }}/assets/AppSecIL_2017_Sponsorships.pdf).

For more details and to confirm your sponsorship, please contact [Or Katz](mailto:katz3112@gmail.com). 

### Diamond Sponsor 
<div>
  {% for sponsor in site.data.sponsors.diamond %}
    <span class="sponsor diamond-sponsor">
      <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
        {% if sponsor.image == "" %}
          <p>{{ sponsor.name }}</p>
        {% else %} 
          <img src="assets/img/Sponsors/{{ sponsor.image }}" width="500" height="200"> 
        {% endif %}
      </a>
    </span>
{% endfor %}
</div>

#### Platinum Sponsors
<div>
  {% for sponsor in site.data.sponsors.platinum %}
    <span class="sponsor platinum-sponsor">
      <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
        {% if sponsor.image == "" %}
          <p>{{ sponsor.name }}</p>
        {% else %} 
          <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
        {% endif %}
      </a>
    </span>
{% endfor %}
</div>


##### Gold Sponsors 
<div>
  {% for sponsor in site.data.sponsors.gold %}
    <span class="sponsor gold-sponsor">
      <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
        {% if sponsor.image == "" %}
          <p>{{ sponsor.name }}</p>
        {% else %} 
          <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
        {% endif %}
      </a>
    </span>
{% endfor %}
</div>


###### Silver Sponsors
<div>
  {% for sponsor in site.data.sponsors.silver %}
    <span class="sponsor silver-sponsor">
      <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
        {% if sponsor.image == "" %}
          <p>{{ sponsor.name }}</p>
        {% else %} 
          <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
        {% endif %}
      </a>
    </span>
{% endfor %}
</div>

###### A La Carte Sponsorships
<div>
  {% for sponsor in site.data.sponsors.alacarte %}
    <span class="sponsor alacarte-sponsor">
      <p>{{ sponsor.type }}</p>
      <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
        {% if sponsor.image == "" %}
          <p>{{ sponsor.name }}</p>
        {% else %} 
          <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
        {% endif %}
      </a>
    </span>
{% endfor %}
</div>

