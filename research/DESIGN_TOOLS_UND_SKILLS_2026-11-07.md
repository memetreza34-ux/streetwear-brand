# Design-Werkzeuge für die NERVALO-Testphase

**Recherchiert:** 2026-11-07. Fokus: abstrakte, hochwertige und drucktaugliche Streetwear-Motive ohne neue Abonnements.

## Top 3

### 1. SVG Pattern Generator – höchste Priorität für eigene Muster
- GitHub: https://github.com/ratpi-studio/svg-pattern-generator
- 12 Musterfamilien: Topographie, Rosette, Mandala, Fraktal, Tessellation, Grid, Radial, Symmetrie, Spirograph, Guilloche, Woven, Lattice.
- Exportiert SVG- und PNG-Dateien, Parametereinstellungen und reproduzierbare Seeds.
- Lizenz im Repo: MIT. Die **Softwarelizenz** ersetzt keine Prüfung konkreter verwendeter Fremdgrafiken, Marken oder übernommenen Vorlagen.
- Für uns: elegante geometrische Rückengrafiken und kontrollierbare Variation. Nachteil: eher Designbaukasten; für künstlerischen Feinschliff weitere Gestaltung nötig.

### 2. Pattern Monster – sofort im Browser testen
- GitHub: https://github.com/catchspider2002/svelte-svg-patterns
- Website: https://pattern.monster/
- 320+ SVG-Muster, Farben, Strichstärke und Winkel einstellbar; Export als SVG oder PNG.
- Lizenz im Repo: MIT.
- Für uns: Ideensuche, Ornamente und textile Muster; nicht 1:1 als angeblich exklusives Luxus-Markenmotiv verkaufen.

### 3. Graphite – feiner visueller Aufbau
- GitHub: https://github.com/GraphiteEditor/Graphite
- App: https://editor.graphite.art/
- Kostenloser Open-Source-Vektor-/Rastereditor mit nicht-destruktivem und prozeduralem Workflow.
- Status: Alpha. Für uns **optional**, nicht zwingend notwendig.
- Für uns: Muster kombinieren, reduzieren, Perspektiven/Kanten überarbeiten, Druckgrafik als SVG/PNG vorbereiten.

## Optionaler externer Skill als Inspiration
- `canvas-design` aus https://github.com/anthropics/skills/tree/main/skills/canvas-design
- Enthält Anweisungen für strukturiertes, professionelles Grafikdesign, ist aber **kein automatischer Modedesigner** und nicht als ChatGPT-Plugin installiert.
- Nicht blind installieren oder fremde Skripte ausführen; zuerst Quelle und Nutzungsbedingungen prüfen.

## Von uns angelegter Projektskill
- [NERVALO Streetwear Design](../.agents/skills/nervalo-streetwear-design/SKILL.md)
- Ziel: wiederholbare Art Direction, getrennte Ausgaben (druckfähiges Motiv / T-Shirt-Mockup), Druck-Check und bewusstes kreatives Feedback.
- Er ist eine **Projektanweisung**, kein automatisch gestarteter KI-Agent und keine „Geschmacksmaschine“.

## Spreadshop-Technik
Offizielle Anforderungen für Pixeldateien: https://www.spreadshop.de/helpcenter/designs-erstellen/pixelgrafiken-optimieren/

PNG empfohlen, freigestellt mit **echter Transparenz**, max. **10 MB**, möglichst **>= 4000 px längste Seite**. Für jeden Export tatsächlich Alphakanal, Maße, Dateigröße, Kanten und auf Schwarz ausreichenden Kontrast überprüfen.

## Praktischer Kurzablauf
1. Bildidee: "ruhiges geometrisches Luxus-Motiv, kein Tier, keine Figur, kein Text".
2. Zwei bis drei **unterschiedliche** Musterfamilien generieren.
3. Beste Form verfeinern, nicht ungeprüft übernehmen.
4. **Nur Motiv** exportieren und technische Anforderungen prüfen.
5. **Separates T-Shirt-Mockup** erzeugen, visuell bewerten.
6. Als Entwurf in Spreadshop testen; keine Veröffentlichung ohne rechtliche Vorbereitung und Zustimmung.
