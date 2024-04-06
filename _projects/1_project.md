---
layout: page
title: Vehicle Identification
description: To identify and analyze vehicles in parking lots.
img: assets/img/VI_EX.JPG
importance: 1
category: work
related_publications: false
---
<!-- 
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

   
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->
<div class="caption" style="text-align: left;">
    The purpose of Vehicle Identification, is to use a camera preferably
    stationed overlooking a parking lot, in order to record and analyze the Vehicle states, moving, stopped, and parking, with the goal to use the information for analytical purposes such as finding out why Vehicles are stopping in certain areas, locating traffic jams, and so on.
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/VI_EX.JPG" title="vehicleStates" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption" style="text-align: left;">
    Apologies for the poor quality, but the picture above is a frame taken from one of our cameras, after being analyzed in our backend.
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/VI_site.JPG" title="VI_Webpage" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption" style="text-align: left;">
    This photo is taken from our web app, and while not particularly pretty, the purpose is to take processed potions of the camera feed and return information pertaining to the changed states of the Vehicles from the feed. We have both an analytic and a security view 
    that both have different purposes.
</div>
<div class="caption" style="text-align: left;">
    The analytic side is able to choose from past feeds we have processed in order to better understand what is occuring, and the security side is more so a live feed that they are able to keep an eye on and if given more development time would return a notification if a crash or improper parking occured.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mongoDB.jpg" title="mongoDB" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption" style="text-align: left;">
    Behind the scenes the data is delivered to our MongoDB database where we have numerous different collections to collect the appropriate data. 
</div>
<div class="caption">
    If you would like to learn more, check out the <a href='https://github.com/tyler-cog/Vehicle_Identification'> GitHub. </a>
</div>
