---
layout: default
title: Sandy Scheppmann - Escrow Agent | LeTip Summerlin
page_name: members
member: sandy_scheppmann
---
{% include mem_bio_data.html %}
<div class="container margin-b-30">
  <div class="wide_banner">
    <h1>{{ mem_cat }} - {{ fullname }}</h1>
  </div>

    <div class="col-sm-8 padding-15">
          <p class="subtitle">{% if mem_data.title %}{{ mem_data.title }}<br>{% endif %}{{ mem_data.company }}</p>
          <p class="phone"><i class="fa fa-phone-square"></i> {{ mem_data.phone }}</p>
          <p class="email"><i class="fa fa-envelope"></i> {{ mem_data.email }}</p>
          {% if mem_data.website %}<p class="web"><i class="fa fa-desktop"></i> <a href="https://www.{{ mem_data.website }}" target="_blank">{{ mem_data.website }}</a></p>{% endif %}

      <p>Sandy is a Licensed Escrow Officer with 18 years combined experience in Residential Escrow, Business Development, and Real Estate Investment. As a value added service for her referring clients, Sandy offers 16 years of experience as a Certified Professional Coach & Consultant specializing in Niche Marketing, Customer Experience, and Leadership Development.</p>

      <p>
        Moving from Orange County, CA to Las Vegas, Sandy joined OS National Title, a fully-diversified national title and settlement provider, in February of 2018. 
      </p>

      <p>
        OS National is a premier nationwide title insurance agency founded on a deeply rooted passion to better serve customers and their evolving needs, as we approach title insurance differently - with the customer first. Keeping this at the forefront, OSN is able to define who we are, what we stand for, and how we will interact with you. We are not your typical title company. We are redefining title services.
      </p>
      
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.jpg" class="img-responsive profile_img">
    </div>

</div>