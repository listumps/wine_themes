# wine_themes
 
A collection of restyled .msstyles themes for wine.
 

## Description

Selected bunch of windows .msstyles themes gathered from allover the Internet tweaked a little bit by using .reg files. Tested and verified to be perfectly working in [wine](https://www.winehq.org/):

*	[Windows XP Luna Blue Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Luna)
*	[Windows XP Luna Silver Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Luna)
*	[Windows XP Luna Olive Green Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Luna)
* [Windows XP Royale Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Royale)
* [Windows XP Zune Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Zune)
* [Windows Classic Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Windows_Classic)
* Light Theme included in wine >= 8.0
* Lunainspaqua Theme
* Ambient Theme


## Getting Started

### Dependencies

* [Wine package](https://wiki.winehq.org/Download) installed
* A viable [wineprefix](https://wiki.winehq.org/FAQ#Wineprefixes)

### Installing

* Download latest [release](https://github.com/listumps/wine_themes/releases/latest)
* Considering your WINEPREFIX is the default one (~/.wine) then just unzip all files and folders into ~/.wine/drive_c/windows/resources/themes

### Applying a theme

* Considering your WINEPREFIX is the default one (~/.wine) then just run in console:
```bash
regedit /C ~/.wine/drive_c/windows/resources/themes/apply_{theme name}_theme.reg
```
where *apply_{theme name}_theme.reg* is one of the .reg files supplied in the [release](https://github.com/listumps/wine_themes/releases/latest).


## Acknowledgments

* [www.skin-soft.co.uk](https://www.skin-soft.co.uk/visualstyles/skingallery.aspx)
* [wine-themes](https://github.com/winunix/wine-themes)

