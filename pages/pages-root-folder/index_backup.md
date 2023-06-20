---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: page-fullwidth
header:
  image_fullwidth: AQL_AirPollutionClimateChange_Desk.jpg
subheadline: "Gregor's test subheadline"
title: "Gregor's test headline"
teaser: "Hello Anastasia, look what strong men does with new website maker tool from work from home while his woman cooking the chicken"

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

Inserting some random text here to see if it works
Edit the html code below to first test some images, then try to get a widget in
Extra message just to test a new commit...

<div class="row">
    <div class="medium-4 columns t30">
    <img src="{{ site.urlimg }}gallery-example-4.jpg" alt="">
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns t30">
      <img src="{{ site.urlimg }}gallery-example-5.jpg" alt="">
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns t30">
      <img src="{{ site.urlimg }}gallery-example-6.jpg" alt="">
    </div><!-- /.medium-4.columns -->

</div><!-- /.row -->


<div class="row">
    <div class="medium-8 columns t30">
    <iframe src="https://erg-modelling.github.io/widgets/base58_NO2.html" height="600px" width="100%" style="border:none;"></iframe>
    </div><!-- /.medium-8.columns -->

    <div class="medium-4 columns t30">
      <img src="{{ site.urlimg }}gallery-example-3.jpg" alt="">
      <img class="t30" src="{{ site.urlimg }}gallery-example-8.jpg" alt="">
    </div><!-- /.medium-4.columns -->

</div><!-- /.row -->



 [1]: http://foundation.zurb.com/docs/components/grid.html

