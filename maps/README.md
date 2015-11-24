# The Apptronica Maps

Welcome fellow iOS music enthusiast! In this repository you'll currently find two interactive maps and their open data:
1. The [iOS Music World Map](iOS-Music-World-Map.geojson), displaying on an interactive map the major stakeholders of the world of iOS music, including iOS app developers, iOS-compatible hardware manufacturers, and more (UPCOMING)
2. The [Apptronica Members map](members-map.geojson), showing iOS musicians publishing under the Apptronica label 

Everybody is welcomed to contribute! Here's the instructions and guidelines.


# TODO

* clean up instructions below
* copy over images from animoog.org repos
* provide guidelines specific to the ios music world map
* add link to animoog.org/satri

# CONTENT COPIED FROM ANIMOOG REPOS AND TO UPDATE

The interactive map is here: <a href="https://github.com/alexandreleroux/Animoog/blob/master/map/animoog-map.geojson" target="_blank">github.com/alexandreleroux/Animoog/blob/master/map/animoog-map.geojson</a>

Animoog Players Map - Instructions for Contributing
============================================

This map is for the <a href="http://animoog.org/map" target="_blank">Animoog Players Map on animoog.org/map</a>, everyone is welcomed to contribute to it


Use cases
---------

* Find Animoog players and fans near you and meet to share tips and tricks, and maybe even jam together?
* Find Moog-related stores around you
* Maps are fun!


Adding yourself to the map
--------------------------

Map data, such as the location of Animoog players and Moog dealers, can be stored in a GeoJSON file. This file format is <a href="https://help.github.com/articles/mapping-geojson-files-on-github" target="_blank">automatically displayed over a map by GitHub</a>.

Adding yourself to the file that contains the map data:

1. Register and login to <a href="http://github.com" target="_blank">GitHub</a> - this step is necessary to avoid spam on the map
2. In a second browser tab, open the <a href="http://geojson.io" target="_blank">geojson.io</a> website
3. Copy the <a href="https://raw.githubusercontent.com/alexandreleroux/Animoog/master/map/animoog-map.geojson" target="_blank">raw animoog-map.geojson</a> content to the geojson.io website in its '</> JSON' tab<br>![image 1](images/raw-data-copy_to_geojsonio.jpg)
4. Click on the 'Table' tab to edit the map content using the 'Table' view:
  1. Add new members by searching for its location (the magnifying glass icon) and then clicking the pushpin to place the marker on the map
  2. Add corresponding text and links in the Table view<br>![image 2](images/add-content-to-map.jpg)
5. Go to the <a href="https://github.com/alexandreleroux/Animoog/blob/master/map/animoog-map.geojson" target="_blank">animoog-map.geojson file</a> page and click 'Edit this file' (the little pen icon), copy your improved geojson from the '</> JSON' tab on geojson.io and copy this content to members-map.geojson on GitHub<br>![image 3](images/edit-original-content.jpg)
6. Indicate what you added or changed in the 'Propose file change' box and click the 'Propose file change' button<br>![image 4](images/propose-file-change.jpg)
7. On the 'Comparing changes' page that loaded, click on 'Create pull request'<br>![image 5](images/create-pull-request.jpg)

Bravo, you're done! Once I'll accept your changes, the map will be updated and all other players will see the improvements you've done.


Warning
-------

PRIVACY warning: 
* Please add only yourself and Moog-related stores 
* Don't use the precise location of your home, you are responsible for the location accuracy and your associated privacy

Symbols and colors
-----
<a href="https://www.mapbox.com/maki/" target="_blank">Maki symbols</a> can be displayed directly on GitHub maps. Symbols and colors used on the map:

* Animoog players use the music notes icon ![example](https://cdn.rawgit.com/mapbox/maki/mb-pages/src/music-24.svg) in the green color (#32CD32)
* Animoog sound designers (presets and timbres) can use the chemist icon ![example](https://cdn.rawgit.com/mapbox/maki/mb-pages/src/chemist-24.svg) in the light purple color (#AD85FF), if you find another Maki icon is more suitable, let us know
* Moog headquarters use the industrial symbol ![example](https://cdn.rawgit.com/mapbox/maki/mb-pages/src/industrial-24.svg) in the orange color
* Orange (#FFA500) is the color for official Moog markers, such as headquarters and Moog staff
* Moog dealers and stores will use the commercial icon ![example](https://cdn.rawgit.com/mapbox/maki/mb-pages/src/commercial-24.svg) in the light blue color (#66CCFF)

Ideas?
-----

If you great ideas to improve this map? [Let us know in the issues](https://github.com/alexandreleroux/Animoog/issues)!






# OLD CONTENT TO DELETE OR MIGRATE:



Apptronica Members Map
============================================

View the interactive map here: https://github.com/alexandreleroux/Apptronica/blob/master/maps/members-map.geojson

This is a map of the <a href="http://apptronica.co.uk">Apptronica label members</a>, Apptronica members are welcomed to contribute to it.



Improving the map
--------------------------

Map data, such as the location of Apptronica members, can be stored in a GeoJSON file. This file format is [automatically displayed over a map by GitHub](https://help.github.com/articles/mapping-geojson-files-on-github).

Improving the file that contains the map data:

1. Register and login to [GitHub](http://github.com) - this step is necessary to avoid spam on the map
2. In a second browser tab, open the [geojson.io](http://geojson.io) website
3. Copy the [raw members_map.geojson](https://github.com/alexandreleroux/Apptronica/raw/master/maps/members-map.geojson) content to the geojson.io website in its '</> JSON' tab
4. Click on the 'Table' tab to edit the map content using the 'Table' view:
  1. Add new members by searching for its location (the magnifying glass icon) and then clicking the pushpin to place the marker on the map
  2. Add corresponding text and links in the Table view
5. Go to the [members_map.geojson file](https://github.com/alexandreleroux/Apptronica/blob/master/maps/members-map.geojson) page and click 'Edit this file' (the little pen icon), copy your improved geojson from the '</> JSON' tab on geojson.io and copy this content to members-map.geojson on GitHub
6. Indicate what you added or changed in the 'Propose file change' box and click the 'Propose file change' button
7. On the 'Comparing changes' page that loaded, click on 'Create pull request'

Bravo, you're done! Once I'll accept your changes, the map will be updated and all other users will see the improvements you've done.


Privacy warning
-------

* Please only add the city where you live in, not the exact address - that's probably something you don't want to make accessible here to everyone in the Universe


To do
-----

* Time is the only limit! If you have ideas, let's discuss... we can probably make this map a bit more useful :)
