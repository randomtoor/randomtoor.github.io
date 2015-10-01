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
  title: "Trio"
  url: 'en/trio/'
  image: trio.jpg
  text: 'The Bering Trio (based in the Netherlands) is composed of Canadian violinist Paul Medeiros, American violist/violinist Ian de Jong and Latvian cellist Aleksandra Kaspera. A strong comradery based on a shared love of chamber music brings these players together.'
widget2:
  title: "Media"
  url: 'en/media/'
  text: "Bering *rocks*! Don't believeme, check this out!"
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://localhost:4000/images/youtube.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Agenda"
  url: 'en/agenda/'
  image: agenda.jpg
  text: 'Here is where you can find us next'
permalink: en/index.html
lang: 'en'
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/XSlw4UduG84" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
