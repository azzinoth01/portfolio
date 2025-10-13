---
layout: default
title: DrinkHero
galleryImages:
- /assets/DrinkHero/Image1.png
- /assets/DrinkHero/Image2.png
- /assets/DrinkHero/Image3.png
- /assets/DrinkHero/Image4.png
- /assets/DrinkHero/Image5.png
- /assets/DrinkHero/Image6.png
- /assets/DrinkHero/Image7.png
- /assets/DrinkHero/Image8.png
- /assets/DrinkHero/Image9.png
- /assets/DrinkHero/Image10.png
background: /assets/DrinkHero/Background.png
overlay: light
fontColor: "#000000"
---
<section id="DrinkHero" markdown="1">
![Drink Hero]({{ '/assets/DrinkHero/Name.png' | relative_url }})

### Engine: Unity Engine
### Teamsize: 7
### Timeframe: 8 weeks

<div class="videoContainer">
	<iframe 
	src="https://www.youtube.com/embed/AS88IZfV9HQ" 
	title="Drink Hero Official Trailer [Goldmaster-Version]" 
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

### Server and database management

Deployed and configured a Linux-based server with a database backend to store and manage both game data and player data. 
This architecture allowed game parameters to be updated server-side without requiring client updates, demonstrating 
proficiency in backend infrastructure and live game operations.

### Server application

Built a custom server-side application to handle client requests, interface with the database, and return the necessary 
game data. This service layer ensured secure, reliable, and efficient communication between client and server, supporting 
real-time gameplay requirements.

### Networking system

Designed and implemented a custom networking system to handle real-time communication between client and server. 
Built a lightweight request and response model for transmitting game data, enabling reliable synchronization of player 
actions and server-side logic. This demonstrates strong understanding of networking fundamentals, client-server 
architecture, and efficient data exchange design.

### Combat system

Developed a card-based combat system where actions are limited by mana and executed through player turns. Cards are 
defined as lists of effects that trigger on play, enabling flexible design of abilities and mechanics. The system 
supports sequential encounters, enemy spawns, and boss battles, providing a scalable gameplay loop.

### Shader

Developed custom shaders to enhance visual feedback and gameplay presentation. Implemented dynamic effects by 
manipulating material properties with noise textures, alpha thresholds, and externally controlled parameters. 
This demonstrates strong knowledge of shader programming, real-time rendering techniques, and the ability to 
create reusable visual effect pipelines adaptable to different gameplay scenarios.


#### [Itch.io page](https://games-academy.itch.io/drink-hero)

#### [Game download Android](https://drive.google.com/file/d/1NvcEH3JYOCcK6d8zQ0Dw2DeM_t3bwB3A/view)
#### [Game download Windows](https://drive.google.com/file/d/1buvoQNqAy3kbYUfeDCP5uRqgVdHuo2tk/view)

</section>