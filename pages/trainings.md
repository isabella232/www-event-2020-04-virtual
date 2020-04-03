---

title: Trainings
layout: event_noheader
permalink: /trainings/

---

<link rel="stylesheet" type="text/css" href="/assets/css/training.css">

# {{ page.title }}
<br>

* **Tuesday, April 28** and **Wednesday, April 29** at
* 12:00pm to 4:00pm EDT/6:00pm to 10:00pm CEST 


**Training subject to change based on trainer availability.**

{% for trainer in site.data.trainings %}
<section id="{{trainer.SectionId}}">
<hr>
<ul>
<li><h3 class='training-header'>{{ trainer.Title }}</h3></li>
<li class="training-desc">{{ trainer.Description }}</li>
    <ul>
        <li><hr><div class="training-container"><div class="training-image" style="background-image:url('{{trainer.Image}}');"></div><div class='trainer-container'><strong>Trainer:</strong><a href="/trainers/#{{trainer.SectionId}}">{{trainer.Name}}</a></div></div></li>
    </ul>
</ul>
</section>
{% endfor %}
