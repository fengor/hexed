Hexed
=====

A roguelile game engine for hexagonal tiles

Inspirations
------------
 * [Cataclysm - Dark Days Ahead](http://en.cataclysmdda.com/)
 * [The crawling eater](http://www.plomlompom.de/PlomRogue/)
 * [Amit Patel's Hexagonal Tiles Resources](http://www.redblobgames.com/grids/hexagons/)
 * [GoCUI](https://github.com/jroimartin/gocui/)

Assumptions
-----------
 * UTF-8 font with a 2:1 height to width ratio
 * 256 color support as in http://www.calmar.ws/vim/256-xterm-24bit-rgb-color-chart.html 
 * pointy topped hex tiles only
 * game data will be in json for easy modding (as in c:dda)
 * needed viewports: playarea, overmap, character_status, log area
