---
layout: default
title: SolarAscension
galleryImages:
- /assets/SolarAscension/Image1.png
- /assets/SolarAscension/Image2.png
- /assets/SolarAscension/Image3.png
- /assets/SolarAscension/Image4.png
- /assets/SolarAscension/Image5.png
- /assets/SolarAscension/Image6.png
background: /assets/SolarAscension/Background.png
overlay: light
fontColor: "#E0B800"
permalink: /SolarAscension
---
<section id="Solar Ascension" markdown="1">
![Solar Ascension]({{ '/assets/SolarAscension/Name.png' | relative_url }})

### Engine: Unity Engine
### Teamsize: 14
### Timeframe: 8 weeks

<div class="videoContainer">
	<iframe 
		frameborder="0" 
		src="https://www.youtube.com/embed/5OTL7PECXG8" 
		title="Solar Ascension Trailer" frameborder="0" 
		allow="accelerometer; 
		autoplay; 
		clipboard-write; 
		encrypted-media; 
		gyroscope; 
		picture-in-picture; 
		web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
	</iframe>
</div>
<div class="space">
</div>
{% include gallery.html 
    id="solarAscension"
    images=page.galleryImages %}


## My work

### Pathfinding in 3D space

Implemented a custom 3D pathfinding system using the A* algorithm. The solution incorporates collision avoidance, 
adaptive speed scaling based on spatial density, and deadlock resolution logic through automated self-destruction 
events. This demonstrates expertise in algorithm design, optimization, and robust fail-safe mechanisms for autonomous 
agents.

### Economy system 

Designed and developed a resource-driven economy framework that dynamically manages and distributes resources across 
interconnected systems. Leveraged scriptable objects for building definitions, enabling modular expansion and streamlined 
data-driven workflows. The system supports multiple building archetypes (production, logistics, storage, housing) and 
ensures balanced gameplay through centralized distribution logic.

### Drone movement

Developed a node-based queueing system to coordinate drone movement in 3D space. Drones dynamically queue for nodes, 
wait until they are available, and then advance to the next target, ensuring collision-free navigation without relying 
on physics simulation. The system adapts movement speed based on spatial context (slower in dense areas, faster in 
open space) and integrates event-driven logic to maintain efficient traffic flow and prevent deadlocks in real time.

### Modular building system

Implemented a scalable architecture for buildings using scriptable objects, allowing for extensibility without 
codebase rewrites. Each building type integrates seamlessly with the economy and pathfinding systems, showcasing 
strong system design, modularity, and maintainability.


#### [Itch.io page](https://games-academy.itch.io/solar-ascension)


#### [Game download](https://drive.google.com/file/d/1CdOvpR_IbEa4QuZ3O_h1xrFJ8u3_YLnx/view?usp=share_link )


</section>