# Localizations for Telegram EmailGateBot

md-files in `doc` folder contain documentation (initially in English), that should be translated.

File `doc/LC_MESSAGES/messages.po` contain messages of the bot in utf-8 encoding.

'msgid' item contains an English string for translation, 'msgstr' must contain the localized (translated) string.

Pay attention to the special characters '{}' in localization strings. When the bot is working, the necessary parameters are substituted for them, so they must be saved in the localization strings in the right place, depending on the content of the phrase.
