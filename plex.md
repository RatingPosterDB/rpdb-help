# Using Plex with RPDB

There are 3 methods of using RPDB with Plex:
- [RPDB Plex Metadata Provider](#rpdb-plex-metadata-provider)
- [RPDB Folders app](#rpdb-folders-app)
- [RPDB Plugin (Legacy)](#rpdb-plugin-legacy)

Using RPDB with Plex will enable ratings on posters: (scroll down for guides)
![smart-tv-1](https://github.com/jaruba/rpdb-help/assets/1777923/1e1e581f-93c1-4526-a53f-13badd0044cb)
![smart-tv-2](https://github.com/jaruba/rpdb-help/assets/1777923/a0834cea-4675-41ee-9c61-25422d00d295)

## RPDB Plex Metadata Provider

The new RPDB Plex Metadata Provider is the recommended way of using RPDB with Plex, while the RPDB Folders app method gives better badge features (as it can probe videos to see if they are HDR, 4K, etc), the Metadata Provider is the simplest way of integrating images with ratings in Plex.

To get started installing the Metadata Provider, follow the steps from [this link](https://ratingposterdb.com/plex-agent/).

## RPDB Folders app

The "RPDB Folders" app works the following way:
- you install it on the same device where you are running your Plex Server from
- you add all your movie and series folders individually to the RPDB Folders app
- it will start adding posters and/or backdrops to the movie and series folders directly, which are then inserted into Plex automatically

The RPDB Folders app can be downloaded from:
- [Desktop downloads (Windows, Linux, MacOS)](https://github.com/RatingPosterDB/rpdb-folders/releases)
- [Docker](https://github.com/RatingPosterDB/rpdb-folders-docker/blob/main/README.md)

For more details, there is a [Quickstart Guide](https://github.com/RatingPosterDB/rpdb-folders/wiki/Quick-Start-Guide) and an [Advanced Usage Guide](https://github.com/RatingPosterDB/rpdb-folders/wiki/Advanced-Usage) available for the RPDB Folders app.

## RPDB Plugin (Legacy)

The RPDB Plugin (Legacy) for Plex will only work with legacy Plex Media Agents, we suggest using either RPDB Plex Metadata Provider or RPDB Folders instead as those methods are more future-proof.

To install the RPDB Plugin for Plex, you can follow [this guide](https://github.com/RatingPosterDB/RPDB-Media-Agent.bundle/blob/main/README.md).
