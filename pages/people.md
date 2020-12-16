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
{% include member.html name="Dr Li Zhang" title="" photo="/images/people/LiZhang.jpg" website="http://www.robots.ox.ac.uk/~lz/" email="lizhangfd@fudan.edu.cn" 
google scholar="https://scholar.google.com/citations?user=-wOTCE8AAAAJ&hl=en"%}
<hr/>



<h3 class="medium-12 section-title">PhD Students</h3>
<br/>
{% for a in site.alumni %}
	{% include collaborator.html name=a.name title=a.title email=a.email website=a.website note=a.note %}
{% endfor %}
<br/>
<hr/>

<h3 class="medium-12 section-title">Master Students</h3>
<br/>
{% for a in site.alumni %}
	{% include collaborator.html name=a.name title=a.title email=a.email website=a.website note=a.note %}
{% endfor %}
<br/>
<hr/>

<h3 class="medium-12 section-title">Undergraduate Students</h3>
<br/>
{% for a in site.alumni %}
	{% include collaborator.html name=a.name title=a.title email=a.email website=a.website note=a.note %}
{% endfor %}
<br/>
<hr/>


<hr/>
</div>


