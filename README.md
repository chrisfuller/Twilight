# Twilight

A delightful dark "font and color theme" for Xcode inspired by the Twilight theme for [TextMate](https://macromates.com).

![Twilight - A delightful dark "font and color theme" for Xcode](https://raw.githubusercontent.com/chrisfuller/twilight/master/twilight.png)

### Fonts

The font family and size can be adjusted in Xcode's preferences, but there are two choices to start with.
Choose either **Menlo** (available in OS X) or **Input** ([available for download from The Font Bureau](http://input.fontbureau.com)),
both at size `12.0`.

### Installation

Menlo:

`$ curl -o ~/Library/Developer/Xcode/UserData/FontAndColorThemes/Twilight\ -\ Menlo.dvtcolortheme https://raw.githubusercontent.com/chrisfuller/twilight/master/Twilight%20-%20Menlo.dvtcolortheme`

Input:

`$ curl -o ~/Library/Developer/Xcode/UserData/FontAndColorThemes/Twilight\ -\ Input.dvtcolortheme https://raw.githubusercontent.com/chrisfuller/twilight/master/Twilight%20-%20Input.dvtcolortheme`

### Notes

Xcode provides two theme settings `DVTSourceTextBlockDimBackgroundColor` and `DVTSourceTextInvisiblesColor`
that do not seem to be used in the Xcode user interface anywhere, so those two attributes have been set to
a pink color. This is simply for theme debugging purposes and will be updated if and when Xcode utilizes
those values.
