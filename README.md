# Helldivers' Ammunition
**Version:** 1.0.0B (public beta)

Adds four ammo type variants to the primary weapons. **Recommended to use in Private lobby.**

## How to use

There's a drop-up menu button to the left of the **Customization** button:

`OFF` `FIRE` `EM` `AP` `SUB` `HP` `GAS` 

- Click the drop-up menu button to choose an ammo type. Click it again (or `OFF`) to clear it.
- Hover an ammo label to preview what it changes (green = better, red = worse).
- Types the weapon cannot take are dimmed.
- The choice is remembered per weapon and applied while that weapon is your equipped primary.
- The traits box shows an `AMMO: X` line.

## Ammo types

| Chip | Ammo | Effect |
|------|------|--------|
| AP | Armor Penetrating | Damage -10%, durable +25%, recoil +5%, armor penetration +1 level (max AP3; not on Medium/Heavy weapons) |
| FIRE | Incendiary | Sets targets alight, fire rate -15%, ergonomics -5% |
| EM | Electromagnetic | Staggers targets, recoil +10%, spray +5%, durable -5% |
| SUB | Subsonic | Damage -15%, durable -5%, recoil -10%, spray -5%, suppressed and quieter (not on explosive or already suppressed weapons) |
| HP | Hollow Point | Damage +25%, durable -20%, recoil +15% |
| GAS | Gas | Slows and blinds targets, recoil +5%, ergonomics -10%, fire rate -10% |

## ROADMAP

- Add support for plasma projectile-based weapons
- Add support for beam-based weapons

## Known issues

- Gas effect strength is still being tuned.
- Fire rate is not applied to 13 primaries yet.

## Not supported yet

- Legendary warbond weapons and energy weapons (lasers, plasma, arc).

## Info to know

- **Shared bullets:** some weapons share one bullet with others (for example the Liberator family), so an ammo type can also change those weapons. The log notes it.
- **Fire rate:** applied to 40 primaries. The rest get the other effects of the ammo type.
- **Handling changes** (recoil, spray, ergonomics, suppression) work on most primaries. The SMG-37 Defender gets damage and status effects only.

## Requirements

- [Arsenal / HD2MM] (https://www.nexusmods.com/helldivers2/mods/4664)
- [Bingus Shared Loader] (https://www.nexusmods.com/helldivers2/mods/16292)

## Installation

1. Remove any older "HD2 Enhanced Ammo" build.
2. Install the Bingus Shared Loader.
3. Install the mod zip from the Releases page with Arsenal / HD2MM.
4. Launch the game and open the ship Armory.

## Files

- Choices: `%LOCALAPPDATA%\CowboyBingus\Helldivers2\EnhancedAmmoVariants.txt`
  - `variant=assault_rifle:ap` (one per weapon; effects: `fire`, `stun`, `ap`, `subsonic`)
  - `auto=1` (1 = apply the choice of the equipped primary)
- Logs: `%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs\EnhancedAmmoEngine.log` and `EnhancedAmmoUi.log`

The file names keep the old `EnhancedAmmo` prefix so existing choices carry over.

## Reporting problems

Open an issue and attach the two log files, plus the weapon and ammo type you used. Removing the mod restores the game.

## Credits

Arsenal, HD2MM, Bingus Shared Loader, and the Armor Transmog approach. Can't express enought thanks to all of them.
