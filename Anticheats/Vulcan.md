# Vulcan
[Anticheat on Spigot](https://www.spigotmc.org/resources/vulcan-anti-cheat-advanced-cheat-detection-1-7-1-19-2.83626/)
/ [Anticheat Discord](https://discord.gg/SCNuwUG)
## Anticheat Notes
- Vulcan will copyright strike your video if uploaded with logs.
- Vulcan will copyright strike you for showing its logo, or an illustration meant to be similar, in your thumbnails.
- Vulcan could be for you! *(if you drink monster, are a femboy, and have a tiny penis)*

## How to detect
- First transaction on join will be -30767
- Second transaction on join will be -30766
- Third transaction on join will be -25767
- Vulcan will send a transaction on velocity starting at -30767 and will go up by 1 every velocity
- Vulcan will send a transaction on every potion effect added starting at -28767 and will go up by 1 for every potion effect
- Vulcan has config options to lag back for ghost blocks and gravity (-0.0784000015258789)
- When Vulcan lagbacks are disabled, there are still two checks that setback. If vulcan thinks you may be ghost blocking, it will set you back. Vulcan will also set you back when it detects no rotation, and will continue to lagback until you respond to the S08 correctly.
- Older vulcan literally tells you all its info if you join the server with one of the developers names, like "Frap". This is useful on cracked servers, however it was changed later in Vulcan.
- Unlike most others AC's that use transactions, vulcan sends one transaction every two ticks, as opposed to another anticheat like karhu, that send one every tick.