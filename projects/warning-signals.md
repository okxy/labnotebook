---
title: Early warning for warning-signals of ecological regime shifts  
layout: project
tag: warning-signals 
github: earlywarning
abstract:

---

{% capture project_collaborators %}
- Alan Hastings 
- Noam Ross 

{% endcapture %}

{% capture project_funding %}
- Department of Energy Computational Sciences Graduate Fellowship 
- Center for Population Biology, UC Davis 

{% endcapture %}


{% capture project_issues %}
{% octokit_issues earlywarning%}
{% endcapture %}

{% capture project_commits %}
{% octokit_issues earlywarning%}
{% endcapture %}

{% capture project_feed %}
{% mendeley_feed 530001/early-warning-signs, 4 %}
{% endcapture %}

{% capture project_entries %}
{% for post in site.tags.warning-signals limit:8 %}
<p> <a href="{{ post.url }}">{{ post.title }}</a> 
<span style="font-style:italic"> {{ post.date | date_to_string }}</span></p>
{% endfor %}
{% endcapture %}

{% capture project_publications %}
<ul prefix="datacite: http://purl.org/spar/datacite/">
<li>Carl Boettiger, Alan Hastings (2013). <strong>Tipping points: From patterns to predictions</strong> <em>Nature</em> 493, 157–158. <a rel="datacite:doi" href="http://dx.doi.org/10.1038/493157a">doi</a>:10.1038/493157a</li>
<li>Carl Boettiger, Alan Hastings (2012). <strong>Early Warning Signals and the Prosecutor’s Fallacy</strong> 279 (1748) 4734-4739. <em>Proceedings of the Royal Society B</em> 279 (1748). <a rel="datacite:doi" href="http://dx.doi.org/10.1098/rspb.2012.2085">doi</a>:10.1098/rspb.2012.2085 (<a href="http://www.mendeley.com/download/public/98752/4972355691/dd5fdd8ebbfc05d9ebf415761be200805254d22e/dl.pdf">pdf</a>) (<a href="http://arxiv.org/abs/1210.1204">arXiv</a>) (<a href="https://github.com/cboettig/earlywarning/blob/prosecutor/inst/examples/fallacy.md">code</a>) (<a href="http://dx.doi.org/10.5061/dryad.2k462">data</a>)</li>
<li>Carl Boettiger and Alan Hastings (2012). <strong>Quantifying Limits to Detection of Early Warning for Critical Transitions</strong>, 2527-2539. <em>Journal of the Royal Society: Interface</em> 9 (75) <a rel="datacite:doi" href="http://dx.doi.org/10.1098/rsif.2012.0125">doi</a>:10.1098/rsif.2012.0125 (<a href="http://www.mendeley.com/download/public/98752/4711221423/df767d6b5f0fbf44cc236470307992b019e6c149/dl.pdf">pdf</a>) (<a href="http://arxiv.org/abs/1204.6231">arXiv</a>) (<a href="https://github.com/cboettig/earlywarning">code</a>)</li>
<li> Carl Boettiger*, Noam Ross*, Alan Hastings.  <strong>Early warning signals: The charted and uncharted territories</strong>. (Submitted) </li>
</ul>
{% endcapture %}

{% capture project_data %}

{% endcapture %}



{% include project_template.html %}


