---
title: Advanced Invasion 1.1 Update
date: 2026-09-19 15:59:00 +0100
---
My efforts to create a [fleet of addons for tertiary functions of my games]({% post_url 2026-02-28-sv-mod-loader %})
have come to a head, and I am pleased to share that - after way too bloody
long - I have finally pushed an update for Advanced Invasion.

<!--more-->

My plan for test driving my addons was to use them to help port my old games to
Godot 4, and overhaul their systems. I always meant to push an update to
Advanced Invasion, since there were aspects I was dissatisfied with. Plus,
Newgrounds users had left a bunch of good feedback in reviews and I wanted to
integrate some of it.

Unfortunately I got busy for absolutely ages, but now that I was porting
Advanced Invasion to Godot 4 and adding all my addons, it was a good opportunity
to really polish the game.

So without further ado, I present the trailer for the Advanced Invasion 1.1
update:

<video controls width="1280" height="720">
    <source src="https://filedn.eu/lQjIWV7eYltL9DHQ8vi1lqp/videos/trailers/advanced-invasion/advanced-invasion-1.1-trailer-1080p.webm" type="video/webm">
    Your browser does not support playing this video. Please <a href="https://filedn.eu/lQjIWV7eYltL9DHQ8vi1lqp/videos/trailers/advanced-invasion/advanced-invasion-1.1-trailer-1080p.mp4">download it</a> instead.
</video>

Here's the patch notes for what exactly's in the update:

## Patch Notes
Update 1.1 brings a major overhaul targeted at several major pain
points in the game. The headline items are a more forgiving experience
on the lower difficulty, an overhauled final boss battle, improved
cutscenes and dialogue in the middle of the game, and a major interface
overhaul.

You will also see a slew of social icons on the main menu. If you
enjoyed Advanced Invasion, please do consider following me to keep
up with my future work

### Mechanics
- Difficulty settings have been renamed. Casual is now Standard, and
  Normal is now Hardcore.
- Boss battles now have slightly easier mechanics on standard
  difficulty. The difficulty descriptions have been updated to reflect
  this.
- When playing on standard, respawn mechanics have been improved.
  - If you have lives left, you will teleport to a safe location after
    falling into pits (whether bottomless or heat blocks) instead of
    restarting the level.
  - On certain moving platform levels, where waiting for the platform
    to return would take way too long, the platform snaps back to an
    accessible location if you respawn.
  - This means that the extra lives granted to you by Standard mode
    should now be helpful in all situations in the game.
- Major overhaul to the final battle
  - The final battle now includes viruses with shields on top.
  - In the final battle, your ally now has to contend with
    horizontally-shielded viruses as well. They are also able to react
    intelligently to a few more situations. This should make the battle
    feel a little more fair, and also give you an example of what to do
    to win the battle.
  - In the final battle, your ally now also has lives if you are playing
    on standard.

### Story
- Added extra expository dialogue before the first cutscene fades in.
- Overhauled the second meeting with your teal ally into a full level.
  Dialogue has been completely overhauled in this level and most of it
  is completely new.
- Overhauled post-boss cutscene after the square virus boss with new
  dialogue and different animation.

### UI
- The UI now scales when playing on high resolutions (e.g. 4K). There
  is a slider in the options menu to customise this behaviour.
- Improved UI styling, covering many previously unstyled elements.
- Added controller support to menus.
- Overhauled main menu with a nicer-looking and more usable layout.
- Added social links to the main menu.
- Overhauled the jukebox. It now has freshly-written per-track liner
  notes, and supports complex playback features like shuffle or looping
  individual tracks.
- Overhauled options menu.
- Added custom keybinds to options menu.
- Made minor changes to achievement menu and popups (these are a
  consequence of under-the-hood changes)
- The achievement menu is now accessible from the pause menu.
- Overhauled about menu. Third-party license information is now
  clearer, more thorough, and separated from the credits.

### Bugfixes
- Fixed jitter when the player character moves.
- Fixed a previously broken non-functional feature that would have
  allowed you to zoom the camera manually. You can now use the scroll
  wheel to zoom in and out.
- Fixed bullet firing when using spacebar to close dialogue

### Technical
- Migrated engine version to Godot 4.7.2.
- Simplified display settings on the web platform (resolution now
  automatically adjusts to the size of the canvas on web).
- Overhauled how achievements work under-the-hood.
- Several save file formats have been changed. Existing files will
  automatically be upgraded when you start the game.
- Calculation of valid zoom levels for the camera have been changed.
  You may see slightly different zoom levels than before on certain
  resolutions.

## What's Next
I've also been working on similar updates for Squid Savings and CircleRC. For
Squid Savings, it's nothing major. Just migrating to the latest Godot version
so I can drop in my new achievement handling.

CircleRC will be a big deal, though. I neglected to upload those to Newgrounds
and Game Jolt because I wanted to add achievements first, and now I'll finally
be getting around to doing it. The Newgrounds release should be pretty exciting
since Newgrounds is quite good at getting a lot of eyes on your game, and I
reckon the Newgrounds community would enjoy it.

CircleRC should be getting a few extra levels as well. 14 doesn't feel like
enough. I don't want to go too crazy, though, since I want to start
making new games soon. I think adding 6 more to make 20 should bring us to a
nice round number.

