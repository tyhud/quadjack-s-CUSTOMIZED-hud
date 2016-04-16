WARNING - BACKUP YOUR CURRENT AUTOEXEC.CFG, AND ALL CURRENT CLASS.CFG FILES BEFORE ANY OF THE INCLUDED CONFIGS.
If you already have an established autoexec or class.cfg collection you should not be using this.

If you ever need to remove your configs or set the game back to default, remove your configs from the \tf\cfg directory and run TF2 with the -autoconfig launch option. Close TF2, remove the launch option, and you should be set.

Drag these .cfg files into the \tf\cfg folder. 

Final result should look like this:

C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\cfg\autoexec.cfg

C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\cfg\scout.cfg

C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\cfg\pyro.cfg

C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\cfg\heavyweapons.cfg

etc

etc

Be sure to look inside each one (using a text editor like notepad++) and alter it to your desires. It's also good to have an understanding of what your configs do.

NOTE 1: If you want to remove viewmodels and/or particles from a weapon (like the flamethrower), open the appropriate class.cfg and alter the proper weapon slot to read:


Primary weapon slot for example:

Removing both viewmodels and particles:
bind "1" "slot1;r_drawviewmodel 0;viewmodel_fov 0"

Removing particles but keeping viewmodels:
bind "1" "slot1;r_drawviewmodel 1;viewmodel_fov 0"

Removing viewmodels but keeping particles:
bind "1" "slot1;r_drawviewmodel 0;viewmodel_fov 90"


It's generally suggested to remove both viewmodels and particles from weapons such as the scattergun, flamethrower, minigun, and rocket launcher, as they aren't accurately depicted and take up a lot of screen space. Of course, it's all up to you.

Several of these configs are pre-configured to remove viewmodels and particles for primary weapons. These configs are pyro.cfg, soldier.cfg, and spy.cfg.

NOTE 2:

Pressing F1, F2, F3, and F4 will change your loadout on the fly. This means that in order to ready up for a matchmaking game or MvM game, you need to press F5.

Note 3: 

The autoexec included in this pack is a "baseline" autoexec. It does not include a full FPS config, fun binds, etc. It does include stabby's null movement + crosshair flasher script, stabby's advanced scoreboard, lerp/interp settings, mild optimizations, and dingaling changes.

CREDIT:

https://steamcommunity.com/groups/stabbyvideo/discussions/0/846963165458399532/

http://www.teamfortress.tv/25328/comanglia-s-config-fps-guide