CNC-Toolbox
===========

This is a CNC made toolbox that you can built with a small CNC machine like the ShopBot Handibot

https://www.youtube.com/watch?v=eiZ6DxULJhg

The project is a derivitive of the Sketchup model that is found here:

http://www.highlandwoodworking.com/woodnews/2009october/sketchup.html

To cut this you will need a piece of baltic birch plywood that is exactly 1/2" thick (make sure you check it with calipers) The sheet size will need to be at least 48" wide and 42" tall.

I cut this on a Handibot with a 1/4" straight router bit.

The Sketchup model (3d) is included here. To cut this I took that model and I laid it out flat and then I exported it to DXF so that I could later import it into VCarve to setup my toolpaths. My toolpaths that I used are included (They are setup for a 1/4" bit and are already tabbed)

Please note that the Sketchup model is done with 0 clearance where parts have to fit into one another. The DXF file has "Dog bones" in it so that parts can pass through as well as a little bit of clearance for parts to pass through. I built this box once, and with 0 clearance it worked, but I had to hammer the parts into the slots quite a bit.

The toolpaths are setup to be cut on a Handibot using 6"x6" tiles. In the cutting files folder you will find every tile that is needed to cut it out, along with a map that shows each tile number and where it coresponds to the design.

The DXF file is already included. (In case you want to make your own toolpath, or cut on a larger machine)

To use a Handibot, you will need to index it EXACTLY at every 6" across, and up to cut this file. Shopbot is releasing a jig that can help you with this. Either that, or you can come up with a jig solution of your own.

With the Handibot, you have to cut about 60 tiles, and you have to load each file individually. To make that process easier, I have included a script in the cutting files folder that you can load. This script will zero out the tool and load one file after another automatically, give you a chance to pause and move to the next tile. This file makes it immensely easier to cut a large amount of tiles like this. While the file that is included in the tile directory will work fine, if there are any updates to that script, you can find them here:

https://github.com/SketchThis/Handibot-Cut-all-Tiles
