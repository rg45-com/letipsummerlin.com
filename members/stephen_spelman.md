---
layout: default
title: Stephen Spelman - Dentist | LeTip Summerlin
page_name: members
member: stephen_spelman
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
      <p class="lead">Cosmetic, Implant, Invisalign and General Dentistry</p>
      <p>Dr. Stephen W. Spelman graduated from the renowned University of the Pacific School of Dentistry and has practiced quality Dentistry in Las Vegas since 1981.  Dr. Spelman studied at the distinguished Las Vegas Institute for Advanced Dental Studies and received the L.V.I. certification for Full Mouth Reconstruction.  Dr. Spelman also was awarded a Fellowship in the Academy of General Dentistry (FAGD) in 1997, one of the few dentists in Nevada to achieve this recognition.</p>
      <p>Dr. Spelman is co-owner of Willow Springs Dental, an award-winning, spa-like dental facility where patients experience state-of-the-art technology in a beautiful, relaxed environment.  Willow Springs Dental is located at 3450 S. Hualapai Way, just minutes from the 215 and Town Center Drive or Flamingo Blvd exits.   Willow Springs Dental is convenient to Summerlin (cross streets are Desert Inn Road and South Hualapai Way) and the entire southwest area of Las Vegas.</p>
      <p>Dr. Spelman specializes in Cosmetic Dentistry, Dental Implants and is an Invisalign Preferred Provider. Using porcelain veneers, CEREC one-day crowns, dental implants, gum contouring, and professional bleaching, Dr. Spelman creates bright, new smiles often in only one or two visits.  For many of his patients, their new smiles have a profound and positive impact on their professional and personal lives.  Our practice also includes three excellent and experienced Registered Dental Hygienists that perform our patient hygiene cleanings.</p>
      <p>Dr. Stephen Spelman has been voted a 2017 Las Vegas top DENTIST by his peers in the dental profession and has been voted to the top DENTIST list every year since 2007.  Additionally, Dr. Spelman has been a volunteer dentist for the Huntridge Teen Clinic since 1998 and collaborates with the Donated Dental Services Program to provide necessary treatments for the needy.</p>
      <p>“Doc Steve” is originally from San Francisco, CA.  He loves classic cars, enjoys pitching in the adult baseball league, playing tennis and spending time with his wife, Janet and two daughters, Hayley and Samantha.</p>
      
      
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.jpg" class="img-responsive profile_img">
    </div>

</div>