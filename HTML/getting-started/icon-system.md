---
layout: default
title: Icon system
weight: "010.-0.060"
brand: [Brand]
parent: Getting Started
---

<div class="row">
	<div class="col-sm-10 col-sm-offset-1">
		<h2 class="body-font">What is different?</h2>
		<p class="lead">
			The new icon system in the GUI 2.* is now based on the equally all new <a href="http://www.grunticon.com/" target="_blank">Grunticon</a> from the
			genious <a href="https://www.filamentgroup.com/">filament group</a>. As opposed to the old icon-font system from GUI 1.* where each icon was a character
			in a font file we are now able to display semantic, accessible icons. A logo now is a logo and not a background image that wouldn't even print.
		</p>
	</div>

	<div class="col-sm-7 col-sm-offset-2">
		<h3 class="body-font">Icons embedding</h3>
		<p>
			There are two ways to use svg&rsquo;s: As a background image or direct embedding. Both methods are valid however it&rsquo;s important to understand the
			implications. For example using the background method is not semantic or accessible where as direct embedding is accessible as every svg comes with a
			title attribute that reflects it&rsquo;s name. Embedded icons can be manipulated with CSS or Javascript.
		</p>
	</div>

	<div class="col-sm-12 example">
		{% capture ID %}blender1{% endcapture %}
		{% capture category %}getting-started/icon-system{% endcapture %}
		{% capture thisVersion %}1{% endcapture %}
		{% assign count = 0 %}
		{% capture example %}
			<span class="icon icon-size-sm icon-face-happy" data-grunticon-embed></span>
			<hr>
			<span class="icon icon-size-md icon-face-happy" data-grunticon-embed></span>
			<hr>
			<span class="icon icon-size-lg icon-face-happy" data-grunticon-embed></span>
		{% endcapture %}
		{% capture HTML %}
	<span class="icon icon-size-sm icon-face-happy" data-grunticon-embed></span>
<span class="icon icon-size-md icon-face-happy" data-grunticon-embed></span>
<span class="icon icon-size-lg icon-face-happy" data-grunticon-embed></span>
		{% endcapture %}
		{% capture CSS %}{% endcapture %}
		{% capture LESS %}{% endcapture %}
		{% capture JS %}{% endcapture %}

		{% include exampleBox.liquid %}
	</div>

	<div class="col-sm-7 col-sm-offset-2">
		<h3 class="body-font">Icons as background image</h3>
		<p>
			Sometimes though you don&rsquo;t want a screenreader to read out your icon as it would just be confusing and not add any value. In those cases you still
			have the option to use the icon as a background image. This image won&rsquo;t easily print nor will it be read out now on assitive technologies.
		</p>
	</div>

	<div class="col-sm-12 example">
		{% capture ID %}blender1{% endcapture %}
		{% capture category %}getting-started/icon-system{% endcapture %}
		{% capture thisVersion %}1{% endcapture %}
		{% assign count = 1 %}
		{% capture example %}
			<span class="icon icon-size-sm icon-face-happy"></span>
			<hr>
			<span class="icon icon-size-md icon-face-happy"></span>
			<hr>
			<span class="icon icon-size-lg icon-face-happy"></span>
		{% endcapture %}
		{% capture HTML %}
	<span class="icon icon-size-sm icon-face-happy"></span>
<span class="icon icon-size-md icon-face-happy"></span>
<span class="icon icon-size-lg icon-face-happy"></span>
		{% endcapture %}
		{% capture CSS %}{% endcapture %}
		{% capture LESS %}{% endcapture %}
		{% capture JS %}{% endcapture %}

		{% include exampleBox.liquid %}
	</div>
</div>