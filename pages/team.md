---
layout: page-fullwidth
title: "Leadership Team"
permalink: "/team/"
---
Graduate student volunteers form the foundation of STATCOM, dedicating their time and expertise to consulting projects that serve community partners. The Leadership Team both organizes projects and actively contributes to their design, analysis, and delivery. Faculty serve as advisors, contributing leadership, guidance, and support throughout our projects.
### Presidents
<div class="row">
{% for member in site.data.team.presidents %}
  <div class="small-12 medium-6 large-6 columns text-center">
    <img src="{{ member.image | default: '/assets/img/team/placeholder.jpg' }}" alt="{{ member.name }}" style="max-width:130px; border-radius:50%;">
    <h5 style="margin-bottom:0.25rem">{{ member.name }}</h5>
    <p style="margin-top:0.25rem">{{ member.degree }}</p>
  </div>
{% endfor %}
</div>

### Project Chairs
<div class="row">
{% for member in site.data.team.project_chairs %}
  <div class="small-12 medium-4 large-4 columns text-center">
    <img src="{{ member.image | default: '/assets/img/team/placeholder.jpg' }}" alt="{{ member.name }}" style="max-width:130px; border-radius:50%;">
    <h5 style="margin-bottom:0.25rem">{{ member.name }}</h5>
    <p style="margin-top:0.25rem">{{ member.degree }}</p>
  </div>
{% endfor %}
</div>

### Internal Communications Chairs
<div class="row">
{% for member in site.data.team.internal_comms %}
  <div class="small-12 medium-6 large-6 columns text-center">
    <img src="{{ member.image | default: '/assets/img/team/placeholder.jpg' }}" alt="{{ member.name }}" style="max-width:130px; border-radius:50%;">
    <h5 style="margin-bottom:0.25rem">{{ member.name }}</h5>
    <p style="margin-top:0.25rem">{{ member.degree }}</p>
  </div>
{% endfor %}
</div>

### External/Events Chairs
<div class="row">
{% for member in site.data.team.external_comms %}
  <div class="small-12 medium-6 large-6 columns text-center">
    <img src="{{ member.image | default: '/assets/img/team/placeholder.jpg' }}" alt="{{ member.name }}" style="max-width:130px; border-radius:50%;">
    <h5 style="margin-bottom:0.25rem">{{ member.name }}</h5>
    <p style="margin-top:0.25rem">{{ member.degree }}</p>
  </div>
{% endfor %}
</div>

### Faculty Advisors
<div class="row">
{% for member in site.data.team.faculty_advisors %}
  <div class="small-12 medium-6 large-6 columns text-center">
    <img src="{{ member.image | default: '/assets/img/team/placeholder.jpg' }}" alt="{{ member.name }}" style="max-width:130px; border-radius:50%;">
    <h5 style="margin-bottom:0.25rem">{{ member.name }}</h5>
    <p style="margin-top:0.25rem">{{ member.degree }}</p>
  </div>
{% endfor %}
</div>
