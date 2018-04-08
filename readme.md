# NFSOL l10n
========

A fan-made localization project for the game Need For Speed ONLINE.

## Getting started

Let's do this.

### Languages
========

**chinese** is the backup of official (Tencent) translation. **Do not modify!!!**

Other folder(s) should contain translation files of language specified by folder name.

### Translation rules
========

#### File creation
========

Create your translation according to latest ***chinese*** or ***english*** translation file.

DO NOT start something new based on your fantasy!!! 

#### File naming
========

Please specify (GMT) time-stamp in format of yyyyMMddHHmm in filename, then add the language name in English.

```
l10n-string-cn_201803301227_english
l10n-string-cn_201803301227_russian
l10n-string-cn_201803301227_spanish
```

#### Syntax
========

The general format of a localization file should look like:

```
{
  "locale": "cn",
  "data": {
    "SOME_IDENTIFIER": "some contents",
    "SOME_OTHER_IDENTIFIER": "more contents",
  }
}
```

Each line of the translation may look like examples below:

```
    "1ON1_DEMOTIONPOPUP_CONFIRM": "Confirm",
    "1ON1_MAIN_CHANGEVEHICLE": "Change Vehicle",
    "GAMEROOM_FRIENDLY_MATCH_DESC": "A variety of multiplayer matches can be played in Friendly Match! \nYou can enter specific room/lobby to play with other players,\n or use Quick Matching to join any room.",
    "STARTSCREEN_PRESSANYKEY": "Press Any Key <span style=\"color:#fffc00\">[Updated March 30, 2018]</span>",
```

#### Add new lines

Compare the difference in **chinese** or **english** translations using programs like Beyond Compare, then add changed lines into your latest translation.

##### You should...

- ALWAYS edit in **UTF-8 without BOM** encoding.

- ALWAYS use *spaces* instead of *Tab*

- ALWAYS use advanced options such as *Match Case* and *Match whole word only* while using *Replace All*.

- ALWAYS make sure each line ends with a **,**

- Use concise words.

- Use sentences shorter or equal to length of their English counterpart.

- Verify context before translating.

##### You should NOT...

- Use misleading words.

- Use irrelevant or even hazardous HTML script

- Use "Replace All" arbitrarily. You may have changed the identifiers unwittingly!

- Use quotation marks or slashes arbitrarily. You may have broken the syntax and thus render the entire translation file unusable.

### Work cycle
========

Normal period -- NFSHelper translation working properly. No actions need to be taken.

Expiration -- NFSHelper no longer displays translation. Needs to update the translation.

#### When does *Expiration* happen?
========

It happens usually when the game receives major update that renders previous localization non-functional due to missing critical strings.

Beware it is **unnecessary** to modify translation files between major game patches.

=================================================================================

Thanks to everyone contributed to the project.

These files were created as part of the NFSHelper project (https://www.needforspeedonline.com/)

Knightmare is not affiliated with or endorsed by Electronic Arts.

<p align="center">Feel free to join our Discord server:<br> 
<a href="https://discord.gg/RFSUhRh"><img width="175" height="50" src="https://cdn.discordapp.com/attachments/341098517760049153/432414919548338187/logo_discord_our.png" /></a></p>