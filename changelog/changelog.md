# Changelog & Unreleased branch Log

All notable changes to the BattleScribe Data Repository will be documented in this file.

---

## [Unreleased] - Current branch

### Added
- **Units**:
  - `[Legiones Astartes]` Added `[Storm Eagle Transporter]` - `[Fast Attack]`
  - `[Legiones Astartes]` Added `[Mutated Spawn]` - `[Fast Attack]` (Traitor only)
  - `[Legiones Astartes]` Added `[Hussar Squadron]` - `[Troops]`
  - `[Legiones Astartes]` Added `[Sky-Seeker Squadron]` - `[Troops]`
  - `[Legiones Astartes]` Added `[Assault Support Squad]` - `[Troops]`
  - `[Legiones Astartes]` Added `[Novicii Squad]` - `[Troops]`
  - `[Legiones Astartes]` Added `[Rhino Advancer]` - `[Dedicated Transport]` (wherever a Rhino Transport can be taken)
  - `[Legiones Astartes]` Added `[Whispercutter]` - `[Dedicated Transport]` (Skirmish infantry squads of 5)
  - `[Legiones Astartes]` Added `[Praetor, Indomitus]` - `[HQ]`
  - `[Legiones Astartes]` Added `[Centurion, Indomitus]` - `[HQ]`
  - `[Legiones Astartes]` Added `[Centurion, Saturnine]` - `[HQ]`
  - `[Legiones Astartes]` Added `[Command Squad, Indomitus]` - `[HQ Retinue]`
  - `[Legiones Astartes]` Added `[Centurion, Contemptor]` - `[HQ]`
  - `[Legiones Astartes]` Added `[Centurion, Castra Ferrum]` - `[HQ]`
  - `[Legiones Astartes]` Added `[Land Raider Dionysus]` - `[HQ]`
  - `[Legiones Astartes]` Added `[Land Raider Tartaros]` - `[HQ / Dedicated Transport]`
  - `[Legiones Astartes]` Added `[Terminator Saturnine Squad]` - `[Elites]`
  - `[Legiones Astartes]` Added `[Assault Veteran Squad]` - `[Elites]`
  - `[Legiones Astartes]` Added `[Contemptor-Cortus Dreadnought Talon]` - `[Elites]`
  - `[Legiones Astartes]` Added `[Possessed Legionnaires]` - `[Elites]` (Traitor only)
  - `[Legiones Astartes]` Added `[Servo-Automata Maniple]` - `[Techmarine Covenant Retinue]`
- **Weapons & Wargear**:
  - `[Mutated Appendages]`, `[Gravis Heavy Flamer]`, `[EM-Storm Charge]`, `[Phosphex Cluster Bombs]`
  - `[Drop Capsules]`, `[Forward Deployment]`, `[Concealed Positions]`, `[Battle Servitor Control]`, `[Hyperios Command Platform]`
  - `[Grenade Launcher (Charges)]`, `[Twin-linked Rotor Cannon]`, `[Estoc Jetbike]`, `[Oracle Array]`
  - `[Saturnine Terminator Armour]`
  - `[Gravis Force Weapon]`, `[Gravis Siege Drill]`, `[Seismic Hammer]`
  - `[Aspectum-Pattern Occularis Array]`, `[Atomantic Dispersion Shield]`, `[Full-Spectra Comms Array]`, `[Signum-Primus]`
  - `[Toxiferno Cannon]`, `[Rad-Fragmentation Charge Launcher]`, `[Twisted Talons]`, `[Charnabal Longsword]`, `[Atomantic Repulsor]`
- **Rules & Abilities**:
  - Added special rules `[Combat Transporter]`, `[Dreadnought Magna-Grapples]`, `[Mindless Aggression]`, `[Neverborn]`
  - Added special rules `[Transport Skiff]`, `[Whispercutter]`
  - Added special rules `[Pater Consularis]`, `[Vox Override]`, `[Automata Attendants]`, `[Reactor Overcharge]`, `[Synthetica Mindlock]`, `[Unstable Internment]`
  - Added `Pater Consularis` upgrades: Librarian, Master of Signals, Forge Lord, Siege Breaker, Chaplain, Armistos, Herald
  - Added Warlord Trait `[Fist of the Legion]` (Land Raider Dionysus)

### Changed
- **Units / Points**:
  - `[Spatha Attack Bike Squadron]`: Added Volkite Culverin, Nuncio-Vox and an optional Attack Bike Sergeant
  - `[Primaris-Lightning Strike Fighter]`: Added Multi-Lasers, EM-Storm Charges, Reaper Autocannons, Cyclone Missile Launcher, Phosphex Cluster Bombs (with a Siege Breaker), Hull Predator Cannon and Battle Servitor Control
  - `[Tarantula Sentry Gun Battery]`: Added six new weapon variants, deployment options and the Hyperios Command Platform
  - `[Javelin Squadron]`, `[Proteus Land Speeder Squadron]`: one model may take a Legion Vexilla
  - `[Terminator Indomitus Squad]`: Added Plasma Blaster / Plasma Cannon (shared 1 per 5 heavy allowance), Havoc Launcher (1 per 5), Volkite Charger and Lightning Claw options
  - `Consul`: `Legiones Consularis` options other than Forge Lord, Siege Breaker and Mortificator are hidden for `[Centurion, Saturnine]`
  - `[Praetor, Cataphractii]`, `[Praetor, Tartaros]`: Master-crafted (+10) now available to all legions
  - `[Command Squad]`, `[Command Squad, Cataphractii/Tartaros/Indomitus]`: may take `[Land Raider Tartaros]` as Dedicated Transport
  - `[Master of Armour]`: not required under Armoured Spearhead when a `[Land Raider Dionysus]` is taken
  - `[Cassian Dracos]`: Warlord restriction now also covers the new Indomitus/Saturnine HQs and both new Land Raiders
  - Siege Breaker name conditions also accept the Pater Consularis Siege Breaker
  - `[Castra Ferrum Dreadnought Talon]`: Added Frag Launchers, Volkite Culverin / Gravis Siege Drill / Seismic Hammer swaps, in-built Plasma Blaster / Graviton Gun and Hunter-Killer Missiles
  - `[Techmarine Covenant]`: may take up to 3 `[Servo-Automata Maniple]` as Retinue (one per Techmarine)
  - `[Charnabal Weapon]`: Added `[Charnabal Longsword]`
- **Weapons & Profiles**:
  - `[Gravis Missile Launcher]`: Added `Rad` profile (hidden for now)

### Fixed
- **BattleScribe Structure**:
  - `[Iron Warriors]`: Restored the `Rite of War` selection, which was accidentally removed with the Dominator Tartaros Cohort update

## Release Archive
## [2026-08-29]

### Added
- **Units**:
  - `[Mechanicum]` Added `[Ironstrider Ballistarii]` - `[Heavy Support]`

### Fixed
- **Units / Points**:
  - `[Archmagos Anacharis Scoria]`: Added `Orders of the High/Proscribed Techno Arcana` as Scoria is an Archmagos and they should have this
  - `[Thanat Calix]`: Made `Shock charger` mandatory

## [2026-08-27]

### Added
- **Units**:
  - `[Death Guard]` Added `[Death Shroud Cataphractii Squad]` - `[Elite]`
  - `[Death Guard]` Added `[Grave Warden Tartaros Squad]` - `[Elite]`
  - `[Iron Warriors]` Added `[Barbas Dantioch]` - `[HQ]`
  - `[Iron Warriors]` Added `[Volk-Sa'ra'ram]` - `[HQ]`
  - `[Iron Warriors]` Added `[Barban Falk]` - `[HQ]`
  - `[Iron Warriors]` Added `[Warsmith Berossus]` - `[HQ]`
  - `[Iron Warriors]` Added `[Berossus, Interred]` - `[HQ]`
  - `[Iron Warriors]` Added `[Warsmith Toramino]` - `[HQ]`
  - `[Iron Warriors]` Added `[Dominator Tartaros Cohort]` - `[Elite]`
  - `[Iron Warriors]` Added `[Rhino Castellan]` - `[Dedicated Transport]`

### Changed
- **Units / Points**:
  - `Consul`: Added new `[Death Guard]` consularis option: `[Alchymus]`
- **Weapons & Profiles**:
  - `Rite of War`: Added new `[Iron Warriors]` rite of war: `[The Iron Without]`
  - `Shrapnel Weapons`: Added `[Twin-Linked Shrapnel Cannon]` for `[Iron Warriors]`
  - `Shrapnel Weapons`: Added `[Gravis Shrapnel Cannon Battery]` for `[Iron Warriors]`

### Fixed
- **BattleScribe Structure**:
  - `Centurion: Rite of War` no longer shows up in crusade detachments and is only mandatory in Centurion detachments
- **Weapons & Profiles**:
  - `Dominator Cohort` : Added missing Terminator Armour
---


### [2026-08-22]

### Added
- **Units**:
  - `[Mechanicum]` Added `[Kataphron Destructor]` - `[Elite]`
  - `[Mechanicum]` Added `[Triaros destructor]` - `[Elite]`
  - `[Mechanicum]` Added `[Sarumiat Maniple]` - `[Elite]`
- **Weapons & Wargear**:
  - `[Sarumiat Cleaver-Blades]` - Equippable by `[Sarumiat]`
  - `[Electrocoil Harpoon]` - Equippable by `[Sarumiat]`
  - `[Arc Claw]` - Equippable by `[Kataphron Destructor]`
  - `[Phospor Repeater]` - Equippable by `[Kataphron Destructor]`
  - `[Sulphur Ejector]` - Equippable by `[Kataphron Destructor]`
  - `[Plasma Culverin]` - Equippable by `[Kataphron Destructor]`
  - `[Erradication Beamer]` - Equippable by `[Kataphron Destructor]`
- **Rules & Abilities**:
  - Added Centurion detachments
    - Still WIP, just text not rules

### Changed
- **Weapons & Wargear**:
  - Fixed strength of `[Gravis Lascannon]`: 10 -> 9
  - Fixed AP of `[Hydraulic claw - Iron Grasp]` : - -> 2


### [1.0.0] - 2026-03-26
- Initial release

### Changed
- **Units**:
  - All units from panoptica
- **Weapons & Wargear**:
  - All weapons and wargear from panoptica
- **Rules & Abilities**:
  - All Rules and abilities from panoptica
- **TODO: 
  - Alternate game modes
  - Some exotic weapons