---

layout: page

show\_meta: false

title: "Publication"

subheadline: ""

teaser: 

header:

   image\_fullwidth: 

permalink: "/publication/"

---

[[2020][1]] [[2019][2]] [[2018][3]] [[2017][4]] [[2016][5]

<div class="">

    {% assign publications = site.publications | sort: "year" | reverse %}
    {% for pub in publications %}

        {%  include pub_item.html 
            
            title=pub.title
            author_list=pub.author_list
            pub_in=pub.pub_in
            bib=pub.bib
            grant=pub.grant
            img_path=pub.img_path
            pdf_url=pub.pdf_url
            website=pub.website
            code_url=pub.code_url
            blog_post=pub.blog_post
        %}    


    {% endfor %}


</div>


[1]:	/publication/#2020
[2]:	/publication/#2019
[3]:    /publication/#2018
[4]:    /publication/#2017
[5]:    /publication/#2016