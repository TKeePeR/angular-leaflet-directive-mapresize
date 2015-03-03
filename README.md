# angular-leaflet-directive-mapresize
Additonnal directive for angular-leaflet-directive to dynamically redim a map

v0.1 - 1st release

# 1) Installation 
after "angular-leaflet-directive": <script src="angular-leaflet-directive.js"></script>
add: <script src="angular-leaflet-directive-mapresize.js"></script>

# 2) Usage
Add dragmap directive to leaflet directive. Example:
<leaflet width='100%' height='600' defaults="defaults" dragmap></leaflet>

# 3) How it works
It adds a div below the map. Click on it, hold and move to resize the map. Everytime the map is resized, invalidateSize() leaflet method is called

# 4) Notes
The resize bar is not very funny and isn't aim to

