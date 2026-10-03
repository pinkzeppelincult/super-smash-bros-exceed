# Changelog

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

#### Change

- Fox: Update to v0.17.0.

## [0.7.0] - 2026-10-03

### Changed

- **Kirby:**
  - **Updated to v0.13.0:**
    - Adjustments to reduce noncommittal movement and improve defensive options.
  - **Burning:**
    - Power 3 → 1.
    - Guard 4 → 5.
    - "Before: Close 2. **+2 Power** for each space you couldn't Close." → "Before: Close 2. **+3 Power** for each space you couldn't Close."
  - **Inhale:**
    - Added "After: If this did not hit, Pull 1."
  - **Final Cutter:**
    - New art.
    - Reworked into a Special.

      > Final Cutter (2G)
      >
      > 1-3/3/2/1/4
      >
      > Attacks at Range 4+ do not hit you.
      >
      > Before: If the opponent is at Range 1 or 2, +2 Power. Then, Advance up to 2.

      →

      > Final Cutter
      >
      > 1-2/2/5/-/3
      >
      > Attacks at Range 5+ do not hit you.
      >
      > Before: If the opponent is at Range 1–2, +2 Power. Then, Advance up to 2.
  - **Stone Smash:**
    - Power 5 → 6.
  - **Float:**
    - Moved from Air Drop → Back Kick.
  - **Oblivious:**
    - Moved from Back Kick → Final Cutter.
  - **Snack Time:**
    - Moved from Burning → Air Drop.
  - **Juggle:**
    - Removed.
  - **Star Warrior:**
    - New boost for Burning.

      > Star Warrior (0F)
      >
      > +1 Power and +1 Speed
      >
      > Now: If you are in Exceed Mode, Strike.
  - **Grasp:**
    - New art.
  - **Assault:**
    - New art.

## [0.6.0] - 2026-10-02

### Changed

- **Kirby:**
  - **Updated to v0.12.0:**
    - Revamped boost kit to discourage early rushdown gameplan.
  - **Character Ability:**
    - Exceed Cost 3 → 4.
    - Added "When you Exceed, Draw 2."
  - **Back Kick:**
    - Power 2 → 3.
  - **Final Cutter:**
    - Armor 0 → 1.
    - Guard 5 → 4.
  - **Stone Smash:**
    - Range 1 → 1–2.
    - Power 6 → 5.
    - Armor 2 → 3.
    - "Before: Close 1." → "After: Lose all Armor."
  - **Shorthop:** 
    - Removed.
  - **Juggle (Old):**
    - Removed.
  - **Float:**
    - Moved from Burning → Air Drop.
  - **Shield Stop:**
    - 1F → 0F.
    - +2 Armor → +1 Armor and +3 Guard.
    - "Now: Close 2" → "Now: Spend up to 2 Force to Close that many spaces."
  - **Star Warrior:**
    - Removed.
  - **Oblivious:**
    - New boost for Back Kick.

      > Oblivious (1F)
      >
      > Stun Immunity.
      >
      > Now: You may discard a Continuous Boost from play.
  - **Snack Time:**
    - New boost for Burning.

      > Snack Time (0F)
      >
      > Now: Draw 2.
      >
      > Before: If you were hit, add this to your Gauge.
  - **Juggle (New):**
    - New boost for Final Cutter.

      > Juggle (0F)
      >
      > Now: If you are in Exceed Mode, Strike.
      >
      > Hit: Push, Pull, Advance, or Retreat 1. Gain Advantage.

## [0.5.0] - 2026-09-28

### Changed

- **Kirby:**
  - **Updated to v0.11.0:**
    - Balance and flavor adjustments.
  - **Back Kick:**
    - Power 3 → 2.
    - "Hit: Pull up to 2" → "Charge 1, Hit: Gain Advantage."
  - **Inhale:**
    - Range 1–3 → 1–2.
  - **Final Cutter:**
    - Range 1–4 → 1–3.
  - **Hammer Flip:**
    - "Ignore Armor" → "Charge 1, Hit: Ignore Armor."
  - **Shorthop:**
    - "Now Advance up to 1" → "Now: Advance or Retreat up to 1."
  - **Tilt Attack:**
    - Removed.
  - **Juggle:**
    - Inhale → Back Kick.
  - **Shield Stop:**
    - New Boost for Inhale.

      > Shield Stop (1F)
      > +2 Armor
      > Now: Close 2.
  - **Jump In:**
    - Renamed to Star Warrior.
    - "Advance 1. Draw 3." → "Draw 3. Strike."

## [0.4.0] - 2026-09-26

### Changed

- **Kirby:** 
  - **Updated to v0.10.0:**
    - Tweaks to increase reward for using UA.
  - **Character Abiilty:**
    - Bonus power now triggers even if the opponent is pushed exactly to the edge of the arena.
  - **Burning:**
    - Speed 2 → 3.
    - Retouched art to better match other cards.
  - **Inhale:**
    - Hit effect now Pushes/Pulls to Range 3 rather than 1 or 2 spaces.
  - **Hammer Flip:**
    - New art.
  - **Ultra Sword:**
    - Speed 5 → 4.
    - New art.
  - **Spike:**
    - New art.
  - **Cardback:**
    - Fixed outdated color scheme.

## [0.3.0] - 2026-09-21

### Changed

- **Kirby:**
  - **Updated to v0.9.0:**
    - Substantial overhaul to go all-in on corner carry gameplan.
    - Replaced placeholder art.
- **General:**
  - Reorganized archive directories by version for better clarity and maintainability.

## [0.2.0] - 2026-09-19

### Changed

- **Kirby:**
  - **Updated to v0.8.0:**
    - Several changes mostly aimed at giving him a more real advantage state.
  - **Character Ability:**
    - No longer restricted to Initiate.
  - **Air Drop:**
    - Added "Hit: Draw 1. Push 2, then Close up to 2."
  - **Stone Smash:**
    - Added "You cannot be Pushed or Pulled."
  - **Insatiable:**
    - Renamed to Jump In.
    - +2 Power → +1 Power.
    - 1F → 0F.
  - **Juggle:**
    - Renamed to Insatiable.
  - **Copy Ability:**
    - Targets opponent's hand rather than discard pile.
    - No longer restricted to Specials and Ultras.
    - No longer grants +1 Power.
  - **Squish Down:**
    - Gauges itself at end of next turn rather than on After.
- **General:**
  - Reorganized archive directories for better clarity and maintainability.

## [0.1.1] - 2026-09-18

### Removed

- Extraneous Jigglypuff costume images.

## [0.1.0] - 2026-09-17

### Added

- Kirby v0.7.0.
- Jigglypuff v0.7.1.

### Changed

- **General:**
  - Reorganized project files for better clarity and maintainability.
  - Rearranged Character Status table in readme.
