# Music Commands
These commands are related to playing music, available to all users. If a TextChannel is set, these commands can only be used in that channel.

## `lyrics [song name]`
Fetches the lyrics for the provided song name, or the currently-playing song if no name is provided

## `nowplaying` (or `np` or `current`)
Shows information about the song that is currently playing (name, user that added it, current timestamp, and song URL)

## `play`
Shows the play commands. If the player is paused, it resumes the player.

## `play <URL>`
Plays the song or stream at the provided URL. Supported locations include (but are not limited to): YouTube (and playlists), SoundCloud, BandCamp, Vimeo, and Twitch. Local files or URLs of the following formats are also supported: MP3, FLAC, WAV, Matroska/WebM (AAC, Opus or Vorbis codecs), MP4/M4A (AAC codec), OGG streams (Opus, Vorbis and FLAC codecs), AAC streams, Stream playlists (M3U and PLS)

## `play <song name>`
Plays the top YouTube result for the specified song name

## `play playlist <playlistname>` (or `play pl <playlistname>`)
Plays all songs in the specified playlist. There must already be a playlist of the specified name in the Playlists folder

## `playlists`
Shows available playlists. These playlists must be inside the Playlists folder.

## `queue [pagenum]` (or `list [pagenum]`)
Shows songs in the queue. If no page number is provided, it defaults to the first page.

## `remove <songnum>` (or `delete <songnum>`)
Removes the song at the provided position in the queue. You can only remove songs that you added, unless you are an Admin or have the specified DJ role.

## `remove all` (or `delete all`)
Removes all songs that you have added to the queue

## `search <query>` (or `ytsearch <query>`)
Shows the top YouTube results for a search and allows you to select one to add to the queue

## `scsearch <query>`
Shows the top SoundCloud results for a search and allows you to select one to add to the queue

## `shuffle`
Shuffles (changes the order, randomly) of songs that you have added to the queue

## `skip` (or `voteskip`)
Skips a song if you added it. If you didn't add it, it adds your vote to skip it. Approximately 60% of active listeners need to vote to skip a song for it to be skipped.
