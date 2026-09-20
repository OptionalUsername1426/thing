# Xenon Hub changelog
#
# Newest first. Each version starts with a "## <version> - <date>" line, then one line per change, starting
# with New:, Improved: or Fixed: (or nothing, for a plain line). It's built into the exe (the Changelog
# page), and a copy goes up beside the exe on GitHub, where an out-of-date copy reads what it's about to
# get. Lines starting with a single # are notes like this one and don't show.

## 1.5.2 - 20 Sep 2026
Fixed: Being signed out after a few hours. A sign-in session doesn't last forever, and the app now quietly signs you in again when one runs out, with the farm carrying on.
Fixed: "The sign-in server's answer didn't check out", on sign-in and while running. When the server is busy it sends a page of its own instead of an answer, which was taken for a refusal: now it waits a moment and asks again, up to three times.

## 1.5.1 - 19 Sep 2026
New: Overlay, on the new Tools page. Lays a window you pick (a browser, a video) over Roblox, see-through as much as you like, and the mouse goes straight through it so the macro keeps clicking in Roblox while you watch.

## 1.5 - 19 Sep 2026
New: Auto Raid, on its own Raid page. Pick the raid and the act (or the first one not cleared), and it goes in through Play, Select Stage and Start, then repeats it or goes back to the lobby after a win.
Fixed: Auto Fish only kept up while the fish was out in the open, when a window or an overlay was over part of the bar.

## 1.3 - 19 Sep 2026
New: Auto Portal keeps itself going. At the end of a portal run it takes one of the portals offered, then opens the portal you picked on the Portal page and starts it.
New: Sort the catch, for Auto Fish. The prize fish get used with their slot's key, and anything else goes in the bin. Units are never touched.
New: A Sharktooth Conch you catch is kept, and used once the weather dial says the storm is 5 waves off or fewer. The log says while it's holding one.
Improved: Recast casts again by itself when a cast gets no bite within 20 seconds, so one cast that doesn't take no longer ends the fishing.
Fixed: Auto Fish lost the bar whenever the fish swam over it, on smaller or softer-looking screens, so it only worked now and then.
Fixed: Auto Fish missed the minigame over bright water and rocks, or took a rock beside the bar for the fish.
Fixed: The status said "Can't see Roblox" long after Roblox was back on screen.
Fixed: The lobby's steps (like looking for Events) could start up in the middle of a match, while waiting for a bite.

## 1.2 - 18 Sep 2026
Fixed: The red Return to Lobby button was missed when a menu dimmed it, so the app sat on the Exit Confirmation.
Improved: Changelog page, laid out as a timeline, with where your copy stands at the top.

## 1.1 - 18 Sep 2026
New: Testing the updater.

## 1.0 - 18 Sep 2026
Released
