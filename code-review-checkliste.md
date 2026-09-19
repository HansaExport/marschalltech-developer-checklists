# Code Review Checkliste

Eine kompakte Checkliste für klarere, schnellere und verlässlichere Code Reviews.

## Vor dem Review

- [ ] Aufgabe und gewünschtes Verhalten sind verständlich beschrieben.
- [ ] Der Branch ist aktuell und baut lokal bzw. in CI erfolgreich.
- [ ] Tests wurden ergänzt oder angepasst, wenn sich Verhalten geändert hat.
- [ ] Der Pull Request ist klein genug, um sinnvoll geprüft werden zu können.
- [ ] Beschreibung, Screenshots oder Testhinweise sind vorhanden, wenn sie helfen.

## Beim Review

### Funktionalität

- [ ] Erfüllt der Code die fachliche Anforderung?
- [ ] Sind relevante Randfälle berücksichtigt?
- [ ] Gibt es unbeabsichtigte Seiteneffekte?

### Verständlichkeit

- [ ] Ist der Code ohne unnötige Komplexität verständlich?
- [ ] Sind Namen von Variablen, Funktionen und Klassen aussagekräftig?
- [ ] Ist die Struktur konsistent mit dem bestehenden Code?
- [ ] Gibt es unnötige Duplikate?

### Qualität

- [ ] Fehlerbehandlung ist angemessen.
- [ ] Eingaben werden dort validiert, wo es nötig ist.
- [ ] Logging enthält keine sensiblen Daten.
- [ ] Sicherheitsrelevante Auswirkungen wurden bedacht.
- [ ] Performance-Auswirkungen sind für den Anwendungsfall vertretbar.

### Tests

- [ ] Relevante Tests existieren.
- [ ] Tests prüfen Verhalten statt nur Implementierungsdetails.
- [ ] Neue oder geänderte Randfälle sind abgedeckt.

## Vor der Freigabe

- [ ] Offene Review-Kommentare sind geklärt.
- [ ] CI ist grün.
- [ ] Keine Debug-Ausgaben, temporären Dateien oder auskommentierten Altlasten enthalten.
- [ ] Dokumentation wurde angepasst, wenn sich Schnittstellen oder Nutzung geändert haben.
- [ ] Der Pull Request kann ohne zusätzliche manuelle Nacharbeit gemergt werden.

## Grundsatz

Ein gutes Code Review soll Qualität erhöhen und Wissen teilen – nicht persönliche Vorlieben durchsetzen.

Weitere Praxisinhalte: https://marschallone.de/tech/wissen/code-review-checkliste/
