# Powerstation-Portal

Statische, mehrsprachige Seite mit Hugo (extended, ab Version 0.128) und Pagefind für die Suche.

## Entwicklung (offline)

    hugo server            # http://localhost:1313/de/

Die Suche funktioniert im Entwicklungsserver nicht, weil Pagefind seinen Index erst aus der fertigen Seite erzeugt. Mit Suche:

    hugo --minify
    npx -y pagefind --site public --serve     # oder: python -m pagefind --site public --serve

## Neuer Test

    hugo new content de/tests/modell-x.md --kind test

Übersetzungen werden über `translationKey` im Kopf der Datei verknüpft (gleicher Schlüssel in allen Sprachen).

## Repository

    git init && git add . && git commit -m "Grundgerüst"
    gh repo create powerstation-portal --private --source=. --push

## Vor der Veröffentlichung

- `baseURL` in `hugo.toml` setzen
- Impressum (§ 5 DDG) und Datenschutzerklärung ausfüllen
- Sicherheitshinweise im Bereich Reparatur ausformulieren
- Übersetzungen von einer Person prüfen lassen, die die Sprache beherrscht
