---
title: tracing-vs-freehand
layout: page_no_title
---
## Tracing Versus Freehand for Evaluating Computer-Generated Drawings
{: style="text-align: center"}

Zeyu Wang<sup>1</sup>, Sherry Qiu<sup>1</sup>, Nicole Feng<sup>2</sup>, Holly Rushmeier<sup>1</sup>, Leonard McMillan<sup>3 4</sup>, Julie Dorsey<sup>1 4</sup>
{: style="text-align: center"}

Yale University<sup>1</sup>, Carnegie Mellon University<sup>2</sup>, University of North Carolina at Chapel Hill<sup>3</sup>, Mental Canvas, Inc.<sup>4</sup>
{: style="text-align: center"}

ACM Transactions on Graphics, 2021. Presented at SIGGRAPH and IEEE VIS.
{: style="text-align: center"}

<b>Links:</b>
<a href="https://graphics.cs.yale.edu/sites/default/files/tracing-vs-freehand_0.pdf">[pdf]</a>
<a href="https://github.com/zachzeyuwang/tracing-vs-freehand">[dataset]</a>
<a onclick="copyBibTeX()">[bibtex]</a>

<b>Abstract:</b>
Non-photorealistic rendering (NPR) and image processing algorithms are widely assumed as a proxy for drawing. However, this assumption is not well assessed due to the difficulty in collecting and registering freehand drawings. Alternatively, tracings are easier to collect and register, but there is no quantitative evaluation of tracing as a proxy for freehand drawing. In this paper, we compare tracing, freehand drawing, and computer-generated drawing approximation (CGDA) to understand their similarities and differences. We collected a dataset of 1,498 tracings and freehand drawings by 110 participants for 100 image prompts. Our drawings are registered to the prompts and include vector-based timestamped strokes collected via stylus input. Comparing tracing and freehand drawing, we found a high degree of similarity in stroke placement and types of strokes used over time. We show that tracing can serve as a viable proxy for freehand drawing because of similar correlations between spatio-temporal stroke features and labeled stroke types. Comparing hand-drawn content and current CGDA output, we found that 60% of drawn pixels corresponded to computer-generated pixels on average. The overlap tended to be commonly drawn content, but people’s artistic choices and temporal tendencies remained largely uncaptured. We present an initial analysis to inform new CGDA algorithms and drawing applications, and provide the dataset for use by the community.
{: style="text-align: justify"}

<b>Preview:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/OLoQ5EDljMY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<b>5-Min Talk:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/2Ij54kc9h_A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<b>12-Min Talk:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/qgvPGWT0UoA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<b>19-Min Talk:</b>
<iframe width="720" height="405" src="https://www.youtube.com/embed/xa9AVzNTKdk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div id="toast">BibTeX copied to clipboard</div>
{% raw %}
<script type="text/javascript">
function copyBibTeX() {
	var tempInput = document.createElement("textarea");
	tempInput.style = "position: absolute; left: -1000px; top: -1000px";
	tempInput.value = "@article{Wang:2021:Tracing,\nauthor = {Wang, Zeyu and Qiu, Sherry and Feng, Nicole and Rushmeier,  Holly and McMillan, Leonard and Dorsey, Julie},\ntitle = {Tracing Versus Freehand for Evaluating Computer-Generated Drawings},\nyear = {2021},\nissue_date = {August 2021},\npublisher = {Association for Computing Machinery},\naddress = {New York, NY, USA},\nvolume = {40},\nnumber = {4},\nissn = {0730-0301},\nurl = {https://doi.org/10.1145/3450626.3459819},\ndoi = {10.1145/3450626.3459819},\njournal = {ACM Trans. Graph.},\nmonth = aug,\nnumpages = {12},\nkeywords = {sketch dataset, drawing process, stroke analysis}\n}";
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
