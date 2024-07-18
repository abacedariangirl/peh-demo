---
title: Location Tours
layout: about
permalink: /sights.html
# include CollectionBuilder info at bottom
credits: false
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
# can include photos that are in objects but not collection /objects/filename.jpg
# can paste iframe code right into the markdown
---
{% capture example1 %}
  <iframe width="800" height="600" frameborder="0" scrolling="no" allowfullscreen src="https://arcg.is/1i4aye3"></iframe>  
{% endcapture %}

{% capture example2 %}
  <iframe src="https://www.arcgis.com/apps/instant/exhibit/index.html?appid=750d012512904cea95484755b71a9287" width="800" height="600" frameborder="0" style="border:0" allowfullscreen>iFrames are not supported on this page.</iframe>
{% endcapture %}

{% capture example3 %}
  value
{% endcapture %}

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" heading="Location Tours" text=false%}

{% include feature/accordion.html title1="Example section" text1="{{example1}}" title2="Section two" text2="{{example2}}" title3="Section three" text3="{{example3}}" %}


