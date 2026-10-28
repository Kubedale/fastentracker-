# Fastentracker

Ein einfacher Fastentracker als einzelne HTML-Datei, ohne Installation.

## Nutzung

`index.html` im Browser öffnen.

* Start (letzte Mahlzeit) und Ende (Ziel) eingeben oder eine Schnellauswahl wählen (24, 40 oder 72 Std.)
* **Starten** beginnt das Fasten, **Beenden** stoppt es und speichert es im Verlauf
* Die App zeigt laufend die gefastete Zeit, die Restzeit, den Fortschritt und die aktuelle Stoffwechselphase
* Zählt die Fastenstunden insgesamt (Startwert 2008 Std., das laufende Fasten wird live mitgezählt)
* Jede Minute erscheint ein neuer Motivationsspruch, per Button auch sofort

* Optional Benachrichtigungen bei jedem Phasenwechsel und beim Erreichen des Ziels
* Als App installierbar (PWA) und offline nutzbar

Die Daten werden nur lokal im Browser gespeichert (localStorage).

## Als App installieren

Installation und Offline-Betrieb funktionieren nur, wenn die App über eine https-Adresse
geöffnet wird, nicht als lokale Datei.

### Einrichtung über GitHub Pages (einmalig)

1. Im Projekt: **Settings** → links **Pages**
2. Unter „Build and deployment“ bei **Source**: **GitHub Actions** auswählen
3. Oben auf **Actions** → links **Fastentracker veröffentlichen** → rechts **Run workflow** → grüner Knopf **Run workflow**
4. Nach ca. 1 bis 2 Minuten ist die App da: `https://kubedale.github.io/fastentracker-/`

Danach wird jede Änderung automatisch veröffentlicht.

* **Android / Chrome:** Button „App installieren“ oder im Menü „App installieren“
* **iPhone / Safari:** Teilen, dann „Zum Home-Bildschirm“

## Benachrichtigungen

Ohne Server kann eine Web-App keine Nachrichten senden, während sie komplett geschlossen ist.
Die Benachrichtigungen kommen deshalb, solange die App geöffnet ist oder im Hintergrund läuft.
Auf dem iPhone sind Benachrichtigungen nur in der zum Home-Bildschirm hinzugefügten App
möglich (ab iOS 16.4).

## Hinweis

Die Phasen sind Richtwerte aus der Fachliteratur (Cahill 2006, Longo & Mattson 2014,
Anton et al. 2018, de Cabo & Mattson 2019, Ho et al. 1988) und können individuell stark
abweichen. Keine medizinische Beratung.
