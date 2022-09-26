---
layout: page
---


{%- assign foo = page.path | split: "." -%}
{%- assign bar = foo[0]| split: "_" -%}
{%- assign bar2 = "puja" | append: bar[0] | append: "/" | append: bar[1] -%}

{% include menu.html %}

<div class="sticky">{{ bar2 }}</div><br/>


{% for image in site.static_files %}
	{% if image.path contains  bar2  %}
<img style="margin-left:1px;" src="{{ site.baseurl }}{{ image.path }}" alt="image"/><br/><br/>
	{% endif %}
{% endfor %}

<script>
	document.getElementById("dropbtn{{ bar[0] }}").style.backgroundColor = "orange";
</script>	