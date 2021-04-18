+++
title = "Introducing Jellyfin Media Player"
subtitle = "A new user friendly MPV-based desktop client"
author = "Ian Walton"
githubusername = "iwalton3"
date = "2020-04-18"
justify = "center"
+++

Jellyfin Media Player is a new Jellyfin client option intended to offer a more user-friendly experience. It takes the user interface from jellyfin-web, including the playback interface, and combines it with the extensive codec support from MPV.

<!--more-->

<img src="/images/jmp/player.png" name="Player" />

You can [download the client on GitHub](https://github.com/jellyfin/jellyfin-media-player/releases). It is also available on [FlatHub](https://flathub.org/apps/details/com.github.iwalton3.jellyfin-media-player) and the [AUR](https://aur.archlinux.org/packages/jellyfin-media-player/).

## Extensive Feature Set

<img src="/images/jmp/config.png" name="Configuration Dialog" />

Building on the open source foundation of Plex Media Player, this client has support for selecting audio devices and configuring audio passthrough. It also supports changing the refresh rate of your display to match the video content. You can control the client with some remote controls, game controllers, and media keys through jellyfin-web’s TV display mode, in addition to remote control through the Jellyfin mobile apps. While testing the client it was known to be controllable with a PS3 controller in TV mode.

Since the media player is built on MPV, the mpv.conf file may be used to install scripts and shaders, as well as for tweaking the playback characteristics to the user’s liking. The software is also known to work with SVP with some tweaking of configuration files.

## Music Support

<img src="/images/jmp/music.png" name="Music Playback" />

Jellyfin Media Player can also natively play music in addition to videos. Being built on jellyfin-web and implementing player support as plugins, all features of the web client are available as usual, including server management. The client can connect to and switch between multiple separate servers.

## Extensive Cross-Platform Support

Through the help from several community contributions, Jellyfin Media Player now builds for Windows, macOS, and Linux. All release builds are automated through GitHub Actions. Linux users will be happy to know that Debian, Ubuntu, Flatpak, and AUR packages are available. Contributors are already improving the software’s foundation and have gotten it working on Wayland as well.