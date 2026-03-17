# KISUM / Klaviertrainer – Funktionsübersicht

## Überblick

Die App ist ein Klavier-Lernsystem mit Fokus auf Notenlesen, Fortschrittsmessung, Hausaufgaben, Unterrichtsorganisation und mobilen Übungsansichten.

Sie besteht aktuell aus diesen Hauptbereichen:

- Noten lernen
- Bibliothek
- Kalender
- Verwaltung
- Unterrichtsplanung

Zusätzlich gibt es:

- SRS für Violine und Bass
- Hausaufgabenmodus
- MIDI-Eingabe
- mobile Spezialansicht für Notenlesen

## 1. Noten lernen

Der Kernmodus der App.

Funktionen:

- Einzelnes Notenlesen im Violinschlüssel oder Bassschlüssel
- Anzeige eines Notensystems mit aktueller Zielnote
- visuelle Zielmarkierung im System
- Erkennung richtiger und falscher Eingaben
- Rückmeldung über Farbsignale
- Antwortanzeige des Notennamens
- Eingabe per MIDI
- auf Mobil zusätzlich Eingabe per Buchstabenbuttons `C D E F G A H`

## 2. SRS-Modus

Die App enthält ein Spaced-Repetition-System für Noten.

Funktionen:

- eigener SRS-Modus für `Violine`
- eigener SRS-Modus für `Bass`
- automatische Auswahl des passenden Notenbereichs
- Levelsystem je Schlüssel
- Auf- und Abstufung nach Leistung
- Fortschrittsspeicherung pro Modus
- Wiedereinstieg im zuletzt sinnvollen Modus

Aktueller Sicherheitsmaßstab für „Note kennen“:

- mindestens `95%` Korrektheit
- durchschnittliche Antwortzeit maximal `0,5 Sekunden`

## 3. Hausaufgabenmodus

Hausaufgaben können aus dem Tutor-/Unterrichtsbereich erzeugt und im Trainer abgearbeitet werden.

Funktionen:

- Aufgaben mit Modus, Bereich und Zielgenauigkeit
- Hausaufgaben für Violine, Bass oder Dual
- Anzeige der aktuellen Aufgabe im Übungsmodus
- Zielgenauigkeit in Prozent
- optional freies Üben nach Zielerreichung
- Fortschrittsbewertung gegen das gesetzte Ziel

## 4. Bibliothek

Die Bibliothek zeigt den Lernstand aller Noten.

Funktionen:

- Übersicht aller verfolgten Noten
- Anzeige, ob eine Note noch unbekannt ist
- Sicherheitswert pro Note
- Zusammenfassung des aktuellen Lernstands
- geschätzter Fortschritt bis zum Ziel
- Stärke-/Sicherheitsübersicht

## 5. Kalender

Der Kalender zeigt Unterrichtstermine.

Funktionen:

- Schüleransicht für eigene Termine
- Tutoransicht für Unterrichtsplanung
- Monatsnavigation
- Anzeige aktueller und kommender Termine
- Kalender-Abo / Kalender-Feed

## 6. Unterrichtsplanung

Bereich für Tutor:innen zur Planung von Unterricht.

Funktionen:

- Termine anlegen
- Termine bearbeiten
- Schüler auswählen
- Dauer und Zeitfenster verwalten
- Titel und Zusatzfelder pflegen
- Hausaufgabe direkt beim Termin anlegen
- Bereich und Zielgenauigkeit für Hausaufgaben definieren
- Abrechnungs-/Kartenbezug berücksichtigen

## 7. Verwaltung

Bereich zur Nutzer- und Fortschrittsverwaltung.

Funktionen:

- Userliste
- Rollenverwaltung
- Sperren/Entsperren
- Fortschrittsansicht je User
- Genauigkeit und Versuchsanzahl je Schlüssel
- Aktivitäts- und Analyseansichten
- Hausaufgabenstatus pro Schüler

## 8. Grundlagen-Modul

Ein eigener Lernbereich für den Aufbau einer inneren Tastaturkarte.

Funktionen:

- strukturierte Kapitel
- Rechte Hand / Linke Hand
- weiße und chromatische Karten
- Grundlagen- und Orientierungstraining
- Fortschrittsanzeige und Kapitelsteuerung

Hinweis:

- dieses Modul ist in der mobilen Ansicht aktuell nicht verfügbar

## 9. Taktgefühl

Ein Rhythmus-/Timing-Modul.

Funktionen:

- BPM-Anzeige
- Metronom mit Klicksound
- BPM per Klick änderbar
- 4er-Klicklogik
- Timing-Bewertung in Prozent
- Textfeedback: `Schneller`, `Langsamer`, `Genau richtig`

Hinweis:

- dieses Modul ist in der mobilen Ansicht aktuell nicht verfügbar

## 10. MIDI

Die App unterstützt MIDI-Keyboards.

Funktionen:

- Verbindung zu MIDI-Eingängen
- visuelle Statusanzeige
- Noteneingabe per angeschlossenem Instrument
- Weitergabe eingehender MIDI-Nachrichten an den Trainer

Hinweis:

- die MIDI-Statusanzeige ist in der mobilen Ansicht aktuell ausgeblendet

## 11. Fortschritt und Statistik

Die App speichert und bewertet Lernleistung.

Funktionen:

- Anzahl der Versuche pro Note
- Anzahl korrekter Antworten
- Streaks
- durchschnittliche Antwortzeit
- schnellste und langsamste Antwort
- Verwechslungsstatistik
- letzte Sichtung / letztes korrektes Treffen

## 12. Mobile Ansicht

Für kleinere Bildschirme gibt es eine angepasste Oberfläche.

Aktuell:

- angepasste Kachelansicht auf der Startseite
- reduzierte obere Buttonleiste
- mobile Auswahlbuttons für Notennamen
- Buchstabenanzeige unter dem Notensystem
- `Taktgefühl` und `Lerne die Grundlagen` mobil ausgeblendet
- `Schere`, `Klaviatur`, `Info` und `Dualmode` mobil ausgeblendet

## 13. Authentifizierung und Speicherung

Die App nutzt Supabase.

Funktionen:

- Anmeldung per E-Mail und Passwort
- Session-Verwaltung
- Speicherung von Fortschritt und Notenstatistiken
- Speicherung von SRS-Zuständen
- Speicherung von Unterrichts-, Kalender- und Verwaltungsdaten

## 14. Habits-Anbindung

Die App kann Übungsstarts automatisch in die Habits-App protokollieren.

Funktionen:

- automatisches Logging eines Übungsstarts
- Nutzung einer verknüpften Habit-ID
- Schreiben in die passende Tagesstruktur der Habits-App

## 15. Entwickler- und Testhilfen

Vorhandene Hilfen im Code:

- SRS-Status per Konsole abrufbar
- manuelles Hoch-/Runterstufen von SRS-Leveln
- simulierte Schüler-/Tutor-Kontexte
- simulierte Hausaufgaben
- simulierte MIDI-Eingaben

## Kurzfazit

Die App ist aktuell ein kombiniertes System aus:

- Notenlerntrainer
- SRS-Lernlogik
- Unterrichts- und Hausaufgabenverwaltung
- Kalender
- Fortschrittsanalyse
- mobiler Übungsoberfläche

