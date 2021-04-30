---
title: DistanciAR
layout: page_no_title
---
## DistanciAR: Authoring Site-Specific Augmented Reality Experiences for Remote Environments
{: style="text-align: center"}

Zeyu Wang<sup>1</sup>, <a href="http://www.cuongnd.com/">Cuong Nguyen</a><sup>2</sup>, <a href="https://research.adobe.com/person/paul-asente/">Paul Asente</a><sup>2</sup>, <a href="https://graphics.cs.yale.edu/people/julie-dorsey">Julie Dorsey</a><sup>1</sup>
{: style="text-align: center"}

Yale University<sup>1</sup>, Adobe Research<sup>2</sup>
{: style="text-align: center"}

ACM CHI Conference on Human Factors in Computing Systems, 2021
{: style="text-align: center"}

<b>Paper:</b>
<a href="https://graphics.cs.yale.edu/sites/default/files/distanciar.pdf">[pdf]</a>
<a onclick="copyBibTeX()">[bibtex]</a>

<b>Abstract:</b>
Most augmented reality (AR) authoring tools only support the author's current environment, but designers often need to create site-specific experiences for a different environment. We propose DistanciAR, a novel tablet-based workflow for remote AR authoring. Our baseline solution involves three steps. A remote environment is captured by a camera with LiDAR; then, the author creates an AR experience from a different location using AR interactions; finally, a remote viewer consumes the AR content on site. A formative study revealed understanding and navigating the remote space as key challenges with this solution. We improved the authoring interface by adding two novel modes: Dollhouse, which renders a bird's-eye view, and Peek, which creates photorealistic composite images using captured images. A second study compared this improved system with the baseline, and participants reported that the new modes made it easier to understand and navigate the remote scene.
{: style="text-align: justify"}

<b>Video:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/Ez9edE_jFo8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<b>Talk:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/GkVFhL1sRbM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<b>Preview:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/9LiRpn7buRc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<b>User study:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/I09omV8wwnI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div id="toast">BibTeX copied to clipboard</div>
{% raw %}
<script type="text/javascript">
function copyBibTeX() {
	var tempInput = document.createElement("textarea");
	tempInput.style = "position: absolute; left: -1000px; top: -1000px";
  tempInput.value = "@inproceedings{Wang:2021:DistanciAR,\nauthor = {Wang, Zeyu and Nguyen, Cuong and Asente, Paul and Dorsey, Julie},\ntitle = {DistanciAR: Authoring Site-Specific Augmented Reality Experiences for Remote Environments},\nyear = {2021},\nisbn = {9781450380966},\npublisher = {Association for Computing Machinery},\naddress = {New York, NY, USA},\nurl = {https://doi.org/10.1145/3411764.3445552},\ndoi = {10.1145/3411764.3445552},\nbooktitle = {Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems},\npages = {1–12},\nnumpages = {12},\nkeywords = {augmented reality, remote authoring, spatial design, 3D scanning},\nlocation = {Yokohama, Japan},\nseries = {CHI '21}\n}";
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