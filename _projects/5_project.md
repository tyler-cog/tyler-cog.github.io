---
layout: page
title: Colorization
description: Practice with optimization, turning grayscale images to color via scribbles. 
img: assets/img/colorCorb2.JPG
importance: 3
category: fun
---
<div class="caption" style="text-align: left;">
    This was a side project to understand optimization techniques better, inspiration taken from <a href='https://www.cs.huji.ac.il/w~yweiss/Colorization/'> here.</a> The idea is to use optimization techniques to colorize grayscale images via the use of scribbling the color you would like to colorize the image with on the grayscale image. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/colorCorb1.JPG" title="colorCorbGray" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/colorCorb2.JPG" title="colorCorbScribble" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/colorCorb3.JPG" title="colorCorbFinal" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption" style="text-align: left;">
    Here is an output example using my own images where you can see it works out really well. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/colorYa1.JPG" title="colorYaGray" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/colorYa2.JPG" title="colorYaScribble" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/colorYa3.JPG" title="colorYaFinal" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption" style="text-align: left;">
    Here is another output, though it is interesting to note that while this one does come out alright, it does seem to have had some issues along the way resulting in an output that isn't as clean as the previous example.
</div>

<div class="caption">
        If you would like to learn more, check out the <a href='https://github.com/tyler-cog/Colorization'> GitHub. </a> 
</div>