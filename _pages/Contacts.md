---
layout: page
title: Contact
nav-menu: true
---

{% include head.html %}

<!-- Contact -->
<section id="contact">
  <div class="inner">
    <section>
    The best way of contacting me is by sending me a Telegram message or via sending me an direct email.<br/><br/>
    </section>
    <section class="split">
      <section>
        <div class="contact-method">
          <span class="icon alt fa-envelope"></span>
          <h3>Email</h3>
          <a href="mailto:{{ site.email }}">{{ site.email }}</a>
        </div>
      </section>
      <section>
        <div class="contact-method">
          <span class="icon alt fa-telegram"></span>
          <h3>Telegram</h3>
          <a href ="{{site.telegram_url}}">@prateekpunetha</a>
        </div>
      </section>
      <section>
        <div class="contact-method">
          <span class="icon alt fa-home"></span>
          <h3>Address</h3>
          <span>
            {% if site.street_address %}
            {{ site.street_address }}<br />
            {% endif %} {% if site.city %}
            {{ site.city }}, {% endif %} {% if site.state %}
            {{ site.state }}
            {% endif %} {% if site.zip_code %}
            {{ site.zip_code }}<br />
            {% endif %} {% if site.country %}
            {{ site.country }}
            {% endif %}
          </span>
        </div>
      </section>
    </section>

  </div>
</section>
