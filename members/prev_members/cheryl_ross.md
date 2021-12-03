---
layout: default
title: Cheryl Ross - Mobile Notary Public | LeTip Summerlin
page_name: members
member: cheryl_ross
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
      <p>I have been a Notary Public for over 30 years, starting out in California before coming to Las Vegas.  I have a team of Notaries that will travel to your location and can fulfill all of your notary requirements in Las Vegas, North Las Vegas, Henderson and Boulder City.</p>
      <p>We can handle any notary work from <strong>full loan signings</strong> to individual notary needs, including <strong>Power of Attorney, Will &amp; Probate/Estate, Medical, Adoption, Travel</strong>, etc.</p>
      <p>My team and I are all Bonded, Insured and certified, and we service Attorneys and Title companies as well as private parties.  We are a mobile notary service; we come to you at your convenience, 7 days a week from 7 am to midnight.</p>
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.jpg" class="img-responsive profile_img">
    </div>

</div>