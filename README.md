# LA_1000_1


# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

Lennard Bühler

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt


Ich möchte einen zufälligen numerguesser der Zahler zwischen 1 und 100 generieren kann und man diese raten kann.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |     MUSS        |      | Als User möchte ich Zahlen eingeben können, damit die Zahl geprüft werden kann ob richtig oder Falsch|
| ...  |     MUSS        |      | Als User möchte ich Zahlen zwischen 1 und 100, damit man eine Auswahl an Zahlen hat|
| ...  |     MUSS        |      | Als User möchte ich fals die Zahl korekt ist das unten ein grüner botton kommt wo Richtig steht und die Zahl zu sehen ist, damit man auch irgendwann auf die Zahl kommt|
| ...  |     MUSS        |      | Als User möchte ich fals die Zahl falsch ist das unten ein roter botton kommt wo Falsch steht und ob die Zahl grösser oder kleiner ist deis wird mit "higher" fals die Zahl grösser ist und "lower" wenn die Zahl kleiner ist, damit man auch irgendwann auf die Zahl kommt|                                  
| ...  |      KANN       |      |  Als User möchte ich das wenn die Antwort richtig ist es ein von mir ausgewältes Geräusch gibt, damit es nicht so langweilig ist|
| ...  |      KANN       |      |  Als User möchte ich das wenn die Antwort falsch ist es ein von mir ausgewältes Geräusch gibt, damit es nicht so langweilig ist|                                  




✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm gestartet            |  Zahl wird eingegeben       |      Richtig oder Falsch     |
| 1.2  | Programm gestartet            |  Auswehelen welche zwischen welchen Zahlen eine Zahl generiert wird      |     Case zum Zahl eingeben wird gezeigt              |
| 1.3  | Programm gestartet            |   Zahl eingeben      |           Richtig        |
| 1.4  | Programm gestartet            |     Zahl eingeben     |      Falsch             |
| 1.5  | Programm gestartet            |      Zahl eingeben    |       Wird gezeigt ob richtige Zahl grösser oder kleiner ist            |
| 1.6  | Programm gestartet            |      Zahl eingeben   |       Geräusch wird abgespielt wenn richtig oder wenn falsch anderes Geräusch            |


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

![Blank diagram](https://user-images.githubusercontent.com/110892642/186127588-a7f9812c-8983-4153-93db-a3d8ab86f1ab.png)

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |    5.9    |           |       wenn man Zahl eingibt kommt richtig oder falsch       |       30 min        |
| ...  |    5.9    |           |         Man kann auswehlen zwischen welchen Zahlen die zufällige zahl generiert wird     |       40 min        |
| ...  |      5.9  |           |          wenn man Zahl eingibt kommt richtig    |       45 min        |
| ...  |   5.9     |           |       wenn man Zahl eingibt kommt falsch       |         40 min      |
| ...  |    5.9    |           |       wenn man Zahl eingibt kommt ob die Zahl kleiner ist oder grösser    |    40 min           |
| ...  |    5.9    |           |        wenn man Zahl eingibt kommt und es richtig oder falsch ist kommt ein Geräusch bei richtig anders als bei falsch       | 50 min              |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
