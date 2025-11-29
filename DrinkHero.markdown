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
### Teamgröße: 7
### Zeitrahmen: 8 Wochen
### [Trailer](https://www.youtube.com/watch?v=AS88IZfV9HQ)
<!--
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
-->
<div class="space">
</div>
{% include gallery.html 
    id="solarAscension"
    images=page.galleryImages %}


## Meine Arbeit

### Server und Datenbank Verwaltung

Einen Linux-basierten Server mit einer Datenbank-Backend-Struktur bereitgestellt und konfiguriert, um 
Spieldaten als auch Informationen der Spieler zu speichern und zu verwalten. Diese Architektur ermöglichte es, 
Spielparameter serverseitig zu aktualisieren, ohne dass Client-Updates erforderlich waren, und demonstriert 
Kompetenz in Backend-Infrastruktur sowie Live-Spielbetrieb.

### Serveranwendung

Eine serverseitige Anwendung entwickelt, die Client-Anfragen verarbeitet, mit der Datenbank kommuniziert 
und die benötigten Spieldaten zurückliefert. Diese Service-Schicht gewährleistete eine sichere, zuverlässige und effiziente 
Kommunikation zwischen Client und Server und unterstützte die Anforderungen des Echtzeit-Gameplays.

### Netzwerksystem

Ein Netzwerk-System entworfen und implementiert, um die Echtzeit-Kommunikation 
zwischen Client und Server zu ermöglichen. Eine REST API für die Übertragung von Spieldaten entwickelt, 
das eine zuverlässige Synchronisation von Spieleraktionen und serverseitiger Logik sicherstellt. Dies 
demonstriert fundiertes Verständnis von Netzwerktechniken, Client-Server-Architektur und effizientem Datenaustausch-Design.

### Kampfsystem

Ein kartenbasiertes Kampfsystem entwickelt, bei dem Aktionen durch Mana begrenzt sind und über Spielerzüge 
ausgeführt werden. Karten sind als Listen von Effekten definiert, die beim Ausspielen ausgelöst werden, 
was ein flexibles Design von Fähigkeiten und Mechaniken ermöglicht. Das System unterstützt aufeinanderfolgende 
Begegnungen, Gegner-Spawns und Bosskämpfe und bietet eine skalierbaren Gameplay-Loop.

### Shader

Shader entwickelt, um visuelles Feedback und die Spielpräsentation zu verbessern. Dynamische 
Effekte implementiert, indem Materialeigenschaften mithilfe von Noisetexturen, Alpha-Schwellenwerten 
und extern gesteuerten Parametern manipuliert wurden.

### Cross-Platform Entwicklung (PC & Mobile)

Das Projekt für den Einsatz auf PC- und Android-Plattformen optimiert. Die Eingabesteuerung für Tastatur, 
Maus und Touch implementiert. Responsive UI-Layouts auf verschiedenen Bildschirmgrößen und Hardware-Konfigurationen angepasst. 
Performance-Profiling, Speicherverwaltung und plattformspezifische Optimierungen angewendet, um auf allen unterstützten Geräten 
ein hochwertiges Spielerlebnis zu gewährleisten.


#### [Itch.io Seite](https://games-academy.itch.io/drink-hero)

#### [Game download Windows](https://drive.google.com/file/d/1BMh9E1tRVwq1jK39ML10stXOIQqorUrF/view?usp=sharing)
#### [Game download Android](https://drive.google.com/file/d/12G5rFJaouoSVe3aX47TLbhh5yhmCPvpp/view?usp=drive_link)


</section>