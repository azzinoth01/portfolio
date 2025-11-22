---
layout: default
title: index
background: /assets/Background.png
overlay: dark
fontColor: "#FFFFFF"

---
<section id="aboutMe" markdown="1">
## About Me 
Unity Entwickler mit zwei Jahren Berufserfahrung mit Schwerpunkt auf Gameplay Programmierung und 
vier Jahren Berufserfahrung als Software Entwickler mit Schwerpunk auf Datenbanken und 
Serververwaltung sucht neue Stelle als Unity Entwickler.

**Github: [https://github.com/azzinoth01](https://github.com/azzinoth01)**

**Contact: markusdullnig@hotmail.com**

</section>
---

<section id="gameProjects" markdown="1">

## Game Projekte

{% capture solarAscensionBullets %}
- Entwickelt mit Unity
- Pfadfindung im 3D Raum
- Wirtschaftssystem
- Drohnen Bewegung
- Modulares Bausystem
{% endcapture %}

{% capture deathstringNightfallBullets %}
- Entwickelt mit Unreal Engine 5.1
- Modulares Pfadsystem
- Projektilsystem
- Online Highscore Liste
- Eingabesystem
- Tag und Nacht Zyklus
{% endcapture %}

{% capture orbitBullets %}
- Entwickelt mit Unity
- Skillsystem
- Gegner KI
- Object pooling
- Raumschiff Editor
- Steuerung anpassen
{% endcapture %}

{% capture drinkHeroBullets %}
- Entwickelt mit Unity
- Server und Datenbank Verwaltung
- Serveranwendung
- Netzwerksystem
- Kampfsystem
- Shader
- Cross-Platform Entwicklung (PC & Mobile)
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

## Game Jam Projekte

{% capture towerOfBubbleBullets  %}
- Entwickelt mit Unity
- Physik
- Eingabesystem
- Spieler Bewegung
- Hindernisse und Plattformen
{% endcapture %}

{% capture towerAttackBullets %}
- Entwickelt mit Unity
- Einheitenpfadfindung
- Turmtypen
- Einheitentypen
{% endcapture %}

{% capture thouShallLaughBullets %}
- Entwickelt mit Unity
- Rundenbasiertes Kampfsystem
- Kartensystem
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