---
layout: default
title: Joseph Durk - Insurance - Life, Health and Disability | LeTip Summerlin
page_name: members
member: joseph_durk
---
{% include mem_bio_data.html %}
<div class="container margin-b-30">
  <div class="wide_banner">
    <h1>{{ mem_cat }} - {{ fullname }}</h1>
  </div>

    <div class="col-sm-8 padding-15">
      <h3></h3>
      <p class="subtitle">{% if mem_data.title %}{{ mem_data.title }}<br>{% endif %}{{ mem_data.company }}</p>
      <p class="phone"><i class="fa fa-phone-square"></i> {{ mem_data.phone }}</p>
      <p class="email"><i class="fa fa-envelope"></i> {{ mem_data.email }}</p>
      {% if mem_data.website %}<p class="web"><i class="fa fa-desktop"></i> <a href="http://www.{{ mem_data.website }}" target="_blank">{{ mem_data.website }}</a></p>{% endif %}
      Joseph Durk is native to Las Vegas and is married with 4 lovely children. He started his tenure with COUNTRY Financial 15 years ago.  "Everybody has a nephew or uncle in the profession but 80% of the industry turns over every three years" -- wouldn't it be great to do business with someone you know is going to be around and isn't worried about meeting some sales quota?<br><br>
      He has also been a professional musician in Las Vegas for over 15 years.  He is currently playing with the Las Vegas Philharmonic and Nevada Ballet theater orchestras.  He's also a co-founder, along with business partner Larry Ransom, of T.A.P.P.S. - a veterans service charity.
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.jpg" class="img-responsive profile_img">
    </div>

</div>