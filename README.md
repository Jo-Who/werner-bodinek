# Werner Bodinek — Website

Neue Website für **Werner Bodinek**, freischaffender Theatermacher (Schauspiel, Musik, Produktion und Regie). Inhaltlich basiert sie auf der bestehenden Seite [bodinek.ch](https://www.bodinek.ch/), neu gestaltet im Stil eines Theaterzettels im Rampenlicht.

## Aufbau

Statische Website — reines HTML, CSS und ein wenig JavaScript. Keine Build-Schritte, keine Abhängigkeiten.

```
index.html       Startseite
planung.html     Aktuelle Produktionen (Motz & Motzer, Der Tribun)
daten.html       Alle Spieldaten
media.html       Musik & Video
vita.html        Biografie & Auszeichnungen
links.html       Weggefährten & Spielstätten
archiv.html      Werkarchiv 1979–heute
reflexe.html     Texte & Gedanken
assets/
  css/styles.css Gestaltung (Farben, Typografie, Layout)
  js/main.js     Mobile-Menü, Scroll-Effekte
  img/           Bilder aus den Produktionen
```

## Lokal ansehen

Einfach `index.html` im Browser öffnen — oder ein kleiner lokaler Server:

```bash
python3 -m http.server 8080
# danach http://localhost:8080 öffnen
```

## Veröffentlichen mit GitHub Pages

1. Repository auf GitHub → **Settings → Pages**
2. Bei *Source* den Branch `main` und den Ordner `/ (root)` wählen
3. Speichern — die Seite ist nach kurzer Zeit unter
   `https://<benutzername>.github.io/<repo>/` erreichbar.

Für eine eigene Domain (z. B. `bodinek.ch`) lässt sich unter *Pages → Custom domain* eine Adresse hinterlegen.

## Anpassen

- **Texte & Daten:** direkt in den jeweiligen `.html`-Dateien.
- **Farben & Schrift:** ganz oben in `assets/css/styles.css` (Abschnitt `:root`).
- **Bilder:** in `assets/img/` ablegen und im HTML referenzieren.

---

Kontakt: Werner Bodinek · +41 79 461 82 02 · werner@bodinek.ch
