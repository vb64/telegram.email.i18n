# Localizations for Telegram EmailGateBot

This repository contains localization files for Telegram [@EmailGateBot](http://t.me/EmailGateBot?start=utm_KDaxQG000_github-i18n).

The `doc` directory contains files in English that need to be translated into the localization language.

md-files contain English documentation, that should be translated.

File `doc/LC_MESSAGES/messages.po` contain messages of the bot.
'msgid' item contains an original English string for translation, 'msgstr' must contain the localized (translated) string in utf-8 encoding.

Pay attention to the special characters '{}' in localization strings. When the bot is working, the necessary parameters are substituted for them, so they must be saved in the localization strings in the right place, depending on the content of the phrase.

The following directories contain translations of the bot interface and documentation into other languages

- `ru` Russian
- `es` Spanish

To work on the translation, use the gitlocalize.com website. You will need a GitHub account to log in to this site.

After authorization, go to the [EmailGateBot project](https://gitlocalize.com/repo/5622), select the translation language and the desired file.
