---
title: Third Post
layout: default
spoti: <iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/6Le1Cc6RGvSJjOcqNmrVL0?utm_source=generator" width="100%" height="380" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
plist: <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/1xyMASeB4opyAH2xI8aA5m?utm_source=generator" width="100%" height="380" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

---
<div class="w3-main w3-content w3-padding" style="max-width:1200px;margin-top:30px"> 

  <div class="w3-col w3-container m12 l12" style="margin-top:30px">
  {{page.plist}}
</div>


<div class="w3-row-padding">
    {% for item in site.data.sept22.post3 %}
    <div  class="w3-col w3-container m6 l6 w3-margin-top">
        {{item.spoti}}
    </div>
    {%endfor%}
</div>


</div>

