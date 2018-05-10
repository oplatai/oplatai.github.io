---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Speech-to-Text"
  url: 'http://oplatai.github.io/apps/transcribe'
  image: widget-1-302x182.jpg
  text: 'Our speech-to-text technology adapts to your data and effectively simplifies the task to your domain so it beats any other general speech-to-text system. <em>OplataiASR</em> offers you a fully functional speech-to-text easily **deployed in your enviroment**. We offer adaptation to down-stream application like **key-word search in audio**, **Displaying recorded audio for dictations** or **Integration into dialogue/chat systems**'
widget2:
  title: "Speech id / diarization"
  url: 'http://oplatai.github.io/apps/speaker-diar/'
  text: '<em>Speaker diarization is in alpha</em> and will be available soon!'
widget3:
  title: "Get ready for our demos"
  url: 'http://oplatai.github.io/demos'
  image: widget-github-303x182.jpg
  text: 'All you need is a HTML5 browser and working microphone to try out our technology.'


permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
