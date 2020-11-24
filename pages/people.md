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

<h3 class="section-title">Group Leader</h3>
<br/>
{% include member.html name="Philip H.S. Torr" title="Professor" photo="/images/people/Phil.jpg" website="http://www.robots.ox.ac.uk/~phst/" email="mailto:philip.torr@eng.ox.ac.uk"%}

{% include member.html name="Joanna Zapisek" photo="/images/people/JoannaZapisek.jpg" title="Project Manager" %}

{% include member.html name="Cassandra Warren" title="Group Administrator" %}

<hr/>

<h3 class="medium-12 section-title" >Senior Researcher</h3>
<br/>

{% for d in site.senior_researchers %}
	{% include member.html name=d.name photo=d.photo website=d.website email=d.email year=d.year%}
{% endfor %}


<hr/>

<h3 class="medium-12 section-title">Research Fellows</h3>
<br/>

{% assign postdocs = site.postdocs | sort: "name" | reverse %}
{% for pd in postdocs %}
	{% include member.html name=pd.name photo=pd.photo website=pd.website email=pd.email %}
{% endfor %}



<hr/>

<h3 class="medium-12 section-title">Graduate Students</h3>
<br/>

{% for d in site.dphils %}
	{% include member.html name=d.name photo=d.photo website=d.website email=d.email year=d.year%}
{% endfor %}


<br/>
<hr/>

<h3 class="medium-12 section-title">Graduated PhD Students</h3>
<br/>

{% for a in site.alumni %}
	{% include collaborator.html name=a.name title=a.title email=a.email website=a.website note=a.note %}
{% endfor %}
<br/>
<hr/>

<h3 class="medium-12 section-title">Close Associate Members</h3>
<br/>

{% for c in site.close_members %}
	{% include collaborator.html name=c.name title=c.title email=c.email website=c.website note=c.note%}
{% endfor %}
<br/>
<hr/>


<h3 class="medium-12 section-title">Former Members</h3>
<br/>

{% for f in site.former_members %}
	{% include collaborator.html name=f.name title=f.title email=f.email website=f.website note=f.note%}
{% endfor %}
<br/>
<hr/>
</div>


