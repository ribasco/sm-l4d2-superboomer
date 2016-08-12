# Super Boomer

Make Boomer do a super charged rocket jump.  I got this inspiration from ztar's lethal weapon plugin. Credit goes to ztar for his particle code. Also added support for game instructor hints (code snippet was based from DJ_WEST's Witch Control Plugin)

## Features
- Super charged rocket jump
- NEW: Special Attack (When attack button is pressed, boomer descends faster)
- Particle Effects while charging and upon activation of the charge
- NEW: Boomer can move while puking

## Requirements
- This plugin requires SDKHooks v1.3 or above

## CVARS

### General
- sm_superboomer_version - Plugin Version
- sm_sb_debug (0 = Disable / 1 = Enable / 2 = Enable for Admins Only) - Enable/Disable Debug Mode.
- sm_sb_chargetime - Number of seconds to wait before activating (Max : 60s, Default values is 5 seconds)
- sm_sb_chargeexpire - Number of seconds before charge expires (Max: 60s, Default value is 1.5secs)
- sm_sb_effects (0 = Disable / 1 = Enable) - Enable/Disable Particle Effects (Depreceated)
- sm_sb_explode (0 = Disable / 1 = Enable) - Make boomer explode upon impact (Default is 0)
- sm_sb_gravity - The gravity to set for the jump boost (Default gravity is set to 0.06.)
- sm_sb_hint - (0 = Disable, 1 = Chat, 2 = Game Instructor Hint, 3 = Both) Set which type of hints should be displayed for users
- sm_sb_specialattack (0 = Disable / 1 = Enable) - Enable/Disable Speed Drop
- sm_sb_pukemove **NEW** (0 = Disable, 1 = Enable) - Allow boomer to move while puking

### CVARS for customizing Particle/Sound effects

> Warning: Do not bother modifying these cvars unless you want to customize you're own particle/sound effects. Some particles can be quite heavy and sometimes causes clients to crash.

- sm_sb_pathpe_charge - Path of particle effect for Boomer Charge
- sm_sb_pathpe_jump - Path of particle effect for Boomer Jump
- sm_sb_pathpe_land - Path of particle effect for Boomer Land
- sm_sb_pathse_charge - Path for sound effect when charging
- sm_sb_pathse_fail - Path for sound effect on charge fail
- sm_sb_pathse_jump - Path for sound effect on initial jump
- sm_sb_pathse_land - Path for sound effect on landing
- sm_sb_pathse_ready - Path for sound effect on charge readiness indication
- sm_sb_pathse_special - Path for sound effect on special attack ability
- sm_sb_pathse_warcry - Path for sound effect for WAR CRY


### CVARS For Enabling/Disabling Particle/Sound Effects

- sm_sb_pecharge - (0 = Disable, 1 = Enabled) Enable/Disable Particle Effects when Charging
- sm_sb_pejump - (0 = Disable, 1 = Enabled) Enable/Disable Particle Effects when Jumping
- sm_sb_peland - (0 = Disable, 1 = Enabled) Enable/Disable Particle Effects when Landing
- sm_sb_secharge - (0 = Disable, 1 = Enabled) Enable/Disable Sound Effects when Charging
- sm_sb_sefail - (0 = Disable, 1 = Enabled) Enable/Disable Sound Effects after a failed charged attempt
- sm_sb_sejump - (0 = Disable, 1 = Enabled) Enable/Disable Sound Effects when Jumping
- sm_sb_seland - (0 = Disable, 1 = Enabled) Enable/Disable Sound Effects when Landing
- sm_sb_sespecatk - (0 = Disable, 1 = Enabled) Enable/Disable Sound Effects for Special Speed Attack Ability
- sm_sb_sewarcry - (0 = Disable, 1 = Enabled) Enable/Disable Sound Effects for War Cry (Occurs during the jump)


## How to Use
- Crouch for N seconds (this is defined by the cvar) then jump upon activation. Proper timing of the jump is crucial to make a successful super rocket jump.
- To make boomer rocket jump to the desired direction, just hold down the DIRECTIONAL KEYS (W-A-S-D) prior to the jumping.
- While on mid-air, press the ATTACK (By default, that is your left mouse button) key to descend faster to the ground
- If any of you are curious on what to put on the particle effects cvars, I will try to compile a list of all particle effects in Left 4 Dead 2...but for the meantime, you can use the particle browser through the "Left 4 Dead 2 (Tools Mode)" under "Left 4 Dead 2 Authoring Tools". Just take note that you will need the Authoring tools installed for you to access the particle browser.


## DEMO Video (thanks blackalegator)
http://www.youtube.com/watch?v=12v_nHkcZT4