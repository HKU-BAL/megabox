---
layout: default
---

MEGABOX is a web platform for hosting up-to-date [MEGAHIT][MEGAHIT] assemblies of publicly available but challenging metagenome sequence data. If you have any questions or think there are any other public datasets that worth assembling, please file us an [issue][issue].

### Highlights
* [Assemblies of Great Prairie Soil Metagenome Grand Challenge Datasets][GrePraGChallenge]

### Recent Updates [![](images/feed-icon-14x14.png)](feed.xml)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

[MEGAHIT]: https://github.com/voutcn/megahit
[GrePraGChallenge]: {{ site.baseurl }}{% post_url 2015-07-30-GrePraGChallenge %}
[issue]: https://github.com/HKU-BAL/megabox/issues