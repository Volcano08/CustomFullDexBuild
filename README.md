# CustomFullDexBuild

An unofficial community-maintained modification of Pokémon FullDex.

**Original project:** https://github.com/mamesj/pokemon-fulldex

This project builds upon the original FullDex project and adds quality-of-life improvements and community modifications.

## What I've changed

### Separate saves for ROM hacks
In the original version, multiple ROM hacks based on the same game could share a save filename. For example, HeartGold hacks such as Heartfelt Gold and Iridium could overwrite each other's saves.

This modification names save files after their respective ROMs, allowing multiple hacks based on the same game to maintain independent saves.

### Separate cheat files and images
Cheat files and game images are also handled separately for individual ROMs.

- Cheat files go in a `cheats` folder.
- Game images go in an `icons` folder.

These folders should be created alongside your `roms` folder.

### Custom game names
You can rename games within FullDex, making it easier to distinguish multiple ROM hacks based on the same original game.

### Platform builds
Builds are provided for Windows, Linux, macOS, iOS and Nintendo Switch where available.

Linux AppImage builds are my primary testing platform. Other platform builds are provided, but may not have received equivalent testing.

## Installation and usage

Download the appropriate release for your platform and follow the original FullDex installation instructions.

You must provide your own legally obtained ROM files. No commercial Pokémon ROMs are included with this project.

## Contributing

Contributions are welcome!

If you find a bug, have an improvement, or want to contribute a patch:

1. Fork this repository.
2. Create a separate branch for your changes.
3. Make and test your modifications.
4. Submit a pull request to this repository's `main` branch.
5. Include a description of the changes and any relevant testing.

Pull requests are preferred over sending entire modified source archives. This makes it easier to review, integrate and credit individual contributions.

Contributors may be credited in launcher information and release notes.

## Relationship to the original project

This is an unofficial community modification of Pokémon FullDex.

- Original repository: https://github.com/mamesj/pokemon-fulldex
- Community modifications: https://github.com/Volcano08/CustomFullDexBuild

This project is not an official release of the original FullDex project. It is independently maintained and is not affiliated with or endorsed by the original developer.

Original FullDex contributors retain their respective authorship and attribution. Changes made in this repository are intended to supplement, not replace, the original project.

## Licensing and attribution

This project incorporates and modifies software distributed under the GNU General Public License version 3 or later (GPL-3.0-or-later).

The original license is included in this repository as `LICENSE`.

All applicable original copyright notices, license terms, third-party licenses and attribution notices must be preserved when distributing source code or binaries.

Third-party components may have their own licensing terms. Refer to their respective license files in the source distribution.

Original project contributors retain credit for their work. Community contributions should retain their authorship and applicable notices.

## Disclaimer

Pokémon and related trademarks are owned by their respective rights holders, including Nintendo, Game Freak and The Pokémon Company.

This is an unofficial community project and is not affiliated with, sponsored by, or endorsed by those companies.
