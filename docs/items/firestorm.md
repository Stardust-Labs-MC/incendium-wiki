


!!! tip inline end "Firestorm"

    === "Base Sprite"
        ![Firestorm](../assets/items/firestorm.png){.center}

    === "Loaded Sprite"
        ![Firestorm](../assets/items/firestorm_loaded.png){.center}    
    

    __Base Item:__     Crossbow  
    __Durability:__  465  
    __Projectile Damage:__  12 (![Full](../assets/sprites/full.png){width="9"} x 6)  
    __Ammo:__  Spectral Arrows  
    __Charge Time:__  2s  
    > ``` mcf title="Give Item Command"
      function incendium:admin/give/firestorm
      ```


## Description

Firestorm is a fast paced explosive crossbow capable of storing up to 5 shots.

Shots fired from this crossbow are converted into a fire stream that with a range of roughly 22 blocks that explodes on impact with blocks or mobs. This explosion has a range of 2.5 blocks and does 6![Full](../assets/sprites/full.png){width="9"}'s of damage while also igniting foes hit for 4.5s.

When sneaking while holding the crossbow loaded shots will disappear and allow the user to load additional ammo into the crossbow, up to 5 and are saved to the item. If there are stored shots in the crossbow then after firing a shot it will remove a stored shot and auto refill the crossbow allowing rapid fire shots until none remain. The number of loaded shots are displayed above the players hotbar for a short time after firing or loading a shot and in the items text when hovering over it in your inventory.   

This crossbow is only compatible with spectral arrows


This item is immune to burning in lava/explosions and most other means of destroying items

## Obtaining

The Firestorm can be obtained from a vault in the [Infernal Altar](../structures/infernal-altar.md) using an [Infernal Key](infernal-key.md)


## Modifications
This item can be renamed without losing its effect, but it will lose its font color. This can be restored by reseting it's name at an anvil. It can also be grindstoned safely

The Firestorm works with some crossbow enchantments except piercing and multishot and can not be enchanted directly, you must combine enchant books in order to add any enchants
