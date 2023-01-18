---
title: My First Post
layout: default
spoti: <iframe style="border-radius:12px"
    src="https://open.spotify.com/embed/track/2akUccC6qV8lj2UCu9oCKM?utm_source=generator" width="100%" height="380"
    frameBorder="0" allowfullscreen=""
    allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>
---

<div class="w3-row-padding">
    {% for item in site.data.sept22.post1 %}
    <div  class="w3-col w3-container m6 l6 w3-margin-top">
        {{item.spoti}}
    </div>
    {%endfor%}
</div>


Some sample content...
