# Radial Menu for Overwatch-Workshop

<style>
    img {   
        margin: 5px;
    }   

    .gallery-container {
        display: flex; 
        flex-flow: row wrap;
        justify-content: flex-start;
    }
    .gallery-img {
        flex: 1 1 20%;
    }
</style>

This Workshop code lets you open a radial menu that shows all your allowed heroes. From there you can switch one of the heroes.<br>
It is also possible to rewrite it so that anything can be displayed and any action can be performed when selecting a menu item.

<img src="./img/all_heroes_eichenwalde_halloween.jpg" alt="Menu with all heroes" width="100%"/>


Here is a preview for different numbers of items:
<div width="100%" class="gallery-container">
    <img src="./img/2_heroes_lijiang_tower_lunar.jpg" alt="Menu with all heroes" class="gallery-img" width="40%"/>
    <img src="./img/3_heroes_lijiang_tower_lunar.jpg" alt="Menu with all heroes" class="gallery-img" width="40%"/>
    <img src="./img/4_heroes_blizzard_world_winter.jpg" alt="Menu with all heroes" class="gallery-img" width="40%"/>
    <img src="./img/5_heroes_blizzard_world_winter.jpg" alt="Menu with all heroes" class="gallery-img" width="40%"/>
</div>

Features:
- Only shows the allowed heroes of the player
- Menu scales depending on the number of items
- Menu follows player when moving. This allows you to change heroes while walking and flying
- Menu follows your reticle so it doesn't leave the screen. Meaning 360 hero switches are possible
- Animated opening/closing sequence
- Displayed heroes are sorted by type (Support,Tank,Damage)
- Works with multiple players

Known Issues:
- Menu doesn't work in multiplayer:<br> 
This is caused by the limitations of the Workshop. The menu displays a lot of InWorldTexts, which are limited to only 128 at a time. Keep this in mind and try limiting the number of players