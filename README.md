# week11
Layout, design, and tools to help. Plus, how maps complicate things.  

But first, a reminder.  
# No class next week (11/24)! 

## Grid layouts
For a write your own tutorial, w3schools has a not terrible introduction (http://www.w3schools.com/css/css_rwd_grid.asp). Bootstrap from Twitter has a helpful introduction to grid systems in their [documentation](http://getbootstrap.com/css/#grid).  

## Working with layout in maps
Oftentimes, I have found the easist solution to incorporating a web map into a larger website is to use a layout/grid framework such as Bootstrap for all of the pages **except** for the map, which I shuffle into its own full screen subpage. There are alternative approaches. Some folks have developed templates using a framework such as Bootstrap specifically for making web maps.  

### Bootstrap  
#### With Esri JavaScript API
http://esri.github.io/bootstrap-map-js/demo/index.html  

#### With OpenLayers
http://themapguyde.blogspot.co.uk/2014/08/bootstrap-map-viewer-templates.html  

#### With Leaflet
https://github.com/bmcbride/bootleaf  
Older one https://github.com/tobinbradley/leaflet-bootstrap-mapping-template  

### Zurb Foundation
#### With Leaflet (and turf.js - bonus!)
http://bl.ocks.org/pdbartsch/raw/ac5fdd2f0c09e8ff3a4d/  

#### Others?

## Assignment
For our next meeting (which will be 12/1, the Tuesday following Thanksgiving), I would like each group to start and have made some progress on a website for your project. It can be very rough and lacking in content (I suggest [Hipster Ipsum](http://hipsum.co), which provides "Artisanal filler text for your site or project."), but I'd like to see something. And, you'll get a chance to see everything you've accomplished thus far!

### Logistics
If you aren't using one currently, you should create a github repository for your project and use that (and github.io) for all of your storing/serving needs. I can create repos in our umn-gis-5574 organizational space and then add project members to it, or if you'd prefer, one person from each group could just create the repo on their account and add everyone else as collaborators. Doesn't matter!

### Getting Started
Bootstrap may be your best bet, if only because documentation and map-centric examples abound. To that end I've included three starter templates in this repo. You can view them at the following:

- http://umn-gis-5574.github.io/week11/index.html
- http://umn-gis-5574.github.io/week11/grid.html
- http://umn-gis-5574.github.io/week11/dashboard.html

You can use a different theme for Bootstrap. Check out [Bootswatch](https://bootswatch.com), where all you need to do is download and point to the `bootstrap.css` for whatever them you want. I've included an example at the following address:  

- http://umn-gis-5574.github.io/week11/custom.html  

If you take one of these files and copy it to your project repository, you'll have a nice starting point. Take what you want, remove what you don't, add some content, and there you go!
