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
Now available on [OpenDesktop / *-look](https://www.opendesktop.org/p/1287085/)!

Suggestions? File an "issue"! Or you could contribute by sending a pull request my way! I might be a little shy to review them, though.

## How
To install it, simply [download it](https://github.com/ZoomTen/foss-cc-icons/archive/master.zip) or run a quick `git clone` on this repository, within your local themes directory (`~/.themes` or `~/.local/share/themes`).

Then, you may edit `index.theme` to make it show icons from your desired icon theme, within the `Inherits=` parameters (line 5). For example, to make it show icons from the La Capitaine icon theme, you might want to change the line to:

``Inherits=la-capitaine-icon-theme,gnome,hicolor,adwaita``

## Additional Notes
* OpenShot's *.osp MIME type has the icon set to "openshot", will display application icon instead of the filetype icon.
       * To fix this, you might need to head over to `/usr/share/mime/packages/openshot-qt.xml` and remove line 6 entirely (where it says `icon="openshot"`). Then run `sudo update-mime-database /usr/share/mime`.

## Credits
This icon set was made with a bit of help from the [La Capitaine](https://github.com/keeferrourke/la-capitaine-icon-theme) and [Marwaita](https://github.com/kstenerud/marwaita) icon themes.

Also to Adobe for the inspiration, of course :)

Fonts used in this icon set:
 * Roboto Condensed Heavy
