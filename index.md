---
layout: default
---

MEGABOX is a web platform for hosting up-to-date [MEGAHIT][MEGAHIT] assemblies of publicly available but challenging metagenome sequence data.

### Highlights
* [Assemblies of Great Prairie Soil Metagenome Grand Challenge Datasets][GrePraGChallenge]

### Recent Updates [![](images/feed-icon-14x14.png)](feed.xml)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

[MEGAHIT]: https://github.com/voutcn/megahit
[/megabox/GrePraGChallenge]: /megabox/GrePraGChallenge