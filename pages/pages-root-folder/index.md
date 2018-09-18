---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: https://raw.githubusercontent.com/Outdoor-Automation/outdoor-automation-github.io/master/images/outdoor_automation_logo.jpg

widget1:
  title: "Ground"
  url: 'http://127.0.0.1:4000/feeling-responsive/images/open_rover.jpg'
  image: https://raw.githubusercontent.com/Outdoor-Automation/outdoor-automation-github.io/master/images/open_rover.jpg
  text: 'Tele-operated, semi-autonomous, and fully-autonomous solutions for applications ranging from inspection, pest-deterance, asset moving and more...'

widget2:
  title: "Underwater"
  url: 'https://github.com/Phlow/feeling-responsive'
  text: 'Being one of the '
  image: 'https://raw.githubusercontent.com/Outdoor-Automation/outdoor-automation-github.io/master/images/blue_rov_2.jpg'
  text: 'Tele-operated underwater search, underwater mapping, water sampling, boat inspection and more...'

widget3:
  title: "Air"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: https://raw.githubusercontent.com/Outdoor-Automation/outdoor-automation-github.io/master/images/dji_matrice.jpg
  text: 'Teleoperated, semi-autonomous, and fully autonomous mapping, power line inspection, pipe inspection, cell tower inspection and more...'
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
