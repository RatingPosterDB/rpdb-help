# Using Jellyfin with RPDB

There are 2 methods of using RPDB with Jellyfin:
- [RPDB Folders app (recommended)](#rpdb-folders-app-recommended)
- [Dedicated RPDB Plugin (less features)](#dedicated-rpdb-plugin-less-features)

Using RPDB with Jellyfin will enable ratings on posters: (scroll down for guides)
![jellyfin-1](https://github.com/jaruba/rpdb-help/assets/1777923/8ca225e6-ba71-4f2e-b58d-90405afd1f36)

## RPDB Folders app (recommended)

The "RPDB Folders" app works the following way:
- you install it on the same device where you are running your Jellyfin Server from
- you add all your movie and series folders individually to the RPDB Folders app
- it will start adding posters and/or backdrops to the movie and series folders directly, which are then inserted into Jellyfin automatically

The RPDB Folders app can be downloaded from:
- [Desktop downloads (Windows, Linux, MacOS)](https://github.com/RatingPosterDB/rpdb-folders/releases)
- [Docker](https://github.com/RatingPosterDB/rpdb-folders-docker/blob/main/README.md)

For more details, there is a [Quickstart Guide](https://github.com/RatingPosterDB/rpdb-folders/wiki/Quick-Start-Guide) and an [Advanced Usage Guide](https://github.com/RatingPosterDB/rpdb-folders/wiki/Advanced-Usage) available for the RPDB Folders app.

## Dedicated RPDB Plugin (less features)

You can also use the dedicated RPDB Plugin for Jellyfin, but it has a lot less features compared to the RPDB Folders app.

To install the RPDB Plugin for Jellyfin, you can follow [this guide](https://github.com/RatingPosterDB/Jellyfin.Plugin.RPDB/blob/main/README.md)
