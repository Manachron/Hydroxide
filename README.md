*This is not a finished product; there* ***will*** *be bugs.*

<p align="center">
  <img src="https://i.vgy.me/v90wQc.png">
</p>

# Hydroxide

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/633473076688060416/637867363601088512/unknown.png">
</p>
<p align="center">
  Penetration testing tool for games on the Roblox platform.
</p>



## <a href="https://github.com/nrv-ous/Hydroxide/blob/in-dev/main.lua"><b>main.lua</b></a>

### Before you use this script, please make sure you have the auxiliary unit in your exploit's auto-execute folder!

```lua
--[[
                ▄████████▄   ▄█▄    ▄█▄   
                ███    ███   ███    ███   
                ███    ███   ███    ███   
                ███    ███   ████▄▄████  ▄███▄▄▄▄███▄ 
                ███    ███   ████▀▀████  ▀███▀▀▀▀███▀  
                ███    ███   ███    ███   
                ███    ███   ███    ███   
                ▀████████▀   ▀█▀    ▀█▀    
                      :::[H:Y:D:R:O:X:I:D:E]:::
                   -- developed by nrv-ous/hush --   
                   
                  !!PLEASE MAKE SURE YOU HAVE THE!!
                   !!HYDROXIDE AUXILIARY UNIT IN!!
                !!YOUR EXPLOIT'S AUTO-EXECUTE FOLDER!!
]]--
asset(oh, "You do not have the Hydroxide auxiliary unit in your auto-execute folder!")

oh.load_from_file = true
oh.ui = import(4369731232)
oh.assets = import(4369733667)
oh.v_aux = import("visual_aux.lua")
oh.icons = oh.v_aux.icons

import("upvalue_scanner.lua")

oh.initialize()

```
