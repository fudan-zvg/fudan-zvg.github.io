---

layout: frontpage
header:
  image_fullwidth:
title: "Zhang Vision Group - Fudan University"

sidebar: right

permalink: /index.html
homepage: true

---

<div class="row" style= "margin-top: 30px; max-height: 540px; margin-left: 1%">
    <div class="light-section mt-6 mb-6">
      <h3 class="section-title">Breaking News</h3>
      <ul class="timeline col-md-6 off-md-6">
        {% for n in site.news %}
          {% include news_item.html news_date=n.news_date title=n.title year=n.year news_content=n.news_content %}
        {% endfor %}
      </ul>
  </div>
</div>

<div class="pc dark-section" style="">
  <br>
  <h3 class="section-title"> Join the Group </h3> 

  We are currently looking to hire talented students. 
  <br>
  If you are highly creative, have top grades/coding skill and interested in joining our group please do not hesitate to send your CV and transcripts of grades to <a href="mailto:lizhangfd@fudan.edu.cn">lizhangfd@fudan.edu.cn </a>

</div>
