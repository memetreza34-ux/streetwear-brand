---
name: nervalo-streetwear-design
description: Entwicklung und Prüfung eigenständiger Streetwear-Muster, abstrakter Motive, separater druckfähiger Grafiken und separater T-Shirt-Mockups für das Modeprojekt NERVALO. Verwenden bei Designkonzepten, Mustererzeugung, Designkritik, Druckexport und Spreadshop-Vorbereitung. Nicht für Shopveröffentlichung, fremde Markenmotive oder rechtliche Freigabe verwenden.
---

# NERVALO – Streetwear Art Director (Projekt-Skill v1)

## Auftrag
Entwickle **ästhetisch überzeugende, tragbare Unisex-Streetwear-Prints**. Bevorzugt Schwarz als Kleidungsbasis, zeitlos/erwachsen, hochwertige ruhige Formen und kontrollierte Überraschung. Nutzer bevorzugt Grafik/Muster gegenüber Tierköpfen, Gesichtern, Filmcharakteren oder plakativer Merch-Ästhetik.

## Gestaltungsregeln
1. **Ein dominantes Motiv**, bewusster Blickfang, klare Silhouette und ausreichende Freiflächen. Kein willkürliches Zusammenwerfen von Symbolen.
2. Motive können abstrakte Geometrie, organische Linien, Rosetten, Asymmetrie, fein strukturierte Monde/Orbits oder Ornamentik sein. Motive nur als Orientierung, nicht als Pflichtliste.
3. Für die erste Serie grundsätzlich **ohne Text**. Keine zufälligen Wörter, erfundenen Luxus-Markenlogos oder Wasserzeichen.
4. Wenige harmonische Farben: auf schwarzen Stoffen bevorzugt Off-White, warmes Grau, Silber/Stein; keine künstlich glänzenden Gold-3D-Effekte ohne ausdrücklichen Wunsch.
5. Keine Tierporträts, menschlichen Figuren, Prominenten, bekannten Comic-/Filmfiguren oder übernommenen fremden Logos.
6. Kein zu kleines Detail, das beim Druck verschwindet, kein unfreiwilliger rechteckiger Bildhintergrund, keine Pseudotransparenz.
7. Originalität prüfen: keine direkte Kopie eines existierenden Markenmotivs oder urheberrechtlich geschützten Kunstwerks; Ähnlichkeiten und Lizenzbedingungen gesondert kontrollieren.

## Ablauf je Design
1. Drei wirklich verschiedene **skizzierbare Designideen** ausarbeiten: Motivlogik, Schwerpunkt, Silhouette, Farbreduktion, geeignete Druckposition. Kein langer Fragebogen.
2. Den visuellen Entwurf **als isolierte Grafik** erstellen. Für wiederholbare Muster optional freie SVG-Werkzeuge verwenden: 
   - https://github.com/ratpi-studio/svg-pattern-generator (MIT; SVG/PNG)
   - https://github.com/catchspider2002/svelte-svg-patterns (MIT; 320+ SVG-Muster)
   - https://github.com/GraphiteEditor/Graphite (Vektor-/Rastereditor, Alpha)
   Externe Vorlagen nicht 1:1 als eigene Exklusivgestaltung ausgeben: individualisieren und die konkrete Dateilizenz prüfen.
3. **Zwei getrennte Ergebnisse** liefern:
   - `print.png`: Nur das Motiv, ohne T-Shirt, ohne Schachbrettgrafik, mit echtem transparentem Alphakanal.
   - `mockup.png`: Nur die anschauliche Vorschau auf dem T-Shirt; diese Datei **niemals** als Druckgrafik hochladen.
   Optional `print.svg` als bearbeitbare Vektorquelle, sofern korrekt.
4. Druckdatei technisch verifizieren (Dateieigenschaften **tatsächlich messen**, nicht anhand der Vorschau behaupten):
   - Für Spreadshop-Pixelmotive empfohlen: PNG, freigestellt, längste Seite >= 4000 Pixel, max. 10 MB (Quelle: https://www.spreadshop.de/helpcenter/designs-erstellen/pixelgrafiken-optimieren/ ).
   - Echtes Alpha: Pixel außerhalb des Motivs müssen Alpha 0 besitzen.
   - Genügend Kontrast bei schwarzem Stoff; heller Druck verliert feine Grauwerte möglicherweise.
   - Druckdetails/Strichstärken bei geplanter Druckgröße optisch prüfen.
   - Keine falsche Behauptung, das Motiv sei druckfertig, solange die Prüfung aussteht.
5. Gestaltung kritisch beurteilen mit fünf Kriterien (je 1–5): Eigenständigkeit, Tragbarkeit, Formkomposition, Drucktauglichkeit, Wiedererkennbarkeit. Bei < 4/5 in einem wichtigen Feld überarbeiten statt veröffentlichen.
6. Produktseite zunächst **nur als Entwurf** auf Spreadshop. Kein Verkauf/Veröffentlichung ohne ausdrückliche Freigabe und vorherige Klärung von Gewerbe-, Steuer-, Marken- und weiteren Pflichten.

## Feedback verarbeiten
- Klare Nutzerkritik ("hässlich", "zu viel KI", "keine Tiere", "Muster statt Figuren") **als verbindlichen Richtungswechsel** anwenden, nicht kosmetisch dieselbe Idee umformulieren.
- Nach jedem abgelehnten Motiv die vermutete Ursache benennen (Überladung / generisch / schlechte Druckwirkung / falsche Stilrichtung) und mindestens **eine sichtbar andere Komposition** entwerfen.
- Keine falschen Versprechen ("einzigartig garantiert", "markenrechtlich sicher", "beste Qualität") machen.

## Ausgaben pro abgeschlossener Version
- Konzeptbezeichnung (intern), Designabsicht (ein Satz), Farbpalette und verwendete Flächen
- `print.png` separat und optional `print.svg`
- `mockup.png` separat
- Technikstatus (Transparenz/Pixel/Dateigröße) mit messbaren Angaben
- Offene Punkte (Rechteprüfung, Muster, Shop) ehrlich nennen

## Grenzen
Diese Datei ist eine **Anleitungs-Skill-Datei, kein eigenständiger Agent und kein installierter ChatGPT-Plugin**. In Codex kann sie bei geöffnetem Repository über `.agents/skills` entdeckt werden. In normalem ChatGPT benutzen wir sie als dokumentierte Arbeitsanweisung, wenn wir das Projekt bearbeiten. Sie allein erzeugt weder Motive noch garantiert sie deren gestalterische Qualität.
