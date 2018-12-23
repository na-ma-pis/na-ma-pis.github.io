---
layout: page-fullwidth
show_meta: false
header: no
title: "Matematična pismenost"
subheadline: "Kako uporabiti znanje matematike izven šolskih klopi"
category: matematika
permalink: "/matematika/"
dejavnosti:
- obdobje: Vrtec
  url: vrtec
  opis: "Matematična pismenost od malih nog"
- obdobje: Prva triada
  url: prva-triada
  opis: "Berem, pišem, računam in rad rešujem uganke"
- obdobje: Druga triada
  url: druga-triada
  opis: "Geometrija in algebra v malem prstu."
- obdobje: Tretja triada
  url: tretja-triada
  opis: "Matematika ni le računanje, je način razmišljanja."
- obdobje: Srednja šola
  url: srednja-sola
  opis: "Obljube politikov, lahek zaslužek, ... Ne verjamem! Raje preverim sam.  Razmišljam s svojo glavo."
---

Matematična pismenost je zmožnost posameznika, da na osnovi matematičnega mišljenja in matematičnega znanja:

   * zmore uporabljati matematične pojme, postopke in orodja v različno strukturiranih okoljih
   * analizira, utemeljuje in učinkovito sporoča svoje zamisli in rezultate pri oblikovanju, reševanju in interpretaciji matematičnih problemov v različno strukturiranih okoljih
   * zaznava in se zaveda vloge matematike v vsakdanjem in poklicnem življenju, jo povezuje z  drugimi področji in sprejema odgovorne odločitve na osnovi matematičnega znanja ter je pripravljen sprejemati in soustvarjati zanj nova matematična spoznanja

# Dejavnosti po obdobjih

<ul class="small-block-grid-1 medium-block-grid-2 large-block-grid-3">
{% for dejavnost in page.dejavnosti %}
<li>
   <div class="columns t30">
	<h4>{{ dejavnost.obdobje }} </h4>
	{{ dejavnost.opis }}
   <p><a class="button tiny radius" href="/matematika/{{ dejavnost.url }}">{{ site.data.language.more }}</a></p>
   </div>
 </li>
{% endfor %}
</ul><!-- /.row -->

{% if site.categories.matematika %}
## Prispevki o matematični pismenosti
<ul>
    {% for post in site.categories.matematika %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
{% endif %}
