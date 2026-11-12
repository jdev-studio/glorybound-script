# Changelog

The current version is printed in the console when the script loads.

**Numbering:** each new feature or fix gets the next `0.x.y` number. If it takes more than one try to get right, the follow-ups get a letter: `0.1.1`, `0.1.1b` and so on.

## 0.1.1 - 2026-11-12

- Fixed getting stuck after being knocked off the machine. It now sits back down in about 2 seconds instead of retrying for a long time, and skips travelling to the gym when you're already next to the machine.

## 0.1.0 - 2026-11-12

- First version: auto train on the gym machine you're sitting on, auto rebirth at the strength cap, then back to the same machine.
