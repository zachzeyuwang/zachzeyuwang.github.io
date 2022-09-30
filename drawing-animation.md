---
title: drawing-animation
layout: page_no_title
---
## Learning a Style Space for Interactive Line Drawing Synthesis from Animated 3D Models
{: style="text-align: center"}

Zeyu Wang<sup>1</sup>, <a href="https://tuanfeng.github.io/">Tuanfeng Y. Wang</a><sup>2</sup>, <a href="https://graphics.cs.yale.edu/people/julie-dorsey">Julie Dorsey</a><sup>1</sup>
{: style="text-align: center"}

Yale University<sup>1</sup>, Adobe Research<sup>2</sup>
{: style="text-align: center"}

Pacific Conference on Computer Graphics and Applications (PG), 2022
{: style="text-align: center"}

<b>Paper:</b>
<a href="https://graphics.cs.yale.edu/sites/default/files/linedrawinganimation_pg2022.pdf">[pdf]</a>
<a onclick="copyBibTeX()">[bibtex]</a>

<b>Abstract:</b>
Most non-photorealistic rendering (NPR) methods for line drawing synthesis operate on a static shape. They are not tailored to process animated 3D models due to extensive per-frame parameter tuning needed to achieve the intended look and natural transition. This paper introduces a framework for interactive line drawing synthesis from animated 3D models based on a learned style space for drawing representation and interpolation. We refer to style as the relationship between stroke placement in a line drawing and its corresponding geometric properties. Starting from a given sequence of an animated 3D character, a user creates drawings for a set of keyframes. Our system embeds the raster drawings into a latent style space after they are disentangled from the underlying geometry. By traversing the latent space, our system enables a smooth transition between the input keyframes. The user may also edit, add, or remove the keyframes interactively, similar to a typical keyframe-based workflow. We implement our system with deep neural networks trained on synthetic line drawings produced by a combination of NPR methods. Our drawing-specific supervision and optimization-based embedding mechanism allow generalization from NPR line drawings to user-created drawings during run time. Experiments show that our approach generates high-quality line drawing animations while allowing interactive control of the drawing style across frames.
{: style="text-align: justify"}

<b>Talk:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/RDUGHpjQ9pc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<b>Video:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/7kaMZm0YmAo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div id="toast">BibTeX copied to clipboard</div>
{% raw %}
<script type="text/javascript">
function copyBibTeX() {
	var tempInput = document.createElement("textarea");
	tempInput.style = "position: absolute; left: -1000px; top: -1000px";
	tempInput.value = "@inproceedings{Wang:2022:DrawAnim,\nbooktitle = {Pacific Graphics Short Papers, Posters, and Work-in-Progress Papers},\neditor = {Umetani, Nobuyuki and Vouga, Etienne and Wojtan, Chris},\ntitle = {{Learning a Style Space for Interactive Line Drawing Synthesis from Animated 3D Models}},\nauthor = {Wang, Zeyu and Wang, Tuanfeng Y., and Dorsey, Julie},\nyear = {2022},\npublisher = {The Eurographics Association},\nISBN = {},\nDOI = {}\n}";
	document.body.appendChild(tempInput);
	tempInput.select();
	document.execCommand("copy");
	document.body.removeChild(tempInput);
	var x = document.getElementById("toast");
	x.className = "show";
	setTimeout(function(){ x.className = x.className.replace("show", ""); }, 3000);
}
</script>
{% endraw %}
