<img width="3308" height="1755" alt="HELLDIVERS AMMUNITION LOGO" src="https://github.com/user-attachments/assets/e0a73b66-cec7-4ab4-bac7-8627316319ab" />

**Version:** 2.0.1

Adds fifteen ammo type variants to the primary weapons and the secondaries. **Recommended to use in Private lobby.**


## How to use

There's a drop-up menu button to the left of the **Customization** button:

- Click the drop-up menu button to choose an ammo type. Click the active one again (or `OFF`) to clear it.
- Hover an ammo label to preview what it changes (green = better, red = worse).
- Types the weapon cannot take are dimmed.
- The choice is remembered per weapon and applied while that weapon is your equipped weapon.
- The traits box shows an `AMMO: X` line.

## Ammo types

| Ammo | Type | Effect |
|------|------|--------|
| AP | Armor Penetrating | Damage -10%, durable +25%, recoil +5%, projectile speed +25%, armor penetration +1 level (max AP3; not on Medium or Heavy weapons) |
| FIRE | Incendiary | Sets targets alight, fire rate -15%, ergonomics -5% |
| EM | Electromagnetic | Staggers targets, recoil +10%, spread +5%, durable -5% |
| SUB | Subsonic | Damage -15%, durable -5%, recoil -10%, spread -5%, projectile speed -25%, suppressed and quieter (not on explosive or already suppressed weapons) |
| HP | Hollow Point | Damage +25%, durable -20%, recoil +15% |
| GAS | Gas | Slows and blinds targets, damage -15%, ergonomics -15%, fire rate -20% |
| MAGNUM | Magnum | Damage +20%, recoil +25%, ergonomics -5%, fire rate -10% |
| OVERPRESSURE | Overpressure (+P) | Durable -10%, fire rate +10%, recoil +15%, ergonomics +5%, projectile speed +20% |
| URANIUM TIP | Uranium Tip | Armor penetration +1 level (max AP4; not on Heavy weapons), projectile speed +50%, durable +10%, fire rate -45% |
| MAGNETIZED | Magnetized | Spread -55%, durable +35%, fire rate -25% |

Explosive weapons (R-36 Eruptor, CB-9 Exploding Crossbow, GL-15 Evictor): Incendiary, Electromagnetic and Gas put their status effect on the explosion, not on the direct hit.

### Energy ammo (limits present)

| Ammo | Type | Effect for Plasma / Effect for Lasers |
|------|------|--------|
| NUCLEAR PLASMA | Nuclear Plasma | Damage +25%, recoil +15%, fire rate -15% / Damage +25%, heat gain +20% |
| COLD PLASMA | Cold Plasma | Damage -15%, recoil -10%, spread -10%, fire rate +10% / Damage -15%, heat gain -30%, cooling +15% |
| PULSED PLASMA | Pulsed Plasma | Fire rate +20%, recoil +10%, ergonomics -15% / not offered |
| TRITIUM PLASMA | Tritium Plasma | Armor penetration +1 level (max AP4), durable +20%, fire rate -40% / Armor penetration +1 level (max AP4), durable +20%, heat gain +25% |
| CONFINED PLASMA | Confined Plasma | Spread -45%, durable +35%, fire rate -25% / Durable +35%, heat gain +15% |

Weapons that cannot use the fire rate part:

- **PLAS-101 Purifier and PLAS-15 Loyalist:** their fire rate and charge-up are not changed (the charge-up sound has a fixed length). Aim sway takes the place of the fire rate (see below). Tritium also costs damage -10% and recoil +25%, and on the Purifier a minimum gap of about 0.6 s between shots (it slows tap fire only).
- **SG-8P Punisher Plasma:** its fire rate cannot be changed yet, so the cost is handling (recoil, ergonomics, sway). Pulsed Plasma is not offered.
- **LAS-5 Scythe and LAS-13 Trident:** no fire rate, so the cost is heat.
- **ARC-12 Blitzer:** the five types adapted to its arc (fire rate, arc spread and range). Its animation does not follow the fire rate.

Sway instead of fire rate (Purifier, Punisher Plasma, Loyalist), sway / scope sway:

| Ammo | Sway |
|------|------|
| NUCLEAR PLASMA | +20% / +10% |
| COLD PLASMA | -10% / -5% |
| PULSED PLASMA | -20% / -10% |
| TRITIUM PLASMA | +30% / +20% |
| CONFINED PLASMA | +20% / +10% |

### Secondaries

- **Standard ammo types:** P-2 Peacemaker, P-19 Redeemer, P-69 Veto, P-4 Senator, P-113 Verdict, P-92 Warrant and SG-22 Bushwhacker.
- **Energy ammo types:** LAS-58 Talon, LAS-7 Dagger (pays in heat) and PLAS-15 Loyalist.
- **Explosive launchers:** GP-31 Grenade Pistol and P-33 Missile Pistol. Incendiary, EM and Gas halve the direct hit (damage and durable damage -50%) and replace the explosion with a stock grenade explosion (G-13 incendiary, G-23 stun, G-4 gas), with that grenade's own size, damage and effect.
- **GP-20 Ultimatum:** the same, but with orbital explosions.

## ROADMAP

- Legendary warbonds Support (almost ready).
- More ammunition types.
- More secondaries (Breacher, Crisper, Re-Educator) if their data becomes reachable.
- Vehicle expansion: **Helldivers' Ammunition: Beasts of Steel** (standalone).

## Limits and not supported

- **Fire rate:** some weapons' fire rate is hard to pin down or does not exist (charge, beam and arc weapons). They get handling costs instead.
- **Animation and sound:** a changed fire rate does not change the weapon's animation or sound (for example the Blitzer cuts its animation short, the Purifier's charge-up sound stays the same length).
- **LAS-12 Sai with the Focus Lens:** the lens fixes the fire rate at 600 rpm and the ammo type cannot change it. The other changes still apply. The fire rate change works with the default lens.
- **Not changed:** P-34 Breacher, P-11 Stim Pistol, P-72 Crisper, P-35 Re-Educator, legendary warbond weapons and the LAS-22 Shear.

## Known issues

- Stalwart inherits Liberator family effects.
- Explosive launchers can be missing their blast effect without VFX Support (see Requirements).

## Info to know

- **Shared bullets:** some weapons share one bullet with others (for example the Liberator family), so an ammo type can also change those weapons. The log notes it.
- **Other mods that edit stats (SHODAN Stat Editor, HD2Runtime based mods):** the ammo effects are applied on top of the values found when you pick the type. A change another mod makes later is kept when an ammo type is removed, and the ammo type is applied again on top of it. Two mods editing the same stat still fight: use one of them for a given weapon. The logs say who was found (`compat.*` lines) and every value another mod changed (`drift` and `restore.foreign` lines).
- **The mod file is compressed.** The readable source is in this repository.

## Requirements

- [Arsenal](https://www.nexusmods.com/helldivers2/mods/4664)
- [Bingus Shared Loader](https://www.nexusmods.com/helldivers2/mods/16292)
- **Helldivers' Ammunition: VFX Support** (Release Page): the napalm, gas, EMS and stun blast effects for the explosive launchers. Without it those blasts can show no effect when the matching stratagems are not in your loadout.

## Installation

1. Remove any older "Helldivers' Ammunition" build.
2. Install the Bingus Shared Loader.
3. Install the mod zip (and VFX Support) from the Releases page with Arsenal.
4. Make sure Ammunition Mod is above VFX Mod. 
5. Launch the game and open the ship Arsenal.

## Files

- Choices: `%LOCALAPPDATA%\CowboyBingus\Helldivers2\EnhancedAmmoVariants.txt` (`variant=assault_rifle:ap`, one per weapon; `auto=1` applies the choice of the equipped weapon)
- Logs: `%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs\EnhancedAmmoEngine.log`, `EnhancedAmmoUi.log` and `EnhancedAmmoBoot.log`

The file names keep the old `EnhancedAmmo` prefix so existing choices carry over.

## Reporting problems

Open an issue and attach the log files, plus the weapon and ammo type you used. Removing the mod restores the game.

## Credits

Arsenal, SHODAN Stat Editor (research references), HD2Runtime (research references), Bingus Shared Loader, and the Armor Transmog (research references). Can't express enough thanks to all of them.

## License
MIT
