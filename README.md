# Helldivers' Ammunition
**Version:** 0.8.0B (public beta)

Adds four ammo type variants to the primary weapons. **Recommended to use in Private lobby.**

## How to use

There are five chips added left to the **Customization** button:

`OFF` `FIRE` `EM` `AP` `SUB`

- Click a chip to give that weapon the ammo type. Click it again (or `OFF`) to clear it.
- Hover a chip to preview what it changes (green = better, red = worse).
- Chips the weapon cannot take are dimmed.
- The choice is remembered per weapon and applied while that weapon is your equipped primary.
- The traits box shows an `AMMO: X` line.

## Ammo types

| Chip | Ammo | Effect |
|------|------|--------|
| AP | Armor Penetrating | Damage -10%, durable -15%, recoil +5%, armor penetration +1 level (max AP3; not on Medium/Heavy weapons) |
| FIRE | Incendiary | Sets targets alight, fire rate -15%, ergonomics -5% |
| EM | Electromagnetic | Staggers targets, recoil +10%, spray +5%, durable -15% |
| SUB | Subsonic | Damage -15%, durable -5%, recoil -10%, spray -5%, suppressed and quieter (not on explosive or already suppressed weapons) |

## Not supported yet

- Legendary warbond weapons and energy weapons (lasers, plasma, arc): no ammo chips.
- 20 primaries share weapon data with other weapons (Stalwart, Liberator Penetrator, Liberator Concussive, One-Two, Arbitrator, Breaker Spray&Pray, SG-8F, Slugger, Halt, Diligence, Diligence Counter Sniper, Defender, Pummeler, VG-70, CB-9, Eruptor and others). They get damage, armor penetration and fire rate changes only: no recoil/spray/ergonomics changes and no Subsonic. Full support is planned.
- Fire rate is applied to 40 primaries; the rest get the other FIRE effects only.

## Requirements

- [Arsenal / HD2MM] (https://www.nexusmods.com/helldivers2/mods/4664)
- [Bingus Shared Loader] (https://www.nexusmods.com/helldivers2/mods/16292)

## Installation

1. Remove any older "HD2 Enhanced Ammo" build and any scan/test mods.
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
