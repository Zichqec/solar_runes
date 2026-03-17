Put your shell readme here! Especially if you're making a shell for someone else's ghost, or you're making a freeshell. If you decide not to add a readme to your shell, at least remove the template instructions that are in here. Please make sure you add a craftman and replace the name/directory of the shell in the descript.txt and install.txt files!

This shell template is intended for devs that want a simple shell template, but find the Simplicity Template's shell too barebones. This shell template has a bit more structure to it, having all of the recommended surfaces from Ukadoc, blinking animations, a couple of talking animations, and even a simple singing animation loop.

Personally, I have found with most ghosts that I've made that I end up structuring the shell differently every time. So don't be afraid to change the numbering scheme that I've laid out here! And if you'd rather have a blank shell to start with and build your own numbering scheme, you can try the shell that's included with the Simplicity Template (the ghost template), or my Hydrate Shell Template. Those can be found at these links:
https://ukagaka.zichqec.com/template/simplicity_template
https://ukagaka.zichqec.com/template/hydrate_shell_template


As far as the way this template is laid out, the poses follow the recommended surfaces outlined here on Ukadoc: https://ukagakadreamteam.github.io/ukadoc/manual/descript_shell_surfaces.html#caption_standarddef

There are two reasons for this. For one, it's a good spread of expressions to get you started with, and you can write a lot with just these!

The other reason is that there are some external programs/plugins that expect these default surfaces to be there, and will attempt to use them. For example, if you use the plugin for Foobar2000 that sends lyrics to ghosts, it will make them use surface25 while displaying lyrics. surface25 in the recommended surfaces list is the singing pose, so that makes sense! That's just one example, there are some other applications that use these expressions as well. It can be nice if your shell lines up with those, but it's not at all necessary.

And as a bonus reason: if you're making a freeshell, it's just nice to have a standard set that ghost makers can expect when they try out your shell!

All that being said, if the default expressions don't suit your shell, ditch them! Be free! Experiment and do what works best for your project! Don't let this template restrict you.


As far as the blinking and talking animations go, the numbering scheme I've used is like this:

All the blinking animations are in the 1000s. So a 1 in the first column (of a 4 digit number) means it's a blink. The next two digits are the surface number they go with. So 01 goes with surface 1, and 11 goes with surface 11. The last number is the frame of the animation. So 0 is the first frame, 1 is the second frame.

So surface1031 is a blinking animation (1) for surface 3 (03), and it is the second frame of the animation (1). 1 03 1.

The talk frames are much the same, except they all start with a 2 instead of a 1.

The singing frames are an exception, and since there are only two of them, I simply made 3000 be the sakura's singing frame and 3001 the kero's singing frame.

As with the default expressions, don't feel compelled to keep this structure! You could even ditch the animations altogether if you want. Do what makes sense to you, and what suits your project.

I added a surfacetable file just to tidy up the surface test window. I didn't add any groups there, if you want to know how to do that you can check the information about surfacetable here: https://ukagakadreamteam.github.io/ukadoc/manual/descript_shell_surfacetable.html


A couple final notes. This template uses the new definition of SERIKO instead of the old definition. If you don't know what that means, here's a guide talking about it: https://ukagaka.zichqec.com/guide/old_definition_vs_new_definition

Also, in the descript.txt file you'll find the option for seriko.alignmenttodesktop,free is commented out. I'm fond of shells that stick to the edges of the monitor lately, so I'm leaving it off by default. But if you want your shell to be freely moveable, simply uncomment it.

Finally, These pages on Ukadoc are your best friend for making shells:
https://tkagakadreamteam.github.io/ukadoc/manual/descript_shell.html
https://ukagakadreamteam.github.io/ukadoc/manual/descript_shell_surfaces.html


Simplicity Shell v1.0.1
Made by Zichqec https://ukagaka.zichqec.com/
You are free to use this to create any shells/freeshells you like, no need to credit me! But if you'd like to find more by me, including more templates like this, find me at the link above.