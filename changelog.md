# 1.0.4

* Fixed the teleport orb losing its saved position: `RememberPositionInteraction` wrote the position and the `Charged` state through two independent paths to the same hotbar slot, and the second write could silently overwrite the first (regression introduced when porting to 0.5.3)
* Fixed the orb never returning to its default (uncharged) state after teleporting, which made it impossible to save a new position afterwards
* Durability is now only consumed after a successful teleport, not before

# 1.0.3

* Updated to 0.5.3

# 1.0.2

* Updated to 2026.03.26-89796e57b

# 1.0.1

* Updated to 2026.02.17-255364b8e

# 1.0.0

* Initial release