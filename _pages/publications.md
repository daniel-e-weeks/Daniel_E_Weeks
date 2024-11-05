---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Publications



<p>

        <a href="http://pubmed.ncbi.nlm.nih.gov/?term=%28%28Weeks+DE%5BAuthor%5D%29+NOT+%28Weeks+David+E%5BAuthor%5D%29%29+NOT+%2831878736%29&amp;sort=date" target="_blank">Search PubMed</a><br />
        <a href="http://europepmc.org/authors/0000-0001-9410-7228" target="_blank">Europe PMC profile</a><br /><a href="http://scholar.google.com/citations?sortby=pubdate&amp;hl=en&amp;user=oA712DgAAAAJ" target="_blank">Google Scholar profile</a><br />
        <a href="http://www.ncbi.nlm.nih.gov/sites/myncbi/daniel.weeks.2/bibliography/47194278/public/?sort=date&amp;direction=descending" target="_blank">My Bibliography</a><br />
        <a href="http://orcid.org/0000-0001-9410-7228" target="_blank">ORCiD</a><br />
{% for member in site.data.pi %}
{% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> <br /> {% endif %}
{% endfor %}        
</p>
</div>


<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>

<div class="jumbotron">
### Recent refereed journal articles
{% bibliography --query @article %}
</div>

