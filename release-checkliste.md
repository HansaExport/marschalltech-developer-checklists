# Release Checkliste

Eine kompakte Checkliste für planbare und nachvollziehbare Software-Releases.

## Vor dem Release

- [ ] Alle vorgesehenen Änderungen sind gemergt.
- [ ] CI/CD-Pipeline ist erfolgreich.
- [ ] Automatisierte Tests sind grün.
- [ ] Relevante manuelle Tests wurden durchgeführt.
- [ ] Offene kritische Bugs sind geklärt.
- [ ] Migrationsschritte sind dokumentiert und getestet.
- [ ] Konfigurationsänderungen und Secrets sind vorbereitet.
- [ ] Abhängigkeiten wurden auf bekannte Probleme geprüft.
- [ ] Release Notes oder Changelog sind vorbereitet.

## Deployment vorbereiten

- [ ] Zielumgebung ist eindeutig festgelegt.
- [ ] Backup- oder Rollback-Möglichkeit ist vorhanden.
- [ ] Verantwortliche Personen wissen vom Release.
- [ ] Wartungsfenster oder erwartete Einschränkungen sind kommuniziert, falls nötig.
- [ ] Monitoring und Logs sind zugänglich.

## Nach dem Deployment

- [ ] Anwendung startet und ist erreichbar.
- [ ] Kritische Kernfunktionen wurden geprüft.
- [ ] Datenbankmigrationen liefen erfolgreich.
- [ ] Fehlerquoten und Logs zeigen keine neuen Auffälligkeiten.
- [ ] Externe Integrationen funktionieren.
- [ ] Release-Version bzw. Tag stimmt mit dem ausgelieferten Stand überein.

## Abschluss

- [ ] Release wurde dokumentiert.
- [ ] Auffälligkeiten oder manuelle Nacharbeiten wurden festgehalten.
- [ ] Bei Problemen ist klar, ob Hotfix oder Rollback erforderlich ist.
- [ ] Erkenntnisse für das nächste Release wurden notiert.

## Grundsatz

Ein Release sollte reproduzierbar sein. Je weniger Schritte nur im Kopf einzelner Personen existieren, desto robuster wird der Prozess.

Weitere Praxisinhalte: https://marschallone.de/tech/wissen/release-checkliste/
