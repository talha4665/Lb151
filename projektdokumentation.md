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
| 1    |     	Muss            | 	Funktional     | Als ein Benutzer möchte ich mich anmelden können, damit ich mein High-Score sehen kann  |
Als Administrator möchte ich mich mit meinem Benutzernamen und Passwort authentifizieren können, um meine Administratortätigkeiten ausführen zu können.

Als Administrator möchte ich Phrasen und Rätselwörter anlegen, ändern und löschen können, damit ich das Spiel aktualisieren und verwalten kann.

Als Administrator möchte ich Kategorien anlegen und jedes Wort bzw. jede Frage einer Kategorie zuordnen können, damit das Spiel strukturiert und übersichtlich bleibt.

Als Administrator möchte ich in der Lage sein, einzelne Einträge der Highscore-Liste zu löschen, damit ich diese bei Bedarf aktualisieren kann.

Als Spieler möchte ich einen Namen eingeben können, der auf der Highscore-Liste erscheint, um meine Leistungen in der Liste anzeigen zu können.

Als Spieler möchte ich zu jeder Zeit den Kontostand und die Lebenspunkte sehen können, um meine Fortschritte im Spiel zu überwachen.

Als Spieler möchte ich informiert werden, ob meine gewählte Antwort richtig oder falsch war, um mein Wissen zu verbessern.

Als Spieler möchte ich in der Highscore-Liste den Rang, den Namen des Spielers, den Zeitpunkt des Spiels, den Geldbetrag und die Anzahl der Spielrunden sehen, um meine Leistungen mit anderen Spielern vergleichen zu können.

Als Spieler möchte ich sicherstellen, dass kein Rätsel-Wort und keine Phrase mehr als einmal gestellt wird, um das Spiel fair zu gestalten.
✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc. oder Zahl), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). 

# 4.2 Testfälle

| TC-№ | Vorbereitung | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |              |         |                   |
| ...  |              |         |                   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

# 5 Prototyp

✍️ Erstellen Sie Prototypen für das GUI (Admin-Interface und Quiz-Seite).

# 6 Implementation

✍️ Halten Sie fest, wann Sie welche User Story bearbeitet haben

| User Story | Datum | Beschreibung |
| ---------- | ----- | ------------ |
| ...        |       |              |

# 7 Projektdokumentation

| US-№ | Erledigt? | Entsprechende Code-Dateien oder Erklärung |
| ---- | --------- | ----------------------------------------- |
| 1    | ja / nein |                                           |
| ...  |           |                                           |

# 8 Testprotokoll

✍️ Fügen Sie hier den Link zu dem Video ein, welches den Testdurchlauf dokumentiert.

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

# 9 `README.md`

✍️ Beschreiben Sie ausführlich in einer README.md, wie Ihre Applikation gestartet und ausgeführt wird. Legen Sie eine geeignete Möglichkeit (Skript, Export, …) bei, Ihre Datenbank wiederherzustellen.

# 10 Allgemeines

- [ ] Ich habe die Rechtschreibung überprüft
- [ ] Ich habe überprüft, dass die Nummerierung von Testfällen und User Stories übereinstimmen
- [ ] Ich habe alle mit ✍️ markierten Teile ersetzt
