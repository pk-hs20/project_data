---
type: slide
slideOptions:
  transition: slide
---

# Präsi Projektorganisation und -information

---

:::info
**NEWS**
Liebe Arbeitsgruppen
Über diese Seite geben wir euch administrative Info weiter. Wir danken euch für die Beachtung dieser Seite. Meldet euch bei Fragen bei Gaby, Flo oder Vanessa.

Aktuelles werden wir jeweils zuoberst einfügen, damit ihr schnell seht, was zuletzt gelaufen ist, sobald ihr diese Seite aufruft.
:::
 

---

## Projekt-Toolbox
Womit wollen wir in diesem Projektkurs arbeiten?

---

### Terminplanung
Ist integriert auf dieser Seite, mit [mermaid](https://pad.gwdg.de/features?both#Mermaid).

-- 

### Projektcontrolling
Wir haben für jede AG eine CodiMD-Reporting-Seite aufgesetzt, die ihr bloss termingerecht mit Information zu befüllen braucht.

*Links folgen hier*

---


### Texteditor GWDG Sharelatex (Overleaf)
Wir bitten euch, sowohl eure Konzepte wie auch den Abschlussbericht mit Overleaf im GWDG Sharelatex zu erstellen. 

Eröffnet dazu einen Account bei GWDG: 
https://academiccloud.de/registration

Wir haben Templates für eure Konzepte vorbereitet, damit ihr bereits für den Entwurf mit Overleaf üben könnt, denn:

---

:::warning
> "Wissen kommt von Machen."
> 
<div style="text-align: right">Felix Lohmaier, Dozent BAIN</div>
:::

---


### Grund für diesen Texteditor

Wir als Projektleitung sind verantwortlich für die Redaktion des Abschlussberichts. Das Zusammenführen eurer Inhalte und die Formatierung wird durch die gemeinsame Nutzung von ShareLatex für uns extrem vereinfacht. Die Nutzung von ShareLatex ist niederschwellig. 

---

### Vorteile

:::success
* **Keine** $L^aT_eX$-Installation nötig!
* $L^aT_eX$ ist html vom Prinzip her ähnlich, wenig Neues
* Troubleshooting durch die Projektleitung
* volle Online-Kollaboration der AGs auf ihrem Dokument (inklusive Chatfunktion)
* AbReview für Änderungen verfolgen
* Suchen/Ersetzen auch mit RegEx
* Literaturverzeichnis mit Bilatex/Zotero

:::

---

:::success
* Versionskontrolle über die History
* Typografisch ansprechende Dokumente verlinkten Literatur- und Querverweisen
* LaTeX ist de-facto-Standard für naturwissenschaftliches Publizieren
* Daten sind **nicht** bei Google
* perfekte Gelegenheit, die Verwendung von Overleaf/LaTeX **vor** der Bachelor-Arbeit an einem konkreten Projekt quasi mit "Stützrädli" zu üben
::: 

---

#### Nachteile
:::warning
* man muss sich etwas Neues aneignen (Initialaufwand)
* wenn das Kompilieren irgendwo hängt, kann Debugging mühsam sein. Das Debug-Feature von Overleaf, google, und die PL sind eure Freund'innen.
:::

--- 

## Literaturverwaltung mit Zotero
Um das Literaturverzeichnis im Abschlussbericht als Ganzes zu erstellen, haben wir euch in unsere Zotero-Gruppe eingeladen.

Wir werden euch diese Bibliografie dann in Overleaf laden, damit alle einheitlich zitieren. Das ideale Vorgehen mit Literaturverweisen ist ebenfalls in der Overleaf-Anleitung erklärt.

---


## Terminplanung
```mermaid
gantt
  title Zeitplan, provisional

  section Konzept
  LitRech :active,crit  kon1, 2020-09-10, 2020-10-09
  V1      :done,        kon2,  2020-09-21, 11d
  V2      :active,crit, kon3, after kon2, 2020-10-12
  Abgabe      :milestone, after kon3
  
  section Datenerfassung
  AP 1    :             de1, after kon3, 20d
  AP 2    :             de2, after de1, 12d
  AP 3    :             de3, after de1, 20d
  AP 4    :             de4, after de3, 10d
  
  section Interaktionen
  Präsi :milestone,      pres1, 2020-10-14
  Arbeitsstand :milestone,      disk1, 2020-11-03
  Arbeitsstand :milestone,      disk2, 2020-12-01
  Abgabe  :crit, milestone, 2021-01-15
  
  section Bericht
  hund :a, after de4, 1w
  katze :crit, b, after a, 1d
  maus :active, c, after b a, 1d
 
  
  
```

---

| Datum | Beschreibung | Typ |
| -------- | -------- | -------- |
| 21.09.2020 (12:00 Uhr) | Abgabe Konzepte V1 (unbenotet) | Deadline |
| 22.09.2020 | Diskussion der Konzepte mit Betreuenden | Termin |
| 12.10.2020 | Abgabe Konzepte V2 (benotet) | Deadline |
| 14.10.2020 | Präsentation Konzepte & Diskussion | Deadline |
| 03.11.2020 | Diskussion Arbeitsstand mit Betreuenden | Termin |
| 01.12.2020 | Diskussion Arbeitsstand mit Betreuenden | Termin |
| 15.01.2021 | Präsentation Resultate & Diskussion, Projektabschluss | Deadline |

[reference]: https:// "kurzanleitung-overleaf"
## Kurzanleitung Overleaf
Wie sieht es aus, in welchen Feldern sollen sie arbeiten? Kurze Erklärung wie wo was - Gaby?
> [Screenshots einbauen]

Frage: brauchen wir Besprechungstermine mit jeder AG, um auf dem aktuellen Stand der Dinge zu bleiben und allfällige Probleme zu erkennen? Eventuell genügen die Statusberichte auf CodiMD. Wir stehen bei allfälligen Schwierigkeiten zur Verfügung?

Wichtig: Sie müssen Abschlussberichte ca. 1.5-2 Wochen vor Deadline beenden, damit wir Schlussredaktion machen können. Also: 31.12.2020?
> [find ich ne gute Deadline für die Gruppen]
> 



