---
layout: tools
name: Feed N Seed
title: Feed N Seed
description: Test description
keywords: >-
  weddings, receptions, corporate events, conferences, meetings, parties,
  banquets, catering, ballroom, outdoor events, indoor events, venue rental,
  event planning, audiovisual equipment, dance floor, stage, lighting,
  decorations, parking, Lafayette LA, cocktail hour, rehearsal dinners, bridal
  showers, baby showers, graduation parties, proms, galas, fundraisers, trade
  shows, expos, product launches, team building activities, holiday parties,
  birthday celebrations, anniversary parties, photo shoots, film screenings,
  live music events, food and beverage services, event coordination
image: /uploads/fns-fb-picture.jpg
logo: /assets/images/feednseed/feednseed.png
short_description: >-
  At Feed & Seed, we embrace the soul of Cajun country and celebrate the unique
  charm of Lafayette, Louisiana. Our historic venue, deeply rooted in the
  community, offers an intimate and versatile space where modern convenience
  meets the rich heritage of Acadiana. We are more than just a wedding venue; we
  are a gathering place for cherished memories and unforgettable moments.
address: 106 N Grant Street, Lafayette, LA 70501
phone: 337-330-4860
email: info@feedandseedlafayette.com
social_media:
  facebook: https://www.facebook.com/feednseedlafayette
  Instagram: https://www.instagram.com/feednseedbar/
map: >-
  https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3447.3060695303993!2d-92.01664668438083!3d30.228347216815315!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x86249c9bbcb04adb%3A0x1236f41a7ab85cc5!2sFeed%20%26%20Seed%20Lafayette!5e0!3m2!1sen!2sus!4v1679423962690!5m2!1sen!2sus
form_id: xjvdzjbr
---
<div class="container pt-10 pb-5">
  <div class="row justify-content-center"  data-aos="fade-up">
    <div class="col-md-8 text-center">
      <h1 class="h2 editable">Laissez les bons temps rouler!</h1>
      <p class="lh-lg editable">{{page.short_description}}</p>
    </div>
  </div>
</div>

<section class="py-5 py-xl-10">
  <div class="container">
    <div class="row justify-content-center mb-10">
      <div class="col-lg-8 text-center editable aos-init aos-animate"  data-aos="fade-up">
        <h2 class="fw-light">FEED your soul, SEED your community.<br /><span class="fw-bold">Feed N Seed Lafayette</span></h2>
      </div>
    </div>
    <div class="row g-3 g-xl-5 d-flex">
      <div class="col-lg-4 aos-init aos-animate editable"  data-aos="fade-up">
        <div class="card bg-opaque-primary h-100">
          <div class="card-footer">
            <h3 class="fs-5 text-black">Cajun Dance Hall</h3>
            <p class="text-secondary lh-base">Feed &amp; Seed offers a unique space that can be tailored to suit your event. From a cozy open indoor space to charming outdoor settings, we provide the perfect backdrop for gatherings of all sizes.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 aos-init aos-animate editable"  data-aos="fade-up">
        <div class="card bg-opaque-primary h-100">
          <div class="card-footer">
            <h3 class="fs-5 text-black">Modern Comfort</h3>
            <p class="text-secondary lh-base">We've thoughtfully updated our historic feed store to ensure modern amenities and convenience without compromising its rustic charm. From state-of-the-art sound systems to flexible lighting options, we have everything you need to make your event seamless and unforgettable.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 aos-init aos-animate editable"  data-aos="fade-up">
        <div class="card bg-opaque-primary h-100">
          <div class="card-footer">
            <h3 class="fs-5 text-black">Community Connection</h3>
            <p class="text-secondary lh-base">As a cherished staple in Lafayette, we take pride in our deep community involvement. By choosing Feed &amp; Seed, you're not only hosting your event in a unique location but also supporting the local spirit that makes Cajun country truly special.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="overflow-hidden py-10 py-xl-5">
  {% include gallery-code.html %}
  <div class="row justify-content-center px-2">
    {% assign counter = 0 %}
    {% for item in site.data.gallery %} 
    {% if item.location == page.name %}
    {% if item.image contains "https://" %}
      <div class="col-6 my-2">
      <div class="plyr__video-embed" data-video>
        <iframe
          src="https://www.youtube.com/embed/{{item.image | remove 'https://youtu.be/' | remove 'https://www.youtube.com/watch?v=' }}?origin=https://plyr.io&iv_load_policy=3&modestbranding=1&playsinline=1&showinfo=0&rel=0&enablejsapi=1"
          allowfullscreen allowtransparency allow="autoplay"></iframe>
      </div>  
     </div>
     {% endif %}
    {% endif %}
    {% endfor %}
  </div>
</section>

<div class="row px-8 py-15 py-xl-5 justify-content-center">
  <div class="col-md-12">
    <div class="col-lg-8 mx-auto text-center mb-8">
      <h2 class="fw-bold editable mb-1">Calendar of Events</h2>
      <p class="text-secondary editable">Stay in the know of all of our upcoming events</p>
    </div>
  </div>
</div>
<div class="mb-10">
<div id="calendar" data-aos="fade-up"></div>
</div>
<section class="py-15 py-xl-20 bg-black overflow-hidden">
  <div class="level-1">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8 text-white">
          <h2 class="fw-light mb-5"><span class="fw-bold editable">LET’S DANCE!</span></h2>
          <p class="lh-lg editable">We are ready to meet you and start planning your memorable event!</p>
          {% include form.html %}
        </div>
      </div>
    </div>
  </div>
  <figure class="background background-overlay editable" style="background-image: url('{{page.image}}')"
  data-bottom-top="transform: scale(1);" data-top-bottom="transform: scale(1.1);"></figure>
</section>