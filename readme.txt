Freeshell "Solar Runes" v1.0.0
for Etc. Jam 2026


—————————— Terms ——————————
This freeshell is free to use for your own ghost projects, with the following terms.

You must:
	• Mention in your ghost's readme that you are using my freeshell. I can be credited as "Zichqec", with the following link: https://ukagaka.zichqec.com/
	• List any modifications you have made to the freeshell's artwork in your ghost's readme.
	• Keep this readme file as-is. (It can be renamed if you are combining this freeshell with other freeshells.)
	• Keep the craftman information of the freeshell as-is. (If combining this freeshell with other freeshells made by different developers, the craftman information can be modified to ensure all developers are represented.)
	
You may:
	• Modify the shell, including recoloring, drawing new expressions, combining expressions, scaling the images, mirroring the images, etc. (This shell is drawn in a pixel style, please take care when scaling. It'll look best if you keep the pixels sharp!)
	• Modify the settings files in any way you need.
	• Combine this shell with other freeshells.
	• Use this shell to create a thumbnail image for your ghost, or a preview image for use on the ghost's release page, etc.
	
You must not:
	• Distribute any version of this freeshell on its own.
	• Use this freeshell to create commercial works.
	• Use this shell for works outside the realm of ukagaka.
	• Modify the shell to be discriminatory or political, or use it in a work that contains these elements.
	• Modify the shell to add nudity or sexual elements.
	• Use AI tools to modify the artwork in this shell.

It is not required to notify me that you have used this shell, but I'd love to see what you've made!


—————————— Customization ——————————
I haven't included a psd file with this freeshell yet, but I plan to once I have time to clean it up after jam!

I tried out a new surface numbering scheme this time, which should make it easy to add in new custom expressions. The 0-9 range is taken up by the default expressions, and 20-29 is taken up by some additional expressions I wanted, which leaves 30-99 free to add whatever combinations or new face pieces you want.

If you intend to make new faces that have all the eye and arm positions, like the ones I set up, I highly recommend using column editing! There are some giant lists of numbers in there, and those were made with the help of column editing and a little find and replace. They look like rows of numbers, but they're actually columns that have been crushed down and can be expanded again.

One other note: I had thought about setting it up so that the color of the book matches with the symbol on it, but I decided to split it up to have a greater variety. If you wanted, though, you could use addid to link them up. In my head, the star goes with red, the moon goes with blue, both together goes with gold, and title only goes with green. (The tabard also has colors that match with the brooch, although in that case I like to do the star + moon with the purple...) You're free to set it up in any way you like, of course!


—————————— Surface numbering scheme ——————————
This shell follows the recommended surfaces listed on Ukadoc. 00-09 should roughly match up with the standard 0-9 that you'll find there. https://ukagakadreamteam.github.io/ukadoc/manual/descript_shell_surfaces.html#caption_standarddef

I included 10 more expressions beyond the standard. You can also control the eye position and one of the arms with additional digits, allowing for a wide range of expression.

Surfaces have 4 columns: The thousands digit controls the arm, the hundreds digit controls the eye position, and **both the tens and the ones** control the base expression. It's a two digit counter. This means for many expressions the tens column will be 0, but it allows for up to 100 expressions without breaking the numbering scheme.

As an example, \s[3201] will call the surface for the pointing hand (3), the eyes looking left (2), and the embarrassed expression (01). \s[2321] will call the surface for the gesture hand (2), the eyes looking right (3), and the "Grin" expression (21).

The numbering breaks down as follows:

0000 - "Read" arm (hand holding book)
1000 - "Extended" arm
2000 - "Gesture" arm (has magic effects, see below)
3000 - "Point" arm
4000 - "Think" arm

	000 - Eyes looking down at book (Some expressions have the eyes closed since this is the default range)
	100 - Eyes looking forward/at the user
	200 - Eyes looking left
	300 - Eyes looking right
	400 - Eyes looking up and to the left
	500 - Eyes looking up and to the right
	600 - Eyes closed downward
	700 - Eyes closed upward
	800 - Eyes squeezed shut
	
		00-09 - The recommended expressions listed on Ukadoc
		20 - Skeptical
		21 - Grin
		22 - Ambitious
		23 - Sheepish
		24 - Ick
		25 - Bleh
		26 - Yikes
		27 - Grimace
		28 - Shouting
		29 - Anguish


In addition to these, all expressions (that do not display them by default) can have the following extras applied:

\i[11] - Blush
\i[12] - Sweat drops


Finally, the "Gesture" arm has optional magic effects. These are set up as dressups, and you may want to set up something on the ghost side to make it easier to write them.

Any time you use the "Gesture" arm, you should be aware that there may be a dressup already applied to it, and take care to set (or remove) the desired dressup when the surface is displayed.


—————————— Collisions ——————————
The following collisions are included by default.

head - Top of the head.
book - The cover and visible parts of the book's pages.
brooch - The brooch on the chest, when it is visible. The shape changes depending on which one is chosen.