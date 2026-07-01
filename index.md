---
marp: true
theme: thws-sts
paginate: true
header: '**Webprogrammierung** <br> THWS Modul-Nr: 6322170'
math: mathjax
footer: '[zurück zur Agenda](#inhaltsverzeichnis)'

---
<!-- _class: titlepage -->
# Webprogrammierung
## mit KI-gestützten Workflows
## 3. Semester
### Fachlehrer  Stefan Sauer
### THWS Geovisualisierung

![bg right:45%](img/2025-01_Neuplanung_ZOB_Wuerzburg_Arbeitsprogramm_Luftbild.jpeg)

---
<!-- _class: structural-->
# Prüfungsleistung Portfolioabgabe
## Seminaristischer Unterricht & Übung
### 4 SWS | 5 ECTS | Präsenzzeit 60 h | Selbststudium 90 h
Prüfungsleistung benotete Portfolioaufgabe

---
**Lehrinhalt:**
- Kenntnis der grundlegenden Techniken der Web-Programmierung.
- Fähigkeit, Webseiten selbstständig zu erstellen.
- Trennung von Inhalt und Darstellung bei der Webpräsentation.
- Beherrschung von client- und serverseitigen Skriptsprachen.
- Kenntnis gängiger JS-Bibliotheken, deren Einbindung in eigene Anwendungen sowie die Beurteilung ihrer Vor- und Nachteile.


---
<!--_class: structural  -->
# Modulinhalte
## Webprogrammierung
Ein Schwerpunkt des Kurses wird auf den Grundlagen und der KI-gestützen Erstellung von Webseiten liegen.
- Welche Tools gibt es?
- Wie können wir sie nutzen?
- Welche Grundlagen sollte ich kennen?
- Wie fange ich an?
- Wie erstelle ich eine eigene Webpräsentation?

---
<!--_class: structural  -->
# Inhalt

---

## Arbeitsgrundlagen
- Lernmittel
- Software (Notepad++ / VS Code / Antigravity / Cursor / XAMPP / Chrome Git)

---

---
<!--_class: structural  -->
### Lernmittel
- HERDT-Verlag
- Online-Dokumentationen

---

**HERDT-Verlag (Hochschulmedien):**
In der universitären Lehre gilt das Programm HERDT-Campus ALL YOU CAN READ als Standardwerk. 
- HTML5, CSS3 und JavaScript- Webseiten entwickeln
- JavaScript Grundlagen

---
<!--_class: structural  -->
**Essenzielle Webseiten zur Weiterbildung**
- das MDN
- W3Schools
- SelfHTML
- CSS-Tricks
- Can I Use
- W3C Web Accessibility Initiative (WAI)

---

**Das MDN**
- präziseste, aktuellste und verlässlichste Dokumentation für HTML, CSS und JavaScript.
- Wenn im Zuge von modernen Workflows Code durch KI generiert wird, ist der „Algorithmische Skeptizismus“ Pflicht
- Jede Syntax und jedes Web-API sollte gegen das MDN geprüft werden (Halluzinations-Check).

https://developer.mozilla.org/en-US/

---
**W3Schools**
- hervorragende Plattform für Anfänger, um die Grundlagen von HTML, CSS und JavaScript interaktiv zu lernen.
- Der integrierte Code-Editor („Try it Yourself“) ermöglicht sofortiges Ausprobieren und Experimentieren mit Code-Beispielen.
https://www.w3schools.com/

---
**SelfHTML**
- umfassende deutsche Online-Dokumentation für HTML, CSS, JavaScript und weitere Web-Technologien.
- Sie bietet detaillierte Beschreibungen, zahlreiche Code-Beispiele und praktische Anleitungen für Webentwickler aller Erfahrungsstufen.

https://wiki.selfhtml.org/

---
**CSS-Tricks**
- populäre Ressource für Webentwickler, die sich auf CSS, aber auch auf HTML, JavaScript und modernes Webdesign konzentriert.
- Die Seite bietet Artikel, Tutorials und Videos zu aktuellen Web-Technologien und Best Practices.
https://css-tricks.com/

---
**Can I Use**
- essentielle Online-Ressource, die detaillierte Informationen über die Unterstützung von HTML-, CSS- und JavaScript-Funktionen in verschiedenen Webbrowsern bietet.
- Sie hilft Entwicklern zu überprüfen, welche Technologien in Zielbrowsern verfügbar sind und welche Polyfills oder Fallbacks benötigt werden.
https://caniuse.com/

---
**W3C Web Accessibility Initiative (WAI)**
- bietet Richtlinien und Ressourcen für die Schaffung von barrierefreien Webinhalten
- stellt sicher, dass Webseiten für alle Menschen zugänglich sind, einschließlich Menschen mit Behinderungen.
https://www.w3.org/WAI/


---
**Digital Shepherd**

Egal welche Quelle genutzt wird: Der moderne Ansatz lautet "Digital Shepherd" (Digitaler Hirte). Man sollte Code (egal ob aus Tutorials, Foren oder von einer KI generiert) niemals blind kopieren. Die eigentliche Kompetenz liegt aktuell darin, den Code zu verstehen, seine Barrierefreiheit (z.B. korrekte Alt-Texte für Bilder), semantische Sauberkeit und Performance zu validieren, um langfristig wartbare Webprojekte aufzubauen.

---
![bg full:bg](img/digital_shepherd.png)

---
**Digital Shepherd & "Vibe Coding"**
- **Was ist Vibe-Coding?** Das Programmieren mittels natürlicher Sprache und KI-Assistenten (man beschreibt die Absicht, die KI schreibt den Code).
- **Die Verführung:** Es fühlt sich einfach an ("es läuft ja"). Doch KI generiert oft Code, der oberflächlich funktioniert, aber unter der Haube erhebliche Defizite aufweist.
- **Die Rolle des Hirten (Shepherd):**
  - Prompting ersetzt kein Grundlagenwissen!
  - Wer die Grundlagen (HTML-Semantik, CSS-Kaskadierung, JS-Sicherheit) nicht versteht, kann den generierten Code weder korrigieren noch pflegen.
  - Der "Digital Shepherd" leitet die KI gezielt an, statt sich blind von ihr leiten zu lassen.

---

**Die Auditing-Checkliste des Digital Shepherd**
Wenn eine KI Code generiert, müssen Sie diesen stets kritisch auf folgende Kriterien prüfen:
- **Semantik & Struktur:** Nutzt der Code echte HTML5-Elemente (`<main>`, `<article>`, `<header>`) oder handelt es sich um eine unübersichtliche Verschachtelung reiner `<div>`-Elementen?
- **Barrierefreiheit (Accessibility):** Fehlen Alt-Attribute bei Bildern, korrekte Label-Zuordnungen bei Formularen oder barrierefreie Kontraste?
- **Performance & Overhead:** Wurde unnötig komplexer Code vorgeschlagen, wo einfaches Vanilla-CSS/JS ausreicht?
- **Sicherheit:** Werden Eingaben ungeprüft verarbeitet oder veraltete/unsichere Methoden genutzt?

---

**Zukunftsperspektive: Vom Coder zum Architekten**
Wie verändert sich die Rolle von Webentwicklern durch generative KI?
- **Der Wandel:** Die reine Schreibarbeit (Syntax tippen) nimmt ab. Die Rolle verschiebt sich hin zum **Systemarchitekten** und **Qualitätsprüfer**.
- **Menschliche Stärken:** KI versteht selten den größeren geschäftlichen Kontext, Datenschutz-Anforderungen oder das emotionale Design-Gefühl für Benutzer.
- **Fazit:**
  - Reine "Code-Kopierer" werden durch KI ersetzt.
  - **Systemversteher** und **Digital Shepherds**, die komplexe Systeme konzipieren, verifizieren und absichern können, sind gefragter denn je!

---
<!--_class: structural  -->
### Software

- Notepad++
- VS Code
- Antigravity
- Cursor
- XAMPP
- Chrome
- Git
- uvm.



---
#### Notepad++
- Windows only
- Kostenlos & Open Source: quelloffen für Text Code
- ressourcenschonend, schnell
- Syntax-Hervorhebung & -Ausblendung (Code Folding):

https://notepad-plus-plus.org/downloads/
![bg right:50%](img/notepad.jpeg)

---


- Unterstützt viele Programmier-, Skript- und Auszeichnungssprachen (z. B. HTML, CSS, JavaScript, Python, C++).
- Tab-Dokumente: Ermöglicht gleichzeitiges Öffnen und Bearbeiten mehrerer Dateien in Tabs.
- Erweiterbarkeit durch Plugins
- Leistungsstarke Suchen-und-Ersetzen-Funktion
- Makro-Aufzeichnung

---
#### VS Code

https://code.visualstudio.com/

- Kostenlos & plattformübergreifend (Windows, macOS, Linux)
- Riesiger Marketplace für Erweiterungen (Extensions)
- Hervorragende Autovervollständigung (IntelliSense)
- Integrierte Git-Unterstützung und Versionskontrolle
- Eingebautes Terminal und Debugging-Tools
- Industriestandard für moderne Webentwicklung

![bg right:50%](img/vscode.jpg)

---
#### Antigravity

https://antigravity.ai/

- Leistungsstarker, agentischer KI-Coding-Assistent von Google DeepMind
- Arbeitet im direkten Projektkontext und versteht die gesamte Codebasis
- Kann selbstständig Code schreiben, debuggen, testen und Dateien modifizieren
- Unterstützt bei der strukturierten Planung komplexer Webprojekte
- Begleitet Entwickler als digitaler Partner bei Code-Qualität, Semantik und Barrierefreiheit

![bg right:50%](img/antigravity.jpg)

---
#### Cursor

https://cursor.com/

- KI-gestützter Code-Editor, der als Fork von VS Code entwickelt wurde
- Vollständig kompatibel mit allen VS Code-Erweiterungen und -Themes
- Bietet native KI-Features wie Inline-Codegenerierung, Chat und automatische Fehlerbehebung
- Ermöglicht das Referenzieren und Durchsuchen der gesamten Codebasis (@Files, @Folders, @Codebase)
- KI-gestütztes Autocomplete (Tab-Vervollständigung), das oft ganze Zeilen oder Blöcke vorausahnt
![bg right:50%](img/cursor.jpg)

---
#### XAMPP

https://www.apachefriends.org/

- Kostenlose & einfach zu installierende lokale Serverumgebung
- Komplettpaket aus Apache (Webserver), MariaDB (Datenbank), Skriptsprachen PHP und Perl
- Ermöglicht lokales Entwickeln und Testen von dynamischen Webanwendungen ohne Live-Webserver
- Einfache Verwaltung aller Dienste über das XAMPP Control Panel

![bg right:50%](img/xampp.jpg)

---
#### Chrome

https://www.google.com/chrome/

- Schneller, sicherer und weltweit am meisten genutzter Webbrowser von Google
- Leistungsstarke Entwicklertools (Chrome DevTools) zur Fehlerbehebung / Code-Analyse
(HTML, CSS, JS)
- Führend in der Unterstützung moderner
Webstandards und APIs
- Integrierte Tools für mobiles Testen (Responsive Mode) und Performance-Audits (Lighthouse)

![bg right:50%](img/chrome.jpg)

---
#### Weitere Browser

- Firefox: Ausgezeichnetes Privacy- und
Entwickler-Fokus
- Edge: Starker Fokus auf Enterprise und
zunehmend verbesserte DevTools
- Safari: Essentiell für das Testen
auf Apple-Geräten

![bg right:50%](img/browser.jpg)

---

#### Git

https://git-scm.com/
https://github.com/

- Weltweit am häufigsten genutztes, verteiltes Versionskontrollsystem
- Protokolliert alle Änderungen im Quellcode
lückenlos macht sie rückgängig machbar
- Paralleles Arbeiten im Team über unabhängige Entwicklungszweige (Branches)
- Basis für Cloud-Plattformen zur
Zusammenarbeit wie GitHub und GitLab
![bg right:50%](img/git.jpg)

---
#### Weitere Software

- FTP-Client: FileZilla (kostenlos), Cyberduck (macOS/Windows)
- Bildbearbeitung: GIMP (kostenlos), Affinity Photo, Adobe Photoshop
- Design-Tools: Figma, Sketch, Adobe XD
- Lokale Datenbank-GUI: DBeaver, MySQL Workbench

---
<!--_class: structural  -->
## Unser Beispielprojekt
- Das Projekt
- Das Konzept
- Website Struktur
![bg right:50%](img/dasProjekt.jpg)
---

### Das Projekt
2020 beschließt der KFZ Mechaniker
Meister Maik seine Passion zur
Haupterwerbsquelle & sich selbstständi
 zu machen.
Durch sein mobiles Leben im LKW hat er sich auf
den Ausbau von Fahrzeugen zu autarken
Wohnräumen spezialisiert.
Seine jahrelange Erfahrung in der Werkstattleitung
eines Camping- & Caravantechnik Anbieters
nutzt er, um Caravans, Wohnmobile & individuelle
Fahrzeugausbauten zu reparieren, pflegen
& umzurüsten.

![bg right:50%](img/das-ist-Maik.jpeg)

---

**Seine Dienstleistungen beinhalten**
- KFZ und LKW Reparaturen
- Caravan- und Wohnmobil Reparaturen
- Vorbereitung zur TÜV Prüfung und Prüfung von Gasanlagen
- Ein- Aus- und Umbau der KFZ Elektrik bis zur autarken Solaranlagenplanung
- Kompletter Fahrzeugausbau eines Transportfahrzeuges zum
„Wohn“-Mobil

---

Da Maik ein mobiles Leben führt,
ist er selten am gleichen Platz zu finden.
Um ihn und seine Dienstleistungen dennoch
auffinden zu können, benötigt er eine gut
auffindbare Webseite mit seinen
digitalen Kontaktdaten.

![bg right:50%](img/wueste.jpg)

---
### Das Konzept

Bevor überhaupt eine einzige Zeile Code geschrieben wird, muss zuerst definiert werden, welche Ziele mit dem Webauftritt verfolgt werden.
> **Zieldefinition:**
Webseiten-Ziele vor der Entwicklung festlegen.
Am besten in einem Workshop oder Gespräch mit dem Auftraggeber.

---
- **Fokus der Inhalte:**
  - Präsentation von Maiks Dienstleistungen
  - Vermittlung des mobilen Lebensstils (Reisen, Alltag, Tauchlehrer)
  - Kontaktdaten gut auffindbar (schneller Kundenkontakt)
- **Visueller & redaktioneller Ansatz:**
  - Viele Bilder als roter Faden durch alle Bereiche
  - Reiseberichte für Mehrwert und bessere Auffindbarkeit
- **Technische Reduzierung:**
  - Keine komplexe Technik (Webshops, Logins) für einfache Selbstpflege
  - Simple HTML-Webseite > guter Hacker- & Spam-Schutz



---
<!--_class: structural  -->

## Was ist gutes Webdesign?
- Gutes Webdesign ist zielgruppenorientiert
- Gutes Webdesign ist benutzerfreundlich
- Gutes Webdesign ist technisch einwandfrei
- Gutes Webdesign ist "responsive"
- Gutes Webdesign ist SEO-optimiert

---
### Zielguppenorientierung

- **Zentrale Kernfrage der Planung:**
Wer sind die Besucher der Webseite?
- **Zielgruppe bestimmt das Design:**
Es gibt kein universell "gutes" Design
(ob minimalistisch oder Vintage)
 es muss zur Zielgruppe passen.

![bg right:50%](img/zielgruppenorientierung.jpeg)

---

- **Einfluss demografischer Faktoren:**
  - **Ältere Zielgruppen:** Benötigen barrierefreies Design (z. B. größere Schriften), legen mehr Wert auf Inhalt und Seriosität als auf reines Styling.
  - **Jüngere Zielgruppen:** Erwarten ein modernes "Look and Feel" und ein hochwertiges, visuelles Design.
- **Bedürfnisse & Erwartungen:** Die optische und inhaltliche Ausrichtung muss dem Thema entsprechen (z. B. NGO-Informationsseite vs. Lifestyle-Webshop).

---
>Was ist schon schön?


https://seiten-werk.com/die-schoensten-und-besten-52-webseiten-in-deutschland-und-der-welt/

https://www.mankord.com/article/die-10-besten-websites-und-webdesign-trends-2022/

https://mkb-marketing.de/ratgeber/schoene-webseiten-design-beispiele/

---
### Benutzerfreundlichkeit

**Form follows function:**
>Jedes Design-Element muss optisch ansprechend und funktional sein.
Kein Element ohne Funktion!

---
- **Layout-Struktur nach dem F-Schema:**
  - Nutzer scannen Webseiten in F-Form
  (oben links $\rightarrow$ rechts, tiefer links $\rightarrow$ rechts, links nach unten).
  - **Typische Anordnung:** Logo oben links, Navigationsmenü im Kopfbereich, zentraler „Hero-Shot“ (Kernaussage) in der Mitte.
![alt text](img/f-schema.jpg)


---

- **Typografie und Farbkontrast:**
  - Typografie und Farben passend zur Corporate Identity.
  - Hohe Kontraste (z. B. schwarz auf weiß) und lesbare Schriftgrößen für unterschiedliche Sehstärken und Monitore.
- **Wirkung von Weißraum (Whitespace):**
  - „Weniger ist mehr“: Weißraum strukturiert die Inhalte und lässt sie atmen.
  - Minimalistische Layouts wirken professionell und modern.

---
### Technische Korrektheit

- **Trennung von Inhalt & Design:**
  - Erleichtert Suchmaschinen die optimale Indexierung (SEO).
  - Ermöglicht Barrierefreiheit
    (z. B. einfache Navigation für Screenreader).

---

- **Ladezeiten & Performance:**
  - Kritische 3-Sekunden-Regel: Durchschnittsnutzer springen nach ca. 3 Sekunden Wartezeit ab.
  - Technische Fehlerfreiheit ist das Fundament einer positiven User Experience.

---

### Responsive Webdesign


> 64 Prozent des globalen Traffics stammt von Smartphones!
Smartphones sind für 64 Prozent des gesamten Internetverkehrs verantwortlich. In Asien ist der Smartphone-Anteil am Traffic besonders hoch.
![bg right:45%](img/responsive.jpeg)

---
- **Definition:** Flexibles Layout, bei dem sich Navigation, Inhalte und Struktur automatisch der Bildschirmauflösung des Endgeräts anpassen (Desktop, Tablet, Smartphone).
- **Notwendigkeit:** Smartphones sind ständiger Begleiter; über die Hälfte aller Nutzer surft mobil (Tendenz steigend).
- **Ziel:** Gewährleistung einer gleichwertigen Benutzerfreundlichkeit auf allen Gerätetypen.

---

### SEO - Search Engine Optimization

**Mobile-First-Indexing:**
- Google bewertet mobil-optimierte, responsive
Webseiten bevorzugt (höheres Ranking).

**Ladezeiten (Page Speed):**
- Schnelle, optimierte Seiten verringern
Absprünge.
- Performance ist ein direkter Rankingfaktor 
Core Web Vitals).
![bg right:50%](img/seo.jpg)

---

**Nutzererfahrung (UX) & User Signals:**
  - Intuitive Navigation erhöht die Verweildauer (Dwell Time) der Besucher.
  - Ansprechendes Design senkt die Absprungrate (Bounce Rate) – ein wichtiges Qualitätssignal für Google.
- **Semantische Struktur & Barrierefreiheit:**
  - Sinnvolle Überschriftenhierarchien (H1-H6) und beschreibende Alt-Texte helfen Screenreadern *und* Suchmaschinen-Crawlern.
- **Saubere Codestruktur:** Die klare Trennung von Inhalt (HTML) und Gestaltung (CSS) erleichtert Crawlern das effiziente Auslesen und Indexieren der Seite.

---
**20 Tips zur SEO-Optimierung:**

**Inhalt & On-Page-Faktoren**
1. Keyword-Recherche: Zielgerichtete Suchbegriffe identifizieren und passend einsetzen.
2. Einzigartiger Content: Hochwertige Inhalte mit echtem Mehrwert schaffen (Plagiate vermeiden).
3. Aussagekräftige Title-Tags: Wichtige Keywords an den Anfang setzen (max. 60 Zeichen).
4. Meta-Descriptions: Klickstarke, animierende Kurzzusammenfassungen schreiben.
5. Klare Überschriften (H1–H6): Strukturierte Text-Hierarchie mit Fokus-Keywords nutzen.

---

6. Bild-Alt-Attribute: Bildinhalte verständlich für Crawler und Screenreader beschreiben.
7. Bildkomprimierung: Dateigrößen vor dem Upload minimieren, um Ladezeiten zu sparen.
8. Sprechende URLs: Lesbare, kurze und logische URL-Strukturen verwenden.
9. Interne Verlinkung: Seitenlogik durch sinnvolle Querverweise stärken.
10. Suchintention erfüllen: Inhalte exakt an dem ausrichten, was der Nutzer sucht.

---
**Technik & Off-Page-Faktoren**

11. Responsive Webdesign: Volle Mobilfreundlichkeit auf allen Endgeräten sichern.
12. Ladezeitoptimierung: Server-Antwortzeiten senken und Skripte minimieren (Page Speed).
13. SSL-Verschlüsselung (HTTPS): Sicherheitszertifikat hinterlegen (Standard und Rankingfaktor).
14. XML-Sitemap: Den Crawling-Prozess für Google-Bots erleichtern.
15. Robots.txt pflegen: Crawling-Berechtigungen gezielt steuern.

---

16. Strukturierte Daten: Schema.org-Markup verwenden, um Rich Snippets in der Suche zu erzeugen.
17. Broken Links beheben: Defekte Verlinkungen (404-Fehler) aufspüren und umleiten.
18. Canonical Tags: Duplicate Content (doppelte Inhalte) technisch ausschließen.
19. Hochwertige Backlinks: Links von vertrauenswürdigen, themenrelevanten Webseiten erhalten.
20. Google Business Profile: Lokale Auffindbarkeit (Local SEO) einrichten und pflegen.

---
<!--_class: structural  -->

## Bevor wir beginnen!!!
- Urheberrecht
- Impressumspflicht
- Datenschutzerklärung
- Cookies


---

### Urheberrecht
>https://www.gesetze-im-internet.de/urhg/index.html

![bg right](img/urheberrecht-gesetz.jpg)

---

copy & paste?
Das Urheberrecht bezeichnet zunächst
das subjektive und absolute Recht
auf den Schutz geistigen Eigentums
in ideeller und materieller Hinsicht.

>>Recherchieren Sie VOR DER VERÖFFENTLICHUNG, ob und wer Rechte an dem Material (Bilder und Texte) Ihrer Webseite hat.

![bg right:50%](img/urheberrecht.jpg)

---
### Impressumspflicht

**Definition:**
Vorgeschriebene Anbieterkennzeichnung und Herkunftsangabe einer Webseite zur direkten Kontaktaufnahme.

**Gesetzliche Grundlagen:**
Geregelt in **§ 5 DDG** (Digitale-Dienste-Gesetz) und **§ 18 MStV** (Medienstaatsvertrag).

---


**Wer ist verpflichtet?**
- **Gewerbliche Nutzung (§ 5 DDG):** Alle geschäftsmäßigen Onlinedienste und Webseiten mit kommerziellem Hintergrund.
- **Redaktionelle Inhalte (§ 18 MStV):** Alle Webseiten mit journalistisch-redaktionellen Texten/Beiträgen.
- **Privat-Ausnahme:** Nur rein private/familiäre Seiten (Vorsicht: Werbeschaltung hebt die Befreiung auf).

---

> **Empfehlung:** Zur Vermeidung von Abmahnungen auch bei privaten, aber öffentlichen Seiten ein Impressum einrichten.
![bg right](img/abmahnung.jpg)
---
**Pflichtangaben im Impressum**

- **Name & Rechtsform:** Name des Betreibers/ Gesellschaft.
- **Anschrift:** Ladungsfähige physische Adresse (keine Postfachadresse).
- **Schneller Kontakt:** E-Mail & Telefonnummer (Fax 🙂 )
- **Register:** Registergericht & Registernummer (falls eingetragen).
- **Steuern:** Umsatzsteuer-Identifikationsnummer (USt-IdNr.) oder Wirtschafts-ID.
- **Spezialangaben:** Berufsspezifische Kammerdaten, Berufsbezeichnung sowie zuständige Aufsichtsbehörde.

---
### Datenschutzerklärung

> „Ich betreibe eine kleine Seite, auf der ich für meine Familie und Freunde Inhalte zu Verfügung stelle. Benötige ich für diese private Seite eine Datenschutzerklärung?“

---

**Antwort:**
Grundsätzlich gilt: Wer eine Webseite betreibt, muss mindestens die Informationen gem. **§ 5 Abs. 1 DDG** zur Verfügung stellen und über die Verarbeitung von personenbezogenen Daten informieren. Selbst wenn keine Analyse-Tools oder Kontaktformulare eingebaut sind, erfolgt beim Aufruf der Seite eine Datenverarbeitung, da der Webserver die **IP-Adresse** des Nutzers protokolliert (Server-Logfiles). Daher ist für so gut wie jede Webseite eine Datenschutzerklärung erforderlich, um den Informationspflichten der **DSGVO** nachzukommen.

---


**Gesetzliche Grundlage:** DSGVO (EU-Datenschutz-Grundverordnung) und BDSG (Bundesdatenschutzgesetz).

- **Wann benötigt?** Praktisch immer! Sobald personenbezogene Daten verarbeitet werden.
- **Schon gewusst?** Bereits die Übermittlung und Speicherung der **IP-Adresse** in den Server-Logfiles beim Webseitenaufruf gilt als Datenverarbeitung.
- **Fazit:** Jede öffentliche Webseite braucht eine Datenschutzerklärung (Informationspflicht nach Art. 13 DSGVO).

---

**Typische Auslöser auf Webseiten**

Sobald mindestens eines der folgenden Elemente genutzt wird:
- **Kontaktformulare** (E-Mail, Name)
- **Webanalyse & Tracking** (Google Analytics, Matomo etc.)
- **Social-Media-Anbindungen** (Share-Buttons, Widgets)
- **Externe Einbindungen** (Google Fonts, YouTube-Videos, Maps)
- **Newsletter-Registrierung**
- **Cookies** (zu Marketing- oder Analysezwecken)

---
> Muss ich dann zum Anwalt???

**Im Zweifel ja!**

Aber:
Eine Datenschutzerklärung wird häufig über einen Online-Generator erzeugt:

https://datenschutz-generator.de/
https://www.e-recht24.de/muster-datenschutzerklaerung.html


---

### Cookies

**Definition:**
Textdateien, die Informationen enthalten
und im Browser gespeichert werden können.
Sie dienen der Identifikation,
dem Merken von Zuständen oder
der Analyse des Nutzerverhaltens.
![bg right](img/cookies.jpg)

---

**Aufbau einer Cookie**
- Cookie vom Webserver an Browser
- oder im Browser von Skript (JavaScript) erzeugt
- Webserver kann bei späteren, erneuten Besuchen Cookie-Information direkt auslesen
- oder über ein Skript der Website die Cookie-Information an den Server übertragen

---
**Aufgabe von Cookies:**
- Identifizierung des Surfers (Session ID)
- Abspeichern eines Logins
- Abspeichern eines Warenkorbs
- Webtracking von Nutzern mit speziell präparierten Seiten.

---
**Brauche ich einen Cookie Warner?**

**Gesetzliche Grundlage:** **§ 25 TDDDG** (Telekommunikation-Digitale-Dienste-Datenschutz-Gesetz).

- **Nein, wenn** ausschließlich **technisch notwendige Cookies** verwendet werden (z. B. für Warenkörbe, Loginsessions, Sprachauswahl oder den Cookie-Banner selbst).
- **Ja, wenn** technisch **nicht notwendige Cookies** oder Skripte geladen werden (z. B. Tracking- & Marketing-Tools, Google Analytics, YouTube-Embeds, Google Maps).

---
**Anforderungen an ein rechtskonformes Consent-Banner**

- **Aktive Einwilligung (Opt-In):** Cookies dürfen erst nach aktiver Zustimmung des Nutzers gesetzt werden.
- **Gleichwertigkeit:** Der Button „Ablehnen“ muss auf derselben Ebene und visuell gleichwertig zum „Akzeptieren“-Button sein.
- **Keine Voreinstellungen:** Häkchen bei nicht notwendigen Diensten dürfen nicht vorab ausgefüllt sein.
- **Transparenz:** Vollständige Aufklärung über Anbieter, Zweck und Lebensdauer der gesetzten Cookies.


---

> Tipp: In Chrome können Sie unter „Einstellungen > Datenschutz und Sicherheit > Cookies und andere Websitedaten > Alle Cookies und Websitedaten“ anzeigen lassen, ob Ihr Server / Seite Cookies setzt.

---
<!--_class: structural  -->
## Entstehung der HTML-Sprache
![bg](img/entstehung-html.jpg)

---
### Wer hat´s erfunden?

- **Tim Berners-Lee** (britischer Physiker und Informatiker)
- **Wo:** Am **CERN** (Europäische Organisation für
Kernforschung) in Genf
- **Wann:** Entwickelt ab **1989**, vorgestellt **1990/1991**
- **Ursprünglicher Zweck:** Wissenschaftler sollten Forschungsergebnisse unkompliziert austauschen und verlinken können
- **Das Gesamtkonzept:** Er erfand gleichzeitig das
**HTTP-Protokoll**, die **URL** (Webadresse) sowie
den ersten Webbrowser/Webserver –
das Fundament des heutigen World Wide Web (WWW)
![bg right:40%](img/Sir_Tim_Berners-Lee.jpg)

---
### Die Zeit vor der Entwicklung des World Wide Web
- Kein html 
- Brief? Fax? Telefon?
- Keine schnellen Möglichkeiten zum Informationsaustausch
- Kein Dokumentenaustausch mit mehreren Personen

Benötigt werden:
- Übertragungsprotokolle
- Dateiformate
- Quelloffene Standards

---
### Warum gerade am CERN?

- **Riesige Datenmengen & Forscher-Netzwerke:**
Tausende Wissenschaftler weltweit arbeiteten an gemeinsamen physikalischen Projekten.
- **Inkompatible Computersysteme:**
Forscher nutzten unterschiedlichste Hardware & Software; der Dokumentenaustausch war extrem mühsam.
- **Fehlende Verknüpfung:** Es gab keine Methode,
um Informationen auf verschiedenen Servern direkt miteinander in Beziehung zu setzen.
![bg right:40%](img/cern.jpg)

---

> Die Hypertext-Lösung: HTML ermöglichte es, Dokumente plattformunabhängig darzustellen und über Hyperlinks direkt miteinander zu verknüpfen.
Ein flexibles System sollte Berichte, Handbücher und Protokolle für alle Forscher netzwerkweit auffindbar machen.

![bg](img/entstehung-html-2.jpg)


---

**Filmtipp:**
Jurassic Web
Der Film erzählt die unbekannte Geschichte
dieser Wegbereiter der digitalen Welt und
ihrer Nutzungsmöglichkeiten
– die Urgeschichte der sozialen Netzwerke!

Nur erhältlich:
>Bei mir :)

![bg left](img/jurassic-web.jpg)




---
<!--_class: structural  -->
## Basiswissen
- HTML
- Webserver
- Protokolle (http / https / ssl / ftp)
- Zertifikate
- Domain
- Webspace
- FTP-Client
- Browser

---

### HTML

> HTML = Hypertext Markup Language. Hypertext > Verlinkung von Webseiten




---


- "Markup Language" > Auszeichnungssprache > um Dokumente für Webbrowser strukturiert zu beschreiben
- Webseiten werden NICHT programmiert, sondern geschrieben
- Mit HTML-Tags werden Textpassagen ausgezeichnet
- sie kennzeichnen die logische Bedeutung des Textes.
- Bilder, Webseiten, Videos, Musik etc. werden lediglich verlinkt & nicht im html gespeichert!
- flexibel, skalierbar, plattformunabhängig
- html-Seiten werden immer interpretiert & sehen auf jedem Gerät anders aus! 

---
### Beispiel Tag Paragraph

Das Tag Paragraph steht für einen Textabsatz. Dabei leitet das Tag `<p>` den Paragraph ein und `</p>` beendet diesen.
Mit wenigen Ausnahmen (leeren Elementen) besteht ein Tag immer aus einem öffnenden und einem schließenden Element.


```html
<p>Dies ist ein Paragraph.</p>
```

---
### HTML Spezifikation

> 3ter November 1992 erschien die erste Version der HTML-Spezifikation.
- Dateiendung: .html, .htm
- MIME-Type: text/html
- Entwickelt von: World Wide Web Consortium (W3C)
- Aktuelle Version: 5.2 (Stand: 14. Dezember 2017)
- Art: Auszeichnungssprache
Erweitert zu: XHTML, HTML5

(Wikipedia)
![bg right](img/html-spezifikation.jpg)


---
### Webserver

> Wie kommt die Webseite
zum User?

- Html-Dokument =
Textdatei mit spezieller Kodierung
- Alle benötigten Dokumente müssen
auf einen Webserver
- Mit Webspace
- Webserver = Computer, der
unter bestimmter Domain
über das http Protokoll erreichbar ist
![bg right](img/webserver.jpg)

---

- Text wird als Textdatei mit Endung htm/html gespeichert und auf einem Webserver abgelegt
- Webserver = lateinisch servire ‚dienen‘; englisch server ‚Diener‘, ‚Dienst‘
- Server überträgt Dokumente an Clients wie z. B. Webbrowser
- Webserver = Computer mit Webserver-Software
- Häufig wird auch die Webserver-Software so bezeichnet


---

**Webserver können**

- lokal, in Firmennetzwerken
- oder WWW-Dienst im Internet eingesetzt werden
- Dokumente können somit lokal, firmenintern und weltweit
zur Verfügung gestellt werden

---

**Hauptaufgabe eines Webservers**

- Auslieferung von statischen Dateien
- Html-Dateien
- css
- Bild Dateien
- Script Dateien
- Videos
- Uvm
![bg right](img/webserver-system.jpg)

---

> Für komplette Webseite werden benötigt:
- HTML-Seite
- verknüpfter Designbeschreibungen (CSS)
- Bilddateien (JPG, PNG, GIF, SVG)
- Scripte

> Eine komplexen Webseite kann
> hunderte Anfragen und Serverantworten benötigen.
![bg right](img/webserver-farm.jpg)
---
**Webserver ist in der Lage:**

- die Inhalte einer Webseite
- gleichzeitig
- auf viele verschiedene Rechner auszuliefern
- Scripte auszuführen
- Datenbankanbindungen bereitzustellen
- Datenbankinhalte bereitzustellen
- Geschwindigkeit abhängig von Anzahl der Nutzeranfragen & Komplexität der Webinhalte
- uvm.
- dynamische Webinhalte benötigen mehr Ressourcen als statische

---
**Bekannte Beispiele für Webserver**

- Apache / XAMPP
- Nginx
- Microsoft IIS
- uvm:
https://en.wikipedia.org/wiki/Category:Free_web_server_software

---
**Apache**

HTTP Server ist:
- quelloffene
- freies Produkt
- von der Apache Software Foundation
- einer der meistbenutzten Webserver
[https://www.apache.org/](https://www.apache.org/)


![bg right](img/apache.jpg)

---
### Protokolle
- HTTP - Hypertext Transfer Protocol
- HTTPS - Hypertext Transfer Protocol Secure
- SSL - Secure Sockets Layer
- FTP - File Transfer Protocol

---
**HTTP-Protokoll***
> Hypertext Transfer Protocol

- Netzwerkprotokolle wie IP und TCP
- üblicherweise über Port 80 (HTTP)

---
**Schichtenmodell der Netzwerkkommunikation**

HTTP["Anwendungsschicht: HTTP (WAS wird übertragen?) Format der Webinhalte (z. B. HTML)"] 

--> TCP["Transportschicht: TCP (WIE wird es übertragen?) <br> Zuverlässigkeit, Fehlerkontrolle, Ports (z. B. Port 80)"]

--> IP["Netzwerkschicht: IP (WOHIN wird es übertragen?) <br> Adressierung (IP-Adressen) und Routing"]


---

**Definition & Zweck:**
- Zustandsloses Protokoll zur Übertragung von Daten (HTML, CSS, JS, Bilder, Videos) im Web.
- Regelt die Kommunikation zwischen Webbrowser (Client) und Webserver.

---


**Client-Server-Modell:**
- Request (Anfrage): Client fordert eine Ressource an (z. B. beim Klick auf einen Link).
- Response (Antwort): Server liefert die Ressource zurück (z. B. die HTML-Datei).

---

**Zustandslosigkeit (Stateless):**
- Jede Anfrage wird völlig unabhängig von vorherigen Anfragen behandelt.
- Der Server speichert standardmäßig keine Verbindungsinformationen (daher werden Cookies oder Sessions für Logins/Warenkörbe benötigt).

---
**Methoden:**

| Methode | Verwendung |
|---------|------------|
| GET     | Daten auslesen / Seite laden. |
| POST    | Daten übertragen (Formulare, Uploads). |
| PUT     | Daten komplett ersetzen. |
| DELETE  | Daten löschen. |

---
**HTTP-Statuscodes (Antwort des Servers):**

| Code | Status | Bedeutung |
|------|--------|-----------|
| 200  | OK     | Anfrage erfolgreich. |
| 301/302 | Redirection | Umleitung auf eine andere URL. |
| 404  | Not Found | Die angeforderte Datei existiert nicht (Client-Fehler). |
| 500  | Internal Server Error | Fehler auf dem Webserver. |

---

**Beispiel einer HTTP-Anfrage (GET):**

```
Anfrage des Browsers beim Server (vereinfacht):

GET /index.html HTTP/1.1
Host: www.beispiel.de

Antwort des Servers (vereinfacht): 

HTTP/1.1 200 OK
Content-Type: text/html

<html>...
```

--- 
**HTTP-Secure (HTTPS)**
- HTTPS ist die verschlüsselte Variante von HTTP
- SSL-Zertifikat
- Port 443

---
**Verschlüsselung zwischen Webserver und Browser**
- https-Verfahren wird von allen Browsern unterstützt
- https ist eine Sicherheits-Technologie die nicht installiert werden muss
- sofort ersichtlich
- einfach zu überwachen

---
> Eine HTTPS-Seite erkennen Sie daran, dass einerseits oben in der Adresszeile des Browsers der besagte Schriftzug steht, andererseits an dem verriegelten Schloss .
![bg right](img/https.jpg)


---
**SSL - Secure Sockets Layer**

- SSL ist die Verschlüsselungstechnologie,
die für HTTPS verwendet wird.
- Es stellt sicher, dass die Daten, die zwischen
Client und Server übertragen werden,
vertraulich und unverfälscht bleiben.
- SSL/TLS-Zertifikate werden von
Zertifizierungsstellen ausgestellt,
um die Identität einer Website zu verifizieren.

https://wiki.selfhtml.org/wiki/Grundlagen/HTTPS_und_TLS


---
**Zertifikate**

- Gültigkeit von ein bis zwei Jahren
- nach Ablauf kann es nicht mehr verwendet werden
- erforderlich für Online-Dienste
- erforderlich für Online-Shops
- erf

![bg right](img/Zertifikat.jpg)

---
**digitales Zertifikat**
- ist ein digitaler Datensatz
- nach Standards der ITU-T oder der IETF
- bestätigt bestimmte Eigenschaften von Personen oder Objekten
- prüft dessen Authentizität und Integrität
- durch kryptografische Verfahren
- enthält die zu seiner Prüfung erforderlichen Daten

---

> Wer verlängert das Zertifikat?

Technisch wird ein Zertifikat nicht verlängert, sondern **durch ein neues ersetzt**.
- **Certification Authority (CA):** Stellt das neue Zertifikat aus (z. B. Let's Encrypt).
- **Webhoster:** Übernimmt bei Standard-Webspaces die Erneuerung meist vollautomatisch.
- **Server-Administratoren:** Nutzen Bots (z. B. *Certbot* über das ACME-Protokoll), um Zertifikate auf eigenen Servern automatisch alle 60 bis 90 Tage zu erneuern.

---
### Webspace

> beschreibt den Speicherplatz auf einem Server, der zur Unterbringung von Dateien einer Website genutzt wird.

---

- **Speicherplatz** für Dateien auf einem (Web)Server
- Ist über das Internet **dauerhaft verbunden**
- Online-Speicherplatz wird häufig von **Internetdienstanbietern** bereitgestellt
- Kunden stellen Dokumente und Datenbestände (wie Musikdateien), Websites etc zur Veröffentlichung online
- Das Bereitstellen von Speicherplatz im Internet wird **Webhosting** oder auch **Nethosting** genannt
- Die Webserver großer Anbieter stehen in  **Rechenzentren**, in denen hunderte von Webservern Mailservern und Diensteanbietern ihre Dienste verrichten.


---
> HTTPS funktioniert nur dann optimal, wenn alle Inhalte, die auf einer Webseite dargestellt werden, über HTTPS geladen werden.

Werden zum Beispiel auf einer HTTPS-Seite externe Ressourcen wie Bilder, Skripte oder CSS-Dateien unverschlüsselt nachgeladen, spricht man von einem sogenannten Mixed-Content, der zu Problemen bei der sicheren Darstellung führen kann.

---
**Webhoster**

- Preis
- Speicherplatz
- Traffic
- Anzahl der Datenbanken
- Anzahl der E-Mail-Adressen
- Anzahl der Domains
- SSL-Zertifikat
- Support
- Serverstandort

![bg right](img/webhoster.jpg)

---

heise Webhoster-Vergleich
https://www.heise.de/download/specials/Webhosting-Vergleich-So-finden-Sie-den-passenden-Hosting-Anbieter-6037473


---
> Vorsicht bei Homepage-Baukästen:
Meist zielen die Angebote
darauf ab, den Kunden zu binden,
sodaß ein Wechsel zu einem
anderen Anbieter später nur
erschwert möglich ist.
![bg right](img/webhoster-server.jpg)

---

**Selber hosten? Geht das?**
> Ja. Dafür muss jedoch Ihr Rechner 24/7 am Netz in Betrieb sein.


Beachten Sie allerdiengs auch,
dass Ihr Provider das erlauben muss.
Viele DSL Anbieter sehen es nicht gerne,
wenn sie viele externe Zugriffe auf
Ihren Webserver haben.

> Lesen:

https://wiki.selfhtml.org/wiki/Webserver/SELF-Hosting


![bg right](img/selfhosting.jpg)


---
<!-- _class: img-right -->

### Domain & DNS: Grundlagen
- **Definition:** Eine Domain (dt. *Domäne/Bereich*) ist ein weltweit eindeutiger Name im hierarchischen **Domain Name System (DNS)**.
- **Zweck:** Übersetzung von IP-Adressen (z. B. `193.175.120.40`) in menschenlesbare Namen (z. B. `www.thws.de`).

![domain-hierarchy](img/domain-hierarchy.jpg)

---

- **Webspace-Erreichbarkeit:** Um eine Webseite online zu stellen, werden deren Daten auf einen Webspace geladen. Der Webserver macht diese unter der zugeordneten Domain erreichbar.
- **Hierarchischer DNS-Aufbau:**
  - **Root-Label (Wurzel):** Angedeutet durch den letzten Punkt (z. B. `www.thws.de.`).
  - **Top-Level-Domain (TLD):** `.de` (länderspezifisch/ccTLD) oder `.org` (allgemein/gTLD).
  - **Second-Level-Domain:** Der eigentliche Name (z. B. `thws`).



---


### Subdomains & Technische Limits
- **Subdomains:** Einer Domain können beliebig viele weitere Subdomains vorangestellt werden
(z. B. `elearning.thws.de`), abgetrennt durch einen Punkt.
- **Längenbeschränkungen (gemäß RFC 1035):**
  - **Pro Label** (Abschnitt zwischen zwei Punkten): **Maximal 63 Zeichen**.
  - **Gesamt-FQDN** (Fully Qualified Domain Name): **Maximal 253 Zeichen**
  in Textdarstellung (bzw. 255 Byte im DNS-Format).


---
<!-- _class: img-right -->

- **Adressierung:** Mit einem FQDN kann jedes physische oder virtuelle Objekt im Netz eindeutig adressiert werden.
- **Nameserver:** Speichern DNS-Einträge (z. B. A-Record für IPv4) und verbinden den Domain-Namen mit der IP-Adresse des Servers.

![dns](img/webserver-system.jpg)

---
<!-- _class: img-right -->

### Vergabestellen & DENIC

**https://www.denic.de/**

- **Registrar / NIC (Network Information Center):** Top-Level-Domain wird von Vergabestelle verwaltet: exakte Namensregeln:
- **DENIC eG (Frankfurt am Main):**
  - Zentrale Genossenschaft & Registrierungs-
  stelle für alle `.de`-Domains.
  - Verwaltet über 17 Millionen Domains (gehört weltweit zu den größten Länder-TLDs).

![denic](img/denic.png)

---

- **Namensregeln für `.de`:**
  - Erlaubt sind: Kleinbuchstaben (a-z), Ziffern (0-9) und Bindestrich (nicht an 1. oder letzter Stelle, nicht an 3. + 4. Stelle).
  - Umlaute (IDN-Domains wie `ä`, `ö`, `ü`) werden unterstützt.
  - Ein zustellungsbevollmächtigter Ansprechpartner in Deutschland wird benötigt.

---
**Muss ich dann immer zur DENIC?**
> Nein, das erledigt der Webhoster

https://www.ionos.de/
https://www.strato.de/
https://www.hostinger.com/
https://all-inkl.com/
https://checkdomain.de/

> Vergleicht die Angebote!
Welches ist das beste Angebot?

---
**Angebotskriterien:**
- Preis
- Speicherplatz
- Traffic
- Anzahl der Datenbanken
- Anzahl der E-Mail-Adressen
- Anzahl der Domains
- SSL-Zertifikat
- Support
- Serverstandort

---

<!-- _class: img-right -->
**Domainabfrage auf der DENIC-Webseite**

>Ist der gewünschte Domainname noch frei?

Hurra! Die Domain maiks-mobiler-service.de ist noch frei…

(äääh... eigentlich nicht mehr :) )

![alt text](img/denic-webseite.jpg)

---
<!-- _class: img-right -->

### Der „sprechende“ Domain-Name
- **Definition:** Domain-Name verrät beim Lesen Inhalt / Zweck/ Anbieter
- **Suchmaschinen-Relevanz (SEO):**
  - Suchmaschinen analysieren als Erstes Domain-Namen.
  - Ein sprechender Name fungiert als
  direkter Ranking-Faktor und erhöht Klickrate (CTR).
- **Vorteil:** Nutzer verstehen sofort, worum es geht – das schafft Vertrauen und stärkt die Barrierefreiheit/Verständlichkeit.

![domain-seo](img/domain-seo.png)

---
<!-- _class: img-right -->

### Kriterien zur Auswahl des Domain-Namens
- **Persönliche Marke (Identität):**
  - Steht eine Person oder ein persönlicher Service im Vordergrund?
  - *Tipp:* Den eigenen Namen integrieren (z. B. `maik-caravan.de`).
- **Lokaler Bezug (Geographie):**
  - Wird ein Service in einer bestimmten Stadt/Region angeboten?
  - *Tipp:* Ortsnamen einbauen (z. B. `autoinstandsetzung-wuerzburg.de`).
- **Nischen- / Kerntätigkeit (Dienstleistung):**
  - Bieten Sie eine außergewöhnliche oder sehr spezifische Leistung an?
  - *Tipp:* Kern-Keywords verwenden (z. B. `autarker-fahrzeugausbau.de`).

![domain-criteria](img/domain-criteria.png)

---
<!-- _class: img-right -->

### Best Practices & Fallstricke
- **Kurz & Einprägsam:** So kurz wie möglich, leicht zu schreiben und sich zu merken.
- **Bindestriche sinnvoll nutzen:**
  - Verbessert die Lesbarkeit(z. B. `maiks-mobiler-service.de` statt `maiksmobilerservice.de`).
  - Vermeidet Zweideutigkeiten.
- **Rechtliche Absicherung:**
  - Vor Registrierung prüfen: Keine Markenrechte / Firmennamen / geschützte Begriffe

![domain-checklist](img/domain-checklist.png)

---
> Die richtige TLD:
Für den deutschen Markt immer primär `.de` wählen.

Aber auch spezifische Domains sind möglich:
**`.ai`** ist die TLD für "Caribbean island of Anguilla"
 :)

**`.edu`** Domain ist streng limitiert und steht offiziell fast ausschließlich US-amerikanischen, staatlich akkreditierten Bildungseinrichtungen zur Verfügung. Internationale oder private Institutionen können diese meist nicht registrieren.

**`.com`** ist die TLD für kommerzielle Unternehmen und Organisationen weltweit & wirkt professionell.

---
<!-- _class: img-right -->

### FTP: Grundlagen & Dateitransfer
- **Definition:** Das **File Transfer Protocol (FTP)** Netzwerkprotokoll zur Übertragung von Dateien über IP-Netzwerke.
- **Zustandsbehaftet:** Der Server speichert während einer Sitzung den Zustand (z. B. das aktuelle Arbeitsverzeichnis).
- **Funktionen:** Upload (Client → Server), Download (Server → Client), Datei- & Verzeichnisverwaltung (Erstellen, Löschen, Umbenennen).

![ftp-basics](img/ftp-basics.png)

---

### FTP-Verbindungsaufbau: Aktiv vs. Passiv
- **Zwei getrennte Kanäle:**
  - **Steuerkanal (Control Port 21):** Client initiiert TCP-Verbindung für Befehle & Statuscodes.
  - **Datenkanal:** Übertragung der eigentlichen Dateiinhalte.

---
<!-- _class: img-right -->
- **Aktives FTP (PORT):**
  - Server initiiert die Datenverbindung aktiv zum Client (Port 20 → Client).
  - *Problem:* Client-Firewalls/NAT blockieren oft den eingehenden Zugriff vom Server.
- **Passives FTP (PASV):**
  - Client initiiert die Datenverbindung zu
  einem vom Server vorgegebenen Port.
  - *Standard im Webhosting,* da firewallsicher für den Client.

![ftp-modes](img/ftp-modes.jpg)

---
<!-- _class: img-right -->

### FTP-Sicherheit & FTP-Clients
- **Das Sicherheitsrisiko:** Klassisches FTP überträgt Zugangsdaten (Benutzer/Passwort) und Dateien **unverschlüsselt** im Klartext.
- **Sichere Alternativen (Standard heute):**
  - **SFTP (SSH File Transfer Protocol):** Komplett verschlüsselte Übertragung über SSH (Port 22).
  - **FTPS (FTP over SSL/TLS):** Verschlüsseltes FTP (Port 21 mit Explicit TLS oder Port 990).

![ftp-security](img/ftp-security.png)

---
<!-- _class: img-right -->

- **FTP-Clients:** Spezialisierte Software wie **FileZilla** (Open Source, plattformunabhängig) ermöglicht einfache Übertragung per Drag-and-Drop.

![ftp-client](img/ftp-client.jpg)


---

## Eine Testumgebung
- XAMPP
- Mongoose
- Chrome
- Git

---
<!-- _class: img-right -->

### XAMPP: Lokale Testumgebung
- **Was ist XAMPP?** Ein kostenloses Softwarepaket zur lokalen Simulation eines Webservers.
- **Namensbedeutung:** **X** (plattformübergreifend), **A** (Apache Webserver), **M** (MariaDB/MySQL Datenbank), **P** (PHP Skriptsprache), **P** (Perl).

![xampp](img/xampp.jpg)

---
<!-- _class: img-right -->
- **Installationstipps für Einsteiger:**
  - **WICHTIG:** Unter Windows *nicht* in `C:\Program Files` installieren, sondern direkt in `C:\xampp\` ablegen (verhindert Rechteprobleme / UAC-Fehler).
  - Setup-Auswahl: Für unsere Zwecke reichen Apache, MySQL und PHP vollkommen aus.

![xampp-install](img/xampp-install.png)

---

<!-- _class: img-right -->

### Bedienung & Portkonflikte
- **Starten der Dienste:** Das *XAMPP Control Panel* öffnen und bei **Apache** und **MySQL** auf *Start* klicken (Status leuchtet grün).
- **Standard-Ports:** Apache belegt standardmäßig Port **80** (HTTP) und **443** (HTTPS).

![xampp-control](img/xampp-control.png)

---

<!-- _class: img-right -->
- **Häufiger Fehler (Apache startet nicht):**
  - Port 80 ist oft durch Skype, Teams oder
  IIS blockiert.
  - *Lösung:* Im Control Panel auf *Config* bei Apache klicken, `httpd.conf` öffnen, nach `Listen 80` suchen und auf z. B. `Listen 8080` ändern.

![alt text](img/xampp-port.jpg)

---
<!-- _class: img-right -->

### Webseiten ablegen & lokal testen
- **Der htdocs-Ordner:** Der zentrale Speicherort für alle eigenen Webdateien (`.html`, `.css`, `.js`) liegt unter `C:\xampp\htdocs\`.
- **Projekt-Struktur:**
  - Erstelle dort einen eigenen Ordner für dein Projekt (z. B. `htdocs\mein-projekt\`).

![xampp-htdocs](img/xampp-htdocs.png)


---
<!-- _class: img-right -->

### Aufruf im Browser
- **Startseite der Testumgebung:**
  - `http://localhost/` oder `http://127.0.0.1/` eingeben.
  - Leitet automatisch auf die XAMPP-Dashboard-Startseite weiter.
- **Dein Projekt aufrufen:**
  - Adresse zusammensetzen aus localhost + Projektverzeichnis + Datei:
  - `http://localhost/mein-projekt/index.html`

![xampp-localhost](img/xampp-localhost.png)

---

### Was ist „localhost“?
- **Bedeutung:** Der Standard-Hostname für den eigenen, lokalen Computer (auch *Loopback-Adresse* genannt).
- **IP-Adresse:** Löst standardmäßig auf die IP-Adresse `127.0.0.1` (IPv4) bzw. `::1` (IPv6) auf.

---

- **Funktionsweise:** Alle Anfragen an `localhost` verlassen den Rechner nicht, sondern werden 
netzwerkintern direkt an das eigene System zurückgeschleift.
- **Zweck beim Webdesign:**
  - Testen von Webseiten auf dem eigenen Server (z. B. Apache unter XAMPP), ohne dass eine Internetverbindung benötigt wird.
  - Schutz der Entwicklungsumgebung vor unbefugtem Zugriff von außen.

---

### Mongoose: Die XAMPP-Alternative
https://mongoose.ws/binary/
- **Was ist Mongoose?** Ein extrem leichtgewichtiger Webserver für statische Webseiten.
- **Vorteil:** Keine Installation nötig! Er besteht aus einer einzigen Datei (`mongoose.exe`).
- **Ideal für Einsteiger:** Wenn du nur HTML, CSS und JavaScript testen willst (kein PHP oder MySQL), ist Mongoose viel einfacher als das mächtige XAMPP.
- **So einfach geht's:**
  1. `mongoose.exe` herunterladen.
  2. Direkt in deinen Projektordner (neben die `index.html`) kopieren.
  3. Per Doppelklick starten.
  4. Webadresse `http://localhost:8080` im Browser aufrufen.

---

### Mongoose: Praxis-Tipps & Gefahren
- **Wo läuft der Server?** Nach dem Start öffnet sich kein großes Fenster. Mongoose nistet sich lautlos im **Infobereich (System Tray)** unten rechts neben der Uhr ein (rotes Symbol).
- **Beenden:** Rechtsklick auf das rote Mongoose-Symbol im Infobereich -> *Exit*.
- **⚠️ ACHTUNG: Mehrfachausführung vermeiden!**
  - Klicke die `mongoose.exe` nur **einmal** an. Startest du sie mehrfach (z. B. aus zwei Projektordnern), schlägt die Portbindung fehl.
- **⚠️ ACHTUNG: Parallelbetrieb blockiert Ports!**
  - Jeder Port (standardmäßig `8080`) kann nur von **einem** Programm belegt werden.
  - Läuft bereits XAMPP (Apache) oder ein anderes Mongoose auf demselben Port, kommt es zu Konflikten. Beende immer den alten Server, bevor du einen neuen startest!

---
<!-- _class: structural -->
## Websitedarstellung im Browser
- Rendering im Browser
- Die Browser-Welt
- Browsercache
- Entwicklertools F12
- Formatierung von Webseiten mit CSS

---
<!-- _class: img-right -->

### Was ist Browser-Rendering?
- **Definition:** Der Prozess, bei dem ein grafischer Browser aus Programmcode (HTML, CSS, JS) und Ressourcen (Bilder, Schriften) eine interaktive Webseite visuell aufbaut.
- **Rendering Engine:** Das Herzstück des Browsers zur Code-Interpretation und Darstellung.

![browser-rendering](img/browser-rendering.png)

---

- **Die drei dominierenden Engines (Stand 2026):**
  - **Blink** (Chromium-Projekt: Google Chrome, Microsoft Edge, Opera, Brave).
  - **Gecko** (Mozilla Firefox).
  - **WebKit** (Apple Safari).

---
<!-- _class: img-right -->

### Webseiten sind kein starres PDF!
- **Das fluide Web:** html ist flexibel!
- **Einflussfaktoren:** Display-Größe (Mobil bis Desktop), Betriebssystem, Auflösung, installierte Schriften, Benutzereinstellungen.
- **Paradigmenwechsel beim Design:**
  - *Früher:* Der starre Versuch, Webseiten überall exakt identisch aussehen zu lassen („Pixel-Perfect“).
  - *Heute:* **Responsive & Adaptive Webdesign** (Layouts fließen und passen sich dynamisch an).

![fluid-layout](img/fluid-layout.png)

---


### Wann ist ein Layout „korrekt“?

<br>

> Darstellungsunterschiede zwischen Browsern sind normal – solange die **Funktionalität & Usability** gewährleistet bleibt!

---
<!-- _class: img-right -->
**Die 4 goldenen Regeln der Usability:**
  1. **Lesbarkeit:** Alle Texte müssen
  ungehindert lesbar sein.
  2. **Navigation:** Bedienelemente müssen auffindbar sein & wie erwartet reagieren.
  3. **Interaktivität:** Formulare müssen sich problemlos ausfüllen & absenden lassen.
  4. **Logik:** JavaScript-Funktionen müssen fehlerfrei laufen & das richtige Ergebnis liefern.

![rendering-checklist](img/rendering-checklist.png)

---

<!-- _class: img-right -->

### Die Browser-Welt: Marktanteile
- **Google Chrome:** ~70% (Dominant auf Desktop und Android).
- **Apple Safari:** ~15% (Starker Marktanteil durch iOS).
- **Microsoft Edge:** ~5% (Stärker auf Windows-Desktops).
- **Mozilla Firefox:** ~2% (Unabhängige Alternative).
- *Tipp:* Marktanteile variieren regional stark – in den USA liegt Safari z. B. bei über 30%.
- **Quelle:** [Statcounter Global Stats](https://gs.statcounter.com/)

![browser](img/browser.jpg)

---
<!-- _class: img-right -->

**Technischer Vergleich & Engines**
**Blink (Chrome, Edge, Opera, Brave):**
  - Schnelle V8 JavaScript Engine, größte Erweiterungsauswahl.
  - *Kritik:* Hoher Arbeitsspeicherverbrauch (RAM).

![chrome](img/chrome.jpg)

---
<!-- _class: img-right -->

**WebKit (Safari):**
  - Extrem akkuschonend und tief in macOS/iOS integriert.
  - Standardbrowser auf allen Apple-Geräten.
  - *Kritik:* Manchmal zögerliche oder verzögerte Unterstützung neuer Webstandards.

![safari](img/safari.jpg)

---
<!-- _class: img-right -->

**Gecko (Firefox)**

  - Unabhängig und quelloffen. Starke Datenschutzfeatures (Container-Tabs).
  - *Tipp:* Beste DevTools für CSS Grid/Flexbox.
- **Quelle:** [Can I use...](https://caniuse.com/)

![firefox](img/firefox.jpg)

---


**Praxistipps für Webentwickler**
- **Cross-Browser-Testing:** Teste deine Webseiten immer auf mindestens drei unterschiedlichen Rendering-Engines (Blink, WebKit, Gecko).
- **Kompatibilität prüfen:** Nutze [Can I use...](https://caniuse.com/) vor dem Einsatz neuer CSS-/JS-Features.
- **DevTools gezielt einsetzen (F12):**
  - Firefox für Layout-Debugging (Grid/Flexbox).
  - Chrome für Performance- und JavaScript-Analysen.
- **Quelle:** [MDN Web Docs](https://developer.mozilla.org/)

---
### Der Browser-Cache in der Webentwicklung
- **Definition:** Lokaler Pufferspeicher des Webbrowsers, der bereits heruntergeladene Ressourcen (Bilder, CSS, JS, HTML) auf dem Rechner des Nutzers zwischenspeichert.
- **Vorteile:** 
  - **Page Speed:** Beschleunigt das Laden von Folgeseiten erheblich.
  - **Netzwerkschonung:** Reduziert den Datenverkehr und entlastet den Webserver.
- **Das Entwickler-Problem:** 
  - Änderungen an CSS- oder JS-Dateien werden beim einfachen Neuladen oft nicht angezeigt, weil der Browser die veraltete Version aus dem Cache lädt.
---
<!-- _class: img-right -->

### Entwicklertools: Werkzeuge für Profis
- **Definition:** Die Entwicklertools (oft *DevTools* oder *F12-Tools*) sind ein mächtiges, integriertes Werkzeugset in jedem modernen Browser.
- **Bedeutung:** Das wichtigste Instrument für Webentwickler, um Webseiten live zu analysieren, Fehler zu beheben und Performance zu optimieren.
- **Aufruf:** Taste `F12` oder `Strg + Umschalt + I` (Windows) bzw. `Cmd + Opt + I` (macOS).

![devtools](img/devtools.jpg)

---
<!-- _class: img-right -->

### Was du mit den DevTools machen kannst:
- **HTML & CSS inspizieren:** Live-Änderungen am Layout vornehmen und sofort sehen, wie sich das Design verändert.
- **Performance messen:** Ladezeiten analysieren und Optimierungspotenziale identifizieren.
- **Netzwerkverkehr beobachten:** Alle Anfragen an den Server verfolgen und prüfen, ob alle Ressourcen korrekt geladen werden.
- **JavaScript-Code debuggen:** Fehler im Skript finden und die Ausführung schrittweise nachvollziehen.
- **Mobile Ansichten simulieren:** Testen, wie die Webseite auf unterschiedlichen Gerätegrößen und Auflösungen aussieht.

![devtools](img/devtools.jpg)

---
<!-- _class: img-right -->

### 1. Elemente (Elements)
- **Das DOM inspizieren:** Zeigt den aktuellen Zustand des **DOM (Document Object Model)** an – also die Live-Baumstruktur aller HTML-Elemente.
- **Live-Editing:** Ermöglicht das temporäre Bearbeiten von HTML-Tags, Attributen und Texten direkt im Browser.
- **CSS-Entwicklung:** Stylesheets einsehen, Regeln an- und ausschalten oder neue CSS-Eigenschaften live testen.

![devtools-elements](img/devtools-elements.jpg)

---
<!-- _class: img-right -->

### 2. Konsole (Console)
- **Fehlerprotokoll:** Der zentrale Ort für Fehlermeldungen von JavaScript und Netzwerkproblemen (z. B. blockierte Ressourcen).
- **Interaktivität:** Erlaubt das Ausführen von JavaScript-Befehlen direkt im Kontext der geladenen Seite.
- **Debugging:** Ausgabe von Debug-Informationen mittels `console.log()`.

![devtools-console](img/devtools-console.jpg)

---
<!-- _class: img-right -->

### 3. Netzwerk (Network)
- **Datenverkehr überwachen:** Detaillierte Ansicht aller Ressourcen (HTML, CSS, JS, Bilder), die zwischen Browser und Server ausgetauscht werden.
- **Metriken:** Zeigt Ladezeiten, HTTP-Statuscodes, Dateigrößen und Antwort-Header an.
- **Fehlersuche:** Ideal zum Aufspüren von nicht gefundenen Dateien (404) oder langsamen Ladezeiten.

![devtools-network](img/devtools-network.jpg)

---
<!-- _class: img-right -->

### 4. Quellen (Sources)
- **Datei-Explorer:** Zeigt alle geladenen Quelldateien der Website an.
- **Code-Debugging:** Ermöglicht das Setzen von **Breakpoints** in JavaScript.
- **Schritt-für-Schritt-Ausführung:** Der JS-Code kann an bestimmten Zeilen angehalten und Variablen-Werte live inspiziert werden.

![devtools-sources](img/devtools-sources.jpg)

---
<!-- _class: img-right -->

### 5. Performance & Lighthouse
- **Laufzeit-Analyse:** Aufzeichnung und Analyse der Rendering-Performance der Seite.
- **Lighthouse-Audits:** Automatisierter Report von Google zu den vier Kernbereichen:
  - Performance (Ladezeit)
  - Accessibility (Barrierefreiheit)
  - Best Practices
  - SEO (Suchmaschinenoptimierung)

![devtools-lighthouse](img/devtools-lighthouse.jpg)

---
<!-- _class: img-right -->

### Praxistipp: Responsive Design testen
- **Geräte-Modus:** Simuliert verschiedene Smartphones und Tablets (z. B. iPhone oder Pixel) direkt auf dem Bildschirm.
- **Touch-Simulation:** Mauszeiger wird zum Touch-Cursor, um Wisch-Gesten und Touch-Events zu testen.
- **Viewport-Flexibilität:** Beliebiges Skalieren der Breite, um die Breakpoints des CSS-Layouts zu prüfen.

![devtools-responsive](img/devtools-responsive.jpg)

---

**Zusammenfassung der Tools:**

| Reiter | Hauptzweck |
|---|---|
| **Elemente** | HTML/CSS-Struktur und Live-Styling |
| **Konsole** | Debugging von JavaScript-Fehlern |
| **Netzwerk** | Analyse des Datenverkehrs & Ladezeiten |
| **Quellen** | Code-Navigation und Breakpoints |
| **Lighthouse** | Automatisierte Qualitätsprüfungen (Performance, SEO, Barrierefreiheit) |

---

### Formatierung von Webseiten mit CSS: Einführung
- **Früher: Vermischung von Inhalt und Design**
  - Jedes HTML-Element erhielt direkte Formatierungsanweisungen (z. B. `<font color="red">` oder `<b>`).
  - Dies führte zu unlesbarem Code und enormem Pflegeaufwand bei großen Websites.
- **Heute: Separation of Concerns (Trennung der Zuständigkeiten)**
  - **HTML** beschreibt ausschließlich die **Struktur & Semantik** (z. B. Überschriften, Absätze).
  - **CSS** bestimmt das komplette **visuelle Layout** (Layout, Farben, Typografie).

---

**Beispiel**

```html
<!-- index.html -->
<link rel="stylesheet" href="style.css">
<h1>Meine Überschrift</h1>
```
```css
/* style.css */
h1 { color: #ff6a00; font-size: 24px; font-weight: bold; }
```

---

**Was ist CSS? (Cascading Style Sheets)**

- **Bedeutung:** Übersetzt *Gestufte Gestaltungsbögen*. CSS ist ein lebendiger Standard (*Living Standard*), der vom W3C ständig weiterentwickelt wird.
- **Die Kaskade (Cascading):** Legt fest, welcher Style gewinnt, wenn sich Regeln widersprechen. Spezifischere Regeln überschreiben allgemeinere.
- **Das Vererbungskursmodell:** Übergeordnete Elemente vererben Styles an Kind-Elemente (z. B. eine im `<body>` definierte Schriftart gilt für alle Texte darin).

---

**Beispiel**

```css
body {
  font-family: 'Outfit', sans-serif;
  color: #333333; /* Gilt für das gesamte Dokument */
}

h1 {
  color: #005564; /* Überschreibt die vererbte Farbe für h1-Elemente */
}
```

---

**Selektoren & Mediensteuerung**

- **Selektoren:** Bestimmen präzise, welche HTML-Elemente formatiert werden.
  - **Elementname:** `a { color: blue; }` (alle Hyperlinks)
  - **Klasse:** `.highlight { background: yellow; }` (beliebige Elemente mit `class="highlight"`)
  - **ID:** `#main-header { font-size: 2em; }` (einzigartiges Element mit `id="main-header"`)
- **Mediensteuerung (Media Queries):** CSS ermöglicht unterschiedliche Formatierungen je nach Ausgabemedium (z. B. optimierte Druckansicht oder angepasstes Layout für Mobilgeräte).

---

**Beispiel**

```css
/* Normales Styling für Desktop */
body { font-size: 16px; }

/* Spezielles Styling für Smartphones (Breite maximal 600px) */
@media (max-width: 600px) {
  body {
    font-size: 14px;
    background-color: #f8f9fa;
  }
}
```
---

> Und nun?
Learning by Doing!


---
<!-- _class: structural -->
## Und los geht`s (01)
- Notepad und html
- html Syntax
- Das html Grundgerüst
- Index.html (01)

---

<!-- _class: img-right -->
### Notepad & html

- Webseiten bestehen aus Text
- WYSIWYG Editoren („What You See Is What You Get“) schreiben häufig „schlechten“ und unsauberen Code.
- Daher > Texteditor notepad++ 
- notepad++ "versteht" html & strukturiert Code mit Textauszeichnungen
- Notepad++ > neue leere Textdatei an.
- Für korrekte Textauszeichnungen > notepad++ auf html umstellen


![alt text](img/notepad-html.jpg)

---
<!-- _class: img-right -->
**HTML-Syntax: Die Bausteine des Webs**

- Grundprinzip von HTML ist der sogenannte **Tag** (Markierung).
- Fast jedes HTML-Dokument besteht aus einer Abfolge von Start-Tags, Inhalten und End-Tags, die das Gerüst der Seite bilden.

![alt text](img/syntax.jpg)

---

**1. Tags und ihre Funktion**
Ein HTML-Tag besteht aus dem englischen Schlüsselwort in spitzen Klammern, z. B. `<p>` für einen Absatz oder `<h1>` für eine Hauptüberschrift. Fast alle Tags haben einen entsprechenden **Schließenden Tag**, der mit einem Schrägstrich (`/`) beginnt, z. B. `</p>`. Der Inhalt, der formatiert werden soll, steht zwischen diesen beiden Tags.

**Beispiel für einen Absatz:**

```html
<p>Hier steht der Text, den der Browser als neuen Absatz darstellt.</p>
```

---

**2. Attribute: Zusätzliche Informationen**
- Tags können durch sogenannte **Attribute** ergänzt werden
- Attribute stellen zusätzliche Informationen bereit
- Attribute stehen immer im Start-Tag & bestehen aus einem Attributnamen, einem Gleichheitszeichen und dem dazugehörigen Wert in Anführungszeichen.

**Beispiel für ein Bild mit Attributen:**

```html
<img src="foto.jpg" alt="Ein Foto von meiner Katze">
```

In diesem Beispiel definieren das Attribut `src` (source) und `alt` (alternative Text) das Bild und dessen Beschriftung für Screenreader und wenn das Bild nicht geladen werden kann.

---
**3. Elemente & leere Elemente**

- HTML-Elemente können Text oder andere Elemente enthalten.
- z.B. Überschrift `<h1>`:  besteht aus einem Start-Tag `<h1>`, dem Inhalt `Meine Überschrift` und dem entsprechenden End-Tag `</h1>`.  
- Es gibt auch sogenannte **leere Elemente** wie `<img>` oder `<br>`
- leere Elemente besitzen keinen Inhalt & somit keinen End-Tag
- Sie werden stattdessen oft mit einem abschließenden Schrägstrich (`<br />`) geschrieben, um anzuzeigen, dass das Element abgeschlossen ist. (Guter Stil, aber nicht notwendig)

---
**Groß- und Kleinschreibung in HTML**
- Keine Case-Sensitivity: HTML-Element- und Attributnamen sind nicht fallsensitiv (Groß-/Kleinschreibung ist für den Browser egal, z. B. <title> vs. <TITLE>).
- Übersichtlichkeit: Eine einheitliche Schreibweise verbessert die Lesbarkeit und Struktur des Codes.
- Historischer Kontext (XHTML): Im älteren Standard XHTML war die Kleinschreibung zwingend vorgeschrieben.
- Heutiger Standard: Die Kleinschreibung hat sich damals unter Entwicklern durchgesetzt und gilt auch heute noch als Best Practice („guter Stil“).

---
<!-- _class: img-right -->
### Das Grundgerüst

- Kopiervorlage.txt öffnen
- Den Code kopieren
- neue html-Datei in notepad++ anlegen
- Code einfügen
- notepad++ auf html umstellen!


![alt text](img/kopiervorlage.jpg)

---
### Ein valides HTML-Dokument: Die Bestandteile
- **`<!DOCTYPE html>` (Dokumenttyp-Deklaration):** Steht in der allerersten Zeile und teilt dem Browser mit, dass es sich um HTML5 handelt.
- **`<html>` (Wurzelelement):** Umschließt das gesamte Dokument und definiert die Hauptsprache (z. B. `<html lang="de">`).
- **`<head>` (Kopfbereich):** Umschließt unsichtbare Meta-Informationen (z. B. Zeichensatz `<meta charset="utf-8">`).
- **`<title>` (Seitentitel - PFLICHT!):**
  - Ist im `<head>` platziert und für die Validität der Seite **zwingend vorgeschrieben** (Pflichtelement).
  - Definiert den Text, der im Browser-Tab und in Suchergebnissen (z. B. Google Search) erscheint.
- **`<body>` (Inhaltsbereich):** Umschließt alle sichtbaren Elemente einer Webseite (Texte, Bilder, Links, etc.).

---

**Minimales valides HTML5-Grundgerüst**
Ein voll funktionsfähiges und standardkonformes HTML-Dokument sieht minimal so aus:

```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="utf-8">
    <title>Meine erste Webseite</title>
</head>
<body>
    <h1>Hallo Welt!</h1>
    <p>Dies ist ein valides HTML5-Dokument.</p>
</body>
</html>
```

---
### Code-Einrückung (Indentation)
- **Für den Browser:** Völlig egal. Browser ignorieren überflüssige Leerzeichen (Whitespaces) und Zeilenumbrüche im Quelltext.
- **Für den Entwickler:** Essentiell für die Lesbarkeit. Man erkennt auf den ersten Blick, welche Elemente ineinander verschachtelt sind und ob Tags korrekt geschlossen wurden.
- **Die Grundregel:** Jedes Kind-Element (untergeordnetes Element) wird um eine Stufe (meist 2 oder 4 Leerzeichen oder 1 Tabulator) weiter eingerückt als sein Eltern-Element.

```html
<ul> <!-- Übergeordnetes Eltern-Element -->
    <li>Erster Eintrag</li> <!-- Untergeordnete Kind-Elemente -->
    <li>Zweiter Eintrag</li>
</ul>
```
- **Tipp:** In Notepad++ > `Tab`-Taste zum Einrücken > `Umschalt + Tab` zum „Ausrücken“

---
**Die 5 Elemente des HTML-Grundgerüsts**

- `<!DOCTYPE html>`
- `<html>`
- `<head>`
- `<title>`
- `<body>`

---
<!-- _class: img-right -->
`<!DOCTYPE html>`

- **Dokumenttyp-Deklaration:** in erster Zeile & teilt Browser mit, dass es sich um HTML5 handelt.
- früher Angabe der html-Version erforderlich (z.B. `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">`)
- Seit HTML5  `<!DOCTYPE html>`.
- rigorose Vereinfachung im Sinne von
Less-is-more

![alt text](img/doctype.jpg)

---
<!-- _class: img-right -->
`<html lang="de">`

- ist das **Wurzelelement**
- umschließt die gesamte HTML-Seite
- das Attribut `lang="de"` gibt die Sprache an (hier: Deutsch)
- Alternativ: en, fr, es, ru, etc.
- wichtig für Suchmaschinen & Screenreader

![alt text](img/html-tag.jpg)

---
<!-- _class: img-right -->
`<head>`

- unsichtbar, aber unverzichtbar
- umschließt unsichtbare Meta-Informationen
- Zeichensatz `<meta charset="utf-8">`
- enthält title-Element (Pflicht für ein valides html-Dokument)
- Enthält Links zu externen CSS-Dateien und JavaScript-Dateien (optional)
- Kann Links zu externen Schriftarten enthalten (z.B. Google Fonts, optional)

![alt text](img/head-tag.jpg)

---
<!-- _class: img-right -->
**Zeichensatz-Deklaration im Head**

- `<meta charset="utf-8">`
- Zeichenkodierung festlegen
- für Suchmaschinen & Screenreader wichtig
- korrekte Darstellung von Sonderzeichen, Umlauten und Emojis über verschiedene Betriebssysteme & Browser hinweg.
- erstes Element im `<head>`, vor allen anderen Elementen im `<head>` (nicht zwingend, gilt aber als Best Practice).
- muss innerhalb  erster 512 Bytes des Dokuments stehen

![alt text](img/utf8.jpg)

---
<!-- _class: img-right -->

> Wichtig: Das Dokument muss
auch in der Dateikodierung
als UTF-8 gespeichert werden!

![alt text](img/utf8.jpg)

---
<!-- _class: img-right -->

**Meta-tag Viewport**
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

- sorgt dafür, dass sich die Webseite an die Bildschirmbreite des Geräts anpasst
- sorgt dafür, dass die Webseite in der korrekten Zoomstufe angezeigt wird
- **unabdingbar für Responsives Webdesign**

![alt text](img/viewport-tag.jpg)

---

**Weitere Meta-Tags im Head**

`<meta name="description" content="Beschreibung meiner Webseite">` (für Suchmaschinen)

`<meta name="viewport" content="width=device-width, initial-scale=1.0">` (für Mobilgeräte)

`<meta name="keywords" content="mobiler Service, Camping, Fahrzeugausbau">` (für Suchmaschinen)

`<meta name="author" content="Maik Mustermann">` (für Suchmaschinen)

`<meta name="robots" content="index, follow">` (für Suchmaschinen)

`<meta name="language" content="German">` (für Suchmaschinen)
...

---
<!-- _class: img-right -->

**<title>**

- umschließt den Titel der Webseite
- erscheint im Browser-Tab und in Suchergebnissen
- für die Validität der Seite **zwingend vorgeschrieben** (Pflichtelement)
- SEO-Relevanz!


![alt text](img/title-tag.jpg)

---
<!-- _class: img-right -->
`<body>`

- umschließt alle **sichtbaren** Elemente der Webseite
- Texte, Bilder, Links, Tabellen, etc. sind hier platziert
- Verlinkung von Javascript-Datei (optional) am Ende des body-tags

![alt text](img/body-tag.jpg)

---
<!-- _class: img-right -->

**Weitere Elemente der Kopiervorlage**

`<h1>` – `<h6>` **Überschriften**
- h steht für heading
- Die Zahl gibt die Wichtigkeit der Überschrift an.
- normalerweise reicht h1-h2
- bei technischen Dokumenten h1-h6



![alt text](img/ueberschriften.jpg)

---


> h1 ist semantisch wichtig!
Nicht nur für Darstellung, sondern auch für SEO und Barrierefreiheit.

<br>

> Es ist nur eine h1 pro Seite erlaubt!




---

 `<p>` **Absätze: Gliederung & Syntax**
- **Funktion:** Dienen der Strukturierung von Fließtext in logische Absätze (engl. *paragraph*).
- **Syntax:** `<p>` leitet einen Absatz ein, `</p>` beendet ihn.
- **Schließendes Tag optional?**
  - In HTML5 ist das schließende `</p>` technisch optional (der Browser schließt den Absatz bei bestimmten Folgeelementen implizit).
  - In XHTML ist es zwingend **Pflicht**.
  - **Guter Stil:** Das schließende `</p>` sollte immer angegeben werden. Es umschließt einen zusammenhängenden Textblock – es steht nicht für den Zwischenraum.

---

**Verschachtelung & Abstände bei Absätzen**
- **Keine Block-Elemente im Absatz:** Ein `<p>`-Element darf keine anderen blockerzeugenden Elemente (z. B. Überschriften, Listen `<ul>`, Tabellen `<table>` oder andere Absätze) enthalten.
- **Implizites Schließen:** Erkennt der Browser ein unzulässiges Element innerhalb eines offenen `<p>`, schließt er den Absatz automatisch vorzeitig. Ein späteres schließendes `</p>` ist dann ein verwaister Fehler.
- **Abstände gestalten:**
  - **Falsch:** Leere Absätze (`<p>&nbsp;</p>`) oder mehrere `<br>`-Tags zur Abstandserzeugung missbrauchen.
  - **Richtig:** Abstände sauber über die CSS-Eigenschaft `margin` definieren.


---
**`<br>` :Zeilenumbruch (Line Break)**
- **Bedeutung:** Das `<br>`-Element (*break*) erzeugt einen logischen Zeilenumbruch innerhalb eines Textes.
- **Best Practice:** Nur nutzen, wenn der Umbruch **Bestandteil des Inhalts** ist. Fließtext sollte niemals manuell umgebrochen werden (das regelt der Viewport).
- **Ausnahmen (sinnvoller Einsatz):**
  - Postadressen (wichtig für die korrekte Gliederung der Anschrift).
  - Gedichte, Songtexte oder Liedzeilen.
- **Syntax:** Es ist ein *leeres Element* ohne Inhalt (in HTML `<br>`, in XHTML `<br />` geschrieben, kein End-Tag erforderlich).
- **Quelle:** [SelfHTML: br-Element](https://wiki.selfhtml.org/wiki/HTML/Textauszeichnung/br)

---
### Datei speichern: WIE und WOHIN?
- **Das Grundprinzip:** Bevor Sie Ihre erste HTML-Seite speichern, ist das **WIE** und **WOHIN** in der Webentwicklung von besonderer Bedeutung.
- **Schritt-für-Schritt-Anleitung für XAMPP:**
  1. Öffnen Sie das **XAMPP Control Panel** `1)` und starten Sie den **Apache Webserver** und **MySQL** `2)`.
  2. Öffnen Sie mit **Explorer** `3)` das **XAMPP Root-Verzeichnis** `4)`.
  3. In diesem liegt das **`htdocs`-Verzeichnis** `4)` (dieses wird vom Apache Webserver gehostet).
  4. Legen Sie darin ein **beliebiges Unterverzeichnis** an.
  5. *Empfehlung:* Zur Versionierung empfehlen sich weitere Unterverzeichnisse `5)`.
  6. Nun können Sie im **Notepad++** das HTML-Grundgerüst als HTML-Datei speichern `6)`.

---



![bg full:bg](img/xampp-abspeichern.jpg)


---
**Die Alternative mit dem Mongoose Webserver**

- Projektordner anlegen.
- HTML-Datei als index.html darin abspeichern.
- mongoose.exe herunterladen und in denselben Projektordner kopieren.
- Per Doppelklick ausführen.
- Adresse http://localhost:8080 im Webbrowser aufrufen.
- Wichtiger Sicherheitshinweis zum Thema Mehrfachausführung/Port-Konflikt
und Beenden über den Windows-Infobereich.

---

**Die Startseite (Einstiegsseite)**
- **Definition:** Die Startseite bzw. Einstiegsseite ist dasjenige HTML-Dokument, das standardmäßig ausgeliefert wird, wenn ein Besucher Ihren Webauftritt ohne Angabe einer bestimmten Seite aufruft.
- **Namensgebung:**
  - Wie Sie die Startseite benennen müssen, sodass sie vom Webserver als solche erkannt wird, schreibt Ihr Webspace-Provider vor.
  - Meistens ist der Name `index.html`, `index.htm`, `default.html` oder `default.htm`.
  - Bei manchen Providern können Sie einen beliebigen Namen definieren.
- **Wichtigste Regel:**
  - Die Startseite Ihrer Webseite heißt **IMMER `index.html`**!
  - Beim Aufruf der Domain sucht der Webserver immer nach einer Datei mit diesem Namen, um sie anzuzeigen.

---

<!-- _class: img-right -->

**Darstellen der Seite**

- Webbrowser Chrome undöffnen & Eingabe von:
http://localhost/
- Sollte der Webserver laufen zeigt XAMPP Konfigurationsseite an
- XAMPP hostet Dateien, die im htdocs Verzeichnis liegen und springt automatisch in den Ordner xampp

![alt text](img/xampp-localhost.jpg)

---
<!-- _class: img-right -->

- Um die eigene Webseite anzuzeigen:
-> in das entsprechende Verzeichnis wechseln

Zur Versionierung der Daten > fortlaufende Nummerierung der Verzeichnisse:
http://localhost/maiks-mobiler-service/01/

- Chrome zeigt unsere erste Webseite an.
- Beachten Sie, dass Chrome im Tab den **Title Tag** wiedergibt.
- Beachten Sie ebenfalls die Darstellung des **strukturierten Textes**.

![alt text](img/erste-eigene-Seite.jpg)

---
**Entwicklertools**
In den Einstellungen > Weitere Tools > Entwicklertools
stellt Chrome Ihnen umfangreiche
Debugging-Werkzeuge zur Verfügung.
>Testen Sie diese.

---

![bg](img/entwicklertools.jpg)

---

## Und los geht`s (02)
- Erste eigene Inhalte (02)
- Bilder
- ... und Texte

---

<!-- _class: img-right -->

### Coden mit Notepad++

**Bilder einfügen**

Als visuelle Menschen sprechen uns als erstes hochwertige und spannende Bilder an. Häufig findet sich auf der Startseite ein aussagekräftiges Bild im Header oder im Seitenhintergrund.

Im Rahmen Ihres Studiums lernen Sie, hochwertige Bilder zu erzeugen und zu verarbeiten. Nutzen Sie diese Fähigkeiten, um einen überzeugenden ersten Eindruck zu hinterlassen.


![alt text](img/maikimSprung.jpg)

---

<!-- _class: img-right -->

- neuen Ordner "img" neben index.html anlegen
- "header.jpg" in diesen Ordner kopieren
- Folgenden Code in der index.html einfügen:   


```html
<!-- Sichtbarer Dokumentinhalt im body -->
<img src="img/header.jpg" alt="Maik`s mobiler Service">
<h1>Blindtext.</h1>
```
![alt text](img/header-bild-einfuegen.jpg)

---
**Texte einfügen**

>Herzlich willkommen auf der Webseite von Maik!
Schlimmer geht es nicht!

Wenn Sie gelesen werden wollen:
- Fassen Sie sich kurz.
- Werden Sie originell.
- Transportieren Sie Information.
- Fangen Sie nicht an zu labern.
- Strukturieren Sie Ihre Texte semantisch und inhaltlich!


---
**Think Semantik**

- Semantik ist die Lehre von der Bedeutung
von Zeichen und sprachlichen Ausdrücken.
- Im Zusammenhang mit HTML bezieht sich
Semantik auf die Bedeutung von HTML-Tags.
- HTML-Tags werden verwendet, um die Struktur
und den Inhalt einer Webseite zu beschreiben.
- Semantik ist wichtig, da sie es Suchmaschinen
ermöglicht, den Inhalt einer Webseite zu
verstehen und zu indexieren.

![bg right:45%](img/think_semantik.png)

---
<!-- _class: structural -->
### Tags zur Strukturierung von Text
**HTML-Elemente für Semantik und Lesbarkeit**

- Übersicht der wichtigsten Text-Tags
- Eigenschaften von Block- und Inline-Elementen
- Code-Beispiele für die Praxis

---

**Überschriften (h1 - h6)**

Dienen der Strukturierung und Gewichtung:
- **`<h1>` bis `<h6>`**: Abstufung der Wichtigkeit
- **Eigenschaften**:
  - Block-Elemente (erzeugen eine neue Zeile)
  - Suchmaschinen (SEO) nutzen sie zur Gewichtung
  - Pro Seite sollte es nur genau eine `<h1>` geben
- **Code-Beispiel**:
  ```html
  <h1>Hauptüberschrift</h1>
  <h2>Unterüberschrift</h2>
  ```

---

**Textabsätze (p)**

Der Standard für Fließtext:
- **`<p>` (Paragraph)**: Umschließt Textabschnitte
- **Eigenschaften**:
  - Block-Element mit automatischen Abständen
  - Verbessert den Lesefluss durch visuelle Pausen
  - Ignoriert aufeinanderfolgende Leerzeichen im Quelltext
- **Code-Beispiel**:
  ```html
  <p>Dies ist ein Absatz.</p>
  <p>Dies ist der nächste Absatz.</p>
  ```



---

**Ungeordnete Listen (ul)**

Für Sammlungen ohne feste Reihenfolge:
- **`<ul>` (Unordered List)**: Umschließt Listenelemente
- **`<li>` (List Item)**: Einzelne Listenpunkte
- **Eigenschaften**:
  - Block-Elemente
  - Standardmäßig mit Aufzählungspunkten (Bullets)
- **Code-Beispiel**:
  ```html
  <ul>
    <li>HTML5 Semantik</li>
    <li>CSS Styling</li>
  </ul>
  ```


---
**Geordnete Listen (ol)**

Für Abläufe, Rezepte und Anleitungen:
- **`<ol>` (Ordered List)**: Umschließt Listenelemente
- **`<li>` (List Item)**: Einzelne Listenpunkte
- **Eigenschaften**:
  - Block-Elemente
  - Werden automatisch nummeriert (1., 2., 3...)
  - Attribute wie `start` oder `type` möglich
- **Code-Beispiel**:
  ```html
     <ol>
    <li>HTML-Datei anlegen</li>
    <li>Struktur im Browser prüfen</li>
  </ol>
  ```


---

**Zeilenumbruch (br) & Trenner (hr)**

Für feine Text- und Layoutsteuerung:
- **`<br>` (Line Break)**: Erzwingt einen Zeilenumbruch
- **`<hr>` (Horizontal Rule)**: Thematischer Bruch
- **Eigenschaften**:
  - **Leere Elemente** (haben keinen schließenden Tag!)
  - `<br>` wirkt auf Inline-Ebene (bricht nur Text um)
  - `<hr>` wirkt auf Block-Ebene (erzeugt eine Linie)
- **Code-Beispiel**:
  ```html
     Erste Zeile<br>Zweite Zeile
  <hr>
  Anderes Thema...
  ```


---

**Vorformatierter Text (pre & code)**

Für Quellcode und exakte Abstände:
- **`<pre>` (Preformatted)**: Behält alle Leerzeichen und Zeilenumbrüche exakt bei
- **`<code>`**: Kennzeichnet Text als Programmcode
- **Kombination**: `<pre><code>...</code></pre>`
- **Code-Beispiel**:
  ```html
     <pre><code>
    function init() {
    console.log("Start");
  }
  </code></pre>

---

**Starke Betonung (strong)**

Für besonders wichtige Inhalte:
- **`<strong>` (Strong Importance)**: Kennzeichnet Text von großer Bedeutung
- **Eigenschaften**:
  - Inline-Element (fließt im Text mit)
  - Drückt Wichtigkeit, Dringlichkeit oder Ernsthaftigkeit aus
  - Browser stellen den Text standardmäßig **fett** dar
  - Wichtig für Screenreader (akustische Hervorhebung)
  - *Hinweis*: Nutze `<strong>` für Semantik, nicht das rein dekorative `<b>`
- **Code-Beispiel**:
  ```html
     Achtung: Die Steckdose steht <strong>unter Strom</strong>!
  ```

---

**Hervorhebung (em)**

Für sprachliche Betonung:
- **`<em>` (Emphasis)**: Hebt Wörter oder Phrasen im Satz hervor
- **Eigenschaften**:
  - Inline-Element (fließt im Text mit)
  - Ändert je nach betontem Wort die Aussage des Satzes
  - Browser stellen den Text standardmäßig *kursiv* dar
  - Wird von Screenreadern akustisch betont (Intonation)
  - *Hinweis*: Nutze `<em>` für Semantik, nicht das rein dekorative `<i>`
- **Code-Beispiel**:
  ```html
     Das müssen Sie <em>heute</em> noch erledigen!
  ```

---
<!-- _class: structural center -->
# Quick Check: Semantik
## Welches Tag eignet sich am besten für...

1. ...eine Zutatenliste für eine Pizza?
2. ...eine Schritt-für-Schritt-Anleitung?
3. ...die wichtigste Überschrift der Seite?
4. ...einen einfachen Fließtext?

**Überlegen Sie kurz und besprechen Sie es mit Ihrem Nachbarn!**


---
<!-- _class: img-right -->

Ihre Text-Inhalte fügen Sie nun nach dem Bild ein:
Den Vorlagetext findet Ihr im material-Ordner in der Datei:

**HomeSweetHome.txt**

![alt text](img/maik-02.jpg)

---

![bg](img/maik-02.-imChrome.jpg)

---

### Coden mit Visual Studio Code

Der weltweite Standard für moderne Webentwicklung:
- **Plattformunabhängig & kostenlos**: Läuft auf Windows, macOS und Linux.
- **Riesiger Extension Marketplace**: Tausende Erweiterungen zur Anpassung.
- **IntelliSense**: Intelligente Autovervollständigung für HTML, CSS und JS.
- **Integriertes Terminal & Git**: Alle Werkzeuge an einem zentralen Ort.

![bg right:45%](img/vscode.jpg)

---

**Emmet – Schneller HTML schreiben**

Ein bereits integriertes Feature, das Tipparbeit spart:
- **Funktionsweise**: Kurzschreibweisen eintippen
und mit der **Tab-Taste** expandieren lassen.
- **Wichtige Shortcuts für den Einstieg**:
  - `!` + Tab $\rightarrow$ Erzeugt das komplette
  HTML5-Grundgerüst.
  - `p` + Tab $\rightarrow$ Erzeugt `<p></p>`.
  - `ul>li*3` + Tab $\rightarrow$ Erzeugt eine
  Liste mit 3 Listeneinträgen.
  - `h1{Titel}` + Tab $\rightarrow$ Erzeugt `<h1>Titel</h1>`.


![bg right](img/vscode_emmet.jpg)

---

**Live Server & Auto-Verwaltung**

Die wichtigsten Erweiterungen für Einsteiger:
- **Live Server (Extension)**:
  - Startet mit einem Klick lokalen Webserver.
  - Aktualisiert den Browser automatisch
  beim Speichern (Live Reload).
- **Auto Rename Tag**:
  - Ändert das schließende Tag automatisch,
  wenn das öffnende Tag geändert wird.
- **Prettier (Code Formatter)**:
  - Formatiert den Code beim Speichern
  automatisch nach festen Regeln.

![bg right:50%](img/vscode_liveserver.jpg)

---

**Bedienung: Live Server**

Lokale Entwicklung mit sofortigem Feedback:
- **Starten**: Klicke unten rechts in der Statusleiste
auf **"Go Live"** oder nutze den
Shortcut `Alt + L, Alt + O`.
- **Lokaler Server**: Startet die Seite
unter `http://127.0.0.1:5500/index.html`.
- **Live Reload**: Nach jedem Speichern
(`Strg + S`) lädt der Browser die Seite
automatisch neu. Keine manuelle
Aktualisierung nötig!

![bg right:50%](img/vscode_liveserver.jpg)

---

**Bedienung: Auto Rename Tag**

Verhindert Syntaxfehler durch
unvollständige HTML-Tags:
- **Automatische Anpassung**: Läuft nach der
Installation komplett im Hintergrund.
- **Funktionsweise**:
  - Wenn du ein öffnendes Tag änderst
  (z. B. `<div>` zu `<section>`), wird das
  schließende Tag (`</div>` zu `</section>`)
  zeitgleich angepasst.
- **Vorteil**: Spart Zeit und eliminiert Fehler.

![bg right:50%](img/vscode_autorename.jpg)

---

**Bedienung: Prettier**

Code-Formatierung per Knopfdruck:
- **Format on Save**: Richtet VS Code so ein, dass
beim Speichern automatisch formatiert wird.
  1. Einstellungen öffnen (`Strg + ,`).
  2. Nach **"Format on Save"**
  suchen und aktivieren.
  3. Prettier als Standard-Formatierer festlegen.
- **Vorteil**: Garantiert saubere Einrückungen
und einheitlichen Code beiDreamteam html & css (03)
jedem Speichern (`Strg + S`).

![bg right:50%](img/vscode_prettier.jpg)

---
<!-- _class: structural img-right -->
## Dreamteam html & css (03)

Webseiten funktionieren auch mit reinem html!
> Aber hübsch ist anders ;)

![Dreifaltigkeit](img/dreifaltigkeit.jpg)

<style scoped>
section.img-right img {
  background-color: #343a40;
}
</style>
---

`<body bgcolor="blue">`
> Das ist tabu!

Das Stylen einzelner Elemente ist möglich aber:
- arbeitsaufwendig
- unübersichtlich
- schwer zu pflegen

**-> Daher css: Trennung von Inhalt und Gestaltung**

---

**CSS-Grundprinzip & Syntax**

Cascading Style Sheets
(Mehrstufige Formatvorlagen):
- **Zweck**: Bestimmt das Design, Layout
und die Darstellung von HTML-Elementen.
- **Grundregel**: Selektor wählt das Element,
Deklarationen definieren das Design.
- **Aufbau einer Deklaration**:
  - **Eigenschaft (Property)**: Was soll
  geändert werden (z. B. `color`)?
  - **Wert (Value)**: Wie soll es
  aussehen (z. B. `blue`)?

![bg right:50%](img/css_syntax.jpg)

---

**Die drei Wege der CSS-Einbindung**

Wie kommt das CSS-Design in den HTML-Code?
- **1. Inline-Styles**:
  - Direkt im HTML-Tag mit
  dem `style`-Attribut.
- **2. Interne Stylesheets**:
  - Im `<head>`-Bereich in einem `<style>`-Tag.
- **3. Externe Stylesheets (Best Practice)**:
  - In einer eigenen `.css`-Datei
  (z. B. `style.css`).
  - Verknüpfung im `<head>` über
  ein `<link>`-Tag.

![bg right:50%](img/css_integration.jpg)

---

**Code-Beispiele der CSS-Einbindung**

- **Inline-Style (Direkt am Element)**:
  ```html
  <p style="color: orange; font-size: 20px;">Maiks Service</p>
  ```
- **Internes Stylesheet (Im HTML-Kopf)**:
  ```html
  <style>
    p { color: orange; font-size: 20px; }
  </style>
  ```
- **Externes Stylesheet (Saubere Trennung)**:
  ```html
  <!-- Im HTML-Kopf verlinkt: -->
  <link rel="stylesheet" href="css/style.css">
  ```

---
**Und wann verwende ich was?**
- Inlinestyle > **Nur in Ausnahmefällen**
- Internes Stylesheet > **Hauptsächlich bei One-Pagern**
vereinfacht die Dateiverwaltung 
- Externes Stylesheet > **Immer verwenden bei größeren Webauftritten**

---

**Das Kaskaden-Prinzip (Cascading)**

Welche CSS-Regel gewinnt, wenn es Konflikte gibt?
- **1. Die Reihenfolge**:
  - Später definierte CSS-Regeln überschreiben frühere Regeln.
- **2. Die Spezifität (Gewichtung)**:
  - Spezifischere Selektoren überschreiben allgemeinere.
  - *Reihenfolge*: Inline-Style $>$ ID-Selektor $>$ Klasse $>$ Element-Tag.
- **3. Die Vererbung (Inheritance)**:
  - Viele Eigenschaften (z. B. `font-family`, `color`) werden an untergeordnete Elemente vererbt.

---


**... wie jetzt?**

Na, Microsoft Word macht das nicht anders:
> Formatvorlagen heißt dort
das Zauberwort


![bg right:50%](img/css-beispiel.jpg)

---

**Vererbung in CSS (Inheritance)**

- **Grundprinzip**: CSS-Regeln für ein Element gelten für alle Instanzen dieses Elements auf der Webseite (z. B. Schriftart für alle `<p>`-Elemente).
- **Definition**: Vererbung ist die Übertragung von Eigenschaften von übergeordneten (Eltern-) Elementen auf untergeordnete (Kinder-) Elemente.
- **Vorteil**: Vermeidung redundanter CSS-Regeln – Layouts können effizient an zentraler Stelle gepflegt werden.
- **Vererbte vs. nicht-vererbte Eigenschaften**:
  - *Vererbt*: Text- und Schrifteigenschaften (z. B. `font-family`, `color`, `line-height`).
  - *Nicht vererbt*: Layout- und Box-Eigenschaften (z. B. `margin`, `padding`, `border`, `background-color`).

![bg right:50%](img/css_inheritance_diagram.png)

---
**Praxisaufgabe:**

Neues Textdokument, Umbenennen  -> style.css.
Einbinden der style.css in html:

```
<html lang="de"> <head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />


<link rel="stylesheet" href="style.css">


<title>Titel der Seite | Name der Website</title>
</head>

```

---

![bg](img/maik-03.jpg)

---

**Im css-file dann:**

```

body {
font-family: tahoma,arial,helvetica,verdana,sans-serif;
}

```

![bg](img/maik-03-2.jpg)


---

**Praxisbeispiele zur Vererbung**

- **Zentrale Standardschriftart**:
  - Wird die Schriftart Arial für das `<body>`-Element festgelegt, gilt sie für alle untergeordneten Elemente.
  - Da alle sichtbaren Elemente vom `<body>` abstammen, fungiert dies als globale Standardschriftart der Seite.
- **Das img-Element & Alternativtext**:
  - Ein Bild (`<img>`) selbst ändert sein Aussehen nicht durch Schriftarten.
  - Falls das Bild jedoch nicht geladen werden kann, wird der Alternativ-Text (`alt="..."`) angezeigt.
  - Da das `<img>` dem `<p>`-Element untergeordnet ist, erbt dieser Text automatisch dieselbe Schriftart wie der restliche Absatz.

---

**Weitere css Formatierungen**

```
h1, h2 {
  display: inline;
  color: #FFFFFF ;
  background-color: #303030;
  font-family: "Trebuchet MS", Georgia, Verdana, Geneva, Arial, Helvetica, sans-serif;
  font-size: 1.4em;
  text-align: left;
  margin: 0px;
  padding: 2px;
}
```
---

**display:** inline; 
=>  Schrift wird nicht in einer eigenen Zeile dargestellt
**color:** #FFFFFF ; =>  Schriftfarbe weiß
**background-color:** #303030; =>  Hintergrundfarbe grau
**font-family:** "Trebuchet MS", Georgia, Verdana, Geneva, Arial, Helvetica, sans-serif; 
=>  Schriftart Festlegung
**font-size:** 1.4em; 
=>  Schriftgröße 1,4 mal größer als die Standardschriftgröße
**text-align:** left; =>  Schrift linksbündig
**margin:** 0px; =>  kein Außenabstand
**padding:** 2px; =>  Innenabstand 2px

---

![bg](img/maik-03-3.jpg)


---
<!-- _class: structural-->
**Das CSS-Boxmodell**

Jedes HTML-Element wird vom Browser als rechteckige Box dargestellt.
Diese Box besteht aus vier verschachtelten Bereichen.

> Entwicklertools -> rechte Maustaste -> Inspect (inspizieren) -> Box-Model

---
<!-- _class: img-right -->
- **Content (Inhalt):** Der eigentliche Inhalt wie Text, Bilder oder andere Elemente.
- **Padding (Innenabstand):** Transparenter Bereich zwischen Inhalt und Rahmen. Erbt die Hintergrundfarbe des Elements.
- **Border (Rahmen):** Begrenzungslinie der Box, die das Padding umschließt.
- **Margin (Außenabstand):** Transparenter Abstand zum nächsten Element außerhalb der Box.

![CSS Box Model](img/css_box_model.png)

---
<!-- _class: img-right -->
**Die Box-Dimensionen & box-sizing**

Berechnung der Gesamtbreite einer Box:

- **Entweder: content-box (Standard):**
  - `width` definiert nur die Breite des Inhalts.
  - Gesamtbreite = `width` + `2 * padding` + `2 * border`.
- **Oder: border-box (Best Practice):**
  - `width` definiert die Gesamtbreite (inkl. Padding & Border).
  - Verhindert, dass Boxen unerwartet aus dem Layout ausbrechen.

```css
* {
  box-sizing: border-box;
}
```

![Box Sizing Comparison](img/css_box_sizing.png)

---
**Margin & Padding im Detail**

Wie steuert man Abstände im CSS?
Für beide Eigenschaften gibt es flexible Schreibweisen:

- **Eigenschaften im Uhrzeigersinn definieren:**
  - `margin: 10px;` (alle vier Seiten erhalten 10px)
  - `margin: 5px 20px;` (oben/unten: 5px, links/rechts: 20px)
  - `margin: 10px 15px 20px 25px;` (oben, rechts, unten, links)
- **Wichtige Unterschiede:**
  - **Margin (Außenabstand):**
  Kann negative Werte annehmen und kollabieren (Margins verschmelzen).
  - **Padding (Innenabstand):** Kann keine negativen Werte haben.
  Vergrößert die Hintergrundfläche und die Klickfläche von Elementen.

--- 

<!-- _class: structural -->
## Fonts & Google-Fonts

HTML ist kein Word.
Schriftarten sind nicht im Dokument eingebettet.
Das bedeutet der Browser greift auf die
lokal installierten Fonts des Clients zurück.

---

**Schriftarten im Web: Die Verfügbarkeit**

- **System-Schriftarten:**
Standardmäßig stehen nur Schriftarten zur Verfügung,
die auf dem Gerät des Betrachters lokal installiert sind.

> Welche Schriftarten kennt Ihr?
> Welche verwendet Ihr?


---

- **Problem:**
Endgeräte (PC, Mac, Smartphones, Tablets,
Smartwatches, E-Reader) haben stark
unterschiedliche Schriftarten vorinstalliert.
- **Lösung: Der Font-Stack**
  - Definition einer Prioritätenliste
  (Fallback-Liste) in CSS.
  - Der Browser liest die Liste von
  links nach rechts: Die erste verfügbare
  Schriftart wird gerendert.

![bg right:50%](img/web_fonts_typography.png)

---
**Font-Stack:**
```css
body {
  font-family: "Helvetica Neue", Arial, sans-serif;
}
```

> Am Ende eines Font-Stacks sollte immer eine generische Schriftart stehen


---
** Generische Schriftarten:**

- serif
- sans-serif
- monospace
- cursive
- fantasy
- system-ui

![bg right:50%](img/generic_fonts.png)


---
**Websichere Schriftarten:**

- **Definition:**
Schriftarten, die auf fast allen Betriebssystemen
(Windows, macOS, Linux, iOS, Android)
standardmäßig vorinstalliert sind.
- **Der große Vorteil:**
Sehr hohe Wahrscheinlichkeit, dass die
Schriftart auf dem Gerät des Nutzers vorhanden ist
$\rightarrow$ keine Ladezeitverzögerung und
vollkommen DSGVO-konform.
- **Die Kehrseite:**
Die Auswahl an websicheren Schriftarten ist
sehr stark limitiert
(Gefahr von visuellem Einheitsbrei).

---

- Arial & Arial Black
- Courier New
- Georgia
- Helvetica
- Lucida Sans/Lucida Grande
- Tahoma
- Times New Roman
- Trebuchet MS
- Verdana

---

**Best Practices: Anführungszeichen & Generische Fallbacks**

- **Umgang mit Leerzeichen im Schriftnamen:**
  - **W3C-Empfehlung:** Namen mit Leerzeichen (z. B. `"Times New Roman"`, `"Tw Cen MT"`) sollten in einfache/doppelte Anführungszeichen (Quotes) gesetzt werden.
  - *Hinweis:* Moderne Browser stellen diese oft auch ohne Quotes fehlerfrei dar, dennoch bleibt es Best Practice zur Sicherung der Validität.
- **Generische Schriftfamilie am Ende:**
  - Jeder Font-Stack sollte mit einer generischen Familie (z. B. `serif`, `sans-serif`, `monospace`) enden.
  - Falls gar keine spezifische Schriftart installiert ist, wählt der Browser so die passende Standard-Kategorie des Systems.

---
**Google Fonts**

- **Was sind Google Fonts?**
  - Google Fonts ist ein kostenloser Online-Dienst
    von Google, der eine riesige Bibliothek
    an Schriftarten zum Einbinden in
    Webseiten bereitstellt.
- **Vorteile:**
  - Große Auswahl an Schriftarten
  - Einfache Einbindung
  - Kostenlos
  - DSGVO-konform (unter bestimmten
    Voraussetzungen)

![bg right:50%](img/google-fonts.jpg)

---


> Achtung Datenschutz

- Da Google Fonts auf den Servern von Google gehostet werden, unterliegen sie deren Datenschutzrichtlinien.
- Sobald ein Nutzer eine Webseite besucht, die Google Fonts verwendet, wird eine Anfrage an die Google-Server gesendet.
- Google kann diese Anfrage protokollieren (einschließlich der IP-Adresse des Nutzers), was als Verarbeitung personenbezogener Daten gilt.
- Nach deutschem Recht (DSGVO) ist dies ohne vorherige Einwilligung des Nutzers in der Regel nicht gestattet.
- Um rechtssicher zu sein, sollten Organisationen, die Google Fonts nutzen, vorher eine informierte Einwilligung (Opt-in) von ihren Nutzern einholen oder eine selbstgehostete Alternative wählen.

**Achtung Abmahnfalle!**

---

![bg](img/dgvo-verletzung.jpg)

---
**Alternative mit @font-face:**

Herunterladen und Einbinden der Fonts auf dem eigenen Server.

Beispiel:
```css
@font-face {
  font-family: "MeineSchriftart";
  src: url("pfad/zu/meiner-schriftart.woff2") format("woff2"),
       url("pfad/zu/meiner-schriftart.woff") format("woff");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}
```

---
> Vorsicht! Auch Schriftarten unterliegen dem Urheberrecht.

Es ist legal z.B. .ttf Fonts auf der eigenen Domain anzubieten,
aber man darf nicht beliebige .ttf Fonts von anderen Webseiten
herunterladen und für eigene Zwecke verwenden.

---
**Woher nehmen, wenn nicht stehlen?**

**Google Fonts**
Beschreibung: Die populärste Quelle für kostenlose und Open-Source-Schriftarten. Sie bietet eine riesige Auswahl und die Schriften lassen sich einfach herunterladen, um sie DSGVO-konform selbst zu hosten.
URL: https://fonts.google.com/

**Adobe Fonts**
Beschreibung: Ein professioneller Dienst mit einer extrem hochwertigen Auswahl an kommerziellen Schriftarten. Der Zugriff ist in jedem aktiven Adobe Creative Cloud-Abonnement enthalten.
URL: https://fonts.adobe.com/

---

**Font Squirrel**
Beschreibung: Bietet ausschließlich Schriften an, die zu 100 % für die kommerzielle Nutzung lizenziert und kostenlos sind. Ein besonderes Highlight ist der integrierte Webfont-Generator, der Desktop-Schriften in Web-Formate (.woff2, .woff) umwandelt.
URL: https://www.fontsquirrel.com/

**Bunny Fonts**
Beschreibung: Eine datenschutzfreundliche Open-Source-Alternative zu Google Fonts. Sie wurde speziell so konzipiert, dass sie als direkter Ersatz (Drop-in-Replacement) dient und vollkommen DSGVO-konform ohne Nutzer-Tracking arbeitet.
URL: https://fonts.bunny.net/

---

**MyFonts**
Beschreibung: Der weltweit größte Marktplatz für kommerzielle und professionelle Schriftarten. Perfekt, wenn man für ein Projekt exklusive, kostenpflichtige Fonts namhafter Type-Designer sucht.
URL: https://www.myfonts.com/

**ffonts.net**
Beschreibung: Eine kostenlose Ressource für Designer, die eine große Auswahl an Schriftarten für ihre Projekte suchen. 
URL: https://www.ffonts.net/


---

> Beispiel
 https://www.ffonts.net/1-Punk.font

Font herunterladen und in ein Verzeichnis **fonts** neben der css und html Datei entpacken.

```
/css
/fonts
/html
/img
```

---

![bg](img/install-a-webfont.jpg)

---

Anpassungen im css:
```
@font-face {
font-family: '1-Punk';
src:url('font/1-Punk.ttf.woff') format('woff'),
url('font/1-Punk.ttf.svg#1-Punk') format('svg'),
url('font/1-Punk.ttf.eot'), url('font/1-Punk.ttf.eot?#iefix') format('embedded-opentype'); font-weight: normal;
font-style: normal;}
und
h1{
font-size: 1.8em; font-family: '1-Punk',Georgia,"Trebuchet MS",verdana,arial,helvetica,sans-serif; }
```
---
<!-- _class: img-right-->

Aktuelle CSS-Datei

![bg right](img/maik-03-css.jpg)

---

![bg](img/maik-03-04.jpg)

---
<!-- _class: structural center-->
## Gestaltung mit Schrift

>Ob Bachelorarbeit, Plakat oder Webseite, Schriften werden meist nur dann wahrgenommen, wenn Sie NICHT passen.

---
<!-- _class: structural -->
**Die 10 Schriftgebote**

Regeln für professionelle Typografie und Lesbarkeit im Web.

---
<!-- _class: img-right -->
**1. Schriftgröße**

- Richtet sich nach dem grundsätzlichen Design und dem verwendeten Font.
- **Wichtig:** Nutzer können Schriftgrößen im Browser/Smartphone jederzeit individuell anpassen.
- **Best Practice:** Verwenden Sie stets relative Schriftgrößen (`%`, `em`, `rem`) statt fester Pixelwerte, um Barrierefreiheit zu sichern.

![Gebot 1](img/gebot_1.png)

---
<!-- _class: img-right -->
**2. Zeilenbreite**

- Wird häufig unterschätzt, beeinflusst die Lesbarkeit aber massiv.
- **Optimalwert:** Maximal ca. 70 Zeichen pro Zeile (entspricht etwa einer DIN-A4-Textbreite).
- Zu breite Textblöcke erschweren dem Auge den Zeilensprung am Zeilenende.

![Gebot 2](img/gebot_2.png)

---
<!-- _class: img-right -->
**3. Zeilenabstand**

- Der Zeilenabstand (Durchschuss) ist essenziell für die Erfassung von Textblöcken.
- **Empfehlung:** Ein Wert von `140%` bis `150%` (`line-height: 1.4` bis `1.5`) hat sich im Web etabliert.
- Zu geringer Abstand führt zum optischen Verschmelzen der Zeilen.

![Gebot 3](img/gebot_3.png)

---
<!-- _class: img-right -->
**4. Laufweite**

- Beschreibt den horizontalen Abstand zwischen Buchstaben (`letter-spacing`).
- Sollte nur mit äußerster Vorsicht und Bedacht manupuliert werden.
- **Tipp:** Vor allem für Akzente bei Überschriften einsetzen. Im Zweifelsfall unverändert lassen.

![Gebot 4](img/gebot_4.png)

---
<!-- _class: img-right -->
**5. Kontrast**

- Das Helligkeitsverhältnis zwischen Textfarbe und Hintergrund.
- Fließtexte erfordern maximalen Kontrast (z. B. schwarzer Text auf weißem Grund).
- Hoher Kontrast schützt das Auge vor Ermüdung und sichert Barrierefreiheit.

![Gebot 5](img/gebot_5.png)

---
<!-- _class: img-right -->
**6. Struktur**

- Gut strukturierte Texte fördern das Verständnis und die Semantik.
- **Werkzeuge:** Überschriften-Tags (`<h1>` bis `<h3>`), Absätze (`<p>`), Listen (`<ul>`, `<ol>`) sowie gezielte Auszeichnungen (`<strong>`, `<em>`).
- Eine saubere Struktur verbessert zudem das Google-Ranking (SEO).

![Gebot 6](img/gebot_6.png)

---
<!-- _class: img-right -->
**7. Maximal zwei Schrifttypen**

- Für ein harmonisches Gesamtbild reichen meist ein bis zwei Schrifttypen pro Dokument vollkommen aus.
- **Kombination:** Typischerweise eine Serifenschrift für Überschriften und eine Sans-Serif-Schrift für Fließtext.
- Mehr als zwei Fonts wirken unruhig und unprofessionell.

![Gebot 7](img/gebot_7.png)

---
<!-- _class: img-right -->
**8. Versalien**

- Reine Großbuchstaben (Versalien) sind im Fließtext und in Menüs sehr schwer lesbar.
- **Ausnahme:** Kurze Wörter, z. B. in der Hauptnavigation.
- **Best Practice:** Texte normal schreiben und die Umwandlung in Großbuchstaben per CSS über `text-transform: uppercase;` steuern.

![Gebot 8](img/gebot_8.png)

---
<!-- _class: img-right -->
**9. Standardschriften**

- Nutzen Sie bewährte Systemschriftarten als verlässlichen Fallback am Ende Ihres Font-Stacks.
- Klassiker wie *Arial*, *Verdana* oder *Georgia* sind auf fast jedem Gerät vorinstalliert.
- Dies garantiert eine saubere und schnelle Darstellung, falls Webfonts nicht geladen werden können.

![Gebot 9](img/gebot_9.png)

---
<!-- _class: img-right -->
**10. Fortbildung**

- Typografie ist eine Kunst und ein Handwerk zugleich.
- **Tipp:** Bilden Sie sich kontinuierlich weiter – durch Fachliteratur, Workshops, Design-Magazine oder informative Lehrvideos.
- Schärfen Sie Ihr Auge durch die bewusste Analyse gelungener Web-Layouts.

![Gebot 10](img/gebot_10.png)

---
<!-- _class: structural -->

## Farbwerte definieren


> Farben auf Computermonitoren entstehen durch die Mischung von rotem, grünem und blauem Licht. Aus diesem Grund wird das Farbsystem RGB genannt (von den englischen Bezeichnungen Red, Green und Blue).

Wie werden Farben im html & css verwendet?

---
<!-- _class: img-right -->
**1. Farbnamen (Keywords)**

- **Eigenschaften:**
  - Ignoriert Groß- und Kleinschreibung (`red` oder `Red`).
  - Sehr einfach zu merken und schnell geschrieben.
- **Einschränkung:**
  - begrenzte Palette 141 Namen


```css
h1 {
  color: tomato;
}
```


![Farbnamen](img/color_keywords.png)

---

Liste mit allen Farbnamen:
https://wiki.selfhtml.org/wiki/Farbe/Farbangaben#Farbnamen

![bg right](img/farbnamen.jpg)

---

<!-- _class: img-right -->
**2. RGB- und RGBA-Schreibweise**

- **RGB-Parameter:**
  - Angabe als `rgb(R, G, B)`, wobei jeder Kanal Werte von `0` (kein Licht) bis `255` (maximale Helligkeit) annehmen kann.
- **RGBA (Transparenz):**
  - Ermöglicht über den vierten Wert (`Alpha-Kanal`) eine Deckkraft-Steuerung.
  - Der Alpha-Wert reicht von `0.0` (vollständig transparent) bis `1.0` (vollständig deckend).

```css
h1 {
  color: rgba(255, 118, 117, 0.8);
}
```

![RGB und RGBA](img/color_rgb.png)

---
<!-- _class: img-right -->
**3. Hexadezimal(Hex)-Codes** sehr häufig

- **Aufbau:**
  - Beginnt mit einem Doppelkreuz `#` plus 6 Zeichen: `#RRGGBB`.
  - Nutzt das Hexadezimalsystem (Basis 16: Ziffern `0-9` und Buchstaben `A-F`).
- **Kurzschreibweise:**
  - Kürzen auf 3 Zeichen, wenn die Paare für RGB identisch sind (`#FF0055` -> `#F05`).

```css
h1 {
  color: #ff7675;
}
```

![Hexadezimal-Schreibweise](img/color_hex.png)

---
<!-- _class: img-right -->
**4. HSL- und HSLA-Schreibweise** (intuitiv)


- **Die Komponenten:**
  - **Hue (Farbton):** Winkel auf dem Farbkreis (`0°` bis `360°`). `0` = Rot, `120` = Grün, `240` = Blau.
  - **Saturation (Sättigung):** Anteil an Grauwerten (`0%` bis `100%`).
  - **Lightness (Helligkeit):** Helligkeit (`0%` = Schwarz, `100%` = Weiß).
- **Vorteil:** Designer können Farbpaletten extrem einfach manipulieren (z. B. durch Erhöhung der Helligkeit).

```css
h1 {
  color: hsl(197, 100%, 50%);
}
```

![HSL und HSLA](img/color_hsl.png)

---
<!-- _class: structural -->
## Maßeinheiten in CSS festlegen

Zur Angabe von Höhen, Breiten, Innen- und Außenabständen müssen Sie in CSS einen Wert und eine Maßeinheit angeben.

---
<!-- _class: img-right -->
**Absolute Maßeinheiten**

Absolute Werte: kein Bezug zu anderen Angaben, unabhängig von der Umgebung.

- **Pixel (px):** Standard im Webdesign
  - Entspricht  Bildpunkten des Monitors
- **Physische Maßeinheiten:**
  - **pt (Punkt):** Typograf. Maß (1/72 Inch).
  - **in (Inch), cm (Zentimeter), mm (Millimeter).**
  - *Wichtig:* Physische Einheiten sind nur für **Druck-Stylesheets** (`@media print`) geeignet, da Bildschirme zu ungenau sind.

![Absolute Einheiten](img/css_units_absolute.png)

---
<!-- _class: img-right -->
**Relative Maßeinheiten: em & rem**

Relative Einheiten skalieren dynamisch und stehen immer in Bezug zu anderen Werten, meist Schriftgrößen:

- **em (Element-relativ):**
  - Bezieht sich auf die Schriftgröße des **Elternelements**.
  - `1em` entspricht der vererbten Schriftgröße.
  - *Problem:* Kann sich kaskadierend verschachteln (Multiplikations-Effekt bei verschachtelten Listen).


![em und rem](img/css_units_em_rem.png)

---
<!-- _class: img-right -->
**Beispiel: Der em-Multiplikations-Effekt**

Wenn verschachtelte Listen (`<ul>`) relative `em`-Schriftgrößen verwenden, multipliziert sich der Wert auf jeder Ebene des DOM-Baums:

- **Ebene 1 (Basis 16px):** `1.5em` $\rightarrow$ **24px**
- **Ebene 2 (verschachtelt):** `1.5 * 24px` $\rightarrow$ **36px**
- **Ebene 3 (tief verschachtelt):** `1.5 * 36px` $\rightarrow$ **54px**
- **Das Ergebnis:** Der Text wächst unkontrolliert an (Faktor `3.375`).

![em kaskadierend](img/css_em_multiplication.png)

---

- **rem (Root-em):**
  - Bezieht sich immer auf die Schriftgröße
  des **html-Wurzelelements** (standardmäßig 16px).
  - Verhindert unerwünschte Skalierungs-Effekte
  in tiefen Dokumentstrukturen.



---
<!-- _class: img-right -->
**Relative Maßeinheiten: Viewport**

Viewport-Einheiten beziehen sich direkt auf die aktuellen Dimensionen des Browser-Fensters:

- **vw (Viewport Width):**
  - `1vw` entspricht 1% der Viewport-Breite.
- **vh (Viewport Height):**
  - `1vh` entspricht 1% der Viewport-Höhe
  (ideal für bildschirmfüllende Hero-Sektionen).

![Viewport-Einheiten](img/css_units_viewport.png)

---

<!-- _class: img-right -->
**Viewport-Grenzbereiche: vmin & vmax**

- **vmin (Viewport Minimum):**
  - Nutzt den Prozentwert der jeweils kürzeren Viewport-Seite (Breite im Hochformat, Höhe im Querformat).
- **vmax (Viewport Maximum):**
  - Nutzt den Prozentwert der jeweils längeren Viewport-Seite.
- **Vorteil:**
  - Ermöglicht proportionales Skalieren bei Orientierungswechseln auf Mobilgeräten.

![vmin und vmax](img/css_units_vmin_vmax.png)



---
<!-- _class: img-right -->
**Prozent (%) & Best Practices**

- **Prozentwert (%):**
  - **Layouts (Breiten/Höhen):** Bezieht sich auf umschließenden Container (z. B. Bild `width: 50%` in einer `600px` Box ist `300px` breit).
  - **Schriftgrößen:** Bezieht sich auf die vererbte Schriftgröße des Elternelements (75% bei 16px = 12px).

![Prozent und Best Practices](img/css_units_best_practices.png)

---

- **Best Practices:**
  - **Schriftgrößen:** bevorzugt **rem** nutzen > Browser ermöglicht Barrierefreiheit durch Skalieren.
  - **Layout-Raster:** Verwenden Sie **Prozent (%)** oder **Flexbox/Grid**.
  - **Rahmen:** Nutzen Sie **px** für absolute Randschärfe.



---
<!-- _class: structural img-right -->
## Organisation und Struktur (04)
- Ordner und Dateien benennen
- Referenzieren in html
- Chaos im Code
- Stylesheets mit Kommentaren versehen
- Selektoren im Allgemeinen und Speziellen

![bg right](img/Ordnung-im-Chaos.jpeg)

---
<!-- _class: img-right -->

### Ordnerstruktur für Webprojekte

Für Übersicht und fehlerfreie Verlinkung ist eine saubere Struktur im **Wurzelverzeichnis (Root)** essenziell:

- **index.html (Startseite):** Muss direkt im Stammverzeichnis liegen (darf nicht in Unterordnern platziert werden).
![bg right](img/ordnerstruktur.jpg)
- Startseite muss (fast) immer index.html heißen

---
<!-- _class: img-right -->

**Warum fast immer?**

Server sucht automatisch im angeforderten Verzeichnis nach  `index.html`.

Der Webserver kann aber auch so konfiguriert werden, dass er nach einer anderen Datei sucht:
- httpd.conf öffnen &  "DirectoryIndex" suchen
- kann umkonfiguriert werden, dass page.php die Startseite ist

> Standard ist aber index.html

![alt text](img/httpdconf.jpg)

---

- **Sinnvolle Unterordner zur Organisation:**
  - `css/` – Stylesheets (z. B. `style.css`)
  - `img/` – Alle Bilder und Grafikdateien
  - `font/` – Lokale Schriftarten (z. B. `1-Punk.ttf`)
  - `html/` – Weitere Unterseiten der Webpräsenz
- **Vorteil:** Erleichtert das Referenzieren relativer Pfade und vermeidet Chaos bei wachsenden Projekten.


---
### Datei- und Ordner-Benennung

Webserver (meist UNIX-basiert) unterscheiden strikt zwischen Groß- und Kleinschreibung. Befolgen Sie daher stets diese Konventionen:

| Konvention | Beschreibung | Richtig vs. Falsch |
| :--- | :--- | :--- |
| **Kleinschreibung** | Dateinamen immer komplett klein schreiben. | `index.html` $\leftrightarrow$ `Index.HTML` |
| **Keine Umlaute** | Umlaute umschreiben (`ae`, `oe`, `ue`). | `ueber-uns.html` $\leftrightarrow$ `über-uns.html` |
| **Keine Sonderzeichen** | Keine Zeichen wie `ß`, `=`, `@`, `%` oder `_`. | `fuss.html` $\leftrightarrow$ `fuß.html` |
| **Keine Leerzeichen** | Worttrennung per Bindestrich `-` oder camelCase. | `kontakt-formular.html` $\leftrightarrow$ `kontakt formular.html` |

---
<!-- _class: img-right -->

### Referenzieren in HTML: Relative Pfade

Relative Pfade beziehen sich auf die Position der aktuellen HTML-Datei.
Sie sind ideal für die interne Verlinkung einer Website.

> Relative Pfade beziehen sich
IMMER auf die eigene Position! Wobei ICH die Datei bin, in der ich mich gerade befinde.
![bg right](img/pfade.jpg)

---

- **Gleiches Verzeichnis:**
  * Die Zieldatei liegt im selben Ordner wie das HTML-Dokument.
  * Code: `<img src="header.jpg" alt="Maiks Service">`
- **Unterverzeichnis (Abwärts navigieren):**
  * Die Zieldatei liegt in einem Unterordner (z. B. `img/`).
  * Code: `<img src="img/header.jpg" alt="Maiks Service">`

---

- **Übergeordnetes Verzeichnis (Aufwärts navigieren):**
  * Mit `../` springen Sie in der Ordnerstruktur eine Ebene höher.
  * Mehrere Ebenen überspringen Sie mit `../../`.
  * Code: `<img src="../img/header.jpg" alt="...">`
- **Absolute Pfadangabe relativ zur Basis-URI:**
  * Beginnt mit `/` (Slash) und geht vom Hauptverzeichnis (Root) des Webservers aus.
  * Code: `<img src="/img/header.jpg" alt="...">`
  * *Hinweis:** Sollte bei lokaler Entwicklung vermieden werden, da oft Pfadfehler entstehen.



---
<!-- _class: img-right -->

### Referenzieren in HTML: Absolute Pfade

Absolute Pfade existieren systemweit nur ein einziges Mal und sind eindeutig.

> Absolute Pfade haben keinen Bezug zur eigenen Position. Sie beziehen sich immer eine absolute, systemweit erreichbare Adresse!!

![bg right](img/absolute-pfade.jpg)

---

- **Externe Quellen im WWW:**
  * Verwendung für Links auf fremde Websites oder externe Ressourcen.
  * Erfordert immer die Angabe des Protokolls (`http` oder `https`) und die vollständige Domain:
  * Code: `<a href="https://www.maiks-service.de">Maiks Website</a>`
- **Lokale absolute Pfade (Windows):**
  * Dateipfade mit Laufwerksbuchstabe, z. B. `C:\Projekte\img\header.jpg`.
  * **Achtung:** Ungeeignet für Webseiten! Diese Pfade existieren auf den Computern der Webseitenbesucher nicht.

---
<!-- _class: small-text -->

### Wiederholung: HTTP vs. HTTPS

Netzwerkprotokolle regeln die Kommunikation zwischen Browser und Webserver:

- **HTTP (Hypertext Transfer Protocol):**
  * Datenübertragung erfolgt im Klartext.
  * **Gefahr:** Passwörter, Logins und Formulardaten können leicht abgehört oder manipuliert werden.
- **HTTPS (Hypertext Transfer Protocol Secure):**
  * Verschlüsselte Verbindung mittels **TLS/SSL**.
  * Bietet Server-Authentifizierung und Schutz vor Datenmanipulation.
- **Vorteile von HTTPS:**
  * **Sicherheit & Vertrauen:** Pflicht bei Zahlungs- und Formulardaten.
  * **SEO-Vorteil:** Google wertet HTTPS als positives Ranking-Signal.
  * **Browser-Hinweise:** Browser markieren HTTP-Seiten als "nicht sicher".

---
<!-- _class: img-right -->

### Block- und Inline-Elemente

HTML unterscheidet im Textfluss grundlegend zwei Arten von Elementen
- Blockbildende Elemente
- Inline-Elemente


![Block vs Inline](img/block_inline_elements.png)

---

- **Block-Elemente:**
  * Erzeugen automatisch eine neue Zeile und nehmen die volle verfügbare Breite ein.
  * *Beispiele:* `<p>`, `<h1>`–`<h6>`, `<ul>`, `<div>`, `<table>`.
- **Inline-Elemente:**
  * Bleiben im normalen Textfluss (keine neue Zeile) und sind nur so breit wie ihr Inhalt.
  * *Beispiele:* `<a>`, `<strong>`, `<em>`, `<span>`, `<img>`.
> Elemente immer nach ihrer semantischen Bedeutung nutzen, nicht nach ihrem Standard-Aussehen.



---
<!-- _class: img-right -->

### Semantische Seitenstruktur

HTML5 führt spezifische Strukturelemente ein, um Bereichen eine klare logische Bedeutung zu geben:

![HTML5 Semantik](img/html5_semantic_layout.png)

---

- **`<header>` & `<footer>`:** Kopf- und Fußbereiche von Seiten oder Artikeln.
- **`<nav>`:** Navigationsbereich (Haupt- und Subnavigation).
- **`<main>`:** Umschließt den einzigartigen Hauptinhalt einer Webseite.
- **`<section>` & `<article>`:**
  * `section` definiert thematische Abschnitte (z. B. Kapitel).
  * `article` steht für in sich geschlossene, eigenständige Inhalte.
- **`<aside>`:** Randspalten für Zusatzinfos, Werbung oder Verweise.


---
<!-- _class: img-right -->

### Strukturelemente ohne Semantik

Für rein gestalterische Gruppierungen (z. B. Styling oder Layout-Wrapper) existieren neutrale Container.

> Wenn keine semantische Bedeutung gewünscht, erforderlich oder erkennbar ist > SPAN und DIV

![Div & Span](img/div_span_no_semantics.png)

---


- **`<div>` (Division):**
  * Block-Element. Gruppiert Block-Elemente, Bilder oder Tabellen.
  * Dient meist als Layout-Grid-Container.
- **`<span>`:**
  * Inline-Element. Gruppiert Wörter, Phrasen oder Inline-elemente direkt im Fließtext.
- **Best Practice:** Wrapper-Divs vermeiden („Div-Suppe“). CSS-Regeln bevorzugt direkt den semantischen Tags zuweisen.



---
<!-- _class: img-right -->

### Kommentare in HTML und CSS

Kommentare dokumentieren den Quellcode für Entwickler und helfen bei der Fehlersuche. Sie werden vom Browser ignoriert.

> Lässt man sich Code von einer KI entwickeln, kann man sich in den Kommentaren den Code erklären lassen :)

![Kommentare](img/code_comments.png)

---

- **HTML-Kommentare:**
  * Syntax: `<!-- Kommentartext -->`
  * *Einsatz:* Strukturierung von Abschnitten, temporäres Deaktivieren von Code zur Fehlersuche.
- **CSS-Kommentare:**
  * Syntax: `/* Kommentartext */`
  * *Einsatz:* Gliederung des Stylesheets (z. B. Header, Navigation, Footer-Styles).
- **Tipp:** Kommentare nutzen, um unübersichtlichen Code-Bereichen klare Start- und Endpunkte zu geben.

---

**Ergänzen des Quellcodes mit den semantisch
richtigen HTML5 Elementen**

- header
- nav
- article
- footer

> Auch wenn sich die Seite dadurch optisch kaum verändert hat, ist sie jetzt für Suchmaschinen deutlich besser lesbar geworden.

![bg right:50%](img/maik-04-code.jpg)

---
<!-- _class: structural -->

## Navigation (05)
- Hauptnavigation
- Subnavigation
- Große Bilder
- Email Links

![bg right:50%](img/netz.jpeg)

---
<!-- _class: img-right -->

### Die Macht der Vernetzung: Hyperlinks

Hyperlinks sind das Herzstück des WWW. Sie verknüpfen isolierte Seiten zu einem weltweiten Informationsnetz:

> **Entstehung des Netzes:** Erst durch Verknüpfung entsteht das Internet. Inhalte leben davon, vernetzt zu sein.

![Hyperlinks](img/hyperlinks_net.png)

---

- **Keine Angst vor ausgehenden Links:**
  * Surfer kann man nicht festhalten – sie kommen zurück,
  wenn der Inhalt durch Qualität überzeugt!
- **Das Google-Prinzip:**
  * Suchmaschinen und Besucher finden Seiten über Links.
  * Eine Seite mit wenigen Verknüpfungen rankt niedriger als eine, die „mitten im Netz“ steht.

---

> Macht KI das Web kaputt?
Was ist Eure Meinung...


---
<!-- _class: img-right -->

### Hauptnavigation & Nutzerführung

Links sind neben Inhalt und Design das stärkste Instrument zur Benutzerführung
urch die Anordnung und Präsentation von Links wird aktiv gesteuert, wie sich Besucher durch die Seiten bewegen.

- Rückgrat der Website-Informationsarchitektur
- Dient dem Erschließen der gesamten Inhalte
- Muss die geplante Struktur der Site direkt widerspiegeln

![Hauptnavigation](img/navigation_user_guidance.png)

---


### Hyperlinks in HTML: Syntax & Best Practices

Ein Link verbindet Dokumente im Web. In HTML wird dafür das Anchor-Tag (`<a>`) genutzt:

- **Syntax:** `<a href="Linkziel">Linktext</a>`
- **Sprechende Linktexte:**
  * Beschreibt Linkziel klar, damit Besucher und Suchmaschinen sofort wissen, was sich dahinter verbirgt.
  * *Schlecht:* „Hier klicken“, „Weiter“, „Zurück“.
  * *Gut:* „Unser Service-Angebot“, „Aktueller Wetterbericht“.


---
<!-- _class: img-right small-text -->

- **Die target="_blank" Kontroverse:**
  * Zwingt den Browser, den Link in einem neuen Tab/Fenster zu öffnen.
  * **Kritik:** Schränkt die Benutzerkontrolle ein (Browser-Voreinstellung wird übergangen).
- Lasst lieber die Entscheidung, ob der Link in einem neuen Tab oder Fenster geöffnet werden soll, beim Nutzer, indem ihr dieses Attribut weglasst.

![Link Syntax](img/hyperlink_syntax.png)

---
### Aufbau einer URL

`<a href="http://www.wetter.com">Wetterinfo</a>`



> Eine URL kann durchaus beliebig komplex werden,
besteht jedoch immer aus denselben Bestandteilen:

![bg](img/url.jpg)

---
### Relative Links erstellen

Die Hauptnavigation führt in der Regel zu Dokumenten des eigenen Webauftritts.
Wir ergänzen daher auf unserer Startseite folgenden Code


```html
<nav>
  <!-- Hier kommt später unsere Navigation rein -->
  <ul>
    <li><a href="index.html">Heyhoo!</a></li>
    <li><a href="html/dienstleistungen.html">What I do for YOU!</a></li>
    <li><a href="html/mobiles-Leben-im-LKW.html">LKW @home</a></li>
    <li><a href="html/reisen.html">UNTERwegs</a></li>
    <li><a href="html/tauchen.html">UNTERwasser</a></li>
    <li><a href="html/kontakt.html">...DU zu MIR</a></li>
  </ul>
</nav>
```

---
<!-- _class: img-right-->


> Ein Klick auf einen der Links produziert aktuell jedoch noch einen sogenannten **404**


- Fehlermeldung, die der Webserver ausgibt, wenn das Linkziel nicht gefunden wurde.
- Fehlermeldungen sind auf dem Webserver konfigurierbar
- Webserver erwartet unter dem Link
„LKW @home“ eine Webseite mit dem Namen „mobiles-Leben-im-LKW.html“ im Unterordner „html“.

![bg right:50%](img/404.jpg)

---

###### aktueller Stand

![bg](img/maik-05.jpg)

---

## CSS Experimente

Aktuell sieht die Webseite noch nicht besonders schick aus. Das werden wir jetzt gemeinsam ändern, indem wir uns die Styling-Möglichkeiten von CSS ansehen.

1. Wir verschaffen uns einen Überblick über die Stylingmöglichkeiten des jeweiligen Themas
2. Wir probieren die Stylingmöglichkeiten gemeinsam aus (Hands on)
3. Wir arbeiten uns zurück zu Maiks Website und ergänzen die Stylingmöglichkeiten nach und nach in die vorhandene Struktur ein.

---
<!-- _class: img-right-->
### Selektoren im Allgemeinen und Speziellen


**allgemeine Syntax**
- Eigenschaft: Wert;
- Eigenschaft = Eigenschaft, die angesprochen wird
- Wert = Wert, der zugewiesen wird
- Semikolon = Trennzeichen zwischen den Eigenschaften
- Letzte Deklaration kann ohne Semikolon geschriebenwerden,
gilt jedoch als guter Stil.

![bg right:50%](img/css_syntax_de.png)

---

**Unser Testfeld:**
Der Bachelor of Harz
- Definition eines Style Bereiches
- Styles immer im Head
- Kommentarbereiche im Style mit /* xyz */

![bg right:50%](img/css-code.jpg)

---
<!-- _class: small-text-->

**Element- oder Typ-Selektoren**
- Selektor = Name des Elements, das angesprochen werden soll
- Alle Elemente eines Typs werden angesprochen
- **Keine Präfixe**: Werden direkt als HTML-Tag-Name geschrieben (ohne `.` oder `#`, z. B. `p`, `h1`, `body`).
- **Globale Wirkung**: Betrifft *alle* Vorkommen dieses Elements auf der gesamten Webseite. Ideal für allgemeine Standards (z. B. Schriftart auf `body`).
- **Geringe Spezifität**: Besitzen eine sehr niedrige Gewichtung (Spezifität = 1) und lassen sich leicht durch Klassen oder IDs überschreiben.
- **Gruppierung**: Können per Komma kombiniert werden (z. B. `h1, h2, h3 { ... }`), um redundanten Code zu vermeiden.


```css
p {color: red;}
```

---
<!-- _class: small-text-->
**Klassenselektoren**
- Selektor ist das CSS class Attribut
- frei wählbarer Name (ohne Leerzeichen, Umlaute, etc.)
- Kann mehrmals auf der Seite verwendet werden
- Kann auch mit Element Selektoren kombiniert werden
- Selektor wird in CSS mit einem Punkt (.) versehen

```html
<h2 class="meineKlasse">Bachelor of Hartz</h2>
```
```css
.meineKlasse { color: green; }
```

---
<!-- _class: small-text-->

**Kombination von Typ- und Klassen- Selektoren**

```html
<p class="meineKlasse">
Genug Zeit totgeschlagen, wie ein lahmerGaul<br>
Dumm biste nicht, nur einfach stinke faul<br>
...
```
```css
p.meineKlasse {font-style:italic;}
```
oder auch
```html
<p class="meinezweiteKlasse">
Einfach mal zu Hause bleiben<br>
...
```


```css
.meinezweiteKlasse {background-color: yellow;}
```

---
<!-- _class: small-text-->
**Kombination von Klassen**

- Klassen lassen sich miteinander kombinieren
- beide Klassen mit Leerzeichen angeben

```html
<h2 class="meineKlasse undnocheineKlasse">Bachelor of Hartz</h2>
```

```css
.undnocheineKlasse {background-color: red;}
```

---
<!-- _class: small-text-->
**Kombinierte Style-Angaben**

- gleichzeitiges Gestalten mehrerer Klassen & Elemente
- Selektoren mit Kommata trennen

```html
<h1>Blindtext.</h1>
```

```css
.undnocheineKlasse, h1 {background-color: red;}
```

---
<!-- _class: small-text-->

**DIVs & Klassen**

- $\text{<div>}$ ist das Allzweckwerkzeug der Web-Entwicklung
- &nbsp;&nbsp; flexibler Container für beliebige Inhalte
- &nbsp;&nbsp; keine eigene semantische Bedeutung
- &nbsp;&nbsp; ideal für Gruppierungen & Layouts

```html
<div class="einedivKlasse">
  <p>
    16 Semester alles mal probiert<br>
    8 Jahre lang einfach irgendwas studiert<br>
    Sonderpädagogik und Ethnologie<br>
    Wirtschaftsethik und Lexikografie
  </p>
</div>
```

```css
div.einedivKlasse {
   background-color:lightgrey;
   padding: 20px;
}
```



---
<!-- _class: structural -->
## CSS Layout (06)

### Konzepte, Typen & Moderne Techniken


- **Verständnis** der klassischen Layout-Typen (Fixed, Fluid, Elastic)
- **Unterscheidung** von Adaptive vs. Responsive Webdesign
- **Einsatzszenarien**: Wann setzt man was ein?
- **Moderne Werkzeuge**: Flexbox und Grid-Layout im Überblick

---

### Was ist CSS-Layout?

Das Layout bestimmt, wie Elemente auf einer Webseite angeordnet werden und wie sie auf unterschiedliche Bildschirmgrößen (Viewports) reagieren.

#### Klassische Unterteilung:
1. **Fixed** Layout
2. **Fluid** Layout
3. **Elastic** Layout

Diese Begriffe beschreiben vor allem das *Verhalten* des Layouts bei Größenänderungen des Browserfensters.

---

<!-- _class: img-right -->

### Fixed Layout (Starr)

Das Layout hat **feste Abmessungen**, meist definiert in Pixeln (`px`).

- **Verhalten:** Die Breite ändert sich nicht, egal wie groß der Bildschirm ist.
- Ist der Bildschirm kleiner, erscheint ein Scrollbalken. Ist er größer, entsteht ungenutzter Leerraum.
- **Heute:** Wird fast nicht mehr für ganze Seiten verwendet, höchstens noch für spezifische UI-Komponenten.

![Fixed Layout](img/fixed_layout.png)

###### **Quellen:** [MDN Layout Modes](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout), [Smashing Magazine](https://www.smashingmagazine.com/2009/04/fixed-vs-fluid-vs-elastic-layout-whats-the-right-one-for-you/)

---

<!-- _class: img-right -->

### Fluid Layout (Flüssig)

Das Layout nutzt **relative Einheiten**, meist Prozentwerte (`%`) in der Breite, in der Länge können feste Pixelwerte verwendet werden -> Vertikales Scrollen.

- **Verhalten:** Die Elemente dehnen sich aus oder schrumpfen proportional zur Fensterbreite.
- Es füllt immer den verfügbaren Platz aus.
- **Heute:** Ein sehr wichtiger und grundlegender Baustein für Responsive Webdesign.

![Fluid](img/fluid_layout.png)

###### **Quellen:** [MDN CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)

---

<!-- _class: img-right -->

# Elastic Layout (Elastisch)

Das Layout basiert auf der **Schriftgröße**, definiert in Einheiten wie `em` oder `rem`.

- Bleibt proportional zum Text lesbar, auch wenn der Nutzer den Text im Browser vergrößert.
- Ausgezeichnet für Barrierefreiheit (Accessibility).
- Schwer zu gestalten


![Elastic](img/elastic_layout.png)

---
<!-- _class: structural -->
### Adaptive vs. Responsive 


Zwei grundlegend unterschiedliche Konzepte im Webdesign.

---
<!-- _class: img-right small-text -->

**Responsive Webdesign (RWD):**
- Ein **einziges, flüssiges Layout**, mit Media Queries
- nutzt Fluid Grids und flexible Bilder.
- Webseite skaliert auf alle Bildschirmgrößen
- Einziges Layout für alle Geräte



**Adaptive Webdesign (AWD):**
- **Mehrere feste Layouts** für spezifische Breakpoints (z. B. Mobile, Tablet, Desktop).
- Server oder Client entscheidet über das Layout
- *Maßgeschneidert pro Gerät.*

![Devices](img/responsive_devices.png)

###### **Quellen:** [CSS-Tricks: Responsive vs. Adaptive](https://css-tricks.com/the-difference-between-responsive-and-adaptive-design/)

---

### Wann setzt man was ein?

#### Responsive Design (Der Standard)
- Für **Neuentwicklungen** und die allermeisten modernen Websites.
- Besser wartbar (nur eine Codebase) und zukunftssicher (passt auch für unbekannte Zwischengrößen von Displays).

#### Adaptive Design (Der Spezialist)
- Wenn Mobile-Nutzer eine **völlig andere User Experience** oder stark reduzierte Funktionen brauchen (Performance!).
- Um sehr alte, starre Seiten für Mobile nutzbar zu machen, ohne sie von Grund auf komplett neu zu schreiben.

---

<!-- _class: structural -->

### Moderne CSS Layout-Techniken
#### Flexbox und CSS Grid

---

<!-- _class: img-right -->

### Flexbox 

Flexbox (Flexible Box Layout) ist ein **eindimensionales** Layout-Modell (Zeile *oder* Spalte).

- Ideal, um Platz zwischen Elementen zu verteilen und sie auszurichten (endlich einfaches Zentrieren!).
- Reagiert dynamisch auf den verfügbaren Platz.
- Perfekt für UI-Komponenten, Navigationen und Toolbars.

![Flexbox](img/flexbox_layout.png)

###### **Quellen:** [MDN: Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox), [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

---

<!-- _class: img-right -->

### CSS Grid 

Grid ist ein **zweidimensionales** Layout-Modell (Zeilen *und* Spalten gleichzeitig).

- Das mächtigste Werkzeug für komplexe Seitenstrukturen in CSS.
- Ermöglicht das exakte Platzieren von Elementen auf einem Raster.
- Deutlich strikter und strukturierter als Flexbox.

![Grid](img/grid_layout.png)

###### **Quellen:** [MDN: Grids](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids), [CSS-Tricks Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)

---

<!-- _class: structural -->

## Zusammenfassung

1. **Fixed, Fluid, Elastic:** Historische und konzeptionelle Begriffe für Layout-Verhalten.
2. **Responsive Webdesign:** Der moderne Standard (ein flüssiger Code für alle Größen).
3. **Adaptive Webdesign:** Feste, gerätespezifische Layouts für spezielle Use Cases.
4. **Flexbox:** Eindimensional, perfekt für die Ausrichtung von Elementen in einer Reihe.
5. **Grid:** Zweidimensional, ideal für das grobe und feine Seitenlayout.

---

<!-- _class: end -->

# Fragen?

> "The web is inherently responsive. We just keep breaking it with fixed pixels."
> — *John Allsopp (A Dao of Web Design)*

---
<!-- _class: structural -->
### Code-Beispiele

---

<!-- _class: img-right -->
#### **Fixed Layout**
- Feste Breitenangaben in absoluten Pixeln (`px`)
- Layout passt sich **nicht** an den Bildschirm an
- Führt bei kleinen Bildschirmen zu horizontalen Scrollbalken

[Code-Beispiel ansehen](Samples/Layout/fixed.html)

![bg right:50%](img/screenshot_fixed.png)

---

<!-- _class: img-right -->
#### **Responsive Fluid Layout**
- Breitenangaben in relativen Prozentwerten (`%`)
- Layout fließt und füllt den Viewport flexibel aus
- Zentrale Grundlage für modernes Responsive Design

[Code-Beispiel ansehen](Samples/Layout/fluid.html)

![bg right:50%](img/screenshot_fluid.png)

---

<!-- _class: img-right -->
#### **Elastic Layout**
- Größen skalieren mit der gewählten Schriftgröße (`em` / `rem`)
- Layout wächst proportional, wenn der Nutzer die Schrift vergrößert (Strg. + Mausrad)
- Sehr gut für Barrierefreiheit, jedoch komplexer im Design

[Code-Beispiel ansehen](Samples/Layout/elastic.html)

![bg right:50%](img/screenshot_elastic.png)

---

<!-- _class: img-right -->
#### **Flexbox Layout**
- Eindimensionales Verteilungssystem (Zeile *oder* Spalte)
- Boxen verteilen den verfügbaren Platz dynamisch (z.B. `flex: 1`)
- Ideal zur Ausrichtung von Elementen und UI-Komponenten

[Code-Beispiel ansehen](Samples/Layout/flexbox.html)

![bg right:50%](img/screenshot_flexbox.png)

---

<!-- _class: img-right -->
#### **Grid Layout**
- Zweidimensionales Rastersystem (Zeilen *und* Spalten gleichzeitig)
- Elemente lassen sich exakt auf vordefinierten Spuren platzieren
- Das mächtigste CSS-Werkzeug für das strukturelle Seitenlayout

[Code-Beispiel ansehen](Samples/Layout/grid.html)

![bg right:50%](img/screenshot_grid.png)---


---

### Maik's Responsive Layout

- klassisches Zweispalten Layout
- Header & Footer
- Navigationsbar links
- Content-Bereich wird durch
umschließenden Bereich begrenzt




![bg right](img/maiks-layout.jpg)

---
<!-- _class: twocolumns -->
#### Wrapper und body (06a)
- Wrapper fasst den gesamten Inhalt zusammen
- bildet einen Rahmen um das layout
- begrenzt maximale breite auf einen definierten Wert
- zentriert das layout auf der seite
- keine semantische Bedeutung, daher DIV

in index.html ist der wrapper das div-Element mit der id="wrapper"

```html
<body>
<!-- Sichtbarer Dokumentinhalt im body -->
<div id="wrapper">
<header>
....
</footer>
</div>
</body>
```

---
<!-- _class: twocolumns -->


- weißer Hintergrund
- schwarzer text
- Breite 80 % des Bildschirms
- Maximalbreite 1600 px, damit der Inhalt auf großen Monitoren nicht zu breit wird.
- Ränder oben 0 px und seitlich automatisch gleich breit

Wir ergänzen im css:
```css
#wrapper {
background-color: #FFFFFF;
color: #000000;
margin: 0 auto;
padding: 0px;
width: 80%; max-width: 1600px;
}
```

---

![bg](img/06a.jpg)

---
<!-- _class: twocolumns -->
#### Ein neuer Header
- Wrapper funktioniert
- Bild weigert sich im Container zu bleiben
- h1 soll in den Header
- Bild aus dem Header entfernen
- Bild wird über das css geladen

```html

<header>
<div id="h1container"><h1>
  Maik`s mobiler Service</h1></div>
</header>

```

---
<!-- _class: twocolumns -->
##### im css


- Außenabstand des headers von 0 Pixeln
- Innenabstand von 10px nach oben, damit Überschrift nicht am oberen Rand klebt
- Laden des Header-Bildes als background-Image
- keine Wiederholung des Bildes
- Bild wird an die breite des umgebenden Elements angepasst
- Hintergrundfarbe für den Fall, dass das Bild nicht geladen werden kann
- Minimale Höhe des Headers von 360 Pixeln

```css
header {
margin: 0px;
padding-top: 10px;
background:url(img/header.jpg) no-repeat;
background-size: cover;
background-color: #eef1f0;
min-height: 360px;
}

```

---
# Das Projekt
2020 beschließt der KFZ Mechaniker Meister Maik seine Passion zur Haupterwerbsquelle und sich selbstständig zu machen. Durch sein mobiles Leben im LKW hat er sich auf den Ausbau von Fahrzeugen zu autarken Wohnräumen spezialisiert. Seine jahrelange Erfahrung in der Werkstattleitung eines Camping- und Caravantechnik Anbieters nutzt er, um Caravans, Wohnmobile und individuelle Fahrzeugausbauten zu reparieren, pflegen und umzurüsten.
![bg right:40%](img/das-ist-Maik.jpeg)

---

**Seine Dienstleistungen beinhalten**
- KFZ und LKW Reparaturen
- Caravan- und Wohnmobil Reparaturen
- Vorbereitung zur TÜV Prüfung und Prüfung von Gasanlagen
- Ein- Aus- und Umbau der KFZ Elektrik bis zur autarken Solaranlagenplanung
- Kompletter Fahrzeugausbau eines Transportfahrzeuges zum
„Wohn“-Mobil
Da Maik ein mobiles Leben führt, ist er selten am gleichen Platz zu finden. Um ihn und seine Dienstleistungen dennoch auffinden zu können, benötigt er eine gut auffindbare Webseite mit seinen digitalen Kontaktdaten.

---

# Der fundamentale Paradigmenwechsel
## Vom manuellen Kodieren zur KI-gestützten Orchestrierung

Quelle:
(IJACSA) International Journal of Advanced Computer Science and Applications, Vol. 16, No. 11, 2025

**"AI in Web Development: A Comparative Study of
Traditional Coding and LLM-Based Low-Code
Platforms"**

---

### Handwerkliche Kodierung (Status Quo):
Softwareentwicklung als zeilenweises Schreiben von Syntax; Fokus auf Implementierungsdetails und das Beheben von Syntax fehlern.

### KI-gestützte Orchestrierung (Zukunft):
Der Entwickler agiert als „Dirigent“ (Orchestrator), der Anforderungen definiert, KI-Modelle steuert und deren Ergebnisse validiert.

### Kernkompetenz:
Die Fähigkeit zur präzisen Problemformulierung und Systemintegration ersetzt das reine Auswendiglernen von Programmiersprachen.

---
## Spec-Driven Development (SDD)

### Die neue Ära des Workflows

Workflow-Zyklus: Specify → Plan → Tasks → Implement. Der Prozess beginnt bei der Spezifikation, nicht beim Code.

Verschiebung der Wertschöpfung: Produktivitätssprünge durch automatisiertes Scaffolding (Grundgerüst-Erstellung) von HTML, CSS und JS.

Menschliche Rolle: Der Entwickler fungiert als „Digital Shepherd“ (Hirte), der die Qualität, Sicherheit und Semantik des KI-Outputs überwacht.


---
## KI-native Entwicklungsumgebungen
### Vom Texteditor zur intelligenten Plattform

---

### Werkzeugwechsel:
Übergang von klassischen Editoren (wie Notepad++) zu KI-nativen Umgebungen (z. B. Cursor), die Kontext über das gesamte Projekt verstehen.

### Kontextbewusstsein:
Nutzung von agentischen Regeln und ähnlichen Konfigurationen, um der KI projekt-spezifische Architekturregeln beizubringen.

### Echtzeit-Refactoring:
KI-gestützte Identifikation von „Code Smells“ und automatische Optimierung auf moderne Standards.

---




