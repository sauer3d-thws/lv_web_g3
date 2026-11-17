---
marp: true
theme: thws-sts
paginate: true
size: 16:9
header: '**Webprogrammierung (6322170)** · Portfolio Meilenstein 1 Bewertung'
footer: 'THWS Geovisualisierung · WS 2026/2027 · Dozent: Stefan Sauer'
style: |
  section {
    padding-top: 100px !important;
    padding-bottom: 40px !important;
    padding-left: 70px !important;
    padding-right: 70px !important;
    font-size: 13.5px !important;
    justify-content: flex-start !important;
    overflow-y: auto !important;
  }
  section::before {
    height: 48px !important;
    width: 300px !important;
    background-size: 300px 48px !important;
    top: 25px !important;
    left: 40px !important;
  }
  section h1 {
    font-size: 26px !important;
    color: #FF6a00 !important;
    margin-top: 0 !important;
    margin-bottom: 8px !important;
    line-height: 1.2 !important;
  }
  section h2 {
    font-size: 20px !important;
    color: #111827 !important;
    margin-top: 0 !important;
    margin-bottom: 8px !important;
    border-bottom: 2px solid #FF6a00 !important;
    padding-bottom: 4px !important;
  }
  section h3 {
    font-size: 17px !important;
    color: #005a9c !important;
    margin-top: 0 !important;
    margin-bottom: 6px !important;
  }
  section p {
    font-size: 13px !important;
    line-height: 1.4 !important;
    margin-bottom: 6px !important;
    color: #374151 !important;
    width: 100% !important;
  }
  section ul, section ol {
    font-size: 13px !important;
    line-height: 1.35 !important;
    margin-left: 0 !important;
    margin-bottom: 6px !important;
    width: 100% !important;
  }
  section ul li, section ol li {
    font-size: 12.5px !important;
    line-height: 1.35 !important;
    margin-bottom: 2px !important;
    text-indent: 0 !important;
    color: #1f2937 !important;
  }
  section ul li ul {
    margin-top: 2px !important;
    margin-bottom: 2px !important;
  }
  section ul li ul li {
    font-size: 12px !important;
    line-height: 1.3 !important;
    margin-bottom: 1px !important;
  }
  section table {
    font-size: 11.5px !important;
    width: 100% !important;
    margin-top: 6px !important;
    border-collapse: collapse !important;
  }
  section th {
    background-color: #005a9c !important;
    color: #ffffff !important;
    font-size: 11.5px !important;
    padding: 5px 8px !important;
    font-weight: 600 !important;
    border: 1px solid #cbd5e1 !important;
  }
  section td {
    font-size: 11.5px !important;
    padding: 4px 8px !important;
    border: 1px solid #e2e8f0 !important;
    background-color: #ffffff !important;
  }
  section tr:nth-child(even) td {
    background-color: #f8fafc !important;
  }
  .highlight-box {
    background-color: #eff6ff !important;
    border-left: 4px solid #005a9c !important;
    padding: 6px 12px !important;
    border-radius: 4px !important;
    font-size: 12px !important;
    margin-top: 6px !important;
    color: #1e40af !important;
    width: 100% !important;
  }
  .highlight-box strong {
    color: #005a9c !important;
  }
  .badge {
    display: inline-block;
    padding: 2px 7px;
    border-radius: 4px;
    font-size: 11px;
    font-weight: 600;
  }
  .badge-best { background: #dcfce7; color: #15803d; }
  .badge-good { background: #e0f2fe; color: #0369a1; }
  .badge-mid  { background: #fef3c7; color: #b45309; }
---

<!-- _class: titlepage -->
# Meilenstein 1: Bewertungsbericht
## Konzept, Wireframe & SDD-Spezifikation (Portfolio)
### Modul Webprogrammierung (6322170) · THWS Geovisualisierung · WS 2026/2027
**Dozent:** Stefan Sauer · **Gewichtung:** 15 Punkte (15 % der Modulnote)  
**Status:** 10 Abgaben auditiert (Ø 12,4 Pkt. · Bestehensquote 100 %)  

> **Wichtiger Hinweis:** Gemäß mündlicher Freigabe sind sowohl mehrseitige Webauftritte als auch **durchdachte One-Pager mit klar strukturierten Sektionen** vollwertig zulässig (kein Punktabzug).

---

## 1. Kriterien- und Bewertungsmatrix (15 Punkte Maximal)

| Kriterium | Max. Pkt. | Didaktische Anforderungen & Bewertungsfokus |
| :--- | :---: | :--- |
| **K1: Sitemap & Inhaltskonzept** | **3,0 Pkt.** | Mind. 3 logische Unterseiten **ODER** One-Page mit semantischen Sektionen (Hero, Projekte, Skills, Kontakt); thematischer Geovis-Bezug. |
| **K2: Wireframing (Desktop & Mobile)** | **3,5 Pkt.** | Vollständige Skizzen für **Desktop UND Smartphone** (Mobile-First); saubere Komponenten-Transformation (Header, Navigation, Grids, Footer). |
| **K3: Design-System & Gestaltung** | **3,5 Pkt.** | **Design-System:** Farbpalette (Hex/HSL), Typografie, Bildsprache.<br>**Gestaltung:** Visuelle Harmonie, Kontraste (WCAG), Layout-Rhythmus, Ästhetik. |
| **K4: Recherche & Inspiration** | **2,0 Pkt.** | 2–3 dokumentierte Best-Practice-Vorbilder im Netz mit Analyse von Navigation, Farben, Typografie und Interaktionsmustern. |
| **K5: SDD-Spezifikation (`spec.md`)** | **3,0 Pkt.** | Strukturierte, maschinenlesbare `spec.md` zur Steuerung von KI-Prompting; Persona, Breakpoints, geplante Geodaten-Features für Meilenstein 3. |
| **GESAMT** | **15,0 Pkt.** | **Meilenstein 1 (15 % der Gesamtprüfungsleistung)** |

---

## 2. Tabellarische Punkteübersicht (student_001 bis student_010)

| Student ID | K1: Konzept (3,0) | K2: Wireframe (3,5) | K3: Design (3,5) | K4: Inspo (2,0) | K5: SDD (3,0) | Gesamt (15,0) | Note / Prädikat |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **student_001** | 3,0 | 3,5 | 3,0 | 1,5 | 2,5 | **13,5** | <span class="badge badge-good">1,3 · Sehr gut</span> |
| **student_002** | 3,0 | 3,5 | 3,5 | 2,0 | 3,0 | **15,0** | <span class="badge badge-best">1,0 · Bestnote ★</span> |
| **student_003** | 2,5 | 2,5 | 2,0 | 1,5 | 2,0 | **10,5** | <span class="badge badge-mid">3,0 · Befriedigend</span> |
| **student_004** | 3,0 | 3,5 | 3,0 | 1,5 | 2,5 | **13,5** | <span class="badge badge-good">1,3 · Sehr gut</span> |
| **student_005** | 3,0 | 3,0 | 3,0 | 2,0 | 2,5 | **13,5** | <span class="badge badge-good">1,3 · Sehr gut</span> |
| **student_006** | 2,5 | 2,0 | 2,5 | 1,5 | 1,5 | **10,0** | <span class="badge badge-mid">3,3 · Befriedigend</span> |
| **student_007** | 3,0 | 3,5 | 3,5 | 2,0 | 3,0 | **15,0** | <span class="badge badge-best">1,0 · Bestnote ★</span> |
| **student_008** | 2,5 | 3,0 | 3,0 | 1,5 | 2,5 | **12,5** | <span class="badge badge-good">2,0 · Gut</span> |
| **student_009** | 2,0 | 2,5 | 2,5 | 2,0 | 1,0 | **10,0** | <span class="badge badge-mid">3,3 · Befriedigend</span> |
| **student_010** | 2,5 | 2,0 | 2,5 | 1,0 | 2,5 | **10,5** | <span class="badge badge-mid">3,0 · Befriedigend</span> |

---

### student_001 · **13,5 / 15,0 Pkt. (Note: 1,3 · Sehr gut)**
- **Eingereichte Dateien:** `spec.md` (44 Zeilen), `Beispielseiten_student_001.pdf`, `Wireframes_student_001.pdf` (16 Seiten)
- **Kriterien-Punktevergabe:**
  - **K1 (3,0/3,0):** 7 Unterseiten geplant (index, aboutme, fotografie, ehrenamt, studium, praktikas, impressum). Deutschlandkarte mit Pins als interaktive Navigation hervorragend.
  - **K2 (3,5/3,5):** 16 Seiten Wireframes bilden alle Unterseiten für Desktop und Mobil konsistent ab.
  - **K3 (3,0/3,5):** Klares Farbschema (Dunkelrot `#730002`, Weiß, Schwarz), abgerundete Ecken. Typografie mit 5 Schriftfamilien überfrachtet – im Web auf maximal 2 Webfonts fokussieren.
  - **K4 (1,5/2,0):** 4 Referenzseiten benannt (tour-kyrgyzstan.com, nikolaradeski.com etc.), aber ohne textliche Auswertung.
  - **K5 (2,5/3,0):** Detailliert bei Interaktionen & Touch-Targets (44x44px); Geodaten-Schema für MS3 noch präzisieren.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> Schriftauswahl auf 2 harmonische Webfonts konsolidieren und die HTML5-Semantik für die vielen Unterseiten schlank halten.
</div>

---

### student_002 · **15,0 / 15,0 Pkt. (Note: 1,0 · Bestnote ★)**
- **Eingereichte Dateien:** `spec.md` (203 Zeilen), `Inhaltskonzept.pdf` (3 Seiten), `Wireframe.pdf` (4 Seiten)
- **Kriterien-Punktevergabe:**
  - **K1 (3,0/3,0):** Exzellente One-Page-Struktur mit perfekt durchdachten Sektionen (Hero, Über mich, Projekte, Skills, Kontakt, Footer). Nach mündlicher Freigabe volle Punktzahl für die vorbildliche Gliederung.
  - **K2 (3,5/3,5):** Herausragende Wireframe-Qualität auf Agenturniveau! Reale Proportionen, typografische Hierarchie und echte Inhalte für Desktop und Smartphone.
  - **K3 (3,5/3,5):** Kurs-Highlight: Dunkelgrün (`#002418`) mit Würzburg-Höhenlinien in Beige-Bronze (`#917463`) und orangen Akzenten (`#FF6A00`). Perfekt abgestimmte Typografie (Poppins + Spectral).
  - **K4 (2,0/2,0):** Mustergültig dokumentiert mit Screenshots und Begründung (`abatable.com`, `tour-kyrgyzstan.com`).
  - **K5 (3,0/3,0):** Vorbildliche 203 Zeilen `spec.md` mit YAML-Tokens, Parallax-Regeln und Gestaltungsrichtlinien.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> In HTML5 konsequent semantische <code>&lt;section&gt;</code>- und <code>&lt;article&gt;</code>-Tags nutzen und flüssiges Scrollverhalten per CSS (<code>scroll-behavior: smooth</code>) umsetzen.
</div>

---

### student_003 · **10,5 / 15,0 Pkt. (Note: 3,0 · Befriedigend)**
- **Eingereichte Dateien:** `student_003_spec.md` (49 Zeilen), `student_003_Skizzeundinspo.docx`
- **Kriterien-Punktevergabe:**
  - **K1 (2,5/3,0):** 4 Unterseiten geplant (Fotos, Projekte, Plakate, Über mich). Schöne Idee einer Registerkarten-Navigation im Stil von Aktenordnern. Impressum/Datenschutz fehlt noch.
  - **K2 (2,5/3,5):** Skizzen im Word-Dokument vorhanden, jedoch eher flüchtig ohne maßhaltige Gegenüberstellung von Desktop vs. Mobile.
  - **K3 (2,0/3,5):** Retro-/Papier-Konzept hat Charme. Farbwerte benannt (Grün, Rot, Creme). Typografie bleibt jedoch unkonkret („Serifen Schrift – noch nicht entschieden“). Visuell noch unausgereift.
  - **K4 (1,5/2,0):** 2 passende Inspirationen (`pxpush.com`, `illoca.unseen.co`) mit Notizen zum Papier- und Karteikarten-Look dokumentiert.
  - **K5 (2,0/3,0):** Mit 49 Zeilen knapp. Breakpoints sind genannt, aber Abschnitt 4 (Geodaten & Leaflet) fehlt komplett.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> Schrifthierarchie verbindlich festlegen (z. B. eine markante Serif-Schrift und eine neutrale Sans-Serif für Fließtext) und Wireframes in echtes semantisches CSS-Grid übersetzen.
</div>

---

### student_004 · **13,5 / 15,0 Pkt. (Note: 1,3 · Sehr gut)**
- **Eingereichte Dateien:** `Spec.md` (147 Zeilen), `Desktop.pdf` (5 S.), `Handy.pdf` (5 S.), `Farbpalette.png`, `Inspirationen.txt`
- **Kriterien-Punktevergabe:**
  - **K1 (3,0/3,0):** Vorbildliche Seitenstruktur mit 4 logisch getrennten Seiten (`index.html`, `über-mich.html`, `projekte.html`, `kontakt.html` inkl. Impressum).
  - **K2 (3,5/3,5):** Exzellente, 5-seitige farbige Layout-Wireframes separat für Desktop und Handy. Vorbildliche Komponenten-Transformation ins mobile Hochformat.
  - **K3 (3,0/3,5):** Sehr ästhetisches Grafikkonzept mit asymmetrischen Kreisbögen und abgerundeten Karten (`#2e4057`, `#eeae3e`, `#E0E0E2`). Schriften Dutch801 und Bahnschrift müssen durch freie Webfonts ersetzt werden.
  - **K4 (1,5/2,0):** 4 gute URLs in `Inspirationen.txt`, aber ohne begleitende analytische Dokumentation im Spec-Dokument.
  - **K5 (2,5/3,0):** Sehr ausführliche Spezifikation (147 Zeilen) mit sauberer Deklaration offener Baustellen. Geodaten-Planung für Meilenstein 3 ergänzen.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> Die gewählte Typografie auf frei verfügbare Webfonts (z. B. Playfair Display / Inter) umstellen und lokal im Projektverzeichnis ablegen (DSGVO-Pflicht!).
</div>

---

### student_005 · **13,5 / 15,0 Pkt. (Note: 1,3 · Sehr gut)**
- **Eingereichte Dateien:** `spec.md` (40 Zeilen), `Konzept.pdf` (3 Seiten), `Wireframe.pdf` (4 Seiten)
- **Kriterien-Punktevergabe:**
  - **K1 (3,0/3,0):** 4 Unterseiten (`index.html`, `projekte.html`, `ueber-mich.html`, `kontakt.html`) mit starkem Geovis-Bezug (QGIS, ArcGIS, 3ds Max, Webmapping).
  - **K2 (3,0/3,5):** Saubere 4-seitige Wireframe-PDF mit Desktop- und Mobilansichten für Start- und Projektseite. Funktional und aufgeräumt, gestalterisch nüchtern.
  - **K3 (3,0/3,5):** Harmonische maritime Farbpalette („Deep Aqua“ `#003B46`, `#66A5AD`). Professionell definiertes 8px-Spacingsystem und solide Typografie (`Inter` + `Roboto`).
  - **K4 (2,0/2,0):** Perfekt: 3 fachspezifische Kartografie- und Datenvorbilder analysiert (Mapbox Gallery, MapTiler Showcase, Observable Plot).
  - **K5 (2,5/3,0):** Sehr präzise und disziplinierte `spec.md`. Breakpoints (480px, 768px, 1100px) und Datenstrukturen gut vorbereitet.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> Das etwas strenge Kasten-Layout durch mehr typografische Akzente und subtile CSS-Transitions (z. B. bei Hover über Projektkarten) visuell dynamisieren.
</div>

---

### student_006 · **10,0 / 15,0 Pkt. (Note: 3,3 · Befriedigend)**
- **Eingereichte Dateien:** `spec_student_006.md` (29 Zeilen), `Meilenstein1_Abgabe_student_006.png` (Canvas)
- **Kriterien-Punktevergabe:**
  - **K1 (2,5/3,0):** 4 Seiten geplant (index, geo-projekte, digital-art, kontakt). Interessante Symbiose aus Vermessungswesen und digitaler Kunst.
  - **K2 (2,0/3,5):** Nur die Startseite ist als Desktop- und Mobilansicht im Übersichtsbild skizziert. Für die anderen drei Unterseiten fehlen Wireframes vollständig.
  - **K3 (2,5/3,5):** Gute Farbpalette (`#3e363f`, `#ba6e6e`, `#01ffd9`) und Schriftart Figtree. Kreative Skizzen und Icons, aber das Gesamtbild wirkt noch fragmentiert.
  - **K4 (1,5/2,0):** 3 Links (`fivecell.pl`, `explore.org/fat-bear-week`, `esri.com`) mit Hinweisen am Fuß des Canvas notiert.
  - **K5 (1,5/3,0):** Sehr knapp (29 Zeilen). Widerspricht der Aufgabenstellung durch Festlegung auf „Desktop-First“. Für präzises KI-Prompting fehlen Details.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> Dringend auf den geforderten Mobile-First-Ansatz umschwenken und vorab die fehlenden Layoutstrukturen der Unterseiten aufskizzieren, bevor mit dem HTML/CSS-Coding begonnen wird.
</div>

---

### student_007 · **15,0 / 15,0 Pkt. (Note: 1,0 · Bestnote ★)**
- **Eingereichte Dateien:** `spec.md` (112 Zeilen), `Wireframe-Desktop.pdf`, `Wireframe-Mobil.pdf`, `Ideensammlung_student_007.pdf`
- **Kriterien-Punktevergabe:**
  - **K1 (3,0/3,0):** Erstklassiges Gesamtkonzept mit 5 Unterseiten. Großartiger thematischer Brückenschlag zwischen Geovisualisierung, CAD und regionaler Botanik.
  - **K2 (3,5/3,5):** Referenzqualität! Gestochen scharfe Wireframes für Desktop und Mobilgeräte. Perfektes Komponenten-Downscaling und erstklassige Hierarchie.
  - **K3 (3,5/3,5):** Gestalterisches Meisterwerk! Organische Farbwelt (`#85886A`, `#DED7C9`, `#977A60`), eigene botanische Vektor-Zeichnungen, Isohypsen, anspruchsvolle Schrifthierarchie (`Petrona`, `Inter Tight`, `Reenie Beanie`) inkl. WCAG 2.1 AA Kontrastprüfung.
  - **K4 (2,0/2,0):** Ideensammlung dokumentiert Typo-Vergleiche, Farbpaletten-Genese (Coolors) und grafische Vorstudien lückenlos.
  - **K5 (3,0/3,0):** 112 Zeilen starke Musterspezifikation mit Persona-Analysen für 3 Zielgruppen, HTML5-Landmarks, ARIA-Attributen, Leaflet-Architektur und §5 DDG-Richtlinien.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> Das hohe gestalterische Niveau konsequent in sauberes, valides semantisches HTML5 und modulares CSS3 (Custom Properties) überführen.
</div>

---

### student_008 · **12,5 / 15,0 Pkt. (Note: 2,0 · Gut)**
- **Eingereichte Dateien:** `spec.md` (81 Zeilen), `DesktopAnsicht.pdf` (212 MB), `MobilAnsicht.pdf` (5.8 MB), `Datenschutz.html`
- **Kriterien-Punktevergabe:**
  - **K1 (2,5/3,0):** Solide One-Page-Architektur mit klar unterteilten Sektionen (Start, Person, Lebenslauf, Projekte, Kontakt) plus separater `Datenschutz.html`. Nach mündlicher Freigabe anerkannt; kleiner Abzug, da konkrete Projektbeschreibungen und Geodaten noch weitgehend Platzhalter sind.
  - **K2 (3,0/3,5):** Detailliert gestaltete Ansichten für Desktop und Mobile vorhanden. Schöne Bildstimmung mit Altbaufassade und burgunderroter Navigationskachel. (Desktop-PDF künftig komprimieren).
  - **K3 (3,0/3,5):** Eigenständiges Farbschema (Bordeaux `#9B1D20`, Plum `#3D2B3D`, Warmgrau `#635D5C`, Lime `#CBEFB6`). Gute Typografie mit Manrope & DM Sans. Auf ausreichende Farbkontraste bei Texten auf Lime achten.
  - **K4 (1,5/2,0):** Konkrete Vorbildseite `brostclassen.de` analysiert; eine zweite Referenzseite hätte das Bild abgerundet.
  - **K5 (2,5/3,0):** Sehr solide Spezifikation mit Flexbox-Planung und bereits mitgelieferter `Datenschutz.html`. Geodaten-Konzept für Leaflet/GeoJSON muss noch ergänzt werden.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> Die Sektionen in HTML5 mit klaren IDs (<code>#projekte</code>, <code>#ueber-mich</code>) und weichem Scrollverhalten versehen; Geodaten-Anbindung vorbereiten.
</div>

---

### student_009 · **10,0 / 15,0 Pkt. (Note: 3,3 · Befriedigend)**
- **Eingereichte Dateien:** `spec.md` (38 Zeilen), `student_009_Meilenstein_1.pdf` (4 Seiten)
- **Kriterien-Punktevergabe:**
  - **K1 (2,0/3,0):** 4 Unterseiten geplant, jedoch ist `ueber-mich.html` in der Spezifikation komplett leer geblieben.
  - **K2 (2,5/3,5):** Das PDF illustriert das rotierende Karussell und das Kachelkonzept im Desktop- und Mobilformat. Die Skizzen sind jedoch sehr abstrakt.
  - **K3 (2,5/3,5):** Spannender Mondrian- und Kachel-Ansatz mit Farbfilter-Hover. Allerdings ist die Palette mit 10 Bildfarben unruhig. Monospace-Schrift (`Courier Prime`) bei längeren Texten bezüglich Lesbarkeit prüfen.
  - **K4 (2,0/2,0):** Sehr gute Recherche in der PDF: `sethhamptonportfolio.webflow.io` und `ambientcg.com` werden mit Screenshots und direktem Bezug zur eigenen Kachelidee analysiert.
  - **K5 (1,0/3,0):** Gravierende Lücken in der Spezifikation: Leere Sektionen, Platzhalter-Fragezeichen bei Breakpoints (`???px`) und keine Geodaten-Spezifikation.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> Die <code>spec.md</code> vervollständigen, konkrete CSS-Breakpoints festlegen und das Farbschema auf wenige, harmonische Leitfarben reduzieren.
</div>

---

### student_010 · **10,5 / 15,0 Pkt. (Note: 3,0 · Befriedigend)**
- **Eingereichte Dateien:** `spec.md` (54 Zeilen), `Konzept.pdf` (1 Seite), `Wireframe-Desktop.pdf`, `Wireframe-Mobile.pdf`
- **Kriterien-Punktevergabe:**
  - **K1 (2,5/3,0):** 3 Unterseiten definiert (`index.html`, `projekte.html`, `kontakt.html`). Solide Grundlagenstruktur.
  - **K2 (2,0/3,5):** Die beiden Wireframe-PDFs sind praktisch identisch im schmalen Hochformat aufgebaut. Es findet keine echte responsive Transformation auf einen breiten Desktop-Viewport statt.
  - **K3 (2,5/3,5):** Farbpalette vorhanden (Grautöne `#DCDFE3`, `#3A4150`, `#9AA2B1`). Schöne Idee mit Stadtplan-Hintergrund, aber die Ziegelstein-Anordnung wirkt statisch.
  - **K4 (1,0/2,0):** Weder im Konzept noch in der Spezifikation sind externe Web-Inspirationen oder Best-Practice-Analysen dokumentiert.
  - **K5 (2,5/3,0):** Sehr lobenswerter softwaretechnischer Aufbau mit FR (Functional Requirements), NFR und Akzeptanzkriterien (AC). Leaflet-Konzept fehlt noch.

<div class="highlight-box">
<strong>Empfehlung für Meilenstein 2:</strong> Für den Desktop zwingend ein eigenständiges Mehrspalten-Layout (CSS Grid) entwickeln, anstatt die mobile Smartphone-Ansicht auf dem Desktop lediglich mittig anzuzeigen.
</div>

---

## 4. Didaktische Gesamteinschätzung & Empfehlungen

- **Gestaltung & Identität:** `student_007` und `student_002` zeigen eindrucksvoll, wie ein klares visuelles Thema (Höhenlinien, Botanik, Topografie Würzburg) eine Geovisualisierungs-Webseite unverwechselbar macht.
- **Architekturformate:** Sowohl Mehrseiter als auch One-Pager mit Sektionen sind legitim. Wichtig für Meilenstein 2 ist die semantisch saubere HTML5-Strukturierung (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
- **Typografie & Web-Konformität:** Mehrere Studierende haben Systemschriften (Bahnschrift, Century Gothic) spezifiziert. Diese müssen in Meilenstein 2 durch frei lizenzierte, lokal gehostete Webfonts (WOFF2) ersetzt werden.
- **Änderungsprotokoll:**
  - *2026-11-10 14:50:* Bereitstellung Bewertungsdatei `bewertung.md`.
  - *2026-11-10 15:15:* Erstauswertung aller 10 Abgaben.
  - *2026-11-10 15:20:* Nachsteuerung: Mündliche One-Pager-Freigabe eingepflegt (+0,5 Pkt. bei student_002 und student_008).
  - *2026-11-10 15:35:* Marp-Kompatibilität & kompakte Leseschriftarten (12-14px) mit Slide-Paginierung und THWS-Branding integriert.
