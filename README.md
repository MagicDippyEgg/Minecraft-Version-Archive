# Minecraft Version Archive

This repository keeps an archive of official Minecraft releases from `1.0` to the latest version. Both `client.jar` and `server.jar` are available in the [Releases tab](https://github.com/MagicDippyEgg/Minecraft-Version-Archive/releases).

The archive updates automatically every week and adds new versions when Mojang releases them.

## What is included

For each release version, this archive includes:

- `client.jar`, used by the Minecraft Launcher
- `server.jar`, used for hosting multiplayer servers when available

You can download them directly from the [Releases](https://github.com/MagicDippyEgg/Minecraft-Version-Archive/releases) page without needing to dig through Mojang’s API or launcher files.

## How it works

This repository is powered by:

- a Python script that fetches version data from Mojang’s official [version manifest](https://piston-meta.mojang.com/mc/game/version_manifest_v2.json)
- a GitHub Actions workflow that runs every Monday
- a check for new Minecraft versions
- downloads for the latest `client.jar` and `server.jar`
- a new GitHub Release when a version is added

## License

This project redistributes Mojang’s publicly available `.jar` files for archival and preservation only.  
All Minecraft assets are © Mojang Studios / Microsoft. This project is not affiliated with or endorsed by Mojang.

## Credits

Maintained by [@MagicDippyEgg](https://github.com/MagicDippyEgg).  
Made to keep Minecraft history easy to access.
