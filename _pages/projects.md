---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

  <div class="containerh-100 d-flex justify-content-center">
    <div class="row">
      <div class="col-lg-12 col-xl-11 col-sm-12 mx-auto">
        <div id="carouselData" class="carousel slide carousel-fade"
          data-ride="carousel" data-interval=8000>
          <div class="carousel-inner">
            {% for carousel in site.data.carousels %}
            {% if carousel.active %}
            <div class="carousel-item active align-items-center">
              {% else %}
              <div class="carousel-item align-items-center">
                {% endif %}
                {% if carousel.video %}
                <video id="videoBanner" width="100%" loading="lazy" class="d-block w-100 p-0 m-0" autoplay
                  loop muted>
                  <source src="{{ carousel.video }}" type="video/mp4" />
                </video>
                {% else %}
                <img class="d-block w-100 p-0 m-0" loading="lazy" src="{{ carousel.image }}"
                  alt="Slide">
                {% endif %}
                 {% if carousel.text %}
                 <div class="carousel-caption d-none d-md-block">
                 <p> {{ carousel.text }} </p>
                 </div>
                 {% endif %}
              </div>
              {% endfor %}
            </div>
            <a class="carousel-control-prev" href="#carouselData" role="button"
              data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselData" role="button"
              data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
        </div>
      </div>
    </div>

Research Projects

[**Foundations for Equitable Transit Networks**](https://arxiv.org/pdf/2212.12007.pdf)

[**COVIDKG**](http://covidkg.org/)

Github Projects

[**LDA with Word Embeddings**](https://github.com/sophiepavia/ML-Project)

[**C++ Password Server Simulation**](https://github.com/sophiepavia/passserver)

[**Pygame for Speed Tying**](https://github.com/sophiepavia/speedyfingers)

[**Swift Fitness App**](https://github.com/sophiepavia/fitnessapp)

[**Custom C Shell**](https://github.com/sophiepavia/project1)

[**Cruise Controller**](https://github.com/sophiepavia/cruise_control)

{% include base_path %}


{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}

