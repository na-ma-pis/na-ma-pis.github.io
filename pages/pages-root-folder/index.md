---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: leonardo_blue.png
  caption: skica Leonarda da Vincija
widget1:
  title: "Matematična pismenost"
  url: '/matematika/'
  image: 'torta.jpg'
  text: 'Recept za torto: 5 jajc, 150g moke, 120g sladkorja. 
  	Joj, imam le 3 jajca, koliko moke in sladkorja naj dam? 
  	Bom vprašala na forumu! Ali pa izračunam sama, saj smo delali nekaj 
	podobnega v šoli.'
widget2:
  title: "Naravoslovna pismenost"
  url: '/naravoslovje/'
  image: 'luna.jpg'
  text: 'Luna vpliva na potrese? Kakšne vse neumnosti se ljudje spomnijo. 
  	Hmm... zakaj pa je za veliko noč več potresov kot sicer? Kako pa bi Luna lahko vplivala na potres? '
widget3:
  title: "Za učitelje"
  url: '/ucitelji/'
  image: 'neonbrand-426918-unsplash.jpg' 
  text: 'Poglejte si bogato zbirko dejavnosti. Preberite si več o 
  	matematični in naravoslovni pismenosti.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /sodeluj/
  text: Sodeluj z nami pri opismenjevanju ›
  style: alert
permalink: /index.html
---

{%include alert alert="To spletišče je še v izdelavi in je vsebina še nepopolna in se bo še spreminjala. Zato prosimo za potrpljenje." %}
