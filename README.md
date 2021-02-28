# <img src="https://github.com/DavyCraft648/NoFood/blob/main/icon.png" height="64" width="64"></img> NoFood
Don't eat! You are fasting!

This plugin will **forbid** players to eat
### Permission
 - nofood.bypass - Allow the player to eat - default: false
 
### Config
```yaml
# NoFood plugin configuration file

# No hungry feature: true|false
# (NoFood feature is always on)
#noHungry: false
noHungry: false

# World folder name where the feature(s) is enabled
# (case-sensitive)
#worlds:
#- worldName1
#- worldName2
worlds:
- world
- lobby

# Consumable food
# (or leave empty to make all food can't be eaten)
#allowedFood:
#- steak
#- raw_chicken
#- apple
allowedFood: []
```