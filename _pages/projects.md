---
layout: default
title: <Eduardo Silva> - Portfolio
permalink: /projects/
---

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>
I'm currently going to work on my 3d model of making a nut cracker that doesn’t require human force in order to enjoy a hazelnut. A hazelnut has a force of 225kg which is approximately 496 lbs. 

My First option was to go with the Electric Dump Bed Assist Kit which allows a force of 899lbs but it was very expensive and we would need to add two to both sides of the nutcracker since we will need a force acting on both side of the macadamia nut. With each piece having a value of $499.99USD it would be a total of $999.98 USD 

My Second option was going with a very cheap option which was the Compact Micro Linear Actuator With PWN Compatibility. Which has a force of 56 lbs. which has a price of $79.99 USD. A cheaper option compared to the first product. However do the small amount of force it provides we would have to add multiple kits on each side. Approximately 5 on each on side which will lead to a total of 280 lbs on each side with a total of 560 lbs. The total price would be $799.90
Which is $200.08 cheaper then the first option. 

My third and final option was to use the Linear Motion Actuator which can go up to 600lbs. With a price of $137.99 a piece it would result a total of $275.98. This will be the most cheap and efficient way to build a machine that will crack open Macadamia Nuts without any using any human strength 

Just to see more of options I decide to mix two Linear Actuators. I decided to mix IP65 Mini Linear Actuator - Optional Feedback and IP65 Micro Linear Actuator. Using one of each on both sides with the IP65 Micro costing $67.99USD a piece and the IP65 Mini costing $114.99USD piece it would be a total $365.96USD Which even thought its cheaper the the first two options it not as cheap or efficient the third options. 

