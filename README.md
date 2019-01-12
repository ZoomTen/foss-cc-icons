# FOSS-CC
## What
A unified icon set for multimedia-related FOSS apps inspired by Adobe's Creative Cloud.

This icon theme is meant as an "add-in" to other icon themes, because it's meant to be limited to applications (productivity FOSS apps, and some others probably). More specifically, programs and its filetypes.

Below should give you an idea of how this theme will look like:
![The icon previews](https://github.com/zoomten/foss-cc-icons/raw/master/demo.png "preview image")

Currently this icon set has the palette of the approximate corresponding program within Creative Cloud suite (GIMP ~ Photoshop, Inkscape ~ Illustrator, etc.), and ones that were picked near a related program (e.g. Krita).

I might create a branch where the palette of the icons matches its original designs (e.g. Blender -> orange, Inkscape -> black)

Currently a work-in-progress.
## Why
I made this icon theme for fun (and because I can), and maybe it could add a touch of familiarity (or uncanny) for new users.

Unlike most other Adobe-styled icon sets, I took the approach of incorporating the original app's icon/branding into it, instead of the usual periodic-table. I think it makes a little more sense for me, since I could distinguish each app easier instead of "two-letter product mnemonics".

Some icons, for instance KompoZer and Cinelerra, may need to be simplified a little more, but I think this will do for now.

By the way, I am not associated with Adobe in any way, shape or form.

## Where
I plan to release this on opendesktop / *-look sites , when I have the time to do so. For now it's on GitHub and I'm pretty much a nobody here lol

Suggestions? File an "issue"! Or you could contribute by sending a pull request my way! I might be a little shy to review them, though.

## How
To install it, simply [download it](https://github.com/ZoomTen/foss-cc-icons/archive/master.zip) or run a quick `git clone` on this repository, within your local themes directory (`~/.themes` or `~/.local/share/themes`).

Then, you may edit `index.theme` to make it show icons from your desired icon theme, within the `Inherits=` parameters (line 5). For example, to make it show icons from the La Capitaine icon theme, you might want to change the line to:

``Inherits=la-capitaine-icon-theme,gnome,hicolor,adwaita``

## Credits
This icon set was made with a bit of help from the [La Capitaine](https://github.com/keeferrourke/la-capitaine-icon-theme) and [Marwaita](https://github.com/kstenerud/marwaita) icon themes.

Also to Adobe for the inspiration, of course :)

Fonts used in this icon set:
 * Roboto Condensed Heavy
