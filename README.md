# ONIi18n
The repo to hold the translation for [ModI18n](https://github.com/ONI-Wiki-zh/ModI18n).

# Adding your translation
First download the pot file of the mod you interested in [strings directory](/strings). If you can not find the string template of the mod you want, please [create an issue](https://github.com/ONI-Wiki-zh/ONIi18n/issues) to request it.

Then translate it (e.g. with Poedit). When finished, you can [create an issue](https://github.com/ONI-Wiki-zh/ONIi18n/issues) to submit it. You can also create a pull request if you are familiar with Git/GitHub.

To update existing translations, just download the old po file instead.

To test your translations, you can set "Use Local Translations Only" to true in the in-game mod options of ModI18n, and then put your translations as `mods/i18n/xx.po`. Available language code could be found inside [`strings/languages.json`](/strings/languages.json)

# Adding your mod for translation
To add your mod for translation, please make a PR with your `.pot` file under `/strings/YOUR_MOD_NAME/`. The `YOUR_MOD_NAME` here is not strict, just make sure to be different from other's mod. If you want, you can also create a issue a with your pot file so that we can add it for you.

To make sure all users of your mod have ModI18n enabled, you can mention it in your mod's description page or add ModI18n as the dependency of your mod (it should not add any noticeable lag to English users).

To update existing string templates, just create a new issue/PR with the new templates.

# Modder opt-out
The following modders don't want their mods to be translated without thier supervision. Therefore this repo can't provide translation for their mods.
* Cairath

# Known issues & TODO
- Link this repo with smartCat
