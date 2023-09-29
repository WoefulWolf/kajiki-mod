<h1 align="center">
    🐟 カジキ 🌌
</h1>

## Introduction
カジキ ("kajiki") is a game modification to syncronize & visualize player positions across game worlds! 

Built specifically for speedrun racing in mind.
<p align="center">
  <img src="https://i.imgur.com/pC9XGoO.png" width="75%" title="Haha a cool screenshot!">
  <br>
  Image by <a href="https://www.twitch.tv/jaynoo_" target="blank_">Jaynoo_</a>
</p>
<!-- ![HahaScreenshot](https://i.imgur.com/pC9XGoO.png) -->

## Features
- 3D player rendering with depth-buffer.
- Game state is untouched and memory only ever read.
- Personalize your model with custom colors.
- Choose your world's player models.
- Vast configuration options.
- Written in 🦀**Rust**🦀.
- Much more!

## Installation
#### Client
1. Head over to the [latest release](https://github.com/WoefulWolf/kajiki-mod/releases).
2. Download the `kajiki.dll` binary.
3. Place the `kajiki.dll` binary in the same directory as your game's executable.
4. Rename `kajiki.dll` to one of the proxy names specified in [Supported Games](#supported-games).
5. Launch your game!

### Server
1. Head over to the [latest release](https://github.com/WoefulWolf/kajiki-mod/releases).
2. Download the correct executable for your platform.
3. Launch the executable with the `--port <PORT>` argument. (Optionally add `--max-clients <MAX_CLIENTS>` to specify server player limit).
- You might need to port forward UDP `<PORT>` to allow others to connect.

## Basic Usage
1. Open/Close the kajiki-mod menu using the default keybind: `PAGE_UP`.
2. Enter a username and select a custom color.
3. Enter the server's IP & Port split with a colon, eg. `127.0.0.1:1337`.
4. Connect!

## Supported Games
| Game          | Working Proxies                           |
| ---           | ---                                       |
| NieR:Automata | `dxgi.dll`, `d3d11.dll`, `dinput8.dll`    |

If you want a game supported, please contact me to negotiate!

## Reporting Bugs & Requesting Features
- Please use this GitHub repository's [Issues](https://github.com/WoefulWolf/kajiki-mod/issues) section.
- Try including reproduction steps in bug reports if possible!
- For issues relating to the client, please include the relevant log file found in `<GameDir>/logs/kajiki-client.log.XXXX`.
