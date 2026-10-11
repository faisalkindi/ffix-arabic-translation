# Final Fantasy IX: Arabic Translation (v1.0.1, beta)

An Arabic translation of FINAL FANTASY IX (Steam, PC) as a Memoria mod folder. It translates dialogue, battle text, menus, items, abilities, locations and character names, plus the text drawn as images. Arabic replaces the **English (US)** language slot.

العربية: انظر `README_AR.md`.

## Requirements

- FINAL FANTASY IX, Steam PC version.
- [Memoria](https://github.com/Albeoris/Memoria) installed. Tested with Memoria **2025-07-13** (the version shown in `Memoria.log`). Older versions are untested.
The Arabic font is built into the mod, so there is no font to install.

## Install

1. **Copy the mod.** Copy the `ArabicTranslation` folder into the game folder, next to `FF9_Launcher.exe`. By default this is `C:\Program Files (x86)\Steam\steamapps\common\FINAL FANTASY IX\`. You should end up with `FINAL FANTASY IX\ArabicTranslation\ModDescription.xml`.
2. **Enable the mod.** Start the game from Steam to open the Memoria launcher, open the **Mod Manager**, and tick **Arabic Translation**. If you use other mods (Moguri, for example), move Arabic Translation **above** them in the list.
3. **Select the language.** Start the game. In the language menu, choose **English (US)**. The game text is now in Arabic.

If the text shows as boxes or in the wrong font, check that `ArabicTranslation\FF9_Data\EmbeddedAsset\FA\p_fa.mpc` is there and that no mod above Arabic Translation changes the font.

**Updating from v1.0.0-beta:** delete the old `ArabicTranslation` folder before copying the new one. The font you installed for the beta is no longer needed; you can keep it or remove "Readex Pro FFIX" in Windows Settings > Fonts.

## Known limitations

- Two images stay as they are: the Tetra Master logo and the copyright line on the title screen.
- A name you type for a character can only use Latin letters. The default names are in Arabic.
- Not tested with Moguri Mod yet. If you use it, keep Arabic Translation above Moguri in the Mod Manager list.
- Not tested on Steam Deck or Linux.
- This is a beta: please report mistranslations, cut-off lines or display problems.

## Uninstall

1. In the Memoria launcher's Mod Manager, untick Arabic Translation (or remove it), then delete the `ArabicTranslation` folder from the game folder.
2. English (US) is back to normal once the mod is disabled.

## Credits

Translation: Enma.
Font: Readex Pro FFIX (built into the mod), a modified Readex Pro (© The Readex Pro Project Authors), SIL Open Font License 1.1 (see `ArabicTranslation/Font/OFL.txt`). Uses the Memoria engine mod by Albeoris and contributors.
FINAL FANTASY IX is a trademark of Square Enix. This is a non-commercial fan translation. It contains no game program files; it does include edited versions of the game's own text images.
