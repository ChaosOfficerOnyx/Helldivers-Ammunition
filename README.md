# Helldivers' Ammunition
**Version:** 1.5.2B (public beta)

Adds fifteen ammo type variants to the primary weapons. **Recommended to use in Private lobby.**

## How to use

There's a drop-up menu button to the left of the **Customization** button:

- Click the drop-up menu button to choose an ammo type. Click the active one again (or `OFF`) to clear it.
- Hover an ammo label to preview what it changes (green = better, red = worse).
- Types the weapon cannot take are dimmed.
- The choice is remembered per weapon and applied while that weapon is your equipped primary.
- The traits box shows an `AMMO: X` line.

## Ammo types

| Ammo | Type | Effect |
|------|------|--------|
| AP | Armor Penetrating | Damage -10%, durable +25%, recoil +5%, projectile speed +25%, armor penetration +1 level (max AP3; not on Medium weapons) |
| FIRE | Incendiary | Sets targets alight, fire rate -15%, ergonomics -5% |
| EM | Electromagnetic | Staggers targets, recoil +10%, spread +5%, durable -5% |
| SUB | Subsonic | Damage -15%, durable -5%, recoil -10%, spread -5%, projectile speed -25%, suppressed and quieter (not on explosive or already suppressed weapons) |
| HP | Hollow Point | Damage +25%, durable -20%, recoil +15% |
| GAS | Gas | Slows and blinds targets, damage -15%, ergonomics -15%, fire rate -20% |
| MAGNUM | Magnum | Damage +20%, recoil +25%, ergonomics -5%, fire rate -10% |
| OVERPRESSURE | Overpressure (+P) | Durable -10%, fire rate +10%, recoil +15%, ergonomics -5%, projectile speed +20% |
| URANIUM TIP | Uranium Tip | Armor penetration +1 level (max AP4; not on Heavy weapons), projectile speed +50%, durable +10%, fire rate -45% |
| MAGNETIZED | Magnetized | Spread -55%, durable +35%, fire rate -25% |

| Ammo | Type | Effect for Plasma / Effect for Lasers |
|------|------|--------|
| NUCLEAR PLASMA | Nuclear Plasma | Damage +25%, recoil +15%, fire rate -15% / Damage +25%, heat gain +20% |
| COLD PLASMA | Cold Plasma | Damage -15%, recoil -10%, spread -10%, fire rate +10% / Damage -15%, heat gain -30%, cooling +15% |
| PULSED PLASMA | Pulsed Plasma | Fire rate +20%, recoil +10%, ergonomics -15% / — |
| TRITIUM PLASMA | Tritium Plasma | Armor penetration +1 level (max AP4), durable +20%, fire rate -40% / Armor penetration +1 level (max AP4), durable +20%, heat gain +25% |
| CONFINED PLASMA | Confined Plasma | Spread -45%, durable +35%, fire rate -25% / Durable +35%, heat gain +15% |

## ROADMAP

- Add support for Secondaries
- Add support for ARC-12 Blitzer
- Vehicle Expansion (submod)

## Not supported yet

- Legendary warbond weapons and one energy weapon (arc).

## Known issues

- Stalwart inherits Liberator family effects.
- Sai ammo does not change the fire rate when the Focus Lens is fitted.

## Info to know

- **Shared bullets:** some weapons share one bullet with others (for example the Liberator family), so an ammo type can also change those weapons. The log notes it.

## Requirements

- [Arsenal](https://www.nexusmods.com/helldivers2/mods/4664)
- [Bingus Shared Loader](https://www.nexusmods.com/helldivers2/mods/16292)

## Installation

1. Remove any older "Helldivers' Ammunition" build.
2. Install the Bingus Shared Loader.
3. Install the mod zip from the Releases page with Arsenal / HD2MM.
4. Launch the game and open the ship Armory.

## Files

- Logs: `%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs\EnhancedAmmoEngine.log` and `EnhancedAmmoUi.log`

The file names keep the old `EnhancedAmmo` prefix so existing choices carry over.

## Reporting problems

Open an issue and attach the two log files, plus the weapon and ammo type you used. Removing the mod restores the game.

## Credits

Arsenal, SHODAN Stat Editor (research references), HD2Runtime (research references), Bingus Shared Loader, and the Armor Transmog (research references). Can't express enough thanks to all of them.

## License
MIT
