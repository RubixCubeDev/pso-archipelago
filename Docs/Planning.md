# Planning
 
### What this document is:

This is intended as a general planning document for the apworld
for PSO I&II Plus for GameCube. This will have general project
planning and structure information and ideally people who can be
reached about different aspects of the project. This is a living
document, aka it's probably going to change a lot. If you're
someone working on this project, feel free to change things as
you see fit – with respect to the contributions of others.

### What this document isn't:

This is not an exhaustive list of features or a timeline in
which to get them done. It is not a promise or a guarantee that
anything or everything will be possible. It's not an avenue to
gatekeep or prevent people from sharing ideas, however it does
still need to stay clean and maintainable. This document will
not be perfect.

### Bottom Line:

If we're working on this APWorld, it's because we care about
this game and want to enjoy it in fun, new ways. If you'd like
to contribute, please reach out in the [Phantasy Star Online](https://discord.com/channels/731205301247803413/1250009220707909642)
thread in the `#future-game-design` channel in the Archipelago
discord service.

---

# Features

### Current Features (0.0.0)

- Nothing, yet!

### Planned Features

- Getting a functional APWorld to start development from
- Episode 1 Support

### Brainstorming

#### Completion Goals

- Dark Falz
  - Reach Dark Falz by whatever means are available in the
  current settings and defeat both forms (Normal mode)
- Olga Flow
  - Same as Dark Falz, but Episode 2
- Quest Completion
  - Clear a certain number of Hunter's Guild quest
- Complete Collection
  - Something similar to a Triforce Hunt where certain unique / 
  rare items have to be obtained

#### Location Randomization

- Pillars (Forest, Caves, Mines)
- Level-ups send checks / can receive levels / XP
  - This would need to be balanced with XP boosts
- Clearing a room (door unlock) could send a check
  - Presumably this would only send checks and would not be
  a location to be unlocked (otherwise progression would get
  unpleasantly grindy)
  - Possibility to have door switches / lasers as locations
  however (for the truly insane)
- Quest-sanity
  - Location for offline quest completion
  - Option to have quests unlock on checks, either individually
  or in groups (like vanilla)
  - Would quests potentially have their own randomized loot pool?
- Rico-sanity
  - Each capsule from Red Ring Rico would reward a check
- Crate-sanity
  - Either maps locked to specific variations at generation time
  or multiple / all variants are available and have unique
  locations associated with them
- Trap-sanity
  - Triggering traps (either by shooting or walking into them)
  would trigger a check
- Enemy-sanity
  - First kill of an enemy / enemy type rewards a check
  - Enemies have a "rare item" that drops a check
    - This would need to have some sort of bad-luck protection
    or at least something to make it equivalent to looking for
    a 1% Pokémon (since people do that)
- Souls
  - NPCs, Enemies, Bosses, etc. could be locked behind checks

#### Item Randomization

- Stages as Progression Items (Forest 1, Forest 2, etc.)
- Pillars as Progression Items
  - Possibly including door between Vol Opt & Ruins 1 as a check
  depending on how its coded
- Ability Unlocks
  - Hard / Special Attack
  - Techniques
    - Possibily allow previously illegal techs? (e.g. Megid
    on non-Force)
    - All levels, individual levels, or level groups?
  - Traps
  - Feeding Mag
  - Combo Attacks
- Equip Unlocks
  - Weapon Types
    - Players would start with 1 category unlocked
    - Possibility to allow normally illegal weapons? (e.g.
    Rifle on non-ranger)
    - This would also need to affect drop pool
  - Armor Slots
    - Unsure if we would force armor to drop with specific slots
    or if we can unlock armor slots regardless of equipped armor
  - Mag Equip
- Boosts
  - It would be useful to provide multipliers of some kind
  for various things players earn to better scale the game
  especially for higher difficulties. These could be in the
  YAML and / or as checks received during a run.
  - XP
  - Meseta
  - Rare Item drop rate
  - Mag stat growth rate
  - Attack speed
  - Tech cast speed
  - Tech damage
  - Trap damage?
  - Tech level boost (e.g. God\Technique)
  - Movement speed
  - Other things that would previously be armor slots (e.g. 
  Cure mods)

#### Misc

- Filler checks
  - This would presumably come from the standard drop table
  for an area, however it would probably be good to mix
  standard box and special (weapon/armor) box loot
  - This matters more when things like weapon unlocks,
  crates, and / or enemies are randomized since the player
  will have fewer opportunities to find them 
- Handling items beyond what can fit in your inventory / bank
  - Can we expand player inventory / bank space?
- Receiving Traps
  - Either applying negative status effects or spawning a trap
  on the player's location
- Death Link
  - Initially, this might just be setting HP to 0
  - Might be interesting to have Megid as an option
    - There was previously a discussion as to whether avoiding
    a death link was allowed in Archipelago – I believe some
    games provide "only die on X number of received deaths"
    as well as some games provide other ways of handling deaths
    e.g. Candle extinguish in Inscryption so Megid feels fine
    and in-universe
- Support for Episode 2
- Support for more than Normal Mode
  - Possibly Normal -> Hard -> V. Hard. etc.
  if people want a really long game (with sufficient warnings
  when setting their options)
  - Alternatively, players could choose to start their run
  at a different difficulty, but we'd have to make specific 
  considerations for what "starting equipment" would look like
  at that level. (Low Priority)

---

### Contributors 
kayak7435, rubix47, themogul