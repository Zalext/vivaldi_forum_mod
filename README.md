# Vivaldi Forum mod

![vfm](/icons/icon48.png)

Open source extension. Dedicated to improving your experience browsing Vivaldi Forum.

[Available on chrome web store](https://chrome.google.com/webstore/detail/vivaldi-forum-mod/hipnollokpifchndpfhnlfjbdnkhiigg?hl=en-US).

## Features

* Theme machine
* Scheduled theming
* User CSS
* Modifications
* Fixes
* Enhanced functionality

For a detailed rundown and explanation of features, please see the [support site on Vivaldi Forum](https://forum.vivaldi.net/topic/19728/vivaldi-forum-mod).

## Contribute

Vivaldi Forum mod is a community project driven by the ideas and needs of its users. Without users, there's no reason for development. Thus the most straightforward way to help out is installing and using the extension, providing feedback and spotlighting issues.

### Themes

Have you created a beautiful theme with help of the Theme Machine? Great! Please share it by using the **Export** button on the options page, which will copy the theme code to your clipboard. Afterwards simply paste the theme code in a reply to the [feedback topic](https://forum.vivaldi.net/topic/19728/vivaldi-forum-mod) on Vivaldi Forum.  Did you introduce additional changes with User CSS? – Copy the code and paste it alongside your theme.

Create your own theme:

* Download or clone the repository.
* On Vivaldi's extensions page enable developer mode, click **Load unpacked** and select the Vivaldi Forum mod directory.
* Select **Standard** theme in options, open `standard.css` (located in `vivaldi_forum_mod/themes`) in a text editor and start designing your new theme.

### Translations

Vivaldi Forum mod 2.0 introduces translations. Following languages are currently being worked on:

* Czech
* French
* German
* Italian
* Russian
* Spanish
* Vietnamese

You can help out by improving these translations, or by introducing a new translation. Here's a quick **how to**:

* Please make sure the language you want to translate to is [supported](https://developer.chrome.com/webstore/i18n?csw=1#localeTable).
* Clone or download the [repository](https://github.com/luetage/vivaldi_forum_mod/).
* On Vivaldi's extensions page enable developer mode, click **Load unpacked** and select the Vivaldi Forum mod directory.
* In Vivaldi browser settings, go to **Startup** and select your desired target language. Restart the browser.
* In Vivaldi Forum settings pick your target language, hit **Save** and reload the tab.
* Create a new directory in `vivaldi_forum_mod/_locales` and rename it (locale code).
* Make a copy of the English translation file (`vivaldi_forum_mod/_locales/en/messages.json`) and paste it into your newly created translation directory.
* Open the `messages.json` file in a text editor and start translating.

Each entry in the file has a **message** and a **description** part. Only translate the message to your target language, leave everything else untouched. Descriptions which start with the word **Options** are translations for Vivaldi Forum mod's options page, anything else appears on Vivaldi Forum directly. Make sure to check out existing translations on Vivaldi Forum and to enable the different modifications to see your translations in action. If you should have any question about this procedure, or if you need help of any kind, please write a post in the feedback topic or send a [message](https://forum.vivaldi.net/user/luetage). Each translation should at least be checked by one other contributor to assure its accuracy. Finished translations will be released as soon as you submit them. Either make a pull request on Github directly, or submit the `messages.json` file by pasting its contents online (e.g. [pastebin](https://pastebin.com/)) and sharing the link.
