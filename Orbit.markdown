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
### Teamgröße: 6
### Zeitrahmen: 6 Wochen
### [Trailer](https://www.youtube.com/watch?v=jb1rlI62vbo)
<!--
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
-->
<div class="space">
</div>
{% include gallery.html 
    id="solarAscension"
    images=page.galleryImages %}


## Meine Arbeit

#### Skillsystem

Ein modulares Bullet-Skill-System entworfen, bei dem Skills als Prefabs definiert sind, die konfigurierbare 
Projektilsequenzen enthalten. Jeder Skill legt fest, welche Bullet-Prefabs,Spawn-Rotationen und Flugbahnen die 
Projektile haben. Diese können rotiert und kombiniert werden, um vielfältige Angriffsmuster zu erzeugen. 
Das System unterstützt sowohl Spielerwaffen als auch die Skill-Abfolgen von Gegnern und demonstriert hohe 
Flexibilität und Wiederverwendbarkeit im Gameplay-Design.

#### Gegner KI

Eine flexible Gegner-KI implementiert, die mehrere Verhaltensmodi unterstützt: knotenbasiertes Pathfinding, 
achsenbasierte Bewegung in Richtung des Spielers und Drehen zum Spieler. Pfade werden als Sequenzen von Knoten definiert, 
und Gegner können nach Abschluss eines Pfads entweder stoppen oder ihn in einer Schleife wiederholen. Diese modulare 
KI-Struktur ermöglicht eine einfache Anpassung von Bewegungsmustern.

#### Object pooling

Bullet-intensives Gameplay durch ein Object-Pooling-System optimiert, um teure Spawn- und 
Despawn-Operationen zu minimieren. Inaktive Projektile werden in einem Pool gespeichert, zurückgesetzt und 
bei Bedarf wiederverwendet. Neue Projektile werden nur dann instanziiert, wenn der Pool leer ist, und eine 
regelmäßige Bereinigung verhindert übermäßige Speichernutzung. Dieses System reduziert die Laufzeitkosten 
in einer Bullet-Hell-Umgebung erheblich.

#### Raumschiff Editor

Einen In-Game-Editor entwickelt, der zugleich als Shop dient und es den Spielern ermöglicht, 
Waffen zu kaufen und auszurüsten. Ausgerüstete Loadouts werden gespeichert, sodass die Einstellungen 
zwischen den Spielsessions erhalten bleiben und nicht erneut im Menü vorgenommen werden müssen.

#### Steuerung anpassen

Das neue Input System von Unity integriert, um eine flexible Neubelegung der Steuerung zu ermöglichen. 
Spieler können Eingaben für Tastatur und Controller ganz einfach neu definieren, was die Barrierefreiheit 
und das Nutzererlebnis verbessert.

#### [Itch.io Seite](https://cresscentmoon.itch.io/orbit)

#### [Game download](https://drive.google.com/file/d/1fwsPyhNUkhbptqCU8Q1h1Yrkw58HZldE/view?usp=sharing)


</section>