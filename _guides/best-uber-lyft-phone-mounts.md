---
title: "Guide: The Best Uber and Lyft Phone Mounts"
shortTitle: "Phone Mounts"
date: 2017-07-23
order: 1
excerpt: Check out how to you can use magnetic mounts to securly hold your phone for maximum convenience and style.
sitemap:
  lastmod: 2017-09-17
---

Magnetic mounts allow you to secure your phone in-car with absolute ease and style. Other mounts use weak plastic mechanisms that attempt to change shape for any sized device. Magnet mounts allow you to snap your phone in portrait, landscape, or any angle in between. These make getting your phone in and out of your car super easy.
{: .lead}

<div class="row">
<div class="col-md-6" markdown="1">
#### Why Magnets?

Utilizing magnetic mounts makes it easy for you and others to go from vehicle to vehicle and always have an easy place to mount your phone. Once you try this you will never go back to anything else!

#### Warranty + Return Policy

SCOSCHE has been in the car business since 1980 and has a reputation for building quality accessories. Between their 1-year warranty and Amazon's fantastic return policy, you can't go wrong trying a few of these acessories to see what works best for you.
</div>
<div class="col-md-6">
<div class="embed-responsive embed-responsive-16by9">
<iframe class="embed-responsive-item" src="https://www.youtube.com/embed/oaAfdePAWPI?list=PLQnkqD2D8Vga5s6m2APA7sNF1wCW4Ypr6?rel=0;showinfo=0" allowfullscreen></iframe>
</div>
</div>
</div>

<div class="row">
{% assign mounts = site.data.phonemounts.items | sort: 'order' %}
{% for mount in mounts %}
<div class="col-md-9" markdown="1">
### [{{ mount.name }}]({{ mount.purchaseUrl }})
{{ mount.description }}
</div>
<div class="col-md-3">
<a href="{{ mount.purchaseUrl }}">
<img height="200" src="/images/guides/phone-mounts/{{ mount.image }}" class="float-right" alt="{{ mount.name }}" />
</a>
</div>
{% endfor %}
</div>