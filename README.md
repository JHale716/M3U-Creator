M3U Playlist Creator using Tiny Media Manager reporting

This is a quick tool that takes the XML output of Tiny Media Manager, a media library manager, and creates M3U-compliant playlists for your media player.

This assumes you are using a remote share or mapped drive to access your media library, and Tiny Media Manager has a different access pathway to your media player.

Instructions:
- In Tiny Media Manager (TMM), select tracks to add to playlist (Maximum 199)
- Right click and select export (Movies/TVShows)
- Select Excel Movie List by JS
- Adjust the path, and click export
- Open the XML file in Excel or Sheets (not tested in Sheets)
- Add a new column B and label it order
- Number items in desired play order (or not, but this column needs to be added for this to work)
- Sort the list by your sort order
- Select the rows for the items to add to your playlist
- Paste the selected items into the movie list tab starting at the first grey line.
- Complete the two fields below to adjust the playlist file links.
- On the M3U Playlist tab select from #EXTM3U to the bottom of your list
- Right click/copy
- Paste into a plain text file and save as <name>.m3u
- Copy/move the created *.m3u file to your media player's playlist folder to use
	
The prefix in the instructions sheet is to set the default path for your media player
The number of initial characters is to remove the TMM prefix that is different to your media player.

Provided as is, for other media library or data, you'll figure out what needs to go where in the spreadsheet to get what you need.
