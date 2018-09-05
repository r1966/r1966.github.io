---
layout: page
---
<style>
* {
    box-sizing: border-box;
}

.column {
    padding: 2px;
	float:left;
	
}


</style>


{%- assign foo = page.path | split: "." -%}
{%- assign bar = foo[0]| split: "_" -%}
{%- assign bar2 = "puja" | append: bar[0] | append: "/" | append: bar[1] -%}

{{ bar2 }}


{% for image in site.static_files %}
	{% if image.path contains  bar2  %}
<div class="column">	
<img style="margin-left:1px;" src="{{ site.baseurl }}{{ image.path }}" alt="image"/><br/><br/>
</div>
	{% endif %}
{% endfor %}	