---
layout: default
title: Gustavo J Chavez-Pelayo - Residential Realtor | LeTip Summerlin
page_name: members
member: gustavo_chavez
---
{% include mem_bio_data.html %}
<div class="container margin-b-30">
  <div class="wide_banner">
    <h1>{{ mem_cat }} - Gustavo J Chavez-Pelayo</h1>
  </div>

    <div class="col-sm-8 padding-15">
      <div class="row">
        <div class="col-xs-7 padding-15">
          <p class="subtitle">{% if mem_data.title %}{{ mem_data.title }}<br>{% endif %}{{ mem_data.company }}<br/>
          License #S.0175172</p>
          <p class="phone"><i class="fa fa-phone-square"></i> {{ mem_data.phone }}</p>
          <p class="email"><i class="fa fa-envelope"></i> {{ mem_data.email }}</p>
          {% if mem_data.website %}<p class="web"><i class="fa fa-desktop"></i> <a href="https://www.{{ mem_data.website }}" target="_blank">{{ mem_data.website }}</a></p>{% endif %}
        </div>
        <div class="col-xs-5 padding-15">
          <img src="/assets/img/va-certified.jpg" class="img-responsive profile_img" style="max-height: 150px;">
        </div>
      </div>

      <p>My goal is to save or maximize my client's profits by educating them on market conditions and connecting them with business consultants that will help structure a plan to achieve their goals.</p>
      
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.jpg" class="img-responsive profile_img">
    </div>

</div>