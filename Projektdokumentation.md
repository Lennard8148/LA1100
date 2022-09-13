# LA_1000_1


# Projekt-Dokumentation

Lennard Bühler

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 23.08   | 0.0.1   | Ich habe mit dem Planen meines Projekts angefangen und dazu angefangen die Projekt dokumentation zu machen
| 30.08     |  0.0.2      |   ich habe die zufalszahl generiert und einige coole futures eingebaut                                                         |
|  6.09     | 1.0.0   |       Ich habe mein Projekt beendet leider konnte ich nicht mehr viele sachen hinzufügen                                                       |

## 1 Informieren

### 1.1 Ihr Projekt


Ich möchte einen zufälligen numerguesser der Zahler zwischen 1 und 100 generieren kann und man diese raten kann.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |     MUSS        |  Funktional    | Als User möchte ich Zahlen eingeben können, damit die Zahl geprüft werden kann ob richtig oder Falsch|
| 2  |     MUSS        |   Funktional   | Als User möchte ich Zahlen zwischen 1 und 100 haben in denen die random zahl generiert wird, damit man eine Auswahl an Zahlen hat|
| 3  |     MUSS        |   Qualität   | Als User möchte ich fals die Zahl korekt ist das unten ein grüner botton kommt wo Richtig steht und die Zahl zu sehen ist, damit man auch irgendwann auf die Zahl kommt|
| 4  |     MUSS        |   Qualität   | Als User möchte ich fals die Zahl falsch ist das unten ein roter botton kommt wo Falsch steht und ob die Zahl grösser oder kleiner ist deis wird mit "higher" fals die Zahl grösser ist und "lower" wenn die Zahl kleiner ist, damit man auch irgendwann auf die Zahl kommt|                                  
| 5  |      KANN       |   Qualität   |  Als User möchte ich das wenn die Antwort richtig ist es ein von mir ausgewältes Geräusch gibt, damit es nicht so langweilig ist|




### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm gestartet            |  Zahl wird eingegeben       |      Richtig oder Falsch     |
|  2.1 | Programm gestartet            |     Zahl zwischen 1 und 100 eingeben   |     Prüfen ob richtig              |
| 1.2  | Programm gestartet            |   Zahl eingeben      |           Richtig        |
|  1.3 | Programm gestartet            |     Zahl eingeben     |      Falsch             |
| 4.1  | Programm gestartet            |      Zahl eingeben    |       Wird gezeigt ob richtige Zahl grösser oder kleiner ist            |
|  5.1 | Programm gestartet            |      Zahl eingeben   |       Geräusch wird abgespielt wenn richtig oder wenn falsch anderes Geräusch            |
|  3.1 | Programm gestartet            |      Zahl eingeben      |     Richtig auf in grüner Farbe und falsch rote farbe          |


### 1.4 Diagramme

![Blank diagram](https://user-images.githubusercontent.com/110892642/186127588-a7f9812c-8983-4153-93db-a3d8ab86f1ab.png)

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |    5.9    |     Lennard      |       wenn man Zahl eingibt kommt richtig oder falsch       |       30 min        |
|2.A  |    5.9    |     Lennard     |         Man kann auswehlen zwischen welchen Zahlen die zufällige zahl generiert wird     |       40 min        |
| 1.B  |      5.9  |     Lennard      |          wenn man Zahl eingibt kommt richtig    |       45 min        |
| 1.C|   5.9     |     Lennard      |       wenn man Zahl eingibt kommt falsch       |         40 min      |
| 4.A  |    5.9    |     Lennard      |       wenn man Zahl eingibt kommt ob die Zahl kleiner ist oder grösser    |    40 min           |
| 5.A  |    5.9    |     Lennard     |        wenn man Zahl eingibt kommt und es richtig oder falsch ist kommt ein Geräusch bei richtig anders als bei falsch       | 80 min              |
| 3.A  |    5.9    |     Lennard      |      Bei richtiger Zahl grüne Farbe bei falscher rote Farbe    |       60 min        |
Total: 



## 3 Entscheiden
Ich möchte einen guten Zahlen generator der zahlen zwischen 1 und 100 generieren kann und man dann eine Zahl eingibt und es geprüft wird ob sie richtig oder falsch ist. Ich möchte auch Farben einbauen. Wenn man keine Zahl eingibt wird einem gesagt das man eine Zahl eingeben sollte.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |   5.9    |   Lennard Bühler         |       30 min        |    20               |
| 1.B  |  5.9       |   Lennard Bühler         |      45         |        30           |
| 1.C  |  5.9      |   Lennard Bühler         |       40        |         45          |
| 2.A  |       |   Lennard Bühler         |       40        |                   |
| 3.A  |   5.9     |   Lennard Bühler         |       60        |       70            |
| 4.A  |  5.9      |    Lennard Bühler        |        40       |       60            |
| 5.A  |       |    Lennard Bühler        |        80       |                   |


e effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |   13.09      |  Programm gibt aus ob richtig oder falsch        |    Lennard Bühler    |
| 2.1  |   13.09      |  Programm gibt richtig bei richitger Zahl zwischen 1 und 100        |    Lennard Bühler    |
| 1.2  |   13.09      |  Programm gibt falsch aus bei falscher Zahl        |    Lennard Bühler    |
| 1.3  |   13.09      |  Programm gibt richtig aus bei richtiger Zahl        |    Lennard Bühler    |
| 4.1  |   13.09      |      Programm gibt aus ob Zahl grösser oder kleiner ist     |    Lennard Bühler    |
| 5.1  |   13.09      |  Programm gibt kein Geräusch aus         |    Lennard Bühler    |
| 3.1  |   13.09             | Programm gibt richtig mit grüner Farbe aus und falsch mit roter         |    Lennard Bühler    |


✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
