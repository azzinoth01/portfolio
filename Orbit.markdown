---
layout: default
title: Orbit
galleryImages:
- /assets/Orbit/Image1.png
- /assets/Orbit/Image2.png
- /assets/Orbit/Image3.png
- /assets/Orbit/Image4.png
- /assets/Orbit/Image5.png
background: /assets/Orbit/Background.png
overlay: light
fontColor: "#E0B800"
---
<section id="Orbit" markdown="1">
![Orbit]({{ '/assets/Orbit/Name.png' | relative_url }})

### Engine: Unity Engine
### Teamsize: 6
### Timeframe: 6 weeks

<div class="videoContainer">
	<iframe 
	src="https://www.youtube.com/embed/jb1rlI62vbo" 
	title="Orbit - Teaser Trailer" 
	frameborder="0" 
	allow="accelerometer; 
	autoplay; 
	clipboard-write; 
	encrypted-media; 
	gyroscope; 
	picture-in-picture; 
	web-share" 
	referrerpolicy="strict-origin-when-cross-origin" 
	allowfullscreen>
	</iframe>
</div>
<div class="space">
</div>
{% include gallery.html 
    id="solarAscension"
    images=page.galleryImages %}


## My work

#### Bullet skill system

Designed a modular bullet skill system where skills are defined as prefabs containing configurable bullet sequences. 
Each skill specifies bullet prefabs, spawn rotations, and flight paths, which can be rotated and combined to create 
diverse attack patterns. This system supports both player weapons and enemy skill sequencing, demonstrating flexibility 
and reusability in gameplay design.

#### Enemy AI

Implemented lightweight but flexible enemy AI with multiple behavior modes: node-based pathing, axis-aligned movement 
toward the player, and directional turning. Paths are defined as sequences of nodes, and enemies can either loop or stop 
after completing a path. This modular AI structure allows easy customization of enemy movement patterns and complexity.

#### Object pooling

Optimized bullet-heavy gameplay with a custom object pooling system to minimize expensive spawn and despawn operations. 
Inactive bullets are stored in a pool, reset, and reused when needed. New bullets are instantiated only if the pool 
is empty, and periodic cleanup prevents excessive memory use. This system significantly reduces runtime overhead in a 
bullet-hell environment.

#### Shipeditor

Developed an in-game shipeditor that doubles as a shop, enabling players to purchase, equip, and customize weapons 
to match their playstyle. Equipped loadouts are saved, ensuring continuity between sessions without 
repeated menu setup.

#### Control remapping

Integrated Unity’s new Input System to enable flexible control remapping. Players can easily redefine input 
bindings for both keyboard and controller, improving accessibility and user experience.

#### [Itch.io page](https://cresscentmoon.itch.io/orbit)


#### [Game download](https://drive.google.com/file/d/17HIlg10uzzHRdO0c3ZDW4GIJSou0-p4B/view)


</section>