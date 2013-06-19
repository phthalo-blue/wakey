playmusiccl
===========

A command line client for Google Play Music.

From a terminal "cd" to the script and execute it like any other Python script with "python PlayMusicCL.py", you then have access to the following commands:

PLAY - Pauses or unpauses playback
PAUSE - Same as PLAY
LIKE - Loves the current song on Last.fm and gives it a Thumbs Up on Google Play
EXIT - Exits.
NOW - Shows the title and artist of the currently playing song.
NEXT (n) - Plays the nth song after the current song (n has no effect in random play mode, n can also be negative to skip back through tracks).
PMODE [random/linear] [repeat/no repeat] - Specifies play options, if you have used any other media player they should be self explanatory.
LIST (pn) - Shows a list of all artists.
LIST (pn) PLIST - Shows a lit of all user playlists.
LIST (pn) PLIST [playlist] - Shows all songs in specified user playlist.
LIST (pn) [artist] - Shows all albums by specifies artist (including albums they appear on).
LIST (pn) [artist] [album] - Shows all songs in specified album by specified artist.
QUEUE (pn) - Show songs currently in the queue (in the order they are to be played).
QUEUE PLIST [playlist] - Add all songs from specified user playlist to queue.
QUEUE [artist] - Adds all songs by specified artist to queue.
QUEUE [artist] [album] - Adds all songs by specified album to queue.
QUEUE [artist] [album] [song] - Adds specified song to queue.
Note that "n" and "pn" are optional parameters and both default to 1, "pn" denotes the number of the page to display.
