# Changelog

Alle wichtigen Aenderungen an diesem Projekt werden hier dokumentiert.

## [2026-08-12] - Rechtsformzusatz "i.G." aus dem Vereinsnamen entfernt

### Changed
- Vereinsname projektweit von "Friedensfedern Mettmann e.V.i.G." auf "Friedensfedern Mettmann e.V." geaendert (55 Vorkommen in 10 Dateien: index, ueber-uns, aktuelles, kontakt, impressum, datenschutz, danke, header-content.js, footer-content.js, CLAUDE.md)
- Vier uneinheitliche Schreibvarianten (e.V.i.G / e.V.i.G. / e.V. i.G / e.V. i.G.) dabei auf die einheitliche Form "e.V." normalisiert
- Hinweis zur Spendenquittung auf kontakt.html umformuliert: Der Verweis auf den Zusatz "i.G" als Hinderungsgrund entfaellt, Spendenquittungen werden nun angeboten
- .gitignore ergaenzt um .claude/settings.local.json (maschinenspezifische Werkzeug-Berechtigungen gehoeren nicht ins Repo)
- Logo images/header.jpeg durch bearbeitete Fassung ohne den Zusatz "i.G." ersetzt (Schriftzug nun "Mettmann e.V.", Abmessungen 1600x626 unveraendert)

### Offen (nicht per Code aenderbar)
- downloads/mitgliedsantrag.pdf enthaelt 9x "Friedensfedern Mettmann e. V. i. G." und muss neu erstellt werden

## [2026-02-23] - SEO-Tags umfassend optimiert

### Added
- Twitter/X Card Meta-Tags auf allen oeffentlichen Seiten (summary_large_image fuer Hauptseiten, summary fuer Rechtstexte)
- Geo-Meta-Tags (geo.region, geo.placename, geo.position, ICBM) fuer Local SEO auf allen Seiten
- meta robots (index, follow) auf allen oeffentlichen Seiten
- og:image:width und og:image:height fuer schnellere Social-Media-Previews
- JSON-LD strukturierte Daten fuer Unterseiten: AboutPage (ueber-uns), CollectionPage (aktuelles), ContactPage (kontakt)
- Fehlende og:description und og:image auf Impressum und Datenschutz ergaenzt
- Facebook-URL in sameAs-Array der JSON-LD-Daten auf index.html

### Changed
- Sitemap lastmod-Daten auf 2026-02-23 aktualisiert
