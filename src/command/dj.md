# DJ Commands
All Admins can automatically use DJ commands. Admins can also assign one server role to be the "DJ role," which allows anyone with that role to use these commands as well.

## `forceremove <user>` (or `forcedelete <user>` or `modremove <user>` or `moddelete <user>`)
Forcibly removes all songs that were added by the specified user

## `forceskip` (or `modskip`)
Forcibly skips the current song, regardless of who added it and how many votes there are to skip it

## `movetrack <from> <to>` (or `move <from> <to>`)
Moves the track at position in the queue to position

## `pause`
Pauses the player. The player remains paused until a DJ or Admin uses the play command

## `playnext <song name | URL>`
Places a single song at the front of the queue to play next (or begins playing if nothing is currently playing)

## `repeat [on | off]`
Puts the player in (or takes it out of) repeat mode. In repeat mode, when songs end naturally (not removed or skipped), they get put back into the queue.

## `skipto <position>`
Skips forward in the queue to the provided song number, playing that song and removing any songs before that from the queue

## `stop`
Clears the queue, ends the current song, and leaves the voice channel

## `volume [0-150]` (or `vol [0-150]`)
Shows or sets the current volume. For best performance, it is recommended to leave this at 100 and adjust volume on an individual basis within Discord
