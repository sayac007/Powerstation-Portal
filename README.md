# Powerstation-Portal

Statische, mehrsprachige Seite mit Hugo (extended, ab Version 0.128) und Pagefind für die Suche.

**Projektstatus:** Die Veröffentlichung ist in Vorbereitung. Offene Punkte stehen in der [Checkliste](#vor-der-veröffentlichung).

## Produktionsbuild mit Suche lokal prüfen

Benötigt werden Hugo Extended und entweder Node.js mit `npx` oder eine Python-Umgebung mit installiertem Pagefind. Im Repository-Ordner ausführen:

```sh
hugo --minify
npx -y pagefind --site public --serve
```

Mit installiertem Python-Paket kannst du den zweiten Befehl durch `python -m pagefind --site public --serve` ersetzen. Öffne die angezeigte lokale Adresse, wechsle in eine Sprachversion und suche nach dem Titel eines vorhandenen Tests.

Für die schnelle Vorschau beim Schreiben startet `hugo server` die Entwicklungsseite unter `http://localhost:1313/de/`. Pagefind benötigt für die Suche den fertigen Build.

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
