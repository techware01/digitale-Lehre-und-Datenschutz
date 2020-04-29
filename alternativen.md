# Digitale Zusammenarbeit 
## Mit freier Software und Datenschutz
Alle beschriebenen Alternativen sind [OpenSource](https://fsfw-dresden.de/2020/04/DiLi-News-Interview.html) und schützen Deine Daten. Verwende nur Instanzen, bei denen Du den Bereitsteller:innen vertraust, dass diese den Datenschutz ebenfalls ernst nehmen oder biete am Besten selbst eine Instanz an (für fortgeschrittene Benutzer:innen auf einem eigenen Server). Zu jeder vorgestellten Software bieten wir eine kleine Liste öffentlicher Instanzen oder Webadressen, unter denen Du noch weitere Instanzen findest. 

<!-- # Inhaltsverzeichnis
- [JITSI-Meet](#jitsi)
- [BigBlueButton](#bbb)
- [Mumble](#mumble)
- [Etherpad-Lite](#etherpad)
- [Cryptpad](#cryptpad) -->

# Konferenzsysteme
## JITSI-Meet
### Beschreibung
Audio- und Videokonferenzsystem für kleine Gruppen das einfach im Browser läuft. Wurde von der Firma 8x8 entwickelt und hat eine sehr aktive Community, die zur Verbesserung der Software beiträgt. Gerade kommen auch häufiger Updates, welche die Stabilität weiter verbessern.

### Funktionsumfang

- Audio- und Videotelefonie
- Teilen des Bildschirms + Fernsteuerung durch andere Gesprächsteilnehmende möglich
- gemeinsames Schauen von Youtube-Videos
- eigener Chat für jeden Konferenzraum
-  Meldung per Handzeichen

### Vorteile
- läuft direkt im Browser
- kein Account zur Nutzung benötigt
- mit einem Klick einen neuen Konferenzraum mit  beliebigem Namen erstellen
- einfaches Beitreten über einen Link (Räume können mit einem Passwort gesichert werden)
- sehr aktives Entwickler*innen Team und große Community

### Nachteile
- gerade bei geringer Bandbreite häufiger Video- und Audioprobleme => unbedingt vorher ausprobieren, ob es funktioniert und ggf. eine hier beschriebene Alternative (z.B. BigBlueButton) nutzen.
- läuft insb. mit Firefox noch nicht stabil => derzeit lieber einen auf Chromium basierenden Browser nutzen (Brave, Chromium, Chrome, der neue Edge, ...) bzw. die App oder Desktopanwendung verwenden => Update kommt bald
- derzeit keine Ende-Zu-Ende-, sondern nur eine Transportverschlüsselung => Instanz wählen, bei der man den Admins vertraut oder selber hosten => ein Update wird ebenfalls gerade entwickelt
- In den mobilen Apps sind noch CrashTracker von Google eingebaut => FDroid-Version hat diese nicht => Issue wurde erstellt

Clients
- Browser 
- Mobile Apps
- Desktop-Anwendung

Auswahl an öffentlichen Instanzen
- https://jitsi.meet.org (Instanz von jitsi.org => durch hohen Bekanntheitsgrad häufig überlastet)
- https://www.kuketz-meet.de/ (Instanz von Kuketz - Blog mit kritischem Blick auf IT-Sicherheit und Datenschutz )
- https://meet.systemli.org/ (Instanz von systemli.org - linkes Technikkollektiv)
- https://fairmeeting.net/ (Instanz von https://www.fairkom.eu/)
- Große Liste von öffentlichen Instanzen: https://fediverse.blog/~/DonsBlog/videochat-server
- Tool zur automatischen Auswahl einer aktuell sehr performanten Instanz: https://jitsi.random-redirect.de

## BigBlueButton (BBB)
### Beschreibung
Sehr stabile und umfangreiche, aber relativ einfach Bedienbare Konferenzsoftware. Sehr gut für alle möglichen Formen der digitalen Lehre geeignet. Kann aber genauso gut für private Treffen, wie zum Beispiel einen Spieleabend verwendet werden, da sich nicht benötigte Elemente (z.B. der Chat) mit einem Klick ausblenden lassen. Ein sehr großer Vorteil ist ebenfalls, dass BBB ohne Probleme in jedem Browser läuft und keine Anwendung benötigt wird.

### Funktionsumfang
- Audio- und Videotelefonie mit automatischer Stimmaktivierung (Mikro ist stummgeschalten, wenn man nicht redet)
- Teilen des Bildschirm
- es lassen sich feste Konferenzräume erstellen
- Erstellung von Breakouträumen in einem Konferenzraum möglich
- verschiedene Moderationswerkzeuge
- Präsentationsmöglichkeit eigener Folien mit hervorgehobenen 
- Whiteboards mit mehereren Tools zum gemeinsamen Zeichnen, etc.
- Chat
- eingebauter digitaler Notizblock
- Konferenzen lassen sich aufzeichnen und später nochmal anschauen
- gibt auch die Möglichkeit nur zuzuhöhren => Vortrag/Vorlesung

### Vorteile
- unterstützt alle modernen Browser
- großer Funktionsumfang
- läuft sehr stabil
- verträgt auch mehrere Menschen mit Video
- verschiedene Frontends mit unterschiedlichem Funktionsumfang (z.B. mit und ohne notwendiger Registrierung) => wir nutzen derzeit [Greenlight](https://bigbluebutton.org/2018/07/09/greenlight-2-0/)

### Nachteile
- erfordert von Referent*innenseite kurze Einarbeitung in die Funktionen 
- größerer Ressourcenbedarf des Servers und der Anwendung
- keine Ende zu Ende Verschlüsselung
- laut offiziellen Angaben max. 120 Leute pro Konferenzraum

### Clients
- alle modernen Browser, auch mobil

### Auswahl an öffentlichen Instanzen
- https://bbb.cyber4edu.org/b (Instanz der Initiative [Cyber4Edu](https://cyber4edu.org/c4e/wiki/start))
- https://bbb.bluit.de 
- https://bbb.daten.reisen/b




## Mumble
### Beschreibung
Leichtgewichtiges Audiokonferenzsystem, welches gut mit geringen Bandbreiten klar kommt, umfangreiche Audioeinstellungen bietet und via Desktopanwendung oder App verwendet werden kann. Für größere Teamtreffen geeignet, für die kein Video benötigt wird. Kommt auch sehr gut mit wenig Bandbreite klar. Verwenden wir derzeit in der Tuuwi für Plena und AG Treffen und es funktioniert sehr gut.

### Funktionsumfang
- Audiotelefonie
- Chat für jeden Konferenzraum und privater Chat
- durch Admin festlegbare Konferenzräume
- je nach Einrichtung des Servers ist das Anlegen eigener und/oder temporärer Räume möglich
- erweiterbar mit Bots (zum Beispiel Musicbot zum Abspielen von Musik von verschiedenen Internetquellen, Internetradio, mp3-Dateien und Co.)
- sowohl der Server, als auch einzelne Konferenzräume können mit Passwort geschützt werden

### Vorteile
- geringer Ressourcenverbrauch
- gut skalierbar
- umfangreiche Audioeinstellungen (z.B. Voice Activation, PushToTalk, Antihall, Audiokompression)
- auch mit geringer Bandbreite gut nutzbar

Nachteil
- möglicherweise zu Beginn größerer Aufwand bei der Einrichtung des Tons
- die mobilen Apps laufen nicht immer stabil
- mobile Version bietet weniger Einstellungsmöglichkeiten (z.B. um die Lautstärke anderer Gesprächsteilnehmender einzeln anzupassen)

### Clients
- Desktopanwendung
- Apps im Google-PlayStore (Plumble), F-Droid (Mumla) und im iOS AppStore (auch auf dem iPad verfügbar)
- je nach Instanz im Browser nutzbar

### Auswahl öffentlicher Instanzen
- https://www.systemli.org/service/mumble.html (Instanz von systemli.org)
- Informationen zu Mumbleservern vom Freifunk: https://wiki.freifunk.net/Mumble


>Eine ausführliche und laufend aktualisierte Übersicht über öffentliche Instanzen der hier vorgestellten Konferenzsoftware, bietet außerdem der CCC in einem eigenen Pad an: https://pads.ccc.de/jitsiliste.

# Kollarobatives Schreiben
## Etherpad Lite
### Beschreibung
Erlaubt es einfache Online Dokumte direkt im Browser in Echtzeit gemeinsam zu bearbeiten.
Ein super Tool, durch das ewiges hin und her Schicken von Dokumente, mit allen damit verbudenden Nachteilen oder auch die Nutzung von GoogleDocs nicht mehr nötig sind.
Eignet sich zum Beispiel hervorragend, um ein gemeinsames Protokoll einer Videokonferenz anzulegen.

### Funktionsumfang
- grundlegende Formatierungstools, wie fett, kursiv, unterstrichen, Liste, ...
- Exportfunktion
- Chat 
- Kennzeichnung unterschiedlicher Autor:innen im Text
- Zeitstrahl, um vergangene Bearbeitung anzuschauen
- sehr umfangreiche Erweiterungsmöglichkeiten durch eine große Anzahl an Plugins

### Vorteile
- sehr einfach zu bedienen
- neue Pads sind super einfach und schnell erstellt
- automatische synchronisation 
- einfach über einen Link teilbar

### Nachteile
- Pads werden unverschlüsselt auf dem jeweiligen Server abgelegt
- manche Instanzen haben stabilitäts Probleme, gerade wenn viele Plugins eingesetzt werden

### Clients
- alle modernen Browser, auch mobil

### Auswahl öffentlicher Instanzen
- https://yopad.eu/
- https://pad.fridaysforfuture.de/
- https://pad.systemli.org/
- https://pad.riseup.net/
- https://pad.disroot.org/
- Und viele, viele mehr ...

## Cryptpad
Im Grunde die verschlüsselte Variante des Etherpads mit erhöhtem Funktionsumfang. Weitere  Dokumenttypen sind hier direkt mit integriert. Je nach Instanz z.B. Präsentation, Tabelle, Umfrage, Whiteboard, ...

### Vorteile
- je nach Instanz mehr Dokumententypen, wie Tabellen oder Präsentationen
- mit Login, um alle erstellten Dokumente, an einem Ort zu speichern
- einfach über einen Link teilbar

### Nachteile
- längere Ladezeiten
- unerübersichtlicher als Etherpad

### Clients
- alle modernen Browser, auch mobil

### Auswahl öffentlicher Instanzen
- https://cryptpad.piratenpartei.de 
- https://cryptpad.fr/
- https://pads.in-ulm.de (nur Textpad)

# Seiten, die viele veschiedene öffentliche Dienste kostenlos bereitstellen
- [Systemli](https://www.systemli.org/service/index.html)
- [Snopyta](https://snopyta.org/)
- [Dis\`root´](https://disroot.org/de/#services)
- [..::tchncs::..](https://tchncs.de/)
- [Chatons](https://entraide.chatons.org/de/)


**Wenn euch die hier aufgelisteten Dienste gefallen und ihr Sie ebenso lieben lernt wie wir, lasst doch gerne mal eine Spende bei den jeweiligen Anbietern da. Viele Dienste sind auf Spenden angewiesen, um weiter bestehen zu können und tragen maßgäblich zu einem freieren und offeneren Internet, ohne Überwachung und Datenverkauf bei!**

# Weitere Übersichten und Artikel zu den oben beschrieben Diensten
- [Corona: Technik-Tipps fürs Homeoffice](https://digitalcourage.de/blog/2020/corona-homeoffice-tipps#2) (Digitalcourage e.V.)
- [Freie Lern- & Lehrmaterialien](https://wiki.fsfw-dresden.de/doku.php/open_educational_ressources#digitalisierungbeschleuniger_corona_-_auch_in_der_lehre) (FSFW Dresden)
- [Solidarische Infrastruktur für solidarische Aktionen](https://www.systemli.org/de/2020/03/15/solidarische-infrastruktur.html) (Systemli.org)
