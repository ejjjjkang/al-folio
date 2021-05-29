---
layout: page
title: When emotions become form vol.2
description: An interactive machine learning application which reflecting users' emotions
img: assets/img/when_emotions_become_form_vol2.gif
importance: 1
category: previous
tag: machine learning
selected: true
---

This is an extended work from our previous work 'When emotions become form'.

This is the project results from which I participated in 'AI College' in Korea. As a researcher, I was involved in the project, and worked with developers and researcher. Through the reseaching many applied Machin Learning infused creativity process, I became to wonder how that ML facilitate humans' activities.

We introduced our project in Nurips2019 Creativity Workshop and Artcenter Nabi exhibition.

<strong>"When Emotions Become Form"</strong> is an hommage to Harald Szeemann's exhibition "When Attitudes Become Form (1969)". At that time, Szeemann pointed out the importance of the attitude of thinking and conceptualizing the meaning of art rather than of the work itself. It accentuated the role of curators as much of that of the artists as creators or exhibition makers in modern art. From this perspective, we attempted to set Machine as the creator. We also share the same notion by expanding such role to machines, proving that “(human) emotions” can be expressed in “AI-form”.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/1.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/3.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

We used generative adversarial networks (GANs) to learn human emotions. Using simple shapes and colors as basic elements of visul arts, our work seeks to obtain simple form of abstraction. We first consider the norms for positive and negative emotion-laden words and their color associations. And we used lines or circles on a virtual canvas and achieved different results for marks on a page under various conditions of emotions. Then the AI analyses various images labeled with human emotions and generates obscure shapes and colors in layers through installation to present the ability of machine learning in interpreting abstract images such like such as the Korean abstract painting Dansaekhwa.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>
<!-- 
The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/" target="_blank">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above: -->

<!--
```html
<div class="row justify-content-sm-center">
	<div class="col-sm-8 mt-3 mt-md-0">
		<img
			class="img-fluid rounded z-depth-1"
			src="{{ '/assets/img/6.jpg' | relative_url }}"
			alt=""
			title="example image"
		/>
	</div>
	<div class="col-sm-4 mt-3 mt-md-0">
		<img
			class="img-fluid rounded z-depth-1"
			src="{{ '/assets/img/11.jpg' | relative_url }}"
			alt=""
			title="example image"
		/>
	</div>
</div>
``` -->
