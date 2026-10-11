# Final Fantasy IX: Arabic Translation (v1.0.0-beta)

An Arabic translation of FINAL FANTASY IX (Steam, PC) as a Memoria mod folder. It translates dialogue, battle text, menus, items, abilities, locations and character names. Arabic replaces the **English (US)** language slot.

العربية: انظر `README_AR.md`.

## Requirements

- FINAL FANTASY IX, Steam PC version.
- [Memoria](https://github.com/Albeoris/Memoria) installed. Tested with Memoria **2025-07-13** (the version shown in `Memoria.log`). Older versions are untested.
- The Arabic font installed in Windows (step 2 below). Memoria can only draw text with fonts installed in Windows; it cannot load a font file from a mod folder.

## Install

1. **Copy the mod.** Copy the `ArabicTranslation` folder into the game folder, next to `FF9_Launcher.exe`. By default this is `C:\Program Files (x86)\Steam\steamapps\common\FINAL FANTASY IX\`. You should end up with `FINAL FANTASY IX\ArabicTranslation\ModDescription.xml`.
2. **Install the font.** Open the `ArabicTranslation\Font` folder and double-click `Install-Font.bat`. This installs the included font, **Readex Pro FFIX**, for all users on this PC; Windows will ask for administrator permission (the game only sees fonts installed for all users). Use this file: the regular Readex Pro from Google Fonts will not work, because this edited copy adds the pre-joined Arabic letters the mod uses.
3. **Enable the mod.** Start the game from Steam to open the Memoria launcher, open the **Mod Manager**, and tick **Arabic Translation**. If you use other mods (Moguri, for example), move Arabic Translation **above** them in the list.
4. **Select the language.** Start the game. In the language menu, choose **English (US)**. The game text is now in Arabic.

If the text shows as boxes or in the wrong font, the font is not installed or its name does not match `ArabicTranslation\Memoria.ini`. Run `Install-Font.bat` again and read its message.

## Known limitations

- Some text is drawn as images and is still in English: the title-screen buttons, the place-name cards shown when entering a new area, and the continent titles on the world map.
- A name you type for a character can only use Latin letters. The default names are in Arabic.
- Works with Moguri Mod. Keep Arabic Translation above Moguri in the Mod Manager list.
- Not tested on Steam Deck or Linux. The font installer is for Windows only.
- This is a beta: please report mistranslations, cut-off lines or display problems.

## Uninstall

1. In the Memoria launcher's Mod Manager, untick Arabic Translation (or remove it), then delete the `ArabicTranslation` folder from the game folder.
2. Optionally remove the font: double-click `ArabicTranslation\Font\Uninstall-Font.bat` (before deleting the mod folder).
3. English (US) is back to normal once the mod is disabled.

## Credits

Translation: Enma.
Font: Readex Pro FFIX, a modified Readex Pro (© The Readex Pro Project Authors), SIL Open Font License 1.1 (see `ArabicTranslation/Font/OFL.txt`). Uses the Memoria engine mod by Albeoris and contributors.
FINAL FANTASY IX is a trademark of Square Enix. This is a non-commercial fan translation and contains no game files.
