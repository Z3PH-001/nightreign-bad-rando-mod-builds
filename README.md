# Nightreign Bad Rando / Study mod - builds

The latest built mod for testers: `nr_study_tools.dll` (goes in the Boss Arena folder, replacing the old one).
`version.txt` = build time + checksum; the mod reads it at game start and updates itself when a newer build is here
(restart the game to use it). Source code lives in a private repository.

## 2026-10-06 build
The strip is new: `5 MENU 6 MODE 7 CONTROLS 8 LEARN 9 BAD RANDO 0 ROUND TABLE`, `- MEDIA = DEV FEEDBACK` bottom right; 1-9 pick
rows only while a menu is open (5 lists every key). Mode: Free (level 15) / RL1 (level 1) / Practice / Fight Report. Controls:
Take Damage, Boss Takes Damage, Unlimited Deaths, Invisible (I), Pause, Slow Motion (]), Reset Health ([). Learn: Hitboxes, Attack
Timing (O), Parry Timing (P), Sounds, the counters, Boss Colours. Pad: click both sticks for the menu, D-pad to move, X picks, O closes.
The parry green now learns from the parries that work (`parry_windows.txt` next to the DLL; delete it to start over).
