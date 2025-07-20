# PallyPower-TBC-Backport
Backport of PallyPower for the WOTLK 3.3.5a client using TBC spells and features.

To compare this with the original PallyPower made by Aznamir and edited by Phill and Gnomechewer, visit:
https://github.com/yeagerca/WoW-Macros-Addons-Weakauras/tree/e69fb5ac0722e4bcfa97944f4d591e4311613f06/PallyPower

![alt text](https://github.com/yeagerca/PallyPower-TBC-Backport/blob/main/PallyPower%20demonstration.png "PallyPower demonstration image")

## Installation
Move the "PallyPower" folder to the "AddOns" folder such that your full path is "WoW/Interface/AddOns/PallyPower/PallyPower.toc". No renaming is required. Accompanying files like the ReadMe and demonstration image can be deleted or stored wherever you please.

## Notable Changes
- Blessing of Salvation and Blessing of Light are added to the buff assignment list.
- Single-person buff assignments also support Light and Salvation.
- Sanctity Aura is added to the aura assignment list.
- All seals including Martyr, Vengeance, Corruption, Blood, Crusader are supported for the seal button.
- Fixed behavior differences between scrolling up or down on buff assignments.
- Player information on the left side reads the correct spell ids and talents for TBC (e.g., Rank 3 Might + 5 Talent points).
- Unlearned spells will not be displayed in the player information (see Gnpalaa in the demonstration image).
- When a paladin has Sanctity Aura learned, it will take the place of Blessing of Light, because nobody cares about that one.

## My friends won't update, what happens?
If their PallyPower supports Light, Salvation, and Sanctity buff assignments it should work just fine. If their's does not support Light, Salvation, or Sanctity they will see blank spaces as if those buffs were not assigned. It shoudn't break anything on your end unless they willfully change your assignments.

Players running a different version of PallyPower may report incorrect spell or talent ranks. This will not affect the behavior of PallyPower in a meaningful way, but those features will be unhelpful. You can tell if a player is using the WotLK version of PallyPower if they are showing the Sanctity and Salvation icons with no ranks next to them (see Eraina in the deomstration image).
