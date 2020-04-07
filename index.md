---

title: OWASP Virtual AppSec Days April 2020
layout: event

---

<!-- rebuild 9-->

{{ site.data.event-details.pitch }}
     
### Training Sessions hosted 12pm ET (1800 CET) Include


* #### Register for the class you want by clicking below
* Please note: All courses take place simultaneously over 2 days, only register for 1.
* *(more information can be found on the [Training](/trainings/) page)*
<ul>
  {% assign trainings = site.data.trainings | sort: 'Title' %}
  {% for trainer in trainings %}
    <li><a href="{{trainer.URL}}">{{ trainer.Title }}</a></li>
  {% endfor %}
</ul>


