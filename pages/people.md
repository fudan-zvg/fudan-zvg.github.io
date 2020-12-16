---
layout: page
show_meta: false
title: "People"
subheadline: ""
teaser: 
header:
   image_fullwidth: 
permalink: "/people/"


---

<div class="row"> 

	<hr/>

	<h3 class="section-title">Principal Investigator</h3>

    {% for a in site.member %}
	    {% include member.html 
            name=a.name 
            title=a.title 
            photo=a.photo
            website=a.website
            google=a.google
            email=a.email
	    %}
	{% endfor %}
	<hr/>

	<h3 class="medium-12 section-title">PhD Students</h3>

	{% for a in site.phd %}
		{% include collaborator.html 
            name=a.name 
            title=a.title 
            email=a.email 
            website=a.website 
            note=a.note 
        %}
	{% endfor %}

	<hr/>

	<h3 class="medium-12 section-title">Master Students</h3>

	{% for a in site.master %}
		{% include collaborator.html 
            name=a.name 
            title=a.title 
            email=a.email 
            website=a.website 
            note=a.note 
		%}
	{% endfor %}

	<hr/>

	<h3 class="medium-12 section-title">Undergraduate Students</h3>

	{% for a in site.undergraduate %}
		{% include collaborator.html 
            name=a.name 
            title=a.title 
            email=a.email 
            website=a.website 
            note=a.note 
		%}
	{% endfor %}

	<hr/>

	<h3 class="medium-12 section-title">Visiting Students</h3>

	{% for a in site.visit %}
		{% include collaborator.html 
            name=a.name 
            title=a.title 
            email=a.email 
            website=a.website 
            note=a.note 
		%}
	{% endfor %}

	<hr/>

</div>




