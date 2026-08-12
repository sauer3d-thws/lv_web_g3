---
marp: true
theme: thws-sts
paginate: true
header: '**Webprogrammierung** <br> THWS Modul-Nr: 6322170'
math: mathjax
footer: '[zurück zur Übersicht](../index.md)'
---

<!-- _class: titlepage -->







🟢 1. Abgabe: Konzept, Wireframe & SDD-Spezifikation (15 Punkte – ca. Woche 4)
Ziel: Planung der eigenen Webpräsenz (z. B. Geovisualisierungs-Portfolio, Projektseite, Mobiles Leben/Reisen).

Welche Tools eignen sich für den Entwurf?
Wireframing/Design: Excalidraw, Figma, Penpot oder digitale Skizzen.
KI-Spezifikation (SDD): Erstellen eines spec.md-Dokuments, das die geplante Struktur, Farbwelt und Zielgruppe definiert.
Muss-Anforderungen für Abgabe 1:
Sitemap & Content-Konzept: Struktur von mindestens 3 Unterseiten (z. B. Startseite, Galerie/Projekte, Kontakt).
Wireframe (Mobile & Desktop): Skizze des Layouts für mobile Geräte und Desktop.
Design System: Festlegung von Farbpalette (Hex/RGB/HSL), Schriftarten (z. B. Google Fonts) und Bildsprache.
SDD-Prompting-Plan: Erste Spezifikation für die KI (Welche Komponenten sollen wie generiert werden?).
🔵 2. Abgabe: HTML5 & CSS3 Rohentwurf (25 Punkte – ca. Woche 8)
Ziel: Vollständige, semantische und responsive Webseiten-Struktur ohne JavaScript.

Muss-Anforderungen für Abgabe 2:
Semantische HTML5-Struktur: Korrekte Nutzung von <header>, <nav>, <main>, <article>, <section>, <aside>, <footer>. Keine reinen <div>-Wüsten!
Responsive Layout:
Einsatz von Flexbox und/oder CSS Grid.
Mobile-First Ansatz mit mindestens 2 klar definierten Breakpoints via @media screen.
Medien & Urheberrecht:
Eigene Fotos/Grafiken oder lizenzfreie Medien (CC0 / Unsplash / eigene Aufnahmen).
Pflicht: alt-Attribute bei allen Bildern.
Rechtliche Grundlagen (aus Skript):
Impressumspflicht & Datenschutzerklärung (DSGVO-konform, z. B. Google Fonts lokal eingebunden).
🟡 3. Abgabe: JavaScript, Interaktion, APIs & Geodaten (35 Punkte – ca. Woche 12)
Ziel: Dynamisierung der Website, Anbindung externer Daten und interaktive Komponenten.

Anforderungen für das Mindestlevel (Didaktischer Kern):
DOM-Manipulation & Events:
Interaktives Navigationsmenü (z. B. funktionierendes Hamburger-Menü per classList.toggle('active')).
Mindestens ein weiteres Live-Event (input-Event für Zeichenzähler oder change-Event für Filter).
Asynchrone Datenverarbeitung (fetch API) & Geodaten-Bezug:
Einbinden und Laden einer externen GeoJSON-Datei (z. B. Punkte von Orten, Routen oder Kartenelementen) per fetch() und async/await.
Alternativ: Einbinden einer interaktiven OpenStreetMap-Karte (z. B. via Leaflet.js).
Formularverarbeitung & Validierung:
Kontakt- oder Erfassungsformular mit nativer HTML5/JS-Validierung (checkValidity(), FormData-API).
Clientseitige Speicherung oder Dateiverarbeitung:
Speichern von Benutzereinstellungen via localStorage ODER GeoJSON-Export per Blob-API / Upload per FileReader.
🔴 4. Abgabe: SDD-Protokoll & Code-Verteidigung (25 Punkte – ca. Woche 15)
(Sehr dringend empfohlen, um KI-Plagiate ohne Eigenleistung zu verhindern!)

Ziel: Nachweis, dass der KI-generierte Code vollständig verstanden, orchestriert und debuggt wurde.

Muss-Anforderungen für Abgabe 4:
SDD- & Prompt-Protokoll (sdd-protokoll.md):
Dokumentation der verwendeten Prompts & Spezifikationen.
Fehler-Dokumentation: Welche KI-Vorschläge waren falsch/mangelhaft und wie wurden sie behoben? (inkl. Nutzung der DevTools / Breakpoint-Debugging).
Live Code-Verteidigung (5-Minuten-Kolloquium / Präsentation):
Die Studierenden präsentieren ihre Webseite.
Zufällige Code-Frage des Dozenten: Z. B. "Erkläre mir Zeile 42 in deiner script.js – was macht event.preventDefault() hier genau?"
📊 Gerechter Punkte- & Notenschlüssel (100 Punkte Gesamt)
Kriterium / Teilabgabe	Gewichtung	Bewertungsgrundlage
Abgabe 1: Konzept & Wireframe	15 Pkt.	Vollständigkeit Wireframes, Design-System, Qualität der SDD-Spezifikation.
Abgabe 2: HTML5 & CSS3 Layout	25 Pkt.	Semantik (5 Pkt), Responsive Layout/Media Queries (10 Pkt), Design/Medien/Rechtliches (10 Pkt).
Abgabe 3: JavaScript & APIs	35 Pkt.	DOM/Events (10 Pkt), Fetch/GeoJSON/Karte (10 Pkt), Formular/Validierung (10 Pkt), Web Storage/Blob (5 Pkt).
Abgabe 4: SDD-Dokumentation	15 Pkt.	Qualität des Prompt-Protokolls, Dokumentation von Debugging & KI-Korrekturen.
Abgabe 4: Code-Verteidigung	10 Pkt.	Souveränität beim Erklären des eigenen Codes und der JS-Logik.
GESAMT	100 Pkt.	**100 - 95 Pkt: 1,0
⚠️ Limitierungen & Rahmenbedingungen für Studierende
Um den Anspruch hoch zu halten und Wildwuchs zu vermeiden, sollten folgende Regeln gelten:

Keine High-Level-Frameworks (React, Vue, Angular, Svelte):
Es müssen Vanilla HTML5, Vanilla CSS3 und Vanilla JavaScript (ES6+) verwendet werden. Das garantiert, dass die Grundlagen beherrscht werden.
Keine CSS-Frameworks (Tailwind, Bootstrap):
Layouts müssen per handgeschriebenem Flexbox/Grid und Media Queries erstellt werden.
Pflicht-Bezug zur Geovisualisierung:
Mindestens eine Geodaten-Komponente (GeoJSON, OpenStreetMap, Geolocation API, GPS-Koordiniatenerfassung) muss integriert sein.
Rechtliche Abnahme-Hürde (K.O.-Kriterium):
Fehlt das Impressum oder werden Urheberrechte bei Bildern verletzt, führt dies zu Punktabzug.