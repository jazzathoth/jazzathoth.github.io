---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_jb.jpg
widget1:
  title: "Data Science"
  url: 'http://jazzathoth.github.io/ds/'
  image: widget-1-302x182.jpg
  text: "Code, project artifacts, reports, and analysis"
widget2:
  title: "Joe Bender"
  url: 'http://jazzathoth.github.io/info/'
  text: '<em>About Me</em>'
  image: widget-1-302x182.jpg
widget3:
  title: "Writing"
  url: 'https://jazzathoth.github.io/blog/'
  image: widget-1-302x182.jpg
  text: 'Articles and Blog posts.'
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
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
