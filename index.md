---

title: OWASP Virtual AppSec Days April 2020
layout: event

---

<!-- rebuild 9-->

<!-- {{ site.data.event-details.pitch }} -->

## Improve your AppSec Skills for a Great Price

The OWASP Foundation is hosting a Virtual AppSec Days on April 27-29th. We will be running a 90 minute virtual mini-conference Monday, April 27, followed by 8-hour virtual training courses offered in 4-hour blocks on the 28th-29th. The trainings will begin at 12:00pm Eastern Time (USA)/6:00pm Central European Time.
     
### Training Sessions hosted 12pm ET (1800 CET) Include


* #### Register for the class you want by clicking below 
* *(more information can be found on the [Training](/trainings/) page)*
<ul>
  {% assign trainings = site.data.trainings | sort: 'Title' %}
  {% for trainer in trainings %}
    <li><a href="/trainings/{{trainer.URL}}">{{ trainer.Title }}</a></li>
  {% endfor %}
</ul>


