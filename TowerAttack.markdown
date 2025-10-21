---
layout: default
title: TowerAttack
galleryImages:
- /assets/TowerAttack/Image1.png
- /assets/TowerAttack/Image2.png
- /assets/TowerAttack/Image3.png
- /assets/TowerAttack/Image4.png
- /assets/TowerAttack/Image5.png
- /assets/TowerAttack/Image6.png
background: /assets/TowerAttack/Background.png
overlay: dark
fontColor: "#FFFFFF"
---
<section id="Tower Attack" markdown="1">
![Tower Attack]({{ '/assets/TowerAttack/Name.png' | relative_url }})

### Engine: Unity Engine
### Teamsize: 3
### Timeframe: 48 Hours


{% include gallery.html 
    id="TowerAttack"
    images=page.galleryImages %}


## My work

### Unit pathing

Implemented a pathfinding system that directs spawned units along predefined routes toward the throne. 
Each unit follows the path autonomously while reacting to tower placement and attacks. The system ensures 
smooth movement coordination and collision-free progression, even when multiple unit types are active simultaneously.

### Tower types 

Designed two defensive tower archetypes — an Archer Tower for ranged attacks and a Laser Tower for continuous damage. 
Towers automatically target nearby enemies, handle cooldowns, and respawn after destruction, maintaining gameplay flow 
and consistent challenge.

### Unit types 
Developed three unique unit classes with distinct behaviors and attributes: a Giant Skeleton (slow, high health, tank unit), 
an Undead Archer (ranged, targets towers directly), and a Skeleton (fast, low health, swarm unit). Each unit type interacts 
differently with tower defenses, adding tactical depth and requiring balanced design and tuning.

#### [Itch.io page](https://masokuu-games.itch.io/tower-attack)

#### [Game download](https://drive.google.com/file/d/1ldz82xs4ol8YeDsqeW8N4BqDjvpK52bW/view?usp=sharing)


</section>