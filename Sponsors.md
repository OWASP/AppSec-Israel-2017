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
For more details on the available sponsorship options please see [Conference Sponsorships](https://github.com/OWASP/AppSec-Israel-2017/blob/master/assets/AppSecIL_2017_Sponsorships.pdf).

For more details and to confirm your sponsorship, please contact [Or Katz](mailto:katz3112@gmail.com). 

### Diamond Sponsor 
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.diamond %}
    <span class="sponsor diamond-sponsor">
      <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
        {% if sponsor.image == blank %}
          <p>{{ sponsor.name }}</p>
        {% else %} 
          <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
        {% endif %}
      </a>
    </span>
{% endfor %}
</div>

##### Gold Sponsors 
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.gold %}
    <tr>
      <span class="sponsor gold-sponsor" vertical-align: text-top>
        <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
          {% if sponsor.image == %}
            <span>{{ sponsor.name }}</span>
          {% else %} 
            <img src="assets/img/Sponsors/{{ sponsor.image }}">
          {% endif %}
        </a>
      </span>
    </tr>
  {% endfor %}
</div>


###### Silver Sponsors
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.silver %}
    <span class="sponsor silver-sponsor" vertical-align: text-top>
      <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
        {% if sponsor.image == %}
          <span>{{ sponsor.name }}</span>
        {% else %} 
          <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
        {% endif %}
      </a>
    </span>
{% endfor %}
</div>

###### A La Carte Sponsorships
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.alacarte %}
    <span class="sponsor alacarte-sponsor" vertical-align: text-top>
      <span>{{ sponsor.type }}</span>  <hr />
      <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
        {% if sponsor.image == %}
          <span>{{ sponsor.name }}</span>
        {% else %} 
          <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
        {% endif %}
      </a>
    </span>
{% endfor %}
</div>

