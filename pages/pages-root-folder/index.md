---

layout: frontpage
header:
  image_fullwidth:
title: "Torr Vision Group - University of Oxford"

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
  <h3 class="section-title"> About TVG </h3> 

The aim of the group is to engage in state of the art research into the mathematical theory of computer vision and artificial intelligence, but to keep the mathematical research relevant to the needs of society. A particular emphasis of the group has been on real time understanding and reconstruction of the world around using mobile cameras, such as those on drones, intelligent glasses or other robots. Examples of which can be seen here <a href="http://www.robots.ox.ac.uk/~szheng/crfasrnndemo"> CRF-RNN </a> and here <a href="https://www.youtube.com/watch?v=z_TcWC7yjj0"> Semantic Paint </a>.

Members of the group have won major awards in all the main conferences in the field including the International Conference on Computer Vision (ICCV), CVPR, ECCV, BMVC, NeurIPS as well as various thesis awards for the students, and industrial awards such as best Knowledge Transfer Partnership. We have collaborated with many exciting high tech companies including Google, Sony, Microsoft, Technicolor, and Sharp.

</div>


<div class="pc light-section" style="">
  <br>
  <h3 class="section-title"> Join the Lab </h3> 

  We are currently looking to hire both talented post docs and doctoral students, please contact Professor Torr <a href="mailto:philip.torr@eng.ox.ac.uk">philip.torr@eng.ox.ac.uk </a>.

</div>
