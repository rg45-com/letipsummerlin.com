---
layout: default
title: Paul Tschernia - Mortgage Loans | LeTip Summerlin
page_name: members
member: paul_tschernia
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
      <p>As an Axia Home Loans Loan Originator, my aim is to fulfill your real estate goals, whether you want to refinance a home you already own or purchase a new one. I am here to provide you with detailed options and sound recommendations so you can make informed choices that best fit your mortgage financing needs. I would love to learn more about your situation and see how Axia Home Loans can help. When you are ready to begin the mortgage lending process, I will be with you every step of the way to make sure your home loan closes quickly and smoothly. When you’re making a decision as important as buying a home, you need a guide who will put you first. Contact me today and let me show you the Axia difference.</p>
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.png" class="img-responsive profile_img">
    </div>

</div>