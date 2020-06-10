# EXPLANATION FOR THE CONFIG
All of these files should be directly extracted into **Steam\steamapps\common\Team Fortress 2\tf\custom\cfg\cfg**.

If you do not have any of the folders in that directory, you should create them.

The explanation for each of the individual configuration files is as follows:

### configs/ammo_binds.cfg
This file contains binds that are used in order to have infinite ammo in *sv_cheats 1*.

### configs/class_switch_binds.cfg
This file contains binds that are used in order to switch between different classes using the keypad.

### configs/crosshair_binds.cfg
This file contains binds that are triggered when the user press a key from 1-3. It changes your crosshair when you press different keys.
This file also controls the viewmodels, which are in *minmode 1* and *fov 70*.

### configs/crosshair_binds_jump.cfg
This file is identical to the previous file, with the only difference being that when you press the key *1*, your viewmodel switches to *minmode 0* and *fov 90*, and when you press either 2 or 3, it defaults back to *minmode 1* and *fov 70*

### configs/damage_number_settings.cfg
This file configures damage number indicators to be big and yellow, just like b4nny's.

### configs/default_binds.cfg
This file contains all of the binds that I use in game for movement. It is used across every single class file (explained later).

### configs/hitsound_settings.cfg
This file configures hitsounds so that they are identical to b4nny's pitch.

### configs/jump_binds.cfg
This file contains binds that are relevant to jump servers.

### configs/mouse_settings.cfg
This file contains my personal sensitivity and *raw_input* settings.

### configs/net_settings.cfg
This file contains my personal *net_settings*.

### configs/no_ragdolls.cfg
This file contains certain commands that will disable in-game ragdolls.

### configs/server_settings.cfg
This is an old file I have saved. It currently serves no purpose.

### configs/sound_settings.cfg
This file contains in-game volume and other related variables.

### configs/video_settings.cfg
This file contains my in-game visual settings. They are set to medium-low.

### autoexec.cfg
Crucial file. This file is executed when the game is launched an sets up all the aliases for the files in the configs folder, and executes some of them.

The next few class files are configuration files that are executed whenever a player enters the corresponding class.

For example, if I switch to medic, **medic.cfg** will be executed.

The autoexec file also adds a few aliases in console:
- "rj" in console, **configs/crosshair_jump_binds.cfg** gets executed.
- "ammo" in console, **configs/ammo_binds.cfg** gets executed.

You can always type *default* in console to execute the default binds.

### demoman.cfg
Default binds.

### engineer.cfg
Default binds.

### heavyweapons.cfg
Default binds.

### medic.cfg
Default binds plus uber bind and fake uber bind.

### pyro.cfg
Default binds.

### scout.cfg
Default binds.

### sniper.cfg
Default binds.

### soldier.cfg
Default binds.

### spy.cfg
Default binds.

### README.md
Ignore this file.
