---
layout: default
title: index
background: /assets/Background.png
overlay: dark
fontColor: "#FFFFFF"

---
<section id="aboutMe" markdown="1">
## About Me 
I’m a results-driven game programmer with a strong background in software development and a deep passion 
for creating engaging, responsive, and technically refined gameplay experiences. Starting my career in customization 
programming taught me how to design robust, adaptable systems and write clean, scalable code. Building on that foundation, 
I transitioned into game development, where I specialize in turning creative ideas into interactive, polished, and 
performance-optimized experiences.

My focus lies in gameplay systems, player movement, AI, and technical design ensuring that every feature not only 
functions efficiently but also feels intuitive and rewarding to play. I thrive on solving complex technical challenges, 
from developing dynamic pathfinding and economy systems to fine-tuning physics and input handling for precision control.

Driven by curiosity and a commitment to quality, I approach every project as an opportunity to blend 
creativity with engineering. Whether working solo or as part of a team, my goal is always the same: to build games that are fun to 
play, satisfying to interact with, and technically solid under the hood.

**Contact: markusdullnig@hotmail.com**

</section>
---

<section id="gameProjects" markdown="1">

## Game Projects

{% capture solarAscensionBullets %}
- Pathfinding in 3D space
- Economy system
- Drone movement
- Modular building System
{% endcapture %}

{% capture deathstringNightfallBullets %}
- Modular pathing system
- Projectile system
- Online high score
- Input system
- Day and night cycle
{% endcapture %}

{% capture orbitBullets %}
- Bullet skill system
- Enemy AI
- Object pooling
- Shipeditor
- Control remapping
{% endcapture %}

{% capture drinkHeroBullets %}
- Server and database management
- Server application
- Network system
- Combat system
- Shader
{% endcapture %}

<div class="projectGrid">
{% include projectBox.html 
    title="Solar Ascension" 
    url="/SolarAscension/"
	image="assets/Thumbnails/SolarAscension.png"
    bullets=solarAscensionBullets
  %}
  {% include projectBox.html 
    title="Deathstring Nightfall" 
    url="/DeathstringNightfall/"
	image="assets/Thumbnails/DeathstringNightfall.png"
    bullets=deathstringNightfallBullets 
  %}
  {% include projectBox.html 
    title="Orbit" 
    url="/Orbit/"
	image="assets/Thumbnails/Orbit.png"	
    bullets=orbitBullets 
  %}
   {% include projectBox.html 
    title="Drink Hero" 
    url="/DrinkHero/"
	image="assets/Thumbnails/DrinkHero.png"	
    bullets=drinkHeroBullets 
  %}
</div>
</section>
---

<section id="gameJamProjects" markdown="1">

## Game Jam Projects

{% capture towerOfBubbleBullets  %}
- Physics
- Input handeling
- Player movement
- Obstacles and platforms
{% endcapture %}

{% capture towerAttackBullets %}
- Unit pathing
- Tower types
- Unit types
{% endcapture %}

{% capture thouShallLaughBullets %}
- Turn based battle system
- Card system
- Sequencing
{% endcapture %}

<div class="projectGrid">
 {% include projectBox.html 
    title="Tower of Bubble" 
    url="/TowerOfBubble/" 
	image="assets/Thumbnails/TowerOfBubble.png"	
    bullets=towerOfBubbleBullets 
  %}
{% include projectBox.html 
    title="TowerAttack" 
    url="/TowerAttack/"
	image="assets/Thumbnails/TowerAttack.png"
    bullets=towerAttackBullets 
  %}
  {% include projectBox.html 
    title="Thou shall laugh!" 
    url="/ThouShaltLaugh/" 
	image="assets/Thumbnails/ThouShallLaugh.png"
    bullets=thouShallLaughBullets 
  %}
</div>
</section>

{% comment %}
---

<section id="hobbyProjects" markdown="1">

## Learning / Hobby Projects

{% capture aiLearnsToDriveBullets %}
- Feedforward neural network
- Genetic algorithm
{% endcapture %}

{% capture directX11RenderBullets %}
- 2D image rendering
- render pipeline
- memory management
- GPU resource handeling
{% endcapture %}

<div class="projectGrid">
{% include projectBox.html 
    title="AI learns to drive" 
    url="https://space-game.com"
    bullets=aiLearnsToDriveBullets 
  %}
  {% include projectBox.html 
    title="DirectX 11 render" 
    url="https://puzzle-game.com" 
    bullets=directX11RenderBullets 
  %}
</div>
</section>

{% endcomment %}