# About
This repository contains all localizations for FancyMenu and a template (in English) for people who want to help translate the mod.

# "I want to help!"
Great! It's really easy, just download/copy the [template](https://github.com/Keksuccino/FancyMenu-Translations/blob/main/template/en_us.txt) from this repository and start translating!

When you're done translating the template, you can upload it to a text hoster like [Ghostbin](https://ghostbin.com/) and [open a new issue](https://github.com/Keksuccino/FancyMenu-Translations/issues) with the link to the file and some informations about what language it is.

Thank you very much for helping to translate this mod!

### "What should I translate?"
Most of the time, it's simply translating everything **after** the **first** equals sign (=).

Every text line in the template looks similar to this:<br>
`helper.creator.layoutempty.title = Layout is empty!`

In this example, you should translate `Layout is empty!` to your target language.<br>
Everything before the equals sign (`helper.creator.layoutempty.title`) needs to stay the same, otherwise the mod can't find the text anymore.

### "There are weird codes in the text, what to do with them?"

#### Minecraft Formatting Codes
If you look at the template, you will find various Minecraft formatting codes like `§c` or `§3`.<br>
These codes are there to colorize/format the text **after** the certain code.<br>
If you see one of these, please don't remove it, just translate the normal text and move the formatting code if you move the text after it.

#### Newline | %n%
The other code you will find in the template is `%n%`.<br>
This is the `newline` code I'm using to tell the mod to switch to the next line.

For example, `This is the first line!%n%This is the second line!` will look like this ingame:

```
This is the first line!
This is the second line!
```

This code is mostly used in button tooltips and for text in popups.<br>
If you find this code in a text line, it's most probably there because a line of this specific text can't be much longer than the text before the code.

You shouldn't remove these codes, just try to translate the normal part of the text.<br>
If your translated version of the line is longer than the original, you may need to manually add more `%n%` codes.

#### Placeholders | {}
Placeholders (`{}`) get replaced by real values later, so please don't remove them and don't add new ones. The number of placeholders needs to stay the same!

For example, `Mod Version: {}` will later look something like `Mod Version: 2.0.6`.<br>
Try to keep the word order of texts containing placeholders, because `{} Mod Version:` will look a bit wrong later, you know?
