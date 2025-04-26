# Lovely is a runtime lua injector for LÖVE 2d

Lovely is a lua injector which embeds code into a [LÖVE 2d](https://love2d.org/) game at runtime. Unlike executable patchers, mods can be installed, updated, and removed *over and over again* without requiring a partial or total game reinstallation. This is accomplished through in-process lua API detouring and an easy to use (and distribute) patch system.
## Installation

1. Use my fork of [balatro-mobile-maker](https://github.com/kodenamekrak/balatro-mobile-maker) to add the library (Requires manual build)
2. Install the outputted `balatro.apk`
3. Run the game once to create the necessary folders
4. Download mods and extract them in `Android/data/com.unofficial.balatro/files/mods` (Can be done on device using a file explorer)
    - Make sure to download any dependencies that a mod requires
    - If a mod contains a native binary (`.dylib` or `.dll`) then it will *not* work

*While it is likely, there is no guarantee that I will maintain this in the future*

### Patches

See the [Official Documentation](https://github.com/ethangreen-dev/lovely-injector)

## Credits

Credits go to [ethangreen-dev/lovely-injector](https://github.com/ethangreen-dev/lovely-injector) for creating the initial project
