# Projekt-Dokumentation

✍️ Ihr Nachname

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|  23.01.2023     | 0.0.1   | Projekt Dokumentation angefangen. |
|  13.02.2023     | 0.0.2   |  Tutorial ertsellt.                                                             |
| 20.02.2023      | 0.0.3   |  Login ertsellt                                                            |
|  22.02.2023     | 0.0.4   |    Glücksrad erstellt                                                          |
|  25.02.2023     | 0.0.5   |  Wort Rate Funktion ertsllt                                                           |
|   27.02.2023    | 0.0.6   |  Währung Geld impletiert                                                             |
|    28.02.2023   | 0.0.7   | Projekt Doku fertig erstellt                                                             |

# 0 Ihr Projekt

Im Projekt geht es darum ein Glücksrad-Spiel mittels einer Webapplikation zu implementieren. Im Spiel soll es darum gehen ein Wort zu erraten. Jedes Wort den man erraten soll entspricht zu einem Hilfsatz, damit der Spieler sich beim Erraten orientieren kann. Nach dem auflösen des Wortes, kann der Spieler entsprechend am Glücksrad drehen. Nach dem erraten des Lösungswort, wird dem Spieler ein bestimmter Geldbetrag gutgeschrieben, den Geldbetrag kann man am Glücksrad multiplizieren oder alles verlieren. Falls das erratene Wort nicht dem Lösungswort entspricht , Verliehrt man Versuche (Leben)..

# 1 Analyse

✍️ Beschreiben Sie, auf welchem Tier Sie die dynamischen Elemente der Anwendung unterbringen möchten:

* Tier 1 (Presentation): Anzeigen von Buttons (Drahen, Logout, New Word)
* Tier 2 (Webserver): Login Daten geschützt speichern
* Tier 3 (Application Server): Die Usereingabe überprüfen anschliessend einen Wert ausgeben.
* Tier 4 (Dataserver): Speichern von Logindaten auf Firebase.

# 2 Technologie

Als Programmiersprache werde ich React verwenden, um die Darstellung, sowie die Eingabe und Validierung der Daten zu ermöglichen. Damit ich die Daten wie gewünscht speichere, werde ich eine Firebase-Datenbank aufsetzen und diese mit JavaScript verknüpfen und dort all die Daten einfügen bzw. auslesen oder abändern etc.

# 3 Datenbank

✍️ Wie steuern Sie Ihre Datenbank an? Wie ist das Interface aufgebaut? 

# 4.1 User Stories

✍️ Formulieren Sie klare Anforderungen in der Form von User Stories (*„als … möchte ich … damit …“*) und zu jeder Anforderung mindestens einen dazugehörigen Testfall (in Kapitel 4.2). 

✍️ Formulieren Sie weitere, eigene Anforderungen und Testfälle, wie Sie Ihre Applikation erweitern möchten. Geben Sie diesen statt einer Nummer einen Buchstaben (`A`, `B`, etc.)

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |     	Muss            | 	Funktional     |Als Administrator möchte ich mich durch Eingabe eines Benutzernamens und Passworts authentifizieren, um auf die Verwaltungsfunktionen zugreifen zu können.  |
| 2   |     	Muss            | 	Funktional     |Als Administrator möchte ich Phrasen und Rätselwörter anlegen, ändern und löschen können, um den Fragenpool des Spiels verwalten zu können.  |
| 3    |     	Muss            | 	Funktional     |Als Administrator möchte ich Kategorien anlegen und jedem Wort bzw. jeder Frage einer Kategorie zuordnen können, um den Fragenpool des Spiels zu organisieren. |
| 4    |     	Muss            | 	Funktional     | Als Administrator möchte ich einzelne Einträge der Highscore-Liste löschen können, um diese zu bereinigen. |
| 5    |     	Muss            | 	Funktional     |Als Spieler möchte ich einen Namen eingeben können, der auf der Highscore-Liste erscheint, um meine Leistung mit anderen Spielern zu vergleichen.  |
| 6    |     	Muss            | 	Funktional     | Als Spieler möchte ich zu jeder Zeit meinen Kontostand und meine Lebenspunkte sehen können, um den Spielverlauf nachvollziehen zu können. |
| 7    |     	Muss            | 	Funktional     | Als Spieler möchte ich in der Highscore-Liste folgende Daten aufgeführt sehen: meinen Rang, meinen Namen, den Zeitpunkt des Spiels, meinen Geldbetrag und die Anzahl der Spielrunden, um meine Leistung mit anderen Spielern zu vergleichen. |
| 8    |     	Muss            | 	Funktional     |	Als Spieler möchte ich während des Spiels keine bereits gestellten Rätsel-Wörter oder Phrasen erneut gestellt bekommen, um einen fairen Spielverlauf zu gewährleisten.  |


✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc. oder Zahl), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). 

# 4.2 Testfälle

| TC-№ | Vorbereitung | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |     Programm ist gestartet.         | Der Administrator gibt falsche Anmeldedaten ein und versucht sich anzumelden        |  Das System gibt eine Fehlermeldung aus, dass die Anmeldedaten ungültig sind                 |
| 1.2  |    Programm ist gestartet.          |  Der Administrator gibt gültige Anmeldedaten ein und versucht sich anzumelden        |     Das System meldet den Benutzer erfolgreich an              |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

# 5 Prototyp
Siehe Code

# 6 Implementation

✍️ Halten Sie fest, wann Sie welche User Story bearbeitet haben

| User Story | Datum | Beschreibung |
| ---------- | ----- | ------------ |
|   1    |       |              |
|    2   |       |              |
|   3    |       |              |
|    4   |       |              |
|    5   |       |              |
|    6   |       |              |
|    7   |       |              |
|    8   |       |              |

# 7 Projektdokumentation

| US-№ | Erledigt? | Entsprechende Code-Dateien oder Erklärung |
| ---- | --------- | ----------------------------------------- |
| 1    | ja / nein |                                           |
| 2    | ja / nein |                                           |
| 3    | ja / nein |                                           |
| 4    | ja / nein |                                           |
| 5    | ja / nein |                                           |
| 6    | ja / nein |                                           |
| 7    | ja / nein |                                           |
| 8    | ja / nein |                                           |


# 8 Testprotokoll

✍️ Fügen Sie hier den Link zu dem Video ein, welches den Testdurchlauf dokumentiert.

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1 |       |          |        |
| 2.1  |       |          |        |
| 3.1 |       |          |        |
| 4.1  |       |          |        |
| 5.1  |       |          |        |
| 6.1  |       |          |        |
| 7.1 |       |          |        |
| 8.1  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

# 9 `README.md`

✍️ Beschreiben Sie ausführlich in einer README.md, wie Ihre Applikation gestartet und ausgeführt wird. Legen Sie eine geeignete Möglichkeit (Skript, Export, …) bei, Ihre Datenbank wiederherzustellen.

# 10 Allgemeines

- [ ] Ich habe die Rechtschreibung überprüft
- [ ] Ich habe überprüft, dass die Nummerierung von Testfällen und User Stories übereinstimmen
- [ ] Ich habe alle mit ✍️ markierten Teile ersetzt
