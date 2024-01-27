# wine_themes
 
A collection of original and restyled .msstyles themes for [wine](https://www.winehq.org/).
 

## Description

Selected bunch of windows .msstyles themes gathered from allover the Internet and some of them tweaked a little bit by using .reg files. Tested and verified to be perfectly working in [wine](https://www.winehq.org/):

*	[Windows XP Luna Blue Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Luna)
[![](https://i.pinimg.com/originals/0d/01/20/0d0120494eff1a32d9b7e1047333844d.jpg | width=300)](https://i.pinimg.com/originals/0d/01/20/0d0120494eff1a32d9b7e1047333844d.jpg "Windows XP Luna Blue Theme")
*	[Windows XP Luna Silver Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Luna)
*	[Windows XP Luna Olive Green Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Luna)
* [Windows XP Royale Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Royale)
* [Windows XP Zune Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Zune)
* [Windows Classic Theme](https://en.wikipedia.org/wiki/Windows_XP_visual_styles#Windows_Classic)
* Light Theme (*included in wine >= 8.0*)
* Lunainspaqua Theme
* Ambient Theme
* Capriccio Theme
* Human Theme


## Getting Started

### Dependencies

* [Wine package](https://wiki.winehq.org/Download) installed
* A viable [wineprefix](https://wiki.winehq.org/FAQ#Wineprefixes)

### Installing

* Download latest [release](https://github.com/listumps/wine_themes/releases/latest)
* Considering your WINEPREFIX is the default one (~/.wine) then just unzip all files and folders into ~/.wine/drive_c/windows/resources/themes

### Applying a restyled/tweaked theme

* Considering your WINEPREFIX is the default one (~/.wine) then just run in console:
```bash
regedit /C ~/.wine/drive_c/windows/resources/themes/reg/apply_{name}_theme.reg
```
where *apply_{name}_theme.reg* is one of the .reg files supplied in the [release](https://github.com/listumps/wine_themes/releases/latest).

### Applying an original theme

You can always do this by means of running [winecfg](https://wiki.winehq.org/Winecfg) GUI configuration tool and going to 'Desktop Integration' tab.


## Acknowledgments

* [www.skin-soft.co.uk](https://www.skin-soft.co.uk/visualstyles/skingallery.aspx)
* [wine-themes](https://github.com/winunix/wine-themes)

