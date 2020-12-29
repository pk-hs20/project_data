# Ergebnisse des ICR-Tests & Überarbeitung Codebuch 

**Zweck der Seite**
Hier werden die Ergebnisse des ICR-Tests präsentiert. Ausserdem können wir gemeinsam die Änderungen besprechen und bestimmen. Teilweise findet ihr bereits Anmerkungen der AG4 und AG5 im Text.  Bitte aufmerksam durchlesen!


:::info
**Anmerkungen der AG 4 zur Überarbeitung des Codebuchs**
Für die Überarbeitung verwendet ihr bitte das **[aktuelle Worddokument der Codebuchversion 1](https://drive.google.com/drive/folders/1kiBl0lPYwF_FOgPMmKTu-pd1jqcP5isx?usp=sharing).** Dokument direkt herunterladen, eigenen Codebuchteil überarbeiten und File per Mail bis **5.12** an AG4 schicken. Wir kopieren euren Codebuchteil 1:1 in die neue Version.

Die **[Kommentare / Fragen die während des 1. Codierdurchlauf auftauchen](https://pad.gwdg.de/gkz1jPEBT7-944EgCfDdKQ?both#Kommentare--Fragen-die-w%C3%A4hren-des-1-Codierdurchlauf-auftauchen)** können euch bei der Überarbeitung helfen.
:::



## Zuerst ein paar allgemeine Rückmeldungen für alle zum Codierprozess und zu dem Codebuch 

**Anzahl Websiten / Artikel**
* Website: Eigentlich sollte jede*r bei dem ersten Codierdurchgang nur 1 Website codieren - teilweise wurden aber auch 2 gemacht. Beim 2. Durchgang dann bitte die richtige ID wählen im Excel Zuteilung.
<!-- diese Codierung könnt ihr für den Durchgang 2 behalten.
> AG4: wie ist das gemeint? Die AGs müssen mit der neuen Version codieren, oder?? Die Kategorien ändern sich ja wahrscheinlich auch noch.
> AG5: Da habt ihr recht, Entschuldigung. Ihr könnt diese Bemerkung löschen. -->

* Artikel: Bei der ersten Zusammenführung aller Codierbögen war leider die Anzahl Artikel nicht richtig (es waren 90, davon 17 ohne „Partner“ - es müssten aber 80 Artikel sein).
Wir haben die IDs alle manuell überprüft und angepasst. Es waren leider viele falsche IDs drin: Abtipp-Fehler und/oder die Schreibweise der Artikel ist nicht identisch mit der Liste der Zuteilung.
Also bitte achtet beim zweiten Durchgang darauf, dass die IDs einheitlich beschriftet sind - und das ihr den richtigen Artikel auswählt (ja, auch das ist passiert :-).

>@ AG2: ev. muss die Liste Zuteilung auf Dropbox angepasst werden?!

> AG4: Wir werden im Codebuch V2 schreiben, dass die ID aus der Liste «Zuteilung» in den Codierbogen kopiert werden soll. So gibt es keine Inkonsistenzen, falls die Artikelbenennung in der Liste auch beim zweiten Codierdurchgang mal nicht mit den Dateinamen in der Dropbox übereinstimmen sollte. Und durch copypaste gibt’s hoffentlich keine Abtippfehler mehr. 

> AG4/AG5 @ AG2: Artikelbenennung in Liste und Dropbox dennoch bitte vereinheitlichen.

<!--> AG5: Ja, bitte. Aber auch trotzdem die Zuteilungsliste anpassen. Es kann trotzdem noch sein, dass jemanden doch den Dateiname nimmt. i.O.? -->

<br/>

**Unterschied "leere Felder" / 0 / 77 / 99**
Es scheint nicht ganz klar zu sein, wann welche Ausprägung eingesetzt wird. All diese Felder sollten im Codebuch unbedingt besser erklärt und vereinheitlicht werden.
* 0 steht in einigen Kategorien für „Keine Angabe“ und 77 für „Nicht zuordbar“ - jedoch kommen diese Ausprägungen nicht bei allen Kategorien vor.
* Unterschiedlicher Einsatz z.B. bei:
    * W12: „Keine“ =  99 (und nicht wie bei den anderen 0 oder 1)
    * W25: „nicht vorhanden“ = 2
    * W27: „nicht vorhanden“ = 0 ; vorhanden = „1“
> AG4: "nicht vorhanden / trifft nicht" zu muss immer 0 sein und an erster Stelle sein. W12 müsste 0 und 1 sein.
> 
> **Bezüglich Felder 0 / 77 / 99 in Hinblick auf die Codebuchüberarbeitung und den nächsten Codierdurchgang die [Ausführungen von Fr. Dalmus](https://pad.gwdg.de/yxqs5piTS42rOKwx1yFERQ?both#Unterschied-0--77--99-Antwort-C-Dalmus-241120) beachten.**

> **Leere Felder sind in manchen Ausnahmefällen erlaubt (muss aber klar definiert sein!). Siehe dazu die [Ausführungen von Fr. Dalmus](https://pad.gwdg.de/yxqs5piTS42rOKwx1yFERQ?both#Leere-Zellen-Antwort-C-Dalmus-241120)**

<!-- > AG5: Es darf "missing Values" geben, aber dies nicht aufgrund des Codebuch oder weil der Codierer nicht wusste, was einzufügen. Diese dürfen nur sein, wenn wirklich die Kategorie vergessen worden ist. Versteht ihr es besser so?
Die Problematik liegt darin, dann die Ausage eine andere Bedeutung hat, ob es übersehen worden ist oder ob es keine Angabe zu einer Kategorie und dafür im Codebuch keinen entsprechenden Wert gibt. (z.B bei Datum, blieb es immer wieder leer. Aber nur weil es keine Variable gibt für "kein Datum".) -->



<br/>

:::danger

**Und noch etwas allgemeines zum Ausfüllen der Codebogen, das sehr hilfreich ist für das Zusammenführen von Daten:**
- Bitte keine Leerzeichen am Schluss der Textfelder einfügen

- Bitte keine Sonderzeichen „“ % - etc. in die Textfelder schreiben
:::
<br/>

## ICR-Test bei Ebene Akteur und Statement
Das Zuordnen der Akteure & Statements kann zwar automatisch über die ID erfolgen, aber ohne intellektuelle Überprüfung des Textfeldes (bei Akteure K1) kann nicht garantiert werden, dass wirklich der gleiche Akteur bzw. das gleiche Statement gemeint ist. Bei den Akteuren konnten wir das manuell bereinigen - Akteure die beim "Partner-Codierer" nicht vorkommen, wurden gelöscht.

Bei der Ebene Statement gibt es im Codebuch dieses Textfeld nicht und deshalb konnte der ICR-Test leider nicht durchgeführt werden!
Die Felder ID und Text werden also im Codebuch 2 ergänzt, damit auch die Kategorien dieser Ebene mit dem Reliabilitäts-Test überprüft werden können.

<br/>

## Anpassungen Teil-Codebücher
Der Inter-Codierer-Reliabilitäts-Test rechnet aus, wie gut die Codierungen der verschiedenen Codiererinnen übereinstimmen. Und macht so eine Aussage über die Zuverlässigkeit der einzelnen Kategorieren - also ob die Codieranweisungen genügend sind und ob alle Codiererinnen das gleiche unter einer Kategorie verstehen. 


Der ICR-Test wurde mit der Formel von Krippendorf ausgerechnet. Daraus resultiert KAlpha, das wie folgt interpretiert werden kann:
![](https://pad.gwdg.de/uploads/upload_11182dba66fccc54769be254baef02dd.png)


Die α-Werte findet Ihr in [dieser Excel-Liste](https://drive.google.com/file/d/1IVww6L8JQNcFMITSBAVfjyz9Bu0ogXty/view?usp=sharing).<!-- Google Drive Alex --> Für jede Ebene (Website, Artikel, Akteur) gibt es ein Sheet und da für jede Kategorie einen α-Wert.

* :+1: Kategorien mit α > 0.8 müssen NICHT überarbeitet werden.

* :-1: **Alle Kategorien mit α < 0.67** haben eine sehr schwache Übereinstimmung und müssen zwingend überarbeitetet werden! 
Auch die **negativen (roten) Kategorien** müssen überarbeitet werden (Negative Werte ergeben sich sich, wenn systematische Nicht-Übereinstimmung vorliegen - also die Kategorien immer genau gegensätzlich codiert wurden).

* :-1: **Kategorien mit α = 0.67-0.8:** Da wahrscheinlich durch die Hypothesenbildung viele Kategorien wegfallen, bitten wir euch auch diese Kategorien zu überarbeiten (wenn der Aufwand auf eurer Ebene vertretbar ist).

**Überarbeiten heisst:** Beschreibung der Kategorie verbessern, Ausprägungen optimieren und Beispiel anpassen - so dass ein besseres gemeinsames Verständnis entsteht, wie diese Kategorie codiert werden muss. 

<br/>

Achtung nicht erschrecken, wenn die α-Werte bei euren Kategorien sehr schlecht sind:
* Krippendorfs Alpha ist sehr streng wenn es nur zwei Ausprägungen bei einer Kategorie hat (z.B. nur 0 oder 1).
* Wenn mehrere Ausprägungen vorhanden sind (z.B. 0, 1-8, 77, 99) dann ist die Interpretation „lockerer“.

<br/>

**Sheet Website:**
![](https://pad.gwdg.de/uploads/upload_98cb8220979c583ae5b139bdc31e9f37.png)

**Sheet Artikel:**
![](https://pad.gwdg.de/uploads/upload_7a86bdedfa1604be8623b9e99847774c.png)

**Sheet Akteure:**
![](https://pad.gwdg.de/uploads/upload_08d6d160b07431bb06b53c2edbbe26a4.jpg)


## Hier noch zusätzliche Feedbacks zu den Teil-Codebüchern:

### Codebuch Ebene Website:
* Es braucht eine ID für die Website für die Zuteilung: z.B. T4
> AG4: T4 wird integriert. ID wird dann aus der Liste Zuteilung übernommen (wie auch die IDs der Artikel) -> z.B SP_FB



### Codebuch Ebene Akteur:
* Bessere Definition / Beschreibung, was genau ein Akteur  ist.
> AG4: neu werden wahrscheinlich nur Personen/Organisationen Akteur'innen sein, deren Aussage direkt oder indirekt zitiert wird (Vorschlag Frau Dalmus). Dann ist vieles klarer.
* Bessere Beschreibung der Reihenfolge der ID und wie diese aufgebaut ist (einige Codiererinnen starten beim Autor z.B. mit _1, andere _0)

<!--
> AG4: Gemäss Codebuch wird bei 0 gestartet, wenn die Akteurin auch gleich die Urheberin ist. Das heisst: die 0 ist je nach dem gefragt – oder eben nicht. Wurde das nicht einheitlich gemacht? Oder plädiert ihr generell dafür, dass wir einfach bei 1 beginnen, egal ob Urheberin oder nicht? (wäre ja auch eine Option).

> AG5: Da die meisten es richtig gemacht haben, plädieren wir dafür, dass wir mit _0 für Autor bleibt, und für eine bessere Beschreibung. Vielleicht könnt ihr ein Beispiel einbauen und dieses Detail in rot kennzeichnen? -->

* Kategorie K1: Name des Akteurs ist oft vorhanden im Artikel, teilweise etwas versteckt. Bitte achtet darauf, diesen Namen (und ev. auch die Rolle) zu erfassen. Das hilft der Identifikation der Akteure.

> Fazit AG4/AG5: nicht zu schnell aufgeben. Gründlich nach Akteursbezeichnung suchen. 


<!-- > AG 4: ich bin unsicher was mit «versteckt» gemeint ist. Aber grundsätzlich: reicht es euch, wenn wir im Codebuch schreiben, dass die Akteure so genau wie möglich beschrieben werden sollen → wenn möglich Name mit Rolle kombinieren?. Wahrscheinlich werden die Akteure dann nicht sehr einheitlich erfasst. Aber ihr habt mehr Information in der Zelle. 

> AG5: ab und zu ist der Akteurname in einem Kommentar oder irgendwo kleingeschrieben. (Es wurde ab und zu verpasst und als Anonym bezeichnet.) Hier ist es ein Hinweis nötig, damit nicht zu schnell gerbeitet wird. (vielleicht auch die Ausprägung "nicht vorhanden") -->



### Codebuch Ebene Statement:

* Bessere Definition / Beschreibung, was mit Statement gemeint ist.

* Es braucht eine ID für die Statements für die Zuteilung: z.B. T5

* Es muss eine zusätzliche Kategorie für den Text von Statement für die genaue Identifikation ergänzt werden (analog K1)

<br/>


## Weitere Kommentare oder Fragen? 

* AG4: Unsere Kategorie Nr. 7 (K7) funktioniert offenbar nicht und ist aber wichtig für unsere Thesen. Da wäre es spannend zu wissen, wo das Problem liegt, weil im gwdg-File keine Fragen dazu notiert wurden. Wurde sehr oft 77 und/oder 99 gewählt? Falls ihr hier noch mehr Info hättet wäre das super. Ihr könnt uns auch die Daten schicken, die wir dann selber interpretieren oder so (aber ich weiss nicht wie eure «Rohdaten» aussehen ).
> AG5: Alex schickt euch den Link zu dem zusammengeführten File in einem Mail.
> 

 <!-- ## Zwei Fragen haben sich beim Berechnen des KAlpha noch gezeigt (Abklärung mit Frau Dalmus)
Diese Fragen richten sich primär an Frau Dalmus, mit der Bitte, diese parallel zu der Weiterverarbeitung von AG4 (22.-23.11) zu beantworten.

1. Bei der Ebene Website wurde ja pro Codierer nur 1 Website codiert. Das ergibt nur 8 Werte pro Kategorie.
Diese Anzahl erscheint uns nicht aussagekräftig für die Berechnung von KAlpha - weil der α-Wert mit 1 Paar mehr oder weniger ziemlich aussschlägt.
Stimmt das? Wieviele Paare werde normalerweise für die Test-Codierung eingesetzt? 

2. Ebenfalls bei der Ebene Website gibt es einige Kategorien bei denen KAlpha im Minus-Bereich resultiert (Liste W im Anhang).  Anscheinend hat die Formel Probleme, wenn alle Paare, die übereinstimmen, genau die gleiche Ausprägung gewählt haben.  
z.B. W13: 4 von 8 Paaren stimmen überein, aber die sind alle 0/0-Paare, es gibt keine 1/1-Paare.  
oder W33: 5 von 8 Paare stimmen überein, aber die sind alle 2/2-Paare, 1/1 gibt es keine (dann gibt es noch einen kreuzfalschen Wert 0).

Ev. liegt es auch nur an der geringen Anzahl Werten - in der Literatur konnten wir über dieses Resultat nichts finden - danke für eine Aufklärung. -->


## Antworten Dozierende

### Unterschied 0 / 77 / 99 (Antwort C. Dalmus, 24.11.20)

:::info
AG4: Folgende Ausführungen von Frau Dalmus bitte in Hinblick auf die Anpassung des Codebuches und den nächsten Codierdurchgang beachten.
:::

Die 0 codiert man in der Regel, wenn der interessierende Aspekt tatsächlich nicht vorhanden ist. Die 77 besagt, dass der interessierende Aspekt vorkommt, aber nicht klar entschieden werden kann, in welcher Ausprägung (wenn man beispielsweise überzeugt ist, dass sowohl Ausprägung 5 als auch 7 zutreffen könnte). Wenn häufig die 77 codiert wird, ist das ein Hinweis, dass die Ausprägungen nicht trennscharf sind. Die 99 besagt, dass der interessierende Aspekt vorkommt, aber keine der aufgeführten Ausprägungen passt (bspw. wenn es bei Genre die Ausprägungen Bericht, Nachricht, Reportage, Kommentar gibt, es sich aber bei dem Artikel um eine Glosse handelt). Wenn häufig die 99 vorkommt, ist das ein Hinweis, dass die Ausprägungen nicht vollständig sind. 

### Leere Zellen (Antwort C. Dalmus, 24.11.20)

:::info
AG4: Bitte beachten, dass Zellen aber nur leer sein dürfen, wenn das so im Codebuch definiert wurde (z.B wenn aus bestimmten Gründen Kategorien übersprungen werden dürfen). Zellen dürfen nicht leer sein, nur weil Codierer'in unsicher war und  nicht wusste was eingeben (z.B bei Datum, blieb Zelle immer wieder leer oder es wurden Fantasienamen reingeschrieben, weil es keine Variable gibt für “kein Datum” -> nicht gut)
:::

Zellen können leer gelassen werden. SPSS erkennt diese automatisch als missing values (system missing values) an. Man erkennt sie in SPSS dann an einem kleinen Punkt in der jeweiligen Zelle. SPSS kann problemlos damit arbeiten, bei R gibt es manchmal Probleme (aber damit arbeitet die Gruppe ja nicht). Allerdings kann man auch sogenannte user missing values bestimmen. In dem Fall definiert man in SPSS die Art des fehlenden Wertes und vergibt einen tatsächlichen Wert. Der Vorteile ist, dass man dann genau weiss, dass ein Wert beispielsweise aufgrund der Filterführung fehlt. User missing values lassen sich sehr einfach und schnell in SPSS definieren.
