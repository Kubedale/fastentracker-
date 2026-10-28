# Fastentracker

Ein einfacher Fastentracker als einzelne HTML-Datei, ohne Installation.

## Nutzung

`index.html` im Browser öffnen.

* Start (letzte Mahlzeit) und Ende (Ziel) eingeben oder eine Schnellauswahl wählen (12, 14, 16:8, 18:6, 24 Std.)
* **Starten** beginnt das Fasten, **Beenden** stoppt es und speichert es im Verlauf
* Die App zeigt laufend die gefastete Zeit, die Restzeit, den Fortschritt und die aktuelle Stoffwechselphase
* Jede Minute erscheint ein neuer Motivationsspruch, per Button auch sofort

* Optional Benachrichtigungen bei jedem Phasenwechsel und beim Erreichen des Ziels
* Als App installierbar (PWA) und offline nutzbar

Die Daten werden nur lokal im Browser gespeichert (localStorage).

## Als App installieren

Installation und Offline-Betrieb funktionieren nur, wenn die App über eine https-Adresse
geöffnet wird (zum Beispiel GitHub Pages), nicht als lokale Datei.

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
