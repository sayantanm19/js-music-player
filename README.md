# js-music-player
This is a simple User Interface of a music player created in HTML, CSS and JavaScript.

![Output](/output/html-css.png)

## Running the player

The index.html file can be run on any modern browser to run the music player.

## Adding more tracks

The tracks are currently being loaded from the tracklist array specified in main.js. More tracks can be added by adding the details of each track as an object to the tracklist.

## Add more Tracks to <playlist>

More tracks can be added by adding a new <div class="track-number" onclick="numberTrack(track_index ,number = '#')" >New Track</div> in index.html.
make sure that the number is always one less than in playlist details : 0 = 1, 1 = 2 etc
