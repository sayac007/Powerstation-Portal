---
title: "Craftfull PS800: Reparaturtagebuch"
description: "Eine reale, offene Fehlersuche an einer ausgefallenen LiFePO4-Powerstation – vom Innenaufbau bis zur Reparierbarkeit."
date: 2026-10-24
draft: true
translationKey: "craftfull-ps800-repair-log"
---

> **Status (24.10.2026): Fehlerursache noch unbekannt.** Dieses Tagebuch hält Beobachtungen, Hypothesen und Messergebnisse getrennt. Ein gelungener Reparaturversuch wird nicht vorweggenommen.

## Warum wir dieses Gerät untersuchen

An einer realen **Craftfull Fast Charge PS800** wollen wir verstehen, wie eine Powerstation aufgebaut ist, warum der Schutz vor Feuchtigkeit beim Kauf wichtig sein kann und welche Defekte sich wirtschaftlich und technisch reparieren lassen. Insbesondere wollen wir dokumentieren, **wann Selbstreparatur sinnvoll ist – und wann nicht**.

**Gerät:** Craftfull Fast Charge PS800, Artikelnummer PR0032409; LiFePO₄-Energiespeicher (laut Unterlagen 835 Wh), Wechselrichter mit 800 W Nennleistung und 230-V-AC-Ausgang. [Herstelleranleitung](https://www.miweba.de/media/pdf/b1/9d/ba/PR0032409-Craftfull-Powerstation-Fast-Charge-PS800-Anleitung.pdf).

## Fehlerbild und bisherige Untersuchungen

| Phase | Beobachtung | Bewertung |
| --- | --- | --- |
| Vorgeschichte | Das Gerät befand sich während einer kalten, feuchten Nacht im Freien. | Feuchtebelastung möglich, aber kein nachgewiesener Wassereintritt. |
| Ausfall | Beim späteren Einschalten gab es einen auffälligen Vorfall mit Brandgeruch; anschließend reagierte die Powerstation nicht mehr. | Elektrischer Defekt wahrscheinlich; betroffene Baugruppe unbekannt. |
| Öffnung | Der obere Gehäusedeckel wurde entfernt. | Erste Sichtprüfung möglich. |
| Fotos | Mehrere Innenaufnahmen wurden erstellt. | Auf den bisherigen Bildern **keine eindeutigen** Brand-, Korrosions- oder Schmelzschäden identifiziert. |
| Messungen | Noch keine elektrischen Messungen am Gerät vorgenommen. | Keine Schaltung oder Komponente als Ursache nachgewiesen. |
| Reparatur | Bisher weder gereinigt noch Bauteile ersetzt. | Reparatur noch nicht begonnen. |

### Arbeitshypothesen (noch unbestätigt)

- Feuchtigkeit oder Kondensation könnte Kriechströme, Korrosion oder einen Kurzschluss ausgelöst haben.
- Ebenso kommen unabhängig von Feuchtigkeit Fehler in Batterieüberwachung (BMS), Stromversorgung, Steuerung oder Wechselrichter infrage.
- Ein fehlender sichtbarer Schaden **schließt keinen elektronischen Defekt aus**.

## Warum Feuchtigkeitsschutz ein Kaufkriterium ist

„Outdoor-tauglich“ bedeutet nicht automatisch „regenfest“. Für die Bewertung eines Geräts sind eine **ausdrücklich dokumentierte IP-Schutzart**, die zulässigen Betriebs- und Lagertemperaturen und die Angaben zur Nutzung bei Feuchtigkeit entscheidend. Feuchte Luft kann bei Temperaturwechseln kondensieren, auch wenn kein direkter Regen auf das Gerät fällt.

**Noch nicht geklärt:** Welche Schutzart der Hersteller für dieses konkrete PS800-Modell tatsächlich zusichert. Hier wird bewusst keine IP-Einstufung behauptet.

## Was wir im Inneren verstehen möchten

- Batteriepack und Batterie-Management-System (BMS)
- DC/DC-Wandler und Ladeelektronik
- 230-V-Wechselrichter und AC-Ausgänge
- Steuerplatine, Anzeige, Sensoren und Schutzschaltungen
- Thermische Konstruktion und Maßnahmen gegen Feuchtigkeit
- Zugänglichkeit, Austauschbarkeit und Kosten einzelner Baugruppen

Eine grafische Baugruppenkarte und beschriftete Detailfotos ergänzen wir, sobald die Teile sicher identifiziert sind.

## Sicherheit und Isolationsprüfung

Auch ohne angeschlossenes Ladegerät bleiben die LiFePO₄-Batterie und möglicherweise geladene Zwischenkreiskondensatoren gefährliche Energiequellen. Wir dokumentieren zunächst **berührungsfreie Sichtprüfungen** und ordnen Baugruppen zu; unbekannte Hochstrom- oder Hochspannungsanschlüsse werden nicht getrennt und nicht berührt.

Zur Sichtprüfung gehören beschädigte Isolierungen, Scheuerstellen, Korrosion, Ablagerungen, Verfärbungen und Isolierabstände zwischen Netz- und Kleinspannungsbereichen. Eine **Sichtprüfung ist sinnvoll, aber kein Nachweis elektrischer Sicherheit**. Eine pauschale 500-V-Isolationsmessung an der komplett verschalteten Powerstation wäre keine geeignete Standardmethode: Die zulässige Prüfung hängt von der Schaltung und den Herstellerangaben ab. Vor erneuter Nutzung der AC-Funktionen muss die relevante elektrische Sicherheit geeignet beurteilt werden.

## Stand unserer kleinen Elektro-Werkstatt

Vorhanden: Brymen BM235 mit Messzubehör; Hakko FX-888DX mit T18-Spitzen; Sn63Pb37-Lötzinn; No-Clean-Flussmittel; Entlötlitzen (1,9/3,3 mm); iFixit Pro Tech Go; ESD-Pinzetten und Bürsten; Silikonmatte; fusselfreie Tücher und Isopropanol. Außerdem Schutzbrille und weiteres Handwerkzeug. Labornetzteil, Oszilloskop und spezieller Isolations-/Sicherheitsprüfer gehören bislang **nicht** zur Ausstattung.

## Nächste dokumentierte Schritte

1. Bereits vorhandene Fotos nach Aufnahmerichtung und Baugruppe sortieren; unbekannte Bauteile nicht vorschnell benennen.
2. Gehäuse, Leitungsführung, Platinen und sichtbare Isolierungen näher fotografieren – zunächst ohne elektrische Kontakte zu lösen.
3. Mögliche Feuchte-/Hitzespuren nur als Befund kennzeichnen, wenn sie tatsächlich sichtbar sind.
4. Erst nach eindeutiger Identifikation der Schaltung und möglicher Restspannungen über geeignete Messungen entscheiden.
5. Für jede Untersuchung Datum, Messpunkt, Gerätezustand, Messgerät, Ergebnis, Interpretation und offene Fragen festhalten.

## Offene Fragen

- Wo befindet sich die defekte Baugruppe?
- Hat Feuchtigkeit zum Ausfall beigetragen?
- Welche IP-Angaben gelten für das Modell?
- Wie sind die Schutzmaßnahmen für die AC-Ausgänge umgesetzt?
- Ist eine Reparatur auf Bauteilebene möglich und wirtschaftlich?
- Wie lässt sich die Reparatur fachgerecht und sicher verifizieren?

**Bildnachweise:** Ausschließlich authentische Gerätefotos; Aufnahmen werden später ergänzt. KI-Illustrationen dienen nicht als Nachweis.
