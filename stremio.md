# Using Stremio with RPDB

There are 2 methods of using RPDB with Stremio:
- [Stremio Addons that Support RPDB (all platforms)](#stremio-addons-that-support-rpdb-all-platforms)
- [Alternative Method (for desktop only)](#alternative-method-for-desktop-only)

Using RPDB with Stremio will enable ratings on posters: (scroll down for guides)

<img width="1440" alt="desktop-4" src="https://github.com/user-attachments/assets/e96c301a-5f3f-48da-81c5-05b44002b8f6">
![android-tv-4](https://github.com/user-attachments/assets/a76b8a9b-9613-4e89-9fc2-de875705ae4c)


## Stremio Addons that Support RPDB (all platforms)

**In order to accomplish this, you must:**
- [Subscribe to RPDB](https://patreon.com/rpdb) to get an API Key
- Go to the [Default Poster Manager](https://manager.ratingposterdb.com/), insert your API Key, and configure your desired poster settings
- Install an addon that supports RPDB (by adding the RPDB API Key to the configuration page of each addon that supports it)

#### Stremio Addons that currently support RPDB:
- [RPDB Catalogs](https://1fe84bc728af-rpdb.baby-beamup.club/configure)
- [IMDB Catalogs](https://1fe84bc728af-imdb-catalogs.baby-beamup.club/configure)
- [Anime Catalogs](https://1fe84bc728af-stremio-anime-catalogs.baby-beamup.club/configure)
- [The Movie Database Addon](https://94c8cb9f702d-tmdb-addon.baby-beamup.club/configure)
- [Streaming Catalogs](https://7a82163c306e-stremio-netflix-catalog-addon.baby-beamup.club/configure)
- [Cyberflix](https://cyberflix.elfhosted.com/)
- [Trakt.tv](https://2ecbbd610840-trakt.baby-beamup.club/configure/)
- [Rotten Tomatoes](https://7a82163c306e-rottentomatoes.baby-beamup.club/configure)

_If you used the "Default Poster Manager", then you will need to leave the default RPDB settings for each addon when installing it in Stremio, in order for the changes of the poster manager to take effect._

## Alternative Method (for desktop only)

There is also a method of changing all the posters of the Stremio Desktop app (only for Windows, MacOS and Linux) to posters with ratings, in order to use this method you will need to:
- create a new desktop shortcut icon for Stremio (you can call it "Stremio-RPDB", this is needed so the shortcut won't always be overwritten by Stremio on a new update)
- edit the desktop shortcut to add a command line argument ([here is a guide](https://www.digitalcitizen.life/shortcut-arguments-parameters-windows/) for how to do this on Windows)
- the command line argument that you need to add is: `--webui-url="https://stremio.ratingposterdb.com/shell/"`

There is a video showing how this method works on the desktop app, you can [see it here](https://www.youtube.com/watch?v=XPMflQZTcDg). 
