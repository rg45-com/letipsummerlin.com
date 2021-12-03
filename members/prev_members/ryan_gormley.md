---
layout: default
title: Ryan Gormley - Internet Consultant / Developer | LeTip Summerlin
page_name: members
member: ryan_gormley
---
{% include mem_bio_data.html %}
<div class="container margin-b-30">
  <div class="wide_banner">
    <h1>{{ mem_cat }} - {{ fullname }}</h1>
  </div>

    <div class="col-sm-8 padding-15">
      <p class="subtitle">{{ mem_data.company }}</p>
      <p class="phone"><i class="fa fa-phone-square"></i> {{ mem_data.phone }}</p>
      <p class="email"><i class="fa fa-envelope"></i> {{ mem_data.email }}</p>
      {% if mem_data.website %}<p class="web"><i class="fa fa-desktop"></i> <a href="https://www.{{ mem_data.website }}" target="_blank">{{ mem_data.website }}</a></p>{% endif %}
      <p>I've been on the internet since before the turn of the century (1994 to be exact).  Since 1999, I've worked with a variety of companies, from local mom-and-pop operations all the way up to multi-million dollar corporations, on a range of internet-related topics, including: website development, search engine optimization, data analytics, custom programming, hardware administration, website hosting, asset and data management.</p>
      <p>If you don't have a website, you need one.  If you do have a website, it could probably use a tune-up to keep pace with the constantly changing user environment.</p>
      <p>I'm also handy with computer repair, virus protection or recovery, data backup, and general tech-support issues.  I can help you configure your wireless routers and printers/scanners.</p>
      <p>If you need help with anything related to computers or the Internet, I can help!</p>
    </div>
    <div class="col-sm-4 padding-15">
      <img src="/assets/img/members/{{ page.member }}.jpg" class="img-responsive profile_img">
    </div>

</div>
  
{%- comment %}

{%- assign sorted_categories = site.data.members | sort: 'cat'  -%}
<ul>
{%- for entry in sorted_categories %}
{%- capture thecycle %}{% cycle 'odd', 'even' %}{% endcapture -%}
  {% for datum in entry.data %}
    <li {%- if thecycle == 'odd' %} class="{{ thecycle }}"{%- endif -%}> <a href="/members/{{ datum.bio_page }}">{{ entry.cat }} - {{ datum.f_name }} {{ datum.l_name }}</a></li>
  {% endfor %}
{% endfor %}
</ul>


  <!-- Debugging -->
  <pre><code>{{ sorted_categories | inspect }}</code></pre>
  
  <!-- example yml nested data -->
    - title: "Projects"
      subcategories:
        - title: "project-sub1"
          items:
            - title: "project-sub1-item1"
              href: "#"
            - title: "project-sub1-item2"
              href: "#"
        - title: "project-sub2"
          items:
            - title: "project-sub2-item1"
              href: "#"
            - title: "project-sub2-item2"
              href: "#"
  
    - title: "Support"
      subcategories:
       - title: "support-sub1"
         items:
          - title: "support-sub1-item1"
            href: "#"
          - title: "support-sub1-item2"
            href: "#"
   <!-- END example yml nested data -->
        
  <!-- example iteration over nested data -->
  <div class="container">
    <div class="row">
      {% for entry in site.data.entries %}
        <h2>{{ entry.title }}</h2>
        {% for subcategory in entry.subcategories %}
          <h3>{{ subcategory.title }}</h3>
          <ul>
          {% for item in subcategory.items %}
            <li><a href="{{ item.href }}">{{ item.title }}</a></li>
          {% endfor %}
          </ul>
        {% endfor %}
      {% endfor %}
    </div>
  </div>
{% endcomment -%}