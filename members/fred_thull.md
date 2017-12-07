---
layout: default
title: Fred Thull - Accountant | LeTip Summerlin
page_name: members
member: fred_thull
---
{% include mem_bio_data.html %}
<div class="container margin-b-30">
  <div class="wide_banner">
    <h1>{{ mem_cat }} - {{ fullname }}</h1>
  </div>

    <div class="col-sm-8 padding-15">
      <h3></h3>
      <p class="subtitle">{{ mem_data.company }}</p>
      <p class="phone"><i class="fa fa-phone-square"></i> {{ mem_data.phone }}</p>
      <p class="email"><i class="fa fa-envelope"></i> {{ mem_data.email }}</p>
      {% if mem_data.website %}<p class="web"><i class="fa fa-desktop"></i> <a href="http://www.{{ mem_data.website }}" target="_blank">{{ mem_data.website }}</a></p>{% endif %}
      <p>I am a licensed Certified Public Accountant (CPA). I have worked in the accounting profession for over 35 years for several different companies and had a variety of responsibilities providing me with a wide range of knowledge in accounting and finance.  I have a Bachelor’s degree from Southeast Missouri State University and an MBA from the University of New Mexico.</p>
      <p>I've been a Padgett Business Services representative since the spring of 2013.  Padgett's primary goal is to provide accounting, consultation, payroll and tax services to small business, but we also assist individuals in the preparation of their personal taxes.</p>
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.jpg" class="img-responsive profile_img">
    </div>

</div>