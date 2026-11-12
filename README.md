# glorybound-script

Auto gym and auto rebirth for GloryBound. Everything runs through the game's own remotes, so it keeps going while Roblox is tabbed out.

## Running it

Sit on a gym machine (for example a 1.5x barbell), then run:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/jdev-studio/glorybound-script/refs/heads/main/GloryBound"))()
```

Written against Matcha. Needs remote calls and `fireproximityprompt`.

## What it does

- **Trains** on the machine you were sitting on when it started (B10 if you weren't on one). It sends reps the same way the Push button and E do.
- **Rebirths** when strength is at the cap: stops training, travels to the Rebirth Shrine, rebirths, travels back to the gym and sits back down on the same machine.
- **Sits back down** if you get knocked off the machine.

Pushing only adds about 10% over just sitting on the machine, so most of the gain comes from staying seated.

## Stopping it

```lua
_G.AutoGymStop = true
```

Running the loadstring again replaces the running copy, so you never end up with two.
