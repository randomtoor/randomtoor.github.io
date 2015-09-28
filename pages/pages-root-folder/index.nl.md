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
  text: 'Dit is niet iets over Bering'
widget2:
  title: "Media"
  url: '/nl/media/'
  text: "Iets anders in Nederland"
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://localhost:4000/images/youtube.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Agenda"
  url: '/nl/agenda/'
  image: github-303x182.jpg
  text: 'Hier vint u iets anders'
permalink: /nl/index.html
lang: 'nl'
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/XSlw4UduG84" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
