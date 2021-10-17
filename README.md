# Heart of Ice - Dave Morris

In 2018 I ported the classic gamebook from my childhood in the '90s. It was written in Sugarcube (a JS-based language for the TWINE interactive fiction tool)
and the various art assets are from a combination of the original and the reprint. The port will run in any contemporary browser (at the time of writing).

If you'd like to look at the code simply import the latest revision in Twine. I've also included the local copy of the game that Twine uses.

There's a bit more on the port's release over [on Dave Morris' blog](https://fabledlands.blogspot.com/2018/12/warm-heart.html).

## Files:

### sound

Various sound files used in the game in a variety of formats.

* 271453_4190771-hq.mp3 is from [here](https://freesound.org/people/bdunis4/sounds/271453/) (CC0 licence)
* flash_whine.mp3 is from [here](https://freesound.org/people/MichelleGrobler/sounds/410559/) (CC0 licence)

### artwork

A mixture of image assets including the original scans of the book in their aged glory, various assets intended for the book (some used in the reprint), and the images actually used in this port.

The images used in the port are mostly PNGs using indexed colour (with a very limited palette). The goal being to keep the images crisp and clear but without bloating the filesize. The reasoning is simple - I wanted the game itself to be a self-contained file rather than an archive with a collection of different assets. This way the finished game contains all the relevant assets encoded in base64 to allow inline embedding.

### fonts

Much like the images several fonts are embedded in the file using base64. They're included here as separate files for reference (they're all covered by the Open Font Licence)
-Alegreya SC
-Libre Baskerville
-Gruppo
-Geostar Fill
-VT323

### misc

As the finished game is a single HTML file the original release was achieved by hosting it on my server. However social networks don't always create useful thumbnails and descriptions (particularly when there's a lot of JS involved) I opted to add that information manually. OpenGraph is the way that's done and so the two files in this folder are for that. The HTML file needing to be manually added to the finished HTML file.
