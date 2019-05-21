---
layout: default
title: Chapter Members - Las Vegas Business Networking Group | LeTip Summerlin
page_name: members
---

<div class="container margin-b-30">
  <div class="wide_banner">
    <h1>LeTip Summerlin Members</h1>
</div>
  <div class="row">
    <div class="col-md-12">
      <p>If you're looking for a service that one of our members provide, you're in the right place.  We currently have {{ site.data.members | size }} members in our chapter.  They are all experts in their respective fields and are professional and trustworthy in their business dealings.  We hold ourselves accountable to the rest of our group; there's no better recommendation to be found!  Feel free to contact one of us directly.</p>
      <table class="rwd-table">
        <tr>
          <th>Name</th>
          <th>Company</th>
          <th>Category</th>
          <th nowrap>Phone</th>
          <th>Email</th>
          <th>Website</th>
          <th>Position</th>
        </tr>
        {%- assign sorted_categories = site.data.members | sort: 'cat'  -%}
        {%- for entry in sorted_categories %}
          {% for datum in entry.data %}
          {%- capture url %}http://www.{{ datum.website }}{% endcapture -%}
          <tr>
            <td data-th="Name"><a href="/members/{%- if datum.bio_page %}{{ datum.bio_page }}{% endif %}">{{ datum.f_name }} {{datum.l_name}}</a></td>
            <td data-th="Company">{{ datum.company }}</td>
            <td data-th="Catetory">{{ entry.cat }}</td>
            <td data-th="Phone" nowrap>{{ datum.phone }}</td>
            <td data-th="Email">{{ datum.email }}</td>
            <td data-th="Website"><a href="{{ url }}" target="_blank">{{ datum.website }}</a></td>
            <td data-th="Position">{{ datum.position }}</td>
          </tr>
          {% endfor %}
        {% endfor %}
        
      </table>
    </div>
  </div>
</div>

{% include top_10.html %}
