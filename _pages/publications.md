---
layout: publications
title: ""
permalink: /publications/
author_profile: true
---

### <span style="color:rgb(0, 101, 189)"> Submitted manuscripts (under review)
<ul class="preprint_list">
{% assign number_printed = 0 %}
{% for publi in site.data.publication_list %}
{% if publi.type == "preprint" %}

<li ><p style="font-size:0.85em">
<b>{{ publi.title }}</b> ({{ publi.year }}), {{ publi.authors }}, {{ publi.link_main.display }}
<a href="javascript:toggleBibtex('{{ publi.label }}')" style="color:rgb(0, 51, 89, 1.0);">[BibTeX]</a>
<a href="{{ publi.link_pre.url }}" target="_blank" style="color:rgb(0, 51, 89, 1.0);">[Preprint]</a> 
</p>
<div id="bib_{{ publi.label }}" class="bibtex noshow">
<pre>
{{ publi.bibtex }}
</pre>
</div>
</li>

{% endif %}
{% endfor %}

</ul>

### <span style="color:rgb(0, 101, 189)"> Publications in peer-reviewed journals
<!-- Generated from JabRef by PubList by Truong Nghiem at 11:44 on 2015.09.10. -->
<ul class="biblist">

{% assign number_printed = 0 %}
{% for publi in site.data.publication_list %}
{% if publi.type == "journal" %}

<li ><p style="font-size:0.85em">
<b>{{ publi.title }}</b> ({{ publi.year }}), {{ publi.authors }}, {{ publi.link_main.display }}
<a href="{{ publi.link_main.url }}" target="_blank" style="color:rgb(0, 51, 89, 1.0);">[Link]</a>
<a href="javascript:toggleBibtex('{{ publi.label }}')" style="color:rgb(0, 51, 89, 1.0);">[BibTeX]</a>
<a href="{{ publi.link_pre.url }}" target="_blank" style="color:rgb(0, 51, 89, 1.0);">[Preprint]</a> 
</p>
<div id="bib_{{ publi.label }}" class="bibtex noshow">
<pre>
{{ publi.bibtex }}
</pre>
</div>
</li>

{% endif %}
{% endfor %}

</ul>

### <span style="color:rgb(0, 101, 189)"> Thesis
<ul class="biblist">

{% assign number_printed = 0 %}
{% for publi in site.data.publication_list %}
{% if publi.type == "thesis" %}

<li ><p style="font-size:0.85em">
<b>{{ publi.title }}</b> ({{ publi.year }}), {{ publi.authors }}, {{ publi.link_main.display }}
<a href="{{ publi.link_main.url }}" target="_blank" style="color:rgb(0, 51, 89, 1.0);">[Link]</a>
<a href="javascript:toggleBibtex('{{ publi.label }}')" style="color:rgb(0, 51, 89, 1.0);">[BibTeX]</a>
<a href="{{ publi.link_pre.url }}" target="_blank" style="color:rgb(0, 51, 89, 1.0);">[Preprint]</a> 
</p>
<div id="bib_{{ publi.label }}" class="bibtex noshow">
<pre>
{{ publi.bibtex }}
</pre>
</div>
</li>

{% endif %}
{% endfor %}

</ul>
