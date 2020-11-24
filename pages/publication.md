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

[[2020][1]] [[2019][2]] [[2018][3]] [[2017][4]] [[2016][5]] [[2015][6]] [[2014][7]] [[2013][8]] [[2012][9]]
[[2011][10]] [[2010][11]] [[2009][12]] [[2008][13]] [[2007][14]] [[2006][15]] [[2005][16]] [[2004][17]] [[2003][18]]

<div class="">

    {% assign publications = site.publications | sort: "year" | reverse %}
    {% for pub in publications %}

        {%  include pub_item.html 
            pdf_url=pub.pdf_url
            title=pub.title
            author_list=pub.author_list
            pub_in=pub.pub_in
            bib=pub.bib
            grant=pub.grant
        %}    


    {% endfor %}


</div>


[1]:	/publication/#2020
[2]:	/publication/#2019
[3]:    /publication/#2018
[4]:    /publication/#2017
[5]:    /publication/#2016
[6]:    /publication/#2015
[7]:    /publication/#2014
[8]:    /publication/#2013
[9]:    /publication/#2012
[10]:    /publication/#2011
[11]:    /publication/#2010
[12]:    /publication/#2009
[13]:    /publication/#2008
[14]:    /publication/#2007
[15]:    /publication/#2006
[16]:    /publication/#2005
[17]:    /publication/#2004
[18]:    /publication/#2003