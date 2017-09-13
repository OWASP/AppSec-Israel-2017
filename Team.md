---
---

## The people behind the conference

OWASP's AppSec Israel is made by the people who contribute their time, brains, and patience to its success.   
The following people are working to ensure that OWASP AppSec Israel is a success.    

If you feel that you also can contribute or have interesting ideas regarding the conference,   
please don't hesitate to contact [AviD](mailto:avi.douglen@owasp.org) directly.


### Contributors

AppSec Israel 2017 was organized by: 

{% for member in site.data.team.board %}
 - {{ member.name }} ({{ member.title }}) - *{{ member.role }}*
{% endfor %}

<br /> 

The amazing talks at AppSecIL were reviewed and selected by the Content Committee, formed from a group of leading security experts. The Committee includes:

{% for member in site.data.team.content %}
 - {{ member.name }} ({{ member.title }})
{% endfor %}

<br /> 

We also had a lot of help from volunteers, including: 

{% for member in site.data.team.volunteers %}
 - {{ member.name }} ({{ member.title }}) - *{{ member.role }}*
{% endfor %}

