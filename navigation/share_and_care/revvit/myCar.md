---
layout: page
title: REVVIT (My Car)
description: Your Car
permalink: /share_and_care/revvit/mycar
---

{%- include nav/revvit.html -%}

<html>
  <div class="card">
    <h4><b>JOHN DOE</b></h4>
    <img src="{{site.baseurl}}/images/nitd_rpg/mort.png" alt="Avatar" class="pfp">
    <div class="container">
      <h5>MY RIDE</h5>
      <p>I will write more about my sick ride here! I will provide the MAKE, MODEL, and YEAR of my vehicle along with any other relavant information I would like to include!</p>
      <img src="https://www.driving.co.uk/wp-content/uploads/sites/5/2010/08/Jeremy-Clarkson-reviews-the-Pagani-Zonda-R-1440.jpg" alt="Car" class="carpic">
    </div>
  </div>
</html>

<style>
.card {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  background: #121212;
  background: linear-gradient(0deg, rgba(23,23,23,1) 0%, #121212 100%);
  transition: 0.3s;
  text-align: center;
}

.pfp {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 25%;
}

.carpic {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;
}

/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

/* Add some padding inside the card container */
.container {
  padding: 2px 16px;
}
</style>
