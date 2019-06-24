---
layout: page
title: About
permalink: /about/
weight: 1
---

#### **About Me**

Hi I am **{{ site.author.name }}**,<br>

I am a <span id="age"></span> year-old student who is currently studying in Politecnico di Milano as a postgraduate student. I come from Hong Kong, a city of skyscrapers, and have always been attracted to architectural designs since I was young.

Architecture is so much more than just making buildings, instead it is a resolution to utilize the performance of buildings for different purposes. It can create or divide space. It can resolve livelihood problem. It can also handle emergency needs. It is fascinating to look into how architects by using their designs, interact with the vicinity of the buildings and with the citizens who work in or live in the buildings.

{% include figure.html image="/assets/images/graduation.jpg" caption="I graduated from City University of Hong Kong in 2015" %}


<div class="row">
{% include timeline.html %}
</div>

<script>
    var age = new Date().getFullYear() - 1991;
    if (new Date().getMonth() < 10){
        age--;
    }
    document.getElementById("age").innerHTML = age; 
</script>

