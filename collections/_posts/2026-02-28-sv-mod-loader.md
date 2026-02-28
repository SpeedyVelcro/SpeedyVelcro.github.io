---
title: SV Mod Loader and Future Plans
date: 2026-02-28 22:14:00 +0000
---
I haven't released any games lately, partly because I've been busy, but
also because I plan to create a set of reusable UI elements for my
future games to save dev time in the long run. One of these is SV Mod
Loader, releasing v1 today - a GUI and framework for loading mods in
`.pck` format that you can include in your Godot Engine games.

[Get it on GitHub!](https://github.com/SpeedyVelcro/sv-mod-loader)

![Screenshot of SV Mod Loader](/assets/images/blog/2026-02-28-sv-mod-loader/screenshot.png)

<!--more-->

When I made [Advanced Invasion](/games/advanced-invasion) I found
myself spending an inordinate amount of time developing and polishing
the various UI elements towards the end. Partly, my own perfectionism
is to blame. Despite Advanced Invasion being - by design - an
incredibly simple game, I wanted to include all sorts of bells and
whistles including an achievements system, jukebox, and reasonably
fully-featured options menu (although I neglected to include controls
settings in the end because it was already taking too long (and there's
also an about menu for license compliance btw but that's not as fun)).

These kinds of periphiral elements - at least I believe - add a lot of
substance to a game. It gets even better when you include stuff like
level editors, concept art menus, etc. Consequently, I'm quite keen on
including at least a jukebox, achievements, and options screen in all
my future games.

So, to save time, I want to create these various elements in advance
so I can just drop them into future games. One of the first I wanted to
tackle - primarily because it's the most difficult - is a mod loader.

Now, this probably sounds a bit OTT considering that
[a perfectly good option already exists](https://github.com/GodotModding/godot-mod-loader),
and in fact I would recommend most people use that option instead. But,
for an upcoming project I may or may not do, I'd like to have a few
specific features. Specifically, I want a good way of distributing
required asset packs separately from the source code, and this might
as well hook into a modding system. This is good if, like me, you're an
open source game developer and, on occasion, you need to deal with
proprietary assets.

Consequently, one of the main selling point of SV Mod Loader is the
ability to configure checksums for official or required mods and
verifying that you have the real deal before launching the game. Other
than that, the system is pretty rudimentary. It just uses the
[normal methods](https://docs.godotengine.org/en/stable/tutorials/export/exporting_pcks.html#opening-pck-or-zip-files-at-runtime)
for loading `.pck` files.

Other than that there's a couple exxtra bells and whistles. The UI
includes an inbuilt load order editor, with the ability for uses to
create and manage multiple different mod lists. There's an about menu
you can use to show important information e.g. licenses before
launching the game, and you can customise a lot of elements of the mod
loader through exported variables.

Overall, I don't really expect this to be that useful to anybody. There
are much more stable and mature alternatives out there, after all. But,
if your needs just happen to be similar to mine, you might find it
interesting. In that case, it's open source and you can get it
[on GitHub](https://github.com/SpeedyVelcro/sv-mod-loader).

