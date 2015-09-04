# Font Test

Tool for testing whether the web fonts on apple.com support certain characters.

## Instructions

1) Choose a character set from the menu at the top of the page
2) Paste or write your copy on the left-hand side of the page. You can paste in any kind of copy, including full HTML source code - everything except Chinese characters should get stripped out (If there are other characters that do not get stripped out then you may need to delete them manually).
3) On the right-hand side you will see the copy rendered in the font used on the live site. Any unsupported characters will appear in red.

## Advanced options

If you want to automate testing of copy, you can include both the language and the input text as URL parameters, e.g.

> index.html?text=一缕阳光

> index.html?lang=zhhk

> index.html?text=一缕阳光&lang=zhcn

Currently 3 language codes are supported:

* zhcn
* zhhk
* zhtw

## Support

Email ["darryl.snow@apple.com"](mailto:darryl_snow@apple.com) to tell me any problems or suggestions.