# Dokumentation – GitHub Secrets

## 1. Ziel
Ziel dieses Projektes war es, den Umgang
mit GitHub Repository Secrets zu erlernen.

## 2. Repository
Name: Projekt-Dokumentation

## 3. Erstelltes Secret
Name: DOCS_DEPLOY_TOKEN

Verwendungszweck:
Das Secret wird als Umgebungsvariable
in einem GitHub Actions Workflow verwendet.

## 4. GitHub Actions
Es wurde ein Workflow erstellt, der bei
einem Push auf den main-Branch oder manuell
gestartet werden kann.

Der Workflow überprüft, ob das Secret
erfolgreich geladen wurde.

## 5. Testergebnis
Der Workflow wurde erfolgreich ausgeführt.

Das Secret wurde geladen, ohne den
geheimen Wert auszugeben.

## 6. Sicherheitsmaßnahmen
- Keine Secrets im Quellcode.
- Keine Ausgabe von geheimen Werten.
- Möglichst geringe Berechtigungen.
- Secrets regelmäßig erneuern.
- Secret Scanning verwenden.

## 7. Fazit
Durch die praktische Umsetzung habe ich
gelernt, wie GitHub Secrets erstellt,
gespeichert und in GitHub Actions verwendet
werden können.
