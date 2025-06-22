# Using Kodi with RPDB

There are 2 methods of using RPDB with Kodi:
- Using [TheMovieDB Helper](#themoviedb-helper-addon) Addon (works with both online and local media)
- [RPDB Folders app](#rpdb-folders-app) (works only with local media)

Using RPDB with Kodi will enable ratings on posters: (scroll down for guides)
![phone-1](https://github.com/jaruba/rpdb-help/assets/1777923/60009c64-9e52-4e06-9852-aecb61cc315d)
![desktop-1](https://github.com/jaruba/rpdb-help/assets/1777923/23a7d658-bf28-4da6-8e7f-dc7ef929a392)

## TheMovieDB Helper Addon

You can install [TheMovieDB Helper Addon](https://github.com/jurialmunkey/plugin.video.themoviedb.helper/blob/nexus/Readme.md), using this addon you can replace the posters with RPDB posters for both online and local media.

After setting up TheMovieDB Helper addon with your RPDB API Key, you should go to [RPDB Poster Manager](https://manager.ratingposterdb.com/) to set up your poster preferences.

## RPDB Folders app

**Warning: Using the RPDB Folders app will only work with Kodi if you have built your own media library locally, it will not work with addons that serve remote streams, each Kodi addon would need to implement RPDB support individually.**

The "RPDB Folders" app works the following way:
- you install it on the same device where you are running your Kodi app from
- you add all your movie and series folders individually to the RPDB Folders app
- it will start adding posters and/or backdrops to the movie and series folders directly, which are then inserted into Kodi automatically

The RPDB Folders app can be downloaded from:
- [Desktop downloads (Windows, Linux, MacOS)](https://github.com/RatingPosterDB/rpdb-folders/releases)
- [Docker](https://github.com/RatingPosterDB/rpdb-folders-docker/blob/main/README.md)

For more details, there is a [Quickstart Guide](https://github.com/RatingPosterDB/rpdb-folders/wiki/Quick-Start-Guide) and an [Advanced Usage Guide](https://github.com/RatingPosterDB/rpdb-folders/wiki/Advanced-Usage) available for the RPDB Folders app.
