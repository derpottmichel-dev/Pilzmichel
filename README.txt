PilzMichel – Web-Edition (Android-freundlicher Prototyp)
========================================================

Was ist enthalten?
- Responsive Oberfläche für Smartphone und Desktop
- Startseite, Fotoauswahl/Kamera, Pilzwissen, lokale Fundliste
- Optionale Standortabfrage (nur nach Browser-Zustimmung)
- Funddaten lokal im Browser speichern und als JSON exportieren
- PWA-Grundgerüst (Manifest + Service Worker) für spätere Installation auf Android
- Kleine Demo-Artenliste und Sicherheitshinweise

Wichtig – aktueller Stand
- Noch KEINE echte KI-Bilderkennung
- Noch KEINE zentrale Online-Datenbank oder Benutzerkonten
- Noch KEINE automatische wissenschaftliche Datenübermittlung
- Noch KEINE Werbeanzeigen
- Die Demo-Artenliste ist klein und ersetzt kein fachlich geprüftes Pilzlexikon.
- Fotos und Funde bleiben lokal im Browser; sie werden nicht automatisch hochgeladen.

So testest du es auf Android
1. Lade die ZIP-Datei herunter und entpacke sie mit der Dateien-App.
2. Für eine richtige Web-App-Installation muss die Website später unter einer HTTPS-Adresse gehostet werden. Eine lokal geöffnete HTML-Datei lässt sich nicht als vollwertige PWA installieren.
3. Sobald sie gehostet ist, öffne die Website in Chrome. Tippe auf ⋮ und wähle „Zum Startbildschirm hinzufügen“ oder „App installieren“ (die Bezeichnung kann variieren).

Nächste technische Schritte
1. Einen einfachen Hosting-Dienst auswählen und die Dateien dort veröffentlichen.
2. Eine sichere serverseitige Schnittstelle für die KI auswählen und einrichten (API-Schlüssel niemals in index.html eintragen).
3. Eine zentrale Datenbank mit Artendaten und getrennten Fundmeldungen aufbauen.
4. Datenschutz, Einwilligungen, Aufbewahrung, Export und Schutz sensibler Fundorte prüfen.
5. Erst danach die KI-Erkennung anschließen und mit echten Fotos testen.

Sicherheitsnotiz
Eine Foto-App kann Pilze falsch bestimmen. Keine Essbarkeitsfreigabe allein anhand eines KI-Ergebnisses. Bei Unsicherheit nicht verzehren; fachkundige Bestimmung einholen.
