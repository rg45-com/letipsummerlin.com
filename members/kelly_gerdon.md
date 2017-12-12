---
layout: default
title: Kelly Gerdon - Insurance Property and Casualty | LeTip Summerlin
page_name: members
member: kelly_gerdon
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
      <p>Getting the right insurance to protect your dreams can be a big relief, especially if you lead a busy life and find it challenging to explore various insurance options. As your American Family insurance agent, I can help you explore options that meet your unique needs. I have been servicing Las Vegas as an American Family agent for 17 years providing protection for your Auto, Home and Business. Please call me or my expert staff with any Insurance questions.</p>
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.jpg" class="img-responsive profile_img">
    </div>

</div>