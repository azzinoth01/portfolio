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
<section id="DeathstringNightfall" markdown="1">
![Deathstring Nightfall]({{ '/assets/DeathstringNightfall/Name.png' | relative_url }})

### Engine: Unreal Engine 5
### Teamgröße: 11
### Zeitrahmen: 8 Wochen
### [Trailer](https://www.youtube.com/watch?v=JF2pbCEZ3Is)
<!--
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
-->
<div class="space">
</div>
{% include gallery.html 
    id="deathstringNightfall"
    images=page.galleryImages %}


## Meine Arbeit

### Modulares Pfadsystem

Ich habe ein splinebasiertes Pfadsystem für die Gegnerbewegung implementiert. Anstatt 
jede mögliche Route vorher manuell festzulegen, habe ich ein Laufzeitsystem entworfen, 
das Raum-zu-Raum-Splines zu vollständigen Pfaden kombiniert. Dieser Ansatz reduziert den 
manuellen Aufwand, skaliert effizient mit der Levelkomplexität und passt sich dynamisch an 
vom Spieler beeinflusste Wegentscheidungen an.

### Projektilsystem

Ein modulares Projektil-Framework entwickelt, das mehrere Projektiltypen und Spezialeffekte unterstützt. 
Implementierte Projektile mit Kettenzielerfassung, Verlangsamungseffekten, Schaden-über-Zeit (Burn) und 
Flächenschaden. Das System wurde für einfache Erweiterbarkeit ausgelegt und ermöglicht schnelles Prototyping 
neuer Mechaniken, während es zugleich ein konsistentes Verhalten über Türme, Spieler und Gegner hinweg sicherstellt.

### Online Highscore Liste

Eine Online Highscore Liste erstellt, die Leistungsmetriken der Spieler erfasst (Punkte, Kills, Überlebenszeit, Wellenanzahl). 
Ein Übermittlungs- und Abrufsystem entwickelt, um Top-Spieler nachzuverfolgen, den Wiederspielwert zu erhöhen und durch 
persistente, serverseitige Daten zusätzliche Wettbewerbsmotivation zu schaffen.

### Eingabesystem

Vollständige Gamepad-Unterstützung mithilfe des Enhanced Input Systems von Unreal Engine 5 integriert. Eingabeaktionen so konfiguriert, 
dass sowohl Tastatur als auch Gamepad nahtlos unterstützt werden, um Zugänglichkeit, Flexibilität und skalierbares Eingabemanagement 
für verschiedene Steuerungsarten sicherzustellen.

### Tag und Nacht Zyklus

Einen vollständig funktionalen Tag-Nacht-Zyklus mit Lichtübergängen und phasenabhängigen Gameplay-Regeln implementiert. Beispielsweise 
ist der Zugang zu Türen bei Nacht eingeschränkt, was zusätzliche strategische Tiefe schafft. Das System demonstriert Kompetenz in 
Echtzeit-Zustandsverwaltung, ereignisgesteuertem Design und der visuellen Integration ins Gameplay.


#### [Itch.io Seite](https://games-academy.itch.io/deathstring-nightfall)


#### [Game download](https://drive.google.com/file/d/1BF7azcNzVjOwn7JlnboUvCVujP-SeEJ9/view)


</section>