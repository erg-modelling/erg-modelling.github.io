---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: page-fullwidth
header:
  image_fullwidth: FromHPRU_12_Crop.jpg
subheadline: ""
title: "ERG Modelling"
teaser: "CMAQ-Urban Model Outputs"

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

<p>
Welcome to the github page of the ERG Modelling Group at Imperial College London.
</p>

<p>
Our CMAQ-Urban model allows us to predict air pollutant concentrations at an hourly time resolution and 20m spatial resolution over the whole of Great Britain
</p>



<p>
Below is a sample of our 2019 concentration map for NO<sub>2</sub> over Birmingham, UK.  Use the dropdown menus above to look at some other cities and pollutants.  You can also <a href="https://erg-modelling.github.io/request-data/">request data</a> here.
</p>


<iframe src="https://erg-modelling.github.io/widgets/base58_NO2.html" height="600px" width="100%" style="border:none;"></iframe>
