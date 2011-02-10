youtube-dl-playlist

Usage: youtube-dl-playlist PLAYLIST_ID [DESTINATION_PATH]

This utility allows you to download all the videos from a playlist on Youtube. 
It creates a folder in the current directory (or in the specified path) named 
after the playlist name and then downloads each video in order and places it 
within the folder.

If the script fails in the middle of the playlist you can restart it with the 
same options and should pick up where it left off.

Depends on:
 - Python (should be available on Linux/Unix/Mac by default)
 - youtube-dl (avaliable at http://rg3.github.com/youtube-dl/ and in repos for 
   most Linux distros)

To install:
1. Download the file youtube-dl-playlist and place it in /usr/local/bin.
2. Make sure it has execute permissions: 
   chmod /usr/local/bin/youtube-dl-playlist
3. Install youtube-dl by placing its downloaded file in /usr/local/bin as well. 
   It must also have execute permissions.
4. Enjoy.