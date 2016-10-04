---
layout: page
title: The Hubbard Group
tagline: biostatistics...
description: The research webpages of Alan E. Hubbard's research group
keywords: biostatistics, applied statistics, causal inference
---

The Hubbard Group is led by [Prof. Alan E. Hubbard](https://ahubb40.github.io).

The research group is a part of the [Division of
Biostatistics](https://www.stat.berkeley.edu/biostat/), in the [School of
Public Health](http://sph.berkeley.edu), at the University of California,
Berkeley.

Research interests include elements of causal inference, statistical machine
learning, targeted minimum loss-based estimation (TMLE), data-adaptive
estimation for inference under model misspecification, nonparametrics.

---

<head>

<!--Little CSS fade in -->
<style>
.fade-in{
  -webkit-animation: fade-in 2s ease;
  -moz-animation: fade-in ease-in-out 2s both;
  -ms-animation: fade-in ease-in-out 2s both;
  -o-animation: fade-in ease-in-out 2s both;
  animation: fade-in 2s ease;
  visibility: visible;
  -webkit-backface-visibility: hidden;
}

@-webkit-keyframes fade-in{0%{opacity:0;} 100%{opacity:1;}}
@-moz-keyframes fade-in{0%{opacity:0} 100%{opacity:1}}
@-o-keyframes fade-in{0%{opacity:0} 100%{opacity:1}}
@keyframes fade-in{0%{opacity:0} 100%{opacity:1}}

</style>
</head>
<body>

<!--We appendin' on this div - ps: ids make sense here... punk-->
<div id="banner-load"></div>

<!--Don't forget Jquery-->
<script type='text/javascript' 
src='http://ajax.googleapis.com/ajax/libs/jquery/1.8/jquery.min.js'></script>

<!--New images on load -->
<script>
//Add your images, we'll set the path in the next step
    var images = ['morpheus404.jpg', 'vader404.jpg'];
    
//Build the img, then do a bit of maths to randomize load and append to a div. 
//Add a touch off css to fade them badboys in all sexy like.
    $('<img class="fade-in" src="{{ BASE_PATH }}/assets/pubsfigs/' + 
    images[Math.floor(Math.random() * images.length)] + 
    '">').appendTo('#banner-load');
</script>

</body>
