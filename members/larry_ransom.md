---
layout: default
title: Larry Ransom - Financial Advisor | LeTip Summerlin
page_name: members
member: larry_ransom
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
      Larry Ransom is married with 3 beautiful “fur kids”.  He’s been in Las Vegas since 1996 when he moved here to study music at UNLV.  He began his financial services tenure with Country Financial nearly 10 years ago but has 15 years experience in the industry.  Larry still pursues his passion with music as a contract member of The Las Vegas Philharmonic and The Guardian Angel Cathedral Orchestras.  He and business partner, Joseph Durk together with fellow trumpeter, Gary Cordell, founded the charity T.A.P.P.S. to work everyday to honor the valley’s fallen veterans. 
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.jpg" class="img-responsive profile_img">
    </div>

</div>