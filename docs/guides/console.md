## In-Game Console

The in-game console offers extra tools for advanced users, including adjusting player equipment, reassigning config variables, entering cheats, and running scripts. Feedback from the console is currently limited, but command entry is fully supported.

### Commands

#### Player
- `player.set_health <health>`
- `player.set_armor <armor_points> [armor_type]`
  - `armor_type` defaults to the current type
- `player.give_weapon <weapon>`
- `player.give_ammo <ammo_type> [ammo_amount]`
  - `ammo_amount` defaults to the maximum
- `player.set_ammo <ammo_type> <ammo_amount>`
- `player.give_key <key>`
- `player.remove_key <key>`
- `player.give_power <power> <duration>`
- `player.remove_power <power>`
- `player.set_x <coordinate>`
- `player.set_y <coordinate>`
- `player.set_z <coordinate>`
- `player.round_x`
- `player.round_y`
- `player.round_xy`

#### Miscellaneous
- `script.run <script>`
- `check <attribute>`
  - prints config attribute info to the terminal
- `assign <attribute> <value>`
  - temporarily assigns a config value (will not be saved to config file)
- `update <attribute> <value>`
  - permanently updates a config value (will be saved to config file)
- `toggle_assign <attribute>`
  - temporarily toggles a config value (will not be saved to config file)
- `toggle_update <attribute>`
  - permanently toggles a config value (will be saved to config file)
- `exit`
- `quit`

#### Tracking
- `tracker.add_line / t.al <line_id>`
- `tracker.remove_line / t.rl <line_id>`
- `tracker.add_line_distance / t.ald <line_id>`
- `tracker.remove_line_distance / t.rld <line_id>`
- `tracker.add_sector / t.as <sector_id>`
- `tracker.remove_sector / t.rs <sector_id>`
- `tracker.add_mobj / t.am <mobj_id>`
- `tracker.remove_mobj / t.rm <mobj_id>`
- `tracker.add_player / t.ap`
- `tracker.remove_player / t.rp`
- `tracker.reset / t.r`

#### Thing Manipulation
- `target.spawn`
  - set the target thing to its spawn state
- `target.see`
  - set the target thing to its see state
- `target.pain`
  - set the target thing to its pain state
- `target.melee`
  - set the target thing to its melee state
- `target.missile`
  - set the target thing to its missile state
- `target.death`
  - set the target thing to its death state
- `target.xdeath`
  - set the target thing to its xdeath state
- `target.raise`
  - set the target thing to its raise state
- `target.set_state <state_num>`
  - set the target thing to the given state
- `target.set_health <health>`
  - set the target thing's health
- `target.move <x> <y>`
  - move the target to the given coordinates
- `mobj.* <mobj_index> [other args]`
  - same as the above commands, but applied to a specific mobj index
- `spawn <x> <y> <z> <type>`
  - spawns a mobj at the given location, with the given type

#### Demo Tools
- `jump.to_tic <tic>`
- `jump.by_tic <tic_count>`
- `demo.export <name>`
- `demo.start <name>`
- `demo.stop`

#### Build Mode
See the [build mode guide](./build_mode.md) for more info.
- `brute_force.start / bf.start <depth> <forwardmove_range> <sidemove_range> <angleturn_range> <conditions>`
- `build.turbo / b.turbo`
- `mf <value>`
- `mb <value>`
- `sr <value>`
- `sl <value>`
- `tr <value>`
- `tl <value>`
- `fu <value>`
- `fd <value>`
- `fc`
- `lu <value>`
- `ld <value>`
- `lc`
- `ua <value>`

#### Cheats
- `idchoppers`
- `iddqd`
- `idkfa`
- `idfa`
- `idspispopd`
- `idclip`
- `idmypos`
- `idrate`
- `iddt`
- `iddst`
- `iddkt`
- `iddit`
- `idclev <map>`
- `idmus <map>`
- `tntcomp`
- `tntem`
- `tnthom`
- `tntka`
- `tntsmart`
- `tntpitch`
- `tntfast`
- `tntice`
- `tntpush`
- `notarget`
- `fly`
- `fullclip`
- `freeze`
- `nosleep`
- `quicken`
- `ponce`
- `kitty`
- `massacre`
- `rambo`
- `skel`
- `shazam`
- `ravmap`
- `cockadoodledoo`
- `gimme <artifact>`
- `engage <map>`
- `satan`
- `clubmed`
- `butcher`
- `nra`
- `indiana`
- `locksmith`
- `sherlock`
- `casper`
- `init`
- `mapsco`
- `deliverance`
- `shadowcaster <class>`
- `visit <map>`
- `puke <script>`