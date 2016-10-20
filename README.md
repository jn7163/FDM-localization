# FDM-localization

Kindly help us improve Free Download Manager :)


This repository contains .po files for [FDM 5.x](http://www.freedownloadmanager.org/download.htm) localization. To edit and publish files, it's recommanded to use [Qt Linguist](http://down.admin5.com/app/113027.html). However, you can use other code editors or [Poedit](https://poedit.net/download), but you cannot publish .qm files and use the localized files immediately.


There are two ways to download the .po file for your language from GitHub.

1. Choose the file → click it → right click the Raw button ![raw](https://github.com/lychichem/FDM-localization/raw/master/2016-10-18_1231.png) → right click to save as…

The wanted file should be launched in the Poedit program. If it failed, try way 2.

2. Press the ‘Clone or download’ button → Download ZIP ![zip](https://github.com/lychichem/FDM-localization/raw/master/2016-10-18_1227.png)

Tips for translation:  
If you are using Qt Linguist, nothing to specially mention.

If you are using Poedit, translate words in corresponding filed and pay attention to pharses in yellow. Do not translate  words in brackets.

If you are using code editor like me, do not change the file structure and note that your translation should only be filled in `msgstr ""`. The .po file is in UTF-8 encoding and lines end with *nix format(LF).

Once you finished translation and want to make l10n file avalible immediately, use Qt linguist, load the .po file, click File → publish, it will make a smae-named .qm file. Use this file to replace the origin file in FDM install folder/translations.  

Many thanks for your help! It's highly appreciated.

If there are any issues, please [contact us](http://www.freedownloadmanager.org/support.htm) and send the output file via [support@freedownloadmanager.org](mailto:support@freedownloadmanager.org)