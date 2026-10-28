# Gone Fishing: Nintendo button layout fix (PortMaster)

Fixes swapped A/B and X/Y buttons in the PortMaster port of
[Gone Fishing](https://github.com/SkyWalker541/Gone-Fishing) by SkyWalker541
on handhelds with a Nintendo layout (RG35XX H, Batlexp G350, etc.).

## How to apply

1. Install Gone Fishing from PortMaster.
2. Open `ports/gonefishing/gonefishing.gptk` on your SD card.
3. Replace these four lines:

   | Before    | After     |
   |-----------|-----------|
   | `a = x`   | `a = z`   |
   | `b = z`   | `b = x`   |
   | `x = c`   | `x = v`   |
   | `y = v`   | `y = c`   |

4. Save and launch the game.

On an Xbox-layout device, keep the original file.

## Tested on

- Anbernic RG35XX H
- Batlexp G350

## Credits and license

Game by SkyWalker541, licensed CC BY-NC-ND 4.0. This repository does not
contain the game or any modified copy of it, only instructions for a local
edit to a configuration file. Port by the PortMaster team.
