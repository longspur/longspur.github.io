---
title: Home
layout: base.njk
---
### Homepage
<div class="text-secondary" style="font-size:0.9em;"><i class="fa-solid fa-clock"></i> Last updated: July 20th, 2026</div>

---


Hello! My name is Sydney Horan. I am a Ph.D. candidate at the **University of Connecticut** in the [Department of Ecology and Evolutionary Biology](https://eeb.uconn.edu/). I am a scientist, artist, and photographer, and I incorporate these passions together into science communication. My research broadly involves patterns in host-parasite interactions under conditions of environmental change. I balance learning about the parasites, their hosts, and the ecosystems they live in. I also have a passion for natural history collections, museums, and outreach.




---

<div class="row">

<div class="col">
<h5>News</h5>
 <ul>
{% for update in news["recent"]  %}
        <li style="margin-top:-10px;"><b>{{ update.date }}</b>: {{ update.desc }}</li>
{% endfor %}
</ul>

<a href="/news" style="text-decoration:none;">See previous updates... <i class="fa-solid fa-angles-right"></i></a>
</div>
<div class="col-md-4 mt-3">
<div class="card bg-body-tertiary p-3">
<h5>Links</h5>
<p>
<i class="fa-solid fa-envelope text-secondary"></i> <a href="mailto:sydney.horan@uconn.edu" style="text-decoration:none;">sydney.horan[@]uconn[.]edu</a><br><i class="fa-brands fa-orcid text-secondary"></i> <a href="https://orcid.org/0009-0006-5466-1367" style="text-decoration:none;">ORCID</a><br>
<i class="fa-brands fa-bluesky text-secondary"></i> <a href="https://bsky.app/profile/sydhoran.com" style="text-decoration:none;">sydhoran.com</a><br>
<i class="fa-brands fa-github text-secondary"></i> <a href="https://github.com/longspur" style="text-decoration:none;">longspur</a>
</p>
</div>
</div>

</div>
