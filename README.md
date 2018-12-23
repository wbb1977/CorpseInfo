# CorpseInfo
Vanialla World of Warcraft Tooltip Addon 

# Functions
This addon sends automatically /who <name of dead player> if you hover mouse pointer over a corpse. Alternative you can bind a key or do a mouse click to inspect the corpse. It adds then the information from the response to the tooltip. If the player is still online it adds race, class, level and the word 'Online' to the tooltip otherwise it adds Offline or <name of opposite faction>.

# Commands
* /corpseinfo - Display current setup and a help message.
* /corpseinfo mode - Toggle between automatic inspection on/off (Default: automode is on). If off, you have to left click the corpse to inspect it.
* /corpseinfo chat - Toggle whether to suppress the ouput of /who commands initiated by this addon (Default: suppress output) 

# KoS Support
Integrated support for Opium KoS Addon (currently disabled for KoS 2.7b) and SKMap. These two stores data about enemy player (race, level, class).

CorpseInfo utilize this information if available. It will add your note/comment about the player to the tooltip and for enemy player it adds race, level and class.

Notes from HoloFriends and ct_PlayerNotes are also shown if available.

# If you use TipBuddy

With default TipBuddy settings, only the automatic mode from CorpseInfo will work. To get left-click to work with TipBuddy you have to enable "Anchor Unit Frames" or "Fade Default Tooltip" in TipBuddy options. Alternativ bind the key to inspect the corpse.

# Limits
* There is no way to get an exact match via /who command. So you may get a chat result of another player who has a very similiar name as dead player, but tooltip says 'Offline'. The tooltip is always right, because the addon knows the name you are looking for.
* WoW allows the /who command only every 3 seconds, so if you hover fast over many corpses the addon can't keep up.
* Can only inspect dead player of your faction.
