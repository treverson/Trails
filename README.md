# Codename project Manhattan

This is private repo for the next big online io game.

## Quickstart

1. Install node.js
2. Run a console, and browse to the root folder.
3. Run nmp to start the server: "C:\Program Files\nodejs\npm.cmd" start

## TODO list:



*** new features
- add fun combos (teleport modifiers)
- phone support
- feedback when "close call" e.g. sparks

*** needs testing:
- REDx4: when you trigger it, it seems to transfer points somehow

*** known bugs:

*** admin commands (new feature)
- broad cast restart countdown with custom message
- crash logs

======NEW ABILITY DESIGN======

Green:	Greedy		| OLD: is about getting points
Red:	Fast		| OLD: is about playing fast.

Blue:	Solitary	| OLD: is about playing on your own.
Orange:	Hostile		| OLD: is about surprising others.

Yellow: Destructive	| OLD: is about clearing stuff in your way.
Purple: Sneaky		| OLD: is about teleporting.



red-red			*Doomsday Device: Trigger a Doomsday clock. The last player to find shelter dies. This consumes your power ups in the process. Replaces teleport.
purple-purple	Easy Landing: Your teleport now also removes power ups on the ground in a large area.
green-green		Air Bags: Crashing into a wall will cause you to lose some points instead of killing you.
blue-blue		Laser Beam: Trigger a laser beam that clears an entire line, eliminating players in the process. Replaces teleport.
yellow-yellow 	E.M.P.: Clear the entire map (30 second cooldown). Replaces teleport.
orange-orange	Switch-A-Roo: After teleporting, you channel a ray to switch position and color with another player.

purple-red		Rapid recovery: After teleporting, channel a ray on a nearby player in attempt to trigger their cooldown, and reset yours.
purple-green	Improved Teleport: Greatly reduces the cooldown on your teleport at the cost of points.
purple-blue		Chameleon Device: After teleporting, channel a ray on a nearby player in attempt to steal their color
purple-yellow	Bulldozer blade: After teleporting, you also clear blocks in a small radius for a short duration.
purple-orange	Death Ray: After teleporting, channel a Death Ray in attempt to eliminate a nearby player.
red-green		Point Vacuum: After teleporting, channel a ray on a nearby player in attempt to steal a large number of points. 
red-blue		Black Hole: Before teleporting, drop a black hole, attracting nearby players for a few seconds.
red-yellow		C-4: When your teleport is ready, the next wall you hit will cause a large clearing effect and trigger a short cooldown.
green-blue		Bonus Points: Picking up additional blue or green Power Ups will provide bonus points.
red-orange		Quick Escape: Your teleport triggers automatically when you hit a wall. Greatly lowers the cooldown. 
green-yellow	Recycling Device: Gain bonus points for every block you clear by teleporting.
green-orange	Point ray: Channel a ray on a nearby player in attempt to steal a large number of points. Replaces teleport.
blue-yellow		*Cloaking Device: After teleporting, become invisible for a short duration. While invisible, you can pass through all walls. 
blue-orange		Stealing Ray: After teleporting, channel a ray in attempt to steal all of another player's power ups.
yellow-orange	Entrenchment: Clear everything in a large area around you, surrounding you with a thin wall. Replaces teleport.


