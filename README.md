# anfrageprofi.de: Verkaufs-Website

Statische Verkaufs-Website fuer **anfrageprofi**, das Anfrage-System fuer Handwerk
und Dienstleister von Florian Boldt (Leverkusen).

Jede Kundenanfrage wird sofort erfasst, dem Kunden in Ihrem Namen bestaetigt und
geordnet abgelegt. Termin oder Absage gehen mit einem Klick raus.

## Seiten

- `index.html`: Startseite (Erklaerfilm, Leistungen im Ueberblick als vier Kacheln, Fuer wen, Vorher/Nachher, So funktioniert es, Preis, Leistungen im Detail inkl. Google-Profil, Ueber mich, FAQ, Kontakt)
- `anfrage-system-handwerk.html`, `anfrage-system-reinigung.html`, `anfrage-system-events.html`: Branchen-Seiten
  (die alten Adressen `anfrage-system-elektriker.html`, `-maler.html`, `-heizung-sanitaer.html` leiten auf die Handwerk-Seite)
- `rechner.html`: Verlustrechner
- `musterbetrieb.html`: Musterseite eines erfundenen Handwerksbetriebs mit eingebautem Formular
- `formular.html`: das einbettbare Anfrageformular (Branchen-Vorlagen ueber `?gewerk=`, siehe Kommentar in der Datei)
- `vorschlag.html`, `akquise.html`: persoenlicher Vorschlag und Brief-Werkzeug fuer die Akquise (nicht verlinkt, noindex)
- `impressum.html`, `datenschutz.html`: Pflichtseiten
- `branche.css`: gemeinsames Aussehen der Branchen-Seiten

## Veroeffentlichung

Wird kostenlos ueber **GitHub Pages** gehostet (Adresse: anfrageprofi.de). Kein Build noetig,
reines HTML/CSS. Alles, was auf `main` landet, ist nach ein bis zwei Minuten live.
