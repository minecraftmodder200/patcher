# minecraft hypixel patcher
Patcher is a Forge mod for 1.8.9 & 1.12.2 created to improve your all-around Minecraft experience, bringing tons of Quality of Life additions, performance improvements, and tons of Vanilla bug fixes.


For a list of mods that are no longer needed while using Patcher & recommended alternatives, please visit this link.

If you have any issues while using Patcher, please let us know at our support server on Discord.

# how to use  !

  put the mod in your mods folder and when ingame do /patcher 
  this wil bring up the menu




# changes


1.8.7 - 1.8.9, 1.12.2 (May 13, 2023)
Additions

+ Warning about Labymod's RP24
+ Add fishing hooks to clean projectiles
Fixes

+ Resolve optimized font renderer not respecting OptiFine's custom colors
+ Resolve LimitVisGraphScan not working
+ Resolve shadowed actionbar no longer working
Misc

= Change culling nametags to be off by default
1.8.6 - 1.8.9, 1.12.2 (Jan 09, 2023)
Additions

+ Chat background when open
+ Always render the action bar above armor/health
+ Add case command fix to tab completion
+ Fix forge making chests with a bottom slab above being unopenable
Fixes

+ Resolve logs being spammed by lwjgl unlocking
+ Resolve some elements being drawn twice
+ Resolve hidden arrows still showing their bounding boxes
+ Resolve mobs inside of monster spawners being culled
Misc

- Removed "Sky Color Optimization"
1.8.5 - 1.8.9, 1.12.2 (Sep 18, 2022)
Fixes

+ Resolve master volume being set to 100 when tabbing in and out
1.8.4 - 1.8.9, 1.12.2 (Sep 18, 2022)
Additions

+ Support for FR AZERTY keyboard layout
Fixes

+ Resolve unfocused sounds not affecting currently playing sounds
+ Resolve false positives for replacement mods
Misc

+ Allow for setting custom fps in the config
- Remove name history
1.8.3 - 1.8.9, 1.12.2 (Aug 06, 2022)
Additions

+ Image Preview support for Twitter links
Fixes

+ Resolve a typo in preview width option description
+ Resolve an incompatibility with NickHider causing nametag backgrounds to be the wrong width
+ Resolve "Disable Nametag Boxes" not removing the square behind the Essential indicator
+ Resolve Essential force disabling Patcher's Screenshot Manager
+ Resolve formatting issue in "Image Preview Width" description
+ Resolve the Open to Lan button being the wrong width
+ Vanilla: Resolve log spam when switching or leaving servers
+ OptiFine: Resolve an issue with the game freezing when swapping worlds while using Render Regions (by calcastor)
Misc

+ Screenshot Manager is set to off by default
1.8.2 - 1.8.9, 1.12.2 (May 17, 2022)
Additions

+ Confirm Quit (Screens -> General)
+ Keyboard Layout (Bug Fixes -> Linux) (by DeDiamondPro)
+ Player name tab-completion with /patcher name
+ Vanilla Glass Panes (Bug Fixes -> Forge, 1.8.9) (by DJtheRedstoner)
Fixes

+ Resolve NullPointerException when taking a screenshot (by cbyrneee)
+ Resolve OptiFine popup not appearing if clicked away from
+ Resolve invalid mixin target regarding Particle Culling (1.12.2)
+ Resolve log spam from deleted mixin
+ Resolve log spam when checking length of mapDataBytes (by DJtheRedstoner)
+ OptiFine: Resolve crash when using Connected Textures (by Wyvest)
1.8.1 - 1.8.9, 1.12.2 (Mar 01, 2022)
Additions

+ Display amount of usernames in Name History menu
+ Automatically Scale Titles (Miscellaneous -> Titles, by Wyvest)
+ Title Opacity (Miscellaneous -> Titles, by Wyvest)
+ Title Scale (Miscellaneous -> Titles, by Wyvest)
Fixes

+ Resolve Chat Timestamps being incompatible with Safe Chat Clicks
+ Resolve mobs not spawning with Fullbright enabled (1.12.2)
+ Resolve scrollbar in Name History menu not being grabbable
Misc

+ Changed Fire Overlay Opacity to be a Percentage slider
+ Moved "Disable Titles" from "Miscellaneous -> Overlays" to "Miscellaneous -> Titles"
- Removed "Optimized Cloud Renderer"
1.8.0 - 1.8.9, 1.12.2 (Jan 14, 2022)
Additions

+ 1.12.2 Support
+ Allow changing the current Audio Device (Located in the vanilla volume menu, originally by cbyrneee)
+ Disable Lightning Bolts (Miscellaneous -> Rendering)
+ Disable Titles (Miscellaneous -> Overlays)
+ Dynamic Zoom Sensitivty (Miscellaneous -> OptiFine)
+ Extend Chat Background (Screens -> Chat)
+ Left Hand in First Person (Miscellaneous -> Rendering)
+ Levelhead 8.0 Support
+ Show Seconds on Timestamps (Screens -> Chat)
Fixes

+ Resolve Disable Nametag Boxes not working on the Essential nametag indicator
+ Resolve LAN servers showing up in the server menu as the LAN scan entry (monkuous)
+ Resolve OptiFine breaking unicode string width (DJtheRedstoner)
+ Resolve alpha text issues with the Sidebar Revamp mod
+ Resolve bold unicode characters causing incorrect string width (DJtheRedstoner)
+ Resolve depth issues when HUD Caching is enabled
+ Resolve incompatibilities with Tabulous
+ Resolve unicode characters using incorrect bold offset (DJtheRedstoner)
+ Resolve using Shift+Number on the server menu selecting the LAN scan entry (monkuous)
+ Vanilla: Resolve perspective keybind not registering until a key is pressed if bound to a mouse button
+ OptiFine: Resolve VBOs causing the sky to cut off at the void (calcastor)
Misc

+ Change Unfocused FPS Amount minimum from 1 to 15
+ Completely redesign & rework the Name History screen
- Remove "Chat Peek" as it's now built into Essential
1.7.0 - 1.8.9 (Nov 13, 2021)
Additions

+ Add Background to Actionbar (Miscellaneous -> Rendering)
+ Allow changing Inventory Scale through /patcher (Screens -> Inventory, DJtheRedstoner)
+ Allow extra arguments when using /patcher sendcoords
+ Allow providing no username when using /patcher name
+ Allow refreshing sounds in the vanilla sound menu for those without access to F3+S/F3+T
+ Container Opacity (Screens -> General)
+ Fire Overlay Opacity (Miscellaneous -> Overlays)
+ Greatly optimized memory usage when loading chunks while using OptiFine
+ Hide Aura on Invisible Withers (Miscellaneous -> Rendering)
+ Hide Fire Overlay with Fire Resistance (Miscellaneous -> Overlays)
+ Improved smooth lighting while underwater
+ Separate Sound & Texture Reloading (Miscellaneous -> General)
+ Tab Player Count (Screens -> Tab)
+ Translate Unknown Roman Numerals (Miscellaneous -> Rendering, DJtheRedstoner)
+ Warn the user if they're using an outdated version of Forge
Fixes

+ Resolve Chat Timestamps not working on messages with extra siblings
+ Resolve MouseBindFix not working while Labymod is present
+ Resolve Normal FPS Counter not working with OptiFine's debug fps option
+ Resolve Unicode chars rendering too far apart with Optimized Font Renderer (DJtheRedstoner)
+ Resolve crash with 5zig Reborn and Smart Disconnect
+ Resolve crash with Log Optimizer
+ Resolve crash with old versions of Forge
+ Resolve custom debug keybinds causing the default keybinds to not work if disabled
+ Resolve entities flickering at high coordinates with Entity Culling
+ Resolve player hover events not working in singleplayer
+ Resolve possible freeze when starting the client
+ Resolve possible freeze when connecting to a server
+ Resolve possible stability issues with log spam patches
+ Resolve queued messages not respecting Transparent Chat option
+ Resolve startup-notification counting until you reach the main menu, resulting in incorrect times
+ Resolve underline & strikethrough styles to not render with Optimized Font Renderer (DJtheRedstoner)
+ Vanilla: Resolve additional log spam caused by scoreboards
+ Vanilla: Resolve being able to click chat messages that have scrolled out of chat (Lily)
+ Vanilla: Resolve crash when Unicode chars are bound to keybinds
+ Vanilla: Resolve flipped nametag rotation on sneaking players when in third person
+ Vanilla: Resolve not being able to close containers with mouse buttons (Lily)
Misc

+ Display current Patcher version in the Settings GUI
+ OptiFine M6_pre2 support
+ Rename "Instant World Swapping" to "Optimized World Swapping"
+ Rework "Replace Open to Lan" to have multiple choices & rename to "Open to LAN Replacement"
- Remove "Custom Tab Opacity" to reduce the number of steps needed to change tab opacity, can now just modify the slider
- Remove "Remove Water FOV"
- Remove "Skin Refresher" as Essential has replaced this
1.6.1 - 1.8.9 (Aug 18, 2021)
Fixes

+ Possibly resolve resources not being found and appearing black & pink
+ Resolve Server List button being shorter than usual in specific cases with Essential's settings
+ Resolve Show Own Nametag not appearing when HUD is disabled
+ Resolve Tab Height activating when mods disable the bossbar
+ Resolve color bleeding onto entities, tile entities, HUD elements, etc.
+ Resolve crosshair rendering twice with HUD Caching & Custom Crosshair
+ Resolve heads not rendering properly
+ Resolve screenshots returning a null error when it fails to delete the previous message
+ Resolve sorting being lost in the available packs screen
+ Vanilla: Resolve crash when server sends a bad server icon
1.6 - 1.8.9 (Aug 04, 2021)
Additions

+ 1.11 Chat Length (Screens -> Chat)
+ 1.16 Chat Delay (Screens -> Chat)
+ Add Text Shadow to Actionbar (Miscellaneous -> Rendering)
+ Automatically refresh singleplayer menu when a new save is inserted
+ Better FPS Limiter Integration (Done through /patcher fps)
+ Chat Timestamps Style (Screens -> Chat)
+ Clean Projectiles (Miscellaneous -> Rendering)
+ Click Out of Containers (Screens -> Inventory)
+ Consecutive Compact Chat (Screens -> Chat)
+ Disable Hotbar Scrolling (Miscellaneous -> General)
+ Entity Back-face Culling (Performance -> Culling)
+ HUD Caching (Experimental -> HUD Caching) (Credits: Moulberry)
+ Individual Screenshot Feedback Button Toggles (Screenshots -> Feedback)
+ Max Particle Limit (Performance -> Particles)
+ Modifiable F1, F3, and F4 keybinds (Controls menu)
+ Name History Style (Screens -> General)
+ Player Back-face Culling (Performance -> Culling)
+ Remove Map Bobbing (Miscellaneous -> General)
+ Render Hand While Zoomed (Miscellaneous -> OptiFine)
+ Ridden Horse Opacity (Miscellaneous -> Rendering)
+ Split Entity Render Distance into categories (Performance -> Entity Rendering)
+ Static Items (Miscellaneous -> General)
+ Unfocused FPS (Miscellaneous -> General)
+ Unfocused Sounds (Miscellaneous -> General)
+ Unstacked Items (Performance -> Entity Rendering)
+ Use Vanilla Metrics Renderer (Miscellaneous -> OptiFine)
