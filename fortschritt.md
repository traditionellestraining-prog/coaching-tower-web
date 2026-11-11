# Wu-Vita Website – Fortschritt

## Projektstruktur

| Datei | Beschreibung |
|-------|-------------|
| `wu-vita-website.html` | Startseite (Hero, Philosophie, 4 Ebenen, Coach-Vorschau, Qualifikationen, Methode, Kontakt) |
| `was-ist-wu-vita.html` | Das Konzept: Problem-Sektion + 4 Wirkungsebenen (außen → innen) |
| `coach.html` | Der Coach: Slider mit 3 Slides (Geschichte, Fitness-Philosophie, Trainingsphilosophie) |
| `seminare.html` | Seminare & Preise: Online-Kurse, Coaching-Pakete, Einzelbuchungen, Live-Seminar |
| `impressum.html` | Impressum nach § 5 TMG |
| `datenschutz.html` | Datenschutzerklärung nach DSGVO |
| `blog.html` | Blog-Übersichtsseite (3 Kategorien, aktuell „Artikel in Vorbereitung") |

---

## Erledigte Aufgaben

### Navigation & Struktur
- [x] Multi-Page-Struktur: jeder Reiter öffnet eine eigene Seite
- [x] Einheitlicher Header auf allen Seiten: Brand links · Nav Mitte · Sprache rechts
- [x] Reiter umbenannt: „Seminare & Events" → **„Seminare & Preise"** (alle Seiten + Hero-Titel)
- [x] Footer auf allen Seiten: Links zu Impressum & Datenschutz ergänzt

### Branding
- [x] Logo/Brand-Name „Wu-Vita" im Goldton der Marke
- [x] Einheitliches Farbschema (Dunkelgrün, Gold, Creme) auf allen Seiten
- [x] Echtes Logo-Bild (`wu-vita-logo.png`, zugeschnitten aus der Vorlage) ersetzt den Text-/Platzhalter-Schriftzug oben links im Header auf allen 7 Seiten
- [x] Schwarzer Hintergrund im Logo entfernt: transparent + Text in Marken-Gold eingefärbt, passt sich jedem Seitenhintergrund an

### Sprache (DE / EN)
- [x] Sprachumschalter auf allen Seiten, Auswahl im localStorage gespeichert
- [x] Alle Seiten vollständig in DE und EN übersetzt
- [x] EN→DE Rückübersetzung funktioniert auf allen Sektionen
- [x] Root-Cause-Bug behoben: typografische Anführungszeichen in `data-i18n`-Attributen

### Startseite (`wu-vita-website.html`)
- [x] Hero, Philosophie, 4 Ebenen, Fusion-Strip vollständig
- [x] Qualifikationsprofil: 5 Kacheln (inkl. Ernährung & Gesundheit, Schröpfen)
- [x] Methode: 5-Schritte-Prozess (Anamnese → Assessment → Plan → Betreuung → Zeitrahmen)
- [x] Assessment-Text: Kraft, Beweglichkeit, Herz-Kreislauf, Belastbarkeit
- [x] Zielgruppen: Wettkämpfer, Athleten, Langlebigkeit
- [x] Kontaktformular: mailto an `traditionellestraining@gmail.com`, Felder vorausgefüllt
- [x] FAQ-Sektion auf der Landing Page (vor dem Kontaktformular, nach den Zielgruppen): 4 Fragen als Akkordeon (aufklappbar), inkl. FAQPage-Schema (JSON-LD) fürs SEO, DE/EN übersetzt
- [x] Footer: Impressum & Datenschutz verlinkt

### Coach-Seite (`coach.html`)
- [x] Slider mit 3 Slides + Tastaturnavigation
- [x] Qualifikationsliste aktualisiert (Ernährungsberater-Lizenz, Qigong zertifiziert)
- [x] Footer: Impressum & Datenschutz verlinkt

### Was ist Wu-Vita? (`was-ist-wu-vita.html`)
- [x] Problem-Sektion: zweispaltig mit 3 goldenen Callout-Boxen
- [x] 4 Wirkungsebenen alternierend links/rechts
- [x] Pfeil-Balken: Außen · Kraft → Bewegung → Nervensystem → Innen · Energie
- [x] Footer: Impressum & Datenschutz verlinkt

### Seminare & Preise (`seminare.html`)
- [x] **Kachel 1: Basis Wissen Qi Gong** – 60 Min. · Digitales Meeting · 34,99 €
  - 6 Themen: Was ist Qi Gong?, Grundprinzipien, Stile & Formen, Zhang Zhuang, Wirkung & Studienlage, Moderne Anwendung
- [x] **Kachel 2: Nutrition Basic** – 60 Min. · Digitales Meeting · 34,99 €
  - 6 Themen: Energie & Kalorien, Makronährstoffe, Hydratation, Mikronährstoffe, Praxisteil, Feedback
- [x] **Kachel 3: Live-Seminar buchen** – Buchungsformular mit mailto-Fallback
- [x] **Coaching-Preise** (3 Kacheln): 始 2 Monate · 变 6 Monate (Empfohlen) · 道 12 Monate
- [x] **Einzelbuchungen** (4 Kacheln): 力 Personal Training · 養 Ernährungsberatung · 眼 Videoanalyse · 氣 Blutbildanalyse
- [x] Footer: Impressum & Datenschutz verlinkt

### Rechtliches
- [x] **Impressum** (`impressum.html`) – Dominik Frantzen · Robertstr. 18, 51105 Köln · Tel. 0176 25956058 · Ganzheitlicher Coach (Sport, Ernährung)
- [x] **Datenschutzerklärung** (`datenschutz.html`) – DSGVO-konform: Kontaktformular, localStorage, Google Fonts, Betroffenenrechte, Aufsichtsbehörde NRW

### Technisches
- [x] Reveal-Animation: CSS `fadeUp` (zuverlässiger als IntersectionObserver)
- [x] Git-Repository: [traditionellestraining-prog/coaching-tower-web](https://github.com/traditionellestraining-prog/coaching-tower-web)
- [x] Erster Commit & Push

---

## Offen / Nächste Schritte

### Inhalt (Infos von dir nötig)
- [x] Coaching-Pakete: Preise eingetragen – 2 Monate: 550 €/Monat · 6 Monate: 350 €/Monat · 12 Monate: 250 €/Monat
- [x] Einzelbuchungen: Preise eingetragen – Personal Training 60 €/120 € (Online/Live) · Ernährungsberatung 75 € · Videoanalyse 50 € · Blutbildanalyse 50 €
- [ ] Live-Seminar: echte Termine eintragen
- [x] Coach-Foto eingepflegt: `dominik-frantzen-coach.jpg` ersetzt Platzhalter in allen 3 Slides auf `coach.html` sowie in der „Über mich"-Sektion auf `wu-vita-website.html`
- [ ] Weitere eigene Fotos einpflegen (restliche Platzhalter auf anderen Seiten ersetzen)

### Technik
- [x] Newsletter-Anmeldung entfernt (Seminare-Seite) – wird durch Blog ersetzt
- [x] Blog-Grundgerüst: `blog.html` (Übersicht, 3 Kategorien: Training/Ernährung/Kampfkunst & Qigong) + „Blog"-Reiter in Header & Footer auf allen Seiten ergänzt (DE/EN)
- [ ] Erste echte Blogartikel schreiben (z.B. mit der `wu-vita-blog-voice`-Skill) und als eigene HTML-Seiten verlinken
- [ ] Impressum: Steuernummer/USt-IdNr. nachtragen sobald Gewerbe angemeldet

### Launch
- [ ] SEO: Meta-Descriptions und OG-Tags für alle Seiten ergänzen
- [ ] Domain & Hosting einrichten
- [ ] Git-Commits: aktuelle Änderungen pushen
