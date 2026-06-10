# New-Vents-and-Pumps

Modifies and adds new vents and pumps to Ostranauts. Probably alarms as a bonus, as well.

 - Update .1: All the traditional gas pumps are done! HUZZAH! I'll add *one* more "pump" that actually pumps heat, not gas.

Thus far, adds:
 - A configurable auto vent, with three different modes at 15, 10, and 5 KpA
 - Pumps configured to work off of thermostats instead of pressure sensors
 - Concentrators(Called filters in-game, for added confusion) that allow you to push gasses from one room to the other selectively.
 - 3 new pumps with turbo, temperature, and turbo temperature variants! The Extended, Heavy, and S-Bend pumps. Heavy by default has 2 places it pulls gas from; one in the bottom right, one in the top left. The Extended line has a default mode, where it pulls gas from the A slot(barely discernably labeled for your convenience on the pump itself) and a dual mode where it pulls gas from an A slot and a B slot. The B slot is always 1/5 as effective as the A slot, because this is made to allow a player to mix atmo at the ideal ratio. I imagine that it won't do this perfectly, but it'll at least be good enough that you could conceivably get an atmo canister to 'good enough.'

Be warned that at this early stage, the jsons are VERY undercooked. There's a lot of redundant data in there that I think I'll be using but am not 100% sure on. It's ugly, basically. There will be bloat, although there shouldn't be any significant performance impacts.
