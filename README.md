# Flip Tracker

A Forge 1.8.9 mod for Purple Prison (works in Lunar Client) that tracks itemflips, coinflips and tokenflips in a clean,
animated window. It reads chat and the `/itemflip` menu only. It never clicks, sends packets or types for you.

This repository holds the releases and the update log. The mod updates itself from here.

## Install

1. Download `FlipTracker-1.8.9.jar` from the [latest release](https://github.com/Nuccleusbee/fliptracker/releases/latest).
2. Put it in your 1.8.9 Forge mods folder. For Lunar Client that's `.lunarclient/profiles/1.8/mods/forge-1.8.9/`.
3. Join Purple Prison and press **J**.

Remove any older `FlipTracker` jar from the folder so only one is loaded.

## Updates

From v1.1.0 the mod checks this page every few hours. A new version downloads in the background and installs when you
close Minecraft. Every release jar has a `.sig` file next to it. The mod only installs a download whose signature
checks out, so a changed jar is never installed. Turn auto-update off, or check by hand, on the **Updates** tab
(press 0 in the window), or type `/flips update`.

## Shared flip data

Everyone running the mod adds the flip results they see in chat to one shared pool, and gets everyone else's back.
That keeps each player's last 6 and streak right even when their games happened while you were offline. Your own
offline flips also come back with the opponent, item and time. Only flip results are shared (who beat whom, the item
or amount, the side and when), plus your account name. Turn it off with **Share flips** on the Updates tab.

## Update log

See [CHANGELOG.md](CHANGELOG.md). The same notes show in game on the Updates tab.
