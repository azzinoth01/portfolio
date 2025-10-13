---
layout: default
title: DeathstringNightfall
galleryImages:
- /assets/DeathstringNightfall/Image1.png
- /assets/DeathstringNightfall/Image2.png
- /assets/DeathstringNightfall/Image3.png
- /assets/DeathstringNightfall/Image4.png
- /assets/DeathstringNightfall/Image5.png
- /assets/DeathstringNightfall/Image6.png
- /assets/DeathstringNightfall/Image7.png
background: /assets/DeathstringNightfall/Background.png
overlay: light
fontColor: "#FFFFFF"
---
<section id="Solar DeathstringNightfall" markdown="1">
![Deathstring Nightfall]({{ '/assets/DeathstringNightfall/Name.png' | relative_url }})

### Engine: Unreal Engine 5
### Teamsize: 11
### Timeframe: 8 weeks

<div class="videoContainer">
	<iframe 
	src="https://www.youtube.com/embed/JF2pbCEZ3Is" 
	title="GA EN DN Goldmaster Trailer MP  20230811" 
	frameborder="0" 
	allow="accelerometer; 
	autoplay; 
	clipboard-write; 
	encrypted-media; 
	gyroscope; 
	picture-in-picture; 
	web-share" 
	referrerpolicy="strict-origin-when-cross-origin" 
	allowfullscreen></iframe>
</div>
<div class="space">
</div>
{% include gallery.html 
    id="deathstringNightfall"
    images=page.galleryImages %}


## My work

### Modular pathing system

Implemented a spline-based pathing system for enemy movement. Instead of predefining every possible route, 
I designed a runtime system that combines room-to-room splines into complete paths. This approach reduces 
manual setup, scales efficiently with level complexity, and dynamically adapts to player-driven pathing choices.

### Projectile system

Developed a modular projectile framework supporting multiple bullet types and special effects. Implemented 
projectiles with chain targeting, slowing effects, damage-over-time (burn), and area-of-effect damage. 
The system was designed for easy extension, enabling rapid prototyping of new mechanics while maintaining 
consistent behavior across towers, players, and enemies.

### Online high score

Created an online leaderboard that records player performance metrics (score, kills, survival time, wave count). 
Designed a submission and retrieval system to track top players, enhancing replay value and adding competitive 
motivation through persistent, server-side data.

### Input system

Integrated full gamepad support using Unreal Engine 5’s Enhanced Input System. Configured input actions to 
support both keyboard and gamepad seamlessly, ensuring accessibility, flexibility, and scalable input management 
for different control schemes.

### Day and night cycle

Implemented a fully functional day and night cycle with lighting transitions and phase dependent gameplay rules. 
For example, nighttime restricts door access, adding strategic depth. The system demonstrates proficiency in 
real-time state management, event-driven design, and visual gameplay integration.


#### [Itch.io page](https://games-academy.itch.io/deathstring-nightfall)


#### [Game download](https://drive.google.com/file/d/1BF7azcNzVjOwn7JlnboUvCVujP-SeEJ9/view)


</section>