# My flexget configuration

## Features
1. Track.tv movie lists gets picked up automatically.
2. Showrss.info provides a show list and the torrents.
3. Torrents can complete seeding.
4. Renames and organizes shows and movies correctly for Plex or Kodi to read.
5. Automatically adds to transmission and you can manually clean it up.
6. Tasks are scheduled and run automatically.
7. Bonus sports config to download certain sports/teams

## Tasks
1. movie-queue: Queues movies from Trakt.tv (easy to convert to imdb) into flexget movie queue
2. download-movies: Uses movie queue to search kickass torrent for the movie with the indicated quality. Adds it to transmission.
3. download-shows: Uses showrss.info to get the rss with the shows you follow. Accepts them all and adds them to transmission.
4. subtitles: Uses subliminal to search the finished download folders for subtitles
5. sort-shows: Copies TV shows to their final destination and names them correctly using thetvdb.com.
6. sort-movies: Same but for movies using imdb/tmdb.
7. Manual task, clean-transmission: Deletes old torrents from transmission and asks transmission to delete the files.
8. download-sports: search kickass for the sport/team of your choice and add torrents to transmission
9. sort-sports: rename and copy games to an organized folder structure that plex/kodi can recognize
