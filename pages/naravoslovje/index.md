---
layout: page-fullwidth
show_meta: false
header: no
title: "Naravoslovna pismenost"
subheadline: "Kako uporabiti znanje fizike, kemije in biologije"
category: naravoslovje
permalink: "/naravoslovje/"
dejavnosti:
- obdobje: Vrtec
  url: vrtec
  opis: "Naravoslovna pismenost od malih nog"
- obdobje: Prva triada
  url: prva-triada
  opis: "Berem, pišem, računam in rad opazujem naravo"
- obdobje: Druga triada
  url: druga-triada
  opis: "Kemija, fizika, biologija v mlem prstu."
- obdobje: Tretja triada
  url: tretja-triada
  opis: "Naravoslovje je način življenja."
- obdobje: Srednja šola
  url: srednja-sola
  opis: "Ne verjamem! Raje preverim sam.  Razmišljam s svojo glavo."
---

## Opredelitev naravoslovne pismenosti
Naravoslovna   pismenost   zajema   posameznikovo naravoslovno   znanje, 
naravoslovne spretnosti/veščine in odnos do naravoslovja. 
Temelji  na uporabi znanja,  spretnosti/veščin za:

  * **obravnavanje** naravoslovno-znanstvenih  vprašanj
  * **pridobivanje** novega  znanja
  * **razlaganje** naravoslovnih pojavov ter 
  * **izpeljavo** ugotovitev o naravoslovnih tematikah, ki temeljijo na podatkih in preverjenih dejstvih.

Naravoslovna pismenost vključuje tudi razumevanje značilnosti naravoslovnih znanosti
kot oblike človeškega znanja in raziskovanja, zavedanje o tem, kako naravoslovne znanosti in tehnologija oblikujejo naše snovno, intelektualno in kulturno okolje, ter 
pripravljenost  za  sodelovanje in 
zmožnost sporazumevanja o naravoslovno-znanstvenih vprašanjih kot razmišljujoč in odgovoren posameznik v odnosu do narave.

# Dejavnosti po obdobjih

<ul class="small-block-grid-1 medium-block-grid-2 large-block-grid-3">
{% for dejavnost in page.dejavnosti %}
<li>
   <div class="columns t30">
	<h4>{{ dejavnost.obdobje }} </h4>
	{{ dejavnost.opis }}
   <p><a class="button tiny radius" href="/naravoslovje/{{ dejavnost.url }}">{{ site.data.language.more }}</a></p>
   </div>
 </li>
{% endfor %}
</ul><!-- /.row -->

{% if site.categories.naravoslovje %}
## Prispevki o naravoslovni pismenosti
<ul>
    {% for post in site.categories.naravoslovje %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
{% endif %}
