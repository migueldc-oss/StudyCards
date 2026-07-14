# StudyCards Benutzerhandbuch

**Version 1.1**  
**Plattformen:** iOS 18+ • macOS 16+

---

## Inhaltsverzeichnis

1. [Willkommen](#1-willkommen)
2. [Erste Schritte](#2-erste-schritte)
3. [Organisation und Sortierung](#3-organisation-und-sortierung)
4. [Studienmodus](#4-studienmodus)
5. [Importieren und Exportieren](#5-importieren-und-exportieren)
6. [Flashcards teilen](#6-flashcards-teilen)
7. [Einstellungen](#7-einstellungen)
8. [Tipps](#8-tipps)

---

## 1. Willkommen

Willkommen bei **StudyCards** — einer leistungsstarken und eleganten Karteikarten-App für iOS und macOS. Erstelle, verwalte und studiere deine Karteikarten mit Unterstützung für LaTeX-Formeln, Bilder und nahtlose Import-/Export-Funktionen.

<img src="screenshots/ios/main.png" alt="StudyCards — iOS" width="500">
<img src="screenshots/macos/main.png" alt="StudyCards — macOS" width="500">

**Hauptfunktionen:**

- **Karteikarten-Gruppen:** Organisiere deine Karten nach Thema oder Fach.
- **Vollständige Karteikarten:** Jede Karte hat eine Vorder- und Rückseite mit Unterstützung für Text, LaTeX-Formeln und Bilder.
- **Manuelle Reihenfolge:** Ziehe Karteikarten, um ihre Reihenfolge innerhalb einer Gruppe zu ändern.
- **Gruppenbearbeitung:** Bearbeite oder lösche Gruppen über das Kontextmenü (langer Druck).
- **Sortierung und Suche:** Sortiere und suche Gruppen nach Name, Datum oder Anzahl der Karteikarten.
- **Studienmodus:** Bewerte dein Wissen mit Leicht/Gewusst/Nicht gewusst.
- **Import und Export:** Übertrage deine Karten über CSV- oder JSON-Dateien (mit eingebetteten base64-Bildern).
- **Teilen:** Sende deine Karteikarten per E-Mail, WhatsApp, AirDrop und mehr.
- **Anpassbare Einstellungen:** Erscheinungsbild, Sprache und Studienreihenfolge.
- **Adaptives Design:** Passt sich automatisch an iPhone, iPad und Mac an.

### Voraussetzungen

- iOS 18.0 oder neuer / macOS 16.0 oder neuer.
- Internetverbindung nur für die Darstellung von LaTeX-Formeln erforderlich (MathJax).

---

## 2. Erste Schritte

### 2.1 Eine Gruppe erstellen

Gruppen helfen dir, deine Karteikarten nach Thema, Fach oder Kategorie zu organisieren.

**Schritte:**

1. Öffne StudyCards.
2. Tippe auf die Schaltfläche **+** auf dem Hauptbildschirm.
3. Gib einen Namen für deine Gruppe ein (z. B. „Spanischer Wortschatz", „Mathematik-Formeln").
4. Optional: Füge eine Beschreibung hinzu, um den Inhalt der Gruppe zu kennzeichnen.
5. Tippe auf **Speichern**, um zu bestätigen.

<img src="screenshots/ios/create_group.png" alt="Gruppe erstellen" width="500">

<img src="screenshots/macos/create_group.png" alt="Gruppe erstellen – macOS" width="500">

**Tipps zur Organisation von Gruppen:**

- Verwende aussagekräftige Namen zur einfachen Identifikation.
- Erwäge, Gruppen nach Fach, Kapitel oder Schwierigkeitsgrad zu erstellen.
- Du kannst so viele Gruppen erstellen, wie du benötigst.

### 2.2 Eine Gruppe bearbeiten oder löschen

Du kannst eine Gruppe direkt aus der Liste bearbeiten oder löschen.

**Auf iOS:**

1. Halte auf den Gruppennamen, bis das Kontextmenü erscheint.
2. Wähle **Bearbeiten**, um Name oder Beschreibung zu ändern.
3. Wähle **Löschen**, um die Gruppe und alle ihre Karteikarten zu entfernen.

**Auf macOS:**

1. Klicke mit der rechten Maustaste auf den Gruppennamen.
2. Wähle **Bearbeiten** oder **Löschen**.

> **Warnung:** Das Löschen einer Gruppe entfernt dauerhaft alle ihre Karteikarten. Stelle sicher, dass du sie vorher exportierst, wenn du ein Backup benötigst.

### 2.3 Eine Karteikarte erstellen

Sobald du innerhalb einer Gruppe bist, kannst du mit dem Hinzufügen von Karteikarten beginnen.

**Schritte:**

1. Öffne eine Gruppe, indem du darauf tippst.
2. Tippe auf die Schaltfläche **+**.
3. Gib den **Vorderseiten-Text** ein (die Frage oder den Impuls).
4. Gib den **Rückseiten-Text** ein (die Antwort oder Erklärung).
5. Optional: Füge ein **Bild** hinzu, indem du auf **Bild auswählen** tippst.
6. Optional: Füge eine **LaTeX-Formel** hinzu, indem du `$...$` (inline) oder `$$...$$` (Block) verwendest.
7. Tippe auf **Speichern**.

<img src="screenshots/ios/create_card.png" alt="Karteikarte erstellen" width="500">

<img src="screenshots/macos/create_card.png" alt="Karteikarte erstellen – macOS" width="500">

### 2.4 LaTeX-Formeln hinzufügen

StudyCards unterstützt die Darstellung von LaTeX über MathJax für mathematische und wissenschaftliche Notation.

| Typ | Syntax | Beispiel |
|------|--------|---------|
| Inline | `$f(x) = x^2$` | Die Funktion ist $f(x) = x^2$ |
| Block | `$$\int_0^1 x^2 \, dx$$` | Formel in einer separaten Zeile |

**LaTeX-Beispiele:**

- **Quadratische Gleichung:** `$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$`
- **Satz des Pythagoras:** `$a^2 + b^2 = c^2$`
- **Bestimmtes Integral:** `$$\int_a^b f(x)\,dx = F(b) - F(a)$$`

> **Hinweis:** Formeln werden beim Speichern der Karte und während der Studiensitzungen automatisch dargestellt.

### 2.5 Bilder hinzufügen

Du kannst deinen Karteikarten Bilder für visuelles Lernen hinzufügen.

**Schritte:**

1. Tippe beim Erstellen oder Bearbeiten einer Karteikarte auf **Bild auswählen**.
2. Wähle, ob du ein neues Foto aufnehmen oder ein Foto aus deiner Bibliothek auswählen möchtest.
3. Das Bild wird der Karteikarte hinzugefügt.

<img src="screenshots/ios/add_image.png" alt="Bild hinzufügen" width="500">

<img src="screenshots/macos/add_image.png" alt="Bild hinzufügen – macOS" width="500">

> **Hinweis:** Bilder werden automatisch auf eine maximale Größe von 1024 Pixel reduziert, um den Speicher zu optimieren. Beim Exportieren als JSON werden Bilder im base64-Format eingebettet.

### 2.6 Eine Karteikarte löschen

Du kannst eine Karteikarte löschen, indem du sie nach links wischt.

**Schritte:**

1. Wische in der Karteikarten-Liste die Karte nach links.
2. Es erscheint eine rote Schaltfläche **Löschen**.
3. Tippe auf **Löschen**, um zu bestätigen.

<img src="screenshots/ios/swipe_delete.png" alt="Wischen zum Löschen" width="500">

<img src="screenshots/macos/swipe_delete.png" alt="Wischen zum Löschen – macOS" width="500">

> **Warnung:** Das Löschen ist dauerhaft. Stelle sicher, dass du deine Karten vor dem Löschen exportierst, falls du kein Backup hast.

---

## 3. Organisation und Sortierung

### 3.1 Karteikarten manuell sortieren

Du kannst die Reihenfolge der Karteikarten innerhalb einer Gruppe durch Ziehen ändern.

**Auf iOS:**

1. Öffne die Gruppe mit den Karteikarten, deren Reihenfolge du ändern möchtest.
2. Tippe auf **Bearbeiten** in der Symbolleiste (oben links).
3. Ziehgriffe ⟟ erscheinen neben jeder Karteikarte.
4. Ziehe die Karteikarte an die gewünschte Position.
5. Tippe auf **Fertig**, um die neue Reihenfolge zu speichern.

**Auf macOS:**

1. Öffne die Gruppe mit den Karteikarten, deren Reihenfolge du ändern möchtest.
2. Tippe auf die Schaltfläche **Sortieren** (↕-Symbol) in der Symbolleiste.
3. Ziehe die Karteikarte an die gewünschte Position.
4. Tippe auf **Fertig**, um den Sortiermodus zu beenden.

> **Hinweis:** Die manuelle Reihenfolge wird beim Exportieren und Importieren von Karteikarten beibehalten.

### 3.2 Gruppen sortieren

Du kannst die Gruppenliste nach verschiedenen Kriterien sortieren.

**Schritte:**

1. Tippe auf die Sortierschaltfläche (↕-Symbol) in der Symbolleiste.
2. Eines der Sortierkriterien auswählen:

| Kriterium | Beschreibung |
|-----------|-------------|
| **Name (A-Z)** | Aufsteigende alphabetische Reihenfolge |
| **Name (Z-A)** | Absteigende alphabetische Reihenfolge |
| **Neueste** | Zuerst die neuesten Gruppen |
| **Älteste** | Zuerst die ältesten Gruppen |
| **Anzahl der Karteikarten** | Gruppen mit den meisten Karteikarten zuerst |

> **Hinweis:** Die Sortierung gilt sowohl für den Bereich **Gruppen** als auch für den Bereich **Studie**.

### 3.3 Nach Gruppen suchen

**Auf iOS:**

1. Ziehe die Gruppenliste nach unten, um die Suchleiste anzuzeigen.
2. Gib den Namen der gesuchten Gruppe ein.

**Auf macOS:**

1. Verwende die Suchleiste oben in der Seitenleiste.
2. Gib den Namen der gesuchten Gruppe ein.

---

## 4. Studienmodus

Der Studienmodus ist das Herzstück von StudyCards. Er ermöglicht es dir, deine Karteikarten interaktiv zu überprüfen und dein Wissensniveau einzuschätzen.

### 4.1 Eine Studiensitzung starten

**Schritte:**

1. Wähle den Tab **Studie** in der Navigationsleiste.
2. Suche und wähle die Gruppe aus, die du studieren möchtest.
3. Die erste Karteikarte wird auf dem Bildschirm angezeigt.

<img src="screenshots/ios/start_study.png" alt="Studie starten" width="500">

<img src="screenshots/macos/start_study.png" alt="Studie starten – macOS" width="500">

### 4.2 Zwischen Karten navigieren

Während einer Studiensitzung:

1. Lies die **Vorderseite** der Karte (die Frage).
2. Denke über die Antwort nach.
3. Tippe auf **Antwort zeigen** oder tippe auf die Karte, um die **Rückseite** (die Antwort) aufzudecken.
4. Bewerte dein Wissen mit einer von drei Schaltflächen:

| Schaltfläche | Bedeutung | Beschreibung |
|--------|---------|-------------|
| 🟢 **Leicht** | Du wusstest es gut | Die Karte wird als gemeistert markiert. Sie erscheint seltener. |
| 🟡 **Gewusst** | Du hast dich mit Mühe erinnert | Die Karte erscheint bald wieder zur Verstärkung. |
| 🔴 **Nicht gewusst** | Du wusstest es nicht | Die Karte wird mehrmals wiederholt, bis du sie gelernt hast. |

**Tastaturkürzel (macOS):**

| Taste | Aktion |
|-----|--------|
| **Leertaste** | Karte umdrehen |
| **1** | Als Leicht bewerten |
| **2** | Als Gewusst bewerten |
| **3** | Als Nicht gewusst bewerten |

<img src="screenshots/ios/study_session.png" alt="Studienmodus" width="500">

<img src="screenshots/macos/study_session.png" alt="Studienmodus – macOS" width="500">

### 4.3 Eine Studiensitzung abschließen

Wenn du alle Karten der Gruppe überprüft hast:

1. Erscheint eine Zusammenfassung des Abschlusses.
2. Du siehst, wie viele Karten du als *Leicht*, *Gewusst* und *Nicht gewusst* bewertet hast.
3. Tippe auf **Erneut studieren**, um zu wiederholen, oder auf **Zurück zu den Gruppen**, um zu beenden.

<img src="screenshots/ios/study_summary.png" alt="Studienzusammenfassung" width="500">

<img src="screenshots/macos/study_summary.png" alt="Studienzusammenfassung – macOS" width="500">

---

## 5. Importieren und Exportieren

StudyCards ermöglicht es dir, Karteikarten zwischen Geräten zu übertragen oder Backups mit CSV- und JSON-Dateien zu erstellen.

### 5.1 Karteikarten exportieren

**Schritte:**

1. Öffne die Gruppe, die du exportieren möchtest.
2. Tippe auf das Aktionsmenü und wähle **Exportieren**.
3. Wähle das Exportformat:
   - **CSV:** Tabellenkalkulationsformat. Ideal zum Öffnen in Excel, Numbers usw. Enthält keine Bilder.
   - **JSON:** Vollständiges Format. Enthält Text, LaTeX-Formeln und base64-Bilder.
4. Wähle, wo die Datei gespeichert werden soll (Dateien, iCloud Drive usw.).

<img src="screenshots/ios/export.png" alt="Exportieren" width="500">

<img src="screenshots/macos/export.png" alt="Exportieren – macOS" width="500">

### 5.2 JSON-Dateistruktur

Die exportierte JSON-Datei hat die folgende Struktur:

```json
{
  "groupName": "Spanischer Wortschatz",
  "version": "1.0",
  "createdAt": "2026-07-12T10:30:00Z",
  "cards": [
    {
      "front": "Was ist die Hauptstadt von Frankreich?",
      "back": "Paris.",
      "frontLatex": null,
      "backLatex": null,
      "difficulty": 0,
      "frontImage": "base64_kodierter_string...",
      "backImage": null
    }
  ]
}
```

### 5.3 CSV-Dateistruktur

Die CSV-Datei verwendet die folgenden Spalten:

```csv
front,back,frontLatex,backLatex,difficulty,frontImage,backImage
"Was ist die Hauptstadt von Frankreich?","Paris.","","","0","",""
```

> **Hinweis:** Bilder im CSV-Format werden als base64-Zeichenfolgen in den Spalten `frontImage` und `backImage` exportiert.

### 5.4 Karteikarten importieren

**Schritte:**

1. Tippe in der Karteikarten-Liste einer Gruppe auf das Aktionsmenü und wähle **Importieren**.
2. Wähle eine CSV- oder JSON-Datei von deinem Gerät aus.
3. StudyCards importiert die Karteikarten in die aktuelle Gruppe.

<img src="screenshots/ios/import.png" alt="Importieren" width="500">

<img src="screenshots/macos/import.png" alt="Importieren – macOS" width="500">

> **Hinweis:** Wenn du eine JSON-Datei mit base64-Bildern importierst, werden die Bilder in den Karteikarten korrekt angezeigt.

### 5.5 Häufige Importfehler

| Fehler | Ursache | Lösung |
|-------|-------|----------|
| *Format nicht erkannt* | Die Datei ist kein gültiges CSV oder JSON | Überprüfe, ob die Datei die richtige Erweiterung hat und nicht beschädigt ist |
| *Leere Datei* | Die Datei enthält keine Karten | Überprüfe, ob die Datei mindestens eine Datenzeile enthält |

---

## 6. Flashcards teilen

StudyCards macht es einfach, deine Karteikarten mit anderen zu teilen.

### 6.1 Eine Gruppe als JSON teilen

**Schritte:**

1. Öffne die Gruppe, die du teilen möchtest.
2. Tippe auf das Aktionsmenü und wähle **Teilen**.
3. Das systemeigene Freigabefenster wird geöffnet.
4. Wähle die App oder Methode zum Senden:
   - **AirDrop** — für nahegelegene Apple-Geräte.
   - **Mail** — Sende die JSON-Datei als Anhang.
   - **WhatsApp** — Sende die JSON-Datei als Dokument.
   - **Nachrichten** — Sende per iMessage.
   - **Andere Apps** — Jede App, die Dateianhänge akzeptiert.

<img src="screenshots/ios/share.png" alt="Teilen" width="500">

<img src="screenshots/macos/share.png" alt="Teilen – macOS" width="500">

### 6.2 Geteilte Karteikarten empfangen

Wenn dir jemand eine StudyCards JSON-Datei sendet:

1. Öffne die Datei auf deinem Gerät.
2. Wähle **In StudyCards öffnen** oder **Importieren**.
3. Die Gruppe wird automatisch deiner Sammlung hinzugefügt.

---

## 7. Einstellungen

Passe StudyCards an deine Vorlieben an.

### 7.1 Erscheinungsbild

Steuere das visuelle Theme der App.

| Option | Beschreibung |
|--------|-------------|
| **System** | Passt sich automatisch an die Erscheinungsbild-Einstellung deines Geräts an (hell oder dunkel). |
| **Hell** | Immer den hellen Modus verwenden. |
| **Dunkel** | Immer den dunklen Modus verwenden. |

**Schritte:**

1. Gehe zum Tab **Einstellungen**.
2. Wähle im Bereich **Erscheinungsbild** eine der drei Optionen aus.
3. Die Änderung wird sofort angewendet.

<img src="screenshots/ios/appearance.png" alt="Erscheinungsbild-Einstellungen" width="500">

<img src="screenshots/macos/appearance.png" alt="Erscheinungsbild-Einstellungen – macOS" width="500">

### 7.2 Sprache

StudyCards ist in 8 Sprachen verfügbar. Du kannst eine bestimmte Sprache erzwingen oder die Standardsprache des Systems verwenden.

| Sprache | Code |
|----------|------|
| **System** | Wählt automatisch die Gerätesprache |
| Español | es |
| English | en |
| Português | pt |
| Français | fr |
| Deutsch | de |
| Italiano | it |
| 日本語 | ja |
| 中文 | zh |

**Schritte:**

1. Gehe zum Tab **Einstellungen**.
2. Wähle im Bereich **Sprache** die gewünschte Sprache aus.
3. Die Änderung wird sofort ohne Neustart angewendet.

<img src="screenshots/ios/language.png" alt="Sprach-Einstellungen" width="500">

<img src="screenshots/macos/language.png" alt="Sprach-Einstellungen – macOS" width="500">

### 7.3 Studienreihenfolge

Lege die Standardreihenfolge fest, in der Karteikarten im Studienmodus angezeigt werden.

| Option | Beschreibung |
|--------|-------------|
| **Sequenziell** | Karten werden in der Reihenfolge der Erstellung angezeigt (oder in manueller Reihenfolge, wenn du sie neu sortiert hast). |
| **Zufällig** | Karten werden in jeder Sitzung gemischt. |

**Schritte:**

1. Gehe zum Tab **Einstellungen**.
2. Wähle im Bereich **Studienreihenfolge** deine Präferenz aus.
3. Die Änderung gilt für alle zukünftigen Studiensitzungen.

<img src="screenshots/ios/study_order.png" alt="Studienreihenfolge-Einstellungen" width="500">

<img src="screenshots/macos/study_order.png" alt="Studienreihenfolge-Einstellungen – macOS" width="500">

---

## 8. Tipps

### Organisation

- **Erstelle eine Gruppe für jedes Fach oder Thema.** Das hilft dir, schnell das zu finden, was du studieren möchtest.
- **Verwende klare, kurze Namen** für Gruppen und Karteikarten. Vermeide Text, der auf dem Bildschirm zu lang zum Lesen ist.
- **Sortiere Karteikarten manuell**, um die wichtigsten zuerst zu platzieren.
- **Überprüfe deine Gruppen regelmäßig.** Lösche Karten, die du gemeistert hast, und füge neue hinzu, um deinen Fortschritt widerzuspiegeln.

### Studie

- **Verwende verteiltes Lernen.** Studiere dieselben Karten an verschiedenen Tagen, um das Langzeitgedächtnis zu festigen.
- **Ignoriere schwierige Karten nicht.** Wenn du eine Karte als *Nicht gewusst* bewertest, studiere diese Gruppe bald erneut.
- **Wechsle zwischen Studienmodi.** Wechsle zwischen sequenzieller und zufälliger Reihenfolge, um das Auswendiglernen von Kartenpositionen zu vermeiden.
- **Verwende Tastaturkürzel** auf macOS, um schneller zu studieren (Leertaste, 1, 2, 3).
- **Studiere in kurzen Sitzungen.** 10 bis 20 Minuten reichen für eine produktive Sitzung aus.

### Inhalt

- **Schreibe klare, präzise Fragen.** Vermeide Mehrdeutigkeit.
- **Eine Idee pro Karte.** Überlade die Vorder- oder Rückseite nicht mit zu vielen Informationen.
- **Verwende Bilder.** Ein Diagramm oder Bild kann effektiver sein als ein Absatz Text.
- **Verwende LaTeX-Formeln** für Mathematik- oder Wissenschaftsinhalte. Sie sind präzise und sehen professionell aus.

### Backups

- **Exportiere deine Gruppen regelmäßig.** Speichere Kopien auf iCloud Drive oder deinem Computer.
- **Verwende das JSON-Format**, wenn du Bilder erhalten möchtest. CSV speichert nur Text.
- **Teile deine Karteikarten** mit Kommilitonen oder Kollegen, um gemeinsam zu studieren.

### Leistung

- **Schließe andere Apps** beim Studieren, damit StudyCards ohne Unterbrechungen läuft.
- **Halte die App auf dem neuesten Stand**, um die neuesten Funktionen und Fehlerbehebungen zu erhalten.
- **Wenn LaTeX-Formeln nicht dargestellt werden**, überprüfe deine Internetverbindung. MathJax muss die Ressourcen beim ersten Mal herunterladen.

---

## Rechtliche Informationen

- **StudyCards** ist eine unabhängig entwickelte Anwendung.
- Die Nutzung unterliegt der Apache 2.0-Lizenz von MathJax.
- Deine Daten werden nur auf deinem Gerät gespeichert. StudyCards erhebt oder teilt keine persönlichen Daten.

---

*StudyCards Benutzerhandbuch — Version 1.1 — Juli 2026*
