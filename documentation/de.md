<!-- ELUCENIA technical documentation · controle-da-asma-gina · de · no clinical/professional/rights approval -->

# Kontrolle der Asthmasymptome (GINA)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/controle-da-asma-gina)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Tagessymptome mehr als 2 Mal pro Woche

`diurno`

### Nächtliches Erwachen aufgrund von Asthma

`noturno`

### Bedarfsmedikation (SABA) häufiger als 2-mal pro Woche

`alivio`

### Einschränkung von Aktivitäten durch Asthma

`limit`

## Fassung der Methode

GINA-Strategie 2021: Symptome über 4 Wochen, 4 Fragen; SABA-Bedarf; 0/1–2/3–4

## Dokumentierte Formel

Für die letzten 4 Wochen zählen: Tagessymptome \> 2×/Woche; nächtliches Erwachen durch Asthma; SABA-Bedarf \> 2×/Woche (nicht vor Sport); Aktivitätseinschränkung.

0 = gut kontrolliert · 1–2 = teilweise kontrolliert · 3–4 = unkontrolliert.

## Grenzen und Population

Die hier berechnete GINA-Bewertung 2021 erfasst die Symptomkontrolle der letzten vier Wochen bei Erwachsenen und Kindern über 5 Jahren; die Frage zur Bedarfsmedikation bezieht sich auf SABA. Diese Zählung beurteilt nicht das gesamte zukünftige Exazerbationsrisiko, Lungenfunktion, Begleiterkrankungen, Inhalationstechnik oder Therapietreue. Symptomkontrolle und Asthmaschwere sind nicht gleichzusetzen. Die Materialanpassung unterliegt weiterhin den Rechtebedingungen des Inhabers.

## Referenzen

- [Reddel HK et al. Global Initiative for Asthma Strategy 2021: executive summary and rationale for key changes. Eur Respir J, 2022.](https://doi.org/10.1183/13993003.02730-2021)

- [Global Initiative for Asthma (GINA). Global Strategy for Asthma Management and Prevention (relatório anual).](https://ginasthma.org/reports/)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Gut kontrolliertes Asthma

Behandlung beibehalten; erwägen, die Stufe zu reduzieren, wenn seit 3 Monaten kontrolliert.


### 2

Teilweise kontrolliertes Asthma

Inhalationstechnik, Adhärenz, Komorbiditäten und Risikofaktoren vor der Eskalation überprüfen.


### 3

Nicht kontrolliertes Asthma

Technik, Adhärenz und Auslöser überprüfen; eine Eskalation der Behandlung erwägen.

