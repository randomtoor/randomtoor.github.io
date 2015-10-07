---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: bering-header.jpg
widget1:
  title: "Bio"
  url: '/nl/bio/'
  image: trio.jpg
  text: 'Het in Nederland gevestigde Bering Trio bestaat uit Canadese violist Paul Medeiros, Amerikaanse altviolist/violist Ian de Jong en Letse celliste Aleksandra Kaspera. Een hechte (vriendschap?) gebaseerd op een gezamenlijke liefde voor kamermuziek brengt deze musici bij elkaar.'
widget2:
  title: "Media"
  url: '/nl/media/'
  text: "Zie onze afgelopen presentaties in de media sectie"
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://localhost:4000/images/youtube0.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Agenda"
  url: '/nl/agenda/'
  image: agenda.jpg
  text: 'Aankomende concerten'
permalink: /nl/index.html
lang: 'nl'
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/Jb8x-jXjuTg" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
