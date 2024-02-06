---
layout: page
title: OASIS Corpus
description: A Multi-Dimensional Contrastive Study of Open Accessible Summaries and Their Corresponding Abstracts
img: assets/img/kenkyu.jpg
importance: 1
category: academic
related_publications: false
---

Have you ever tried to read a scientific study and found yourself lost in complicated terms and dense sentences? You're not alone. Recognizing this, some organizations are asking researchers to write simpler summaries of their work, so everyone can get the gist. I decided to look into how these summaries for non-experts compare to the traditional, more complex abstracts scientists write for each other.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/oasis1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Summaries for non-experts versus abstracts for experts
</div>

From a database called Open Accessible Summaries in Language Studies (OASIS), I built up a collection of 629 summaries for non-experts and found their corresponding 629 abstracts. My goal was to see which ones were easier to read and how they differed in style and substance. To do this, I used a tool that measures how easy texts are to read, called the Flesch reading ease score, and analyzed their language in depth with a method known as Biber’s multi-dimensional analysis framework.

The findings? Summaries for non-experts are indeed easier to read. They're more engaging, straightforward, and rely more on the context than diving deep into hard facts or detailed explanations. They also tend to be more personal and less formal than their abstract counterparts.

Interestingly, my study showed that these summaries for non-experts and the abstracts serve as unique types of writing. Each has its own style and purpose. This insight is super helpful for anyone looking to make science more accessible. It shows us how we can better share complex ideas with everyone, making the world of science a bit less intimidating and a lot more inclusive.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>





You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
