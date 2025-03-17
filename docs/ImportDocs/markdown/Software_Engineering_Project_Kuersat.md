# Software Engineering Project
* Ticketverwaltung
  --> ich habe (wie auch durch einigen Tickets zu erkennen ist (Siehe Tickets in Review)) Aufgaben bzw. Reviews verteilt 
* Retroperspektiv als Teilnehmer teilgenommen
  - Kritische Reflektion über das Projekt
  - Aspekte der Reflektion wurde in Gruppe besprochen
* Kundenreview teilgenommen / vorgestellt
* Teilnahme am Weekly
  - Ticketverteilung
  - Besprechung des Fortschritts
## Selbstbearbeitete Tickets

Ticket [#2](https://github.com/SEPMFWS422A/time2meet/issues/2)
**Ziel:**  
- Kanbanboard für Ticket-Übersicht erstellt  
- Siehe [Link](https://github.com/orgs/SEPMFWS422A/projects/1)


Ticket [#57](https://github.com/SEPMFWS422A/time2meet/issues/57)
**Ziel:**  
- Profilsettings-Seite fürs MVP erstellen  
- Enthaltene Eigenschaften:  
  - Profilbild  
  - Vorname  
  - Nachname  
  - Benutzername  
  - E-Mail-Adresse  
  - Telefonnummer  
  - Geburtsdatum  
  - Profil-Sichtbarkeit  
  - Kalender-Sichtbarkeit  
  - Theme  
  - Möglichkeit, Passwort zu ändern  
- Alle Commits unten bilden das Ziel ab  

**Commits:**

[6846749](https://github.com/SEPMFWS422A/time2meet/commit/6846749565f80d9859540134e062e5edecd4e5a9):  <br/>
  - Initiale Erstellung der Profilsettings-Komponente  
  - Hinzufügen der Route  
  - Einpflegung der Route in die Navbar

[a96e603](https://github.com/SEPMFWS422A/time2meet/commit/a96e60390ba904c2aae3cb3063cee0287a0738e6): <br/> 
  - Anpassung des Paddings von globaler Ebene auf Seitenebene  

[eb5356f](https://github.com/SEPMFWS422A/time2meet/commit/eb5356f8146c585dff6960b1b3d4999eff1c5160):  <br/>
  - Unnötige Kommentare entfernt  
  - Einzelne HTML-Komponenten mit IDs versehen (für Tests)  

[f49a029](https://github.com/SEPMFWS422A/time2meet/commit/f49a029b0264e5043eceaa30249097fb25f13c6d):  <br/>
  - Einbindung der Navbar in die Profilsettings-Komponente  

[83df405](https://github.com/SEPMFWS422A/time2meet/commit/83df405b9864fc240ba13f86fddff98edb5b0c57):  <br/>
  - Validierungen für Profilsettings eingebaut (Profilbild, Geburtsjahr)  

[10689fb](https://github.com/SEPMFWS422A/time2meet/commit/10689fb712d20a79fe2f8743cb82ff651665d47b): <br/> 
  - Anpassung der E-Mail-Anzeige  


Ticket [#98](https://github.com/SEPMFWS422A/time2meet/issues/98) & Ticket [#58](https://github.com/SEPMFWS422A/time2meet/issues/58)
_Ticket #58 wurde im Ticket #98 mitbearbeitet_

**Ziel:**  
- APIs für User erstellen:  
  - User erstellen  
  - User bearbeiten  
  - User löschen  
- Anbindung ans Profilsetting (Ticket #58)  
- Alle Commits unten bilden das Ziel ab

**Commits:**

[faa5c59](https://github.com/SEPMFWS422A/time2meet/commit/faa5c596f58fd4f1ba3f31b955aeb439ee714512):<br/>
  - Installation von axios
  - Initiale Erstellung der APIs für User
  - Anbindung der User APIs in Profilsetting

[e1cb7bb](https://github.com/SEPMFWS422A/time2meet/commit/e1cb7bb73237cc5ddd20f812406e2f34f64b3195):<br/>
  - Das hinzufügen des Decode fürs entschlüssen des Tokens
  - Anpassung des API Strukturs

[e9c68b6](https://github.com/SEPMFWS422A/time2meet/commit/e9c68b68eec2bff8db24fb317ea255e416339cf4):<br/>
  - Anpassung am API und der Struktur

[9e5fe56](https://github.com/SEPMFWS422A/time2meet/commit/9e5fe56be508fa6551b93347830b4941484c0dae):<br/>
  - Verbesserungsvorschlag vom Review übernommen


Ticket [#108](https://github.com/SEPMFWS422A/time2meet/issues/108) & Ticket [#126](https://github.com/SEPMFWS422A/time2meet/issues/126)
_Ticket #126 wurde im Ticket #108 mitbearbeitet, Commit mit Verbesserung wurde in Ticket #126 committet_

**Ziel:**  
- APIs für Freunde schreiben:  
  - Freunde hinzufügen  
  - Freunde entfernen  
  - Freunde favorisieren  
- Anbindung an Friendlist (Ticket #126)  
- Alle Commits unten bilden das Ziel ab

**Commits:**

[d31e4e9](https://github.com/SEPMFWS422A/time2meet/commit/d31e4e9bbe5b22706c6b1c067cacff81b1b5bae9):<br/>
  - Initiale hinzufügen vom Freundes API (get anfrage)
  - Initiale Anbindung ans Friendlist

[ec879ca](https://github.com/SEPMFWS422A/time2meet/commit/ec879cacb8bf27094d867a2c99543a7ea49d147f):<br/>
  - weitere API anbindungen search => user; remove => Remove Friend; add => Add Friend
  - API Struktur angepasst
  - Weitere Komponente erstellt für die suche von Benutzer (direkte anbindung an search api)
  - Friendlist angepasst, das diese sich dynamisch anpasst

[e69fd7f](https://github.com/SEPMFWS422A/time2meet/commit/e69fd7f6b77ac339861287efc557f49f7b19b0df) & [2565c55](https://github.com/SEPMFWS422A/time2meet/commit/2565c55f415fa131c2388f386c079797d33e5ffd):<br/>
  - Kleine Anpassungen am Code vorgenommen (Performenz & Warning entfernt)

[2565c55](https://github.com/SEPMFWS422A/time2meet/commit/2565c55f415fa131c2388f386c079797d33e5ffd):<br/>
  - Entfernen von Warnings

Ticket [#118](https://github.com/SEPMFWS422A/time2meet/issues/118)
**Ziel:**  
- Nach Fertigstellung des Logins:  
  - Sign Up Button aus der Navbar entfernen  
- Commit in der Tabelle bildet das Ziel ab

**Commits:** <br/>
[f1558b4](https://github.com/SEPMFWS422A/time2meet/commit/f1558b46d84ee81adeb9b56a119c36e6c59880c2): <br/>
  - Sign Up Button entfernt


Ticket [#129](https://github.com/SEPMFWS422A/time2meet/issues/129)
**Ziel:**  
- Ursprünglich war geplant, dass für die Umfrageseite zwei APIs hinzugefügt werden sollen:  
  - Eine API für alle Umfragen, bei denen man Creator ist  
  - Eine API für alle Umfragen, bei denen man Teilnehmer ist  

**Commits:**

[0c14c0d](https://github.com/SEPMFWS422A/time2meet/commit/0c14c0d016ee0a4fd544e1ca8e49384255c15e41): <br/> 
  - Zwei APIs erstellt  
  - API 1: Gibt Umfragen zurück, bei denen der aktuelle Benutzer Creator ist  
  - API 2: Gibt Umfragen zurück, bei denen der aktuelle Benutzer Teilnehmer ist  

[0d96967](https://github.com/SEPMFWS422A/time2meet/commit/0d96967634c9ae03f78b74f8f58e9f55d2c77bff):  <br/>
  - Nach Rücksprache mit Finn Leo Katzenberger:  
    - Nur eine API bleibt erhalten  
    - Diese filtert nach Teilnehmern  
    - Frontend filtert dann selbst nach dem Creator, bei dem der aktuelle User eingetragen ist  

[14c872b](https://github.com/SEPMFWS422A/time2meet/commit/14c872b25809254b388bad46e4ef79260035ce60):  <br/>
  - Problem: API konnte Umfragen nicht finden, da keine ObjectID gelesen werden konnte  
  - Finn Leo Katzenberger hat bei der Recherche geholfen
  - Für den Commit 50 / 50 Kürsat Darcan & Finn Leo Katzenberger

## Kollaborative Tickets

Ticket [#06](https://github.com/SEPMFWS422A/time2meet/issues/6)
**Ziel:**  
- Erster MVP von Time2Meet erstellen  
- Vorgehen:  
  - Commit: [2fa0c75](https://github.com/SEPMFWS422A/time2meet/commit/2fa0c7564e3f66fcbf1c87983a33a66bc3bda256) 
  - Nur bei diesem Commit beteiligt  
  - Mob Programming vor Ort betrieben  (Alle 16.67 %)
  - Besprochen, welche Tools und Komponenten (z. B. Kalender) verwendet werden sollen  


Ticket [#07](https://github.com/SEPMFWS422A/time2meet/issues/7)
**Ziel:**  
- Events aus dem Kalender als .ics-Datei exportieren können  
- Beteiligte: Kürsat Darcan, Timo Neuhaus (beide gleich beteiligt je 50%)  
- Vorgehen:  
  - Zum Zeitpunkt stand nur der MVP  
  - Ziel: Statische Events exportieren als .ics-Datei

**Commits**

[bd11967](https://github.com/SEPMFWS422A/time2meet/commit/bd119674b9480dc47c3962df873bc2666269fec6): <br/>
  - Initiale erstellung des ICS Download

[1a7409f](https://github.com/SEPMFWS422A/time2meet/commit/1a7409f1d3aaf11172851c854d3e9201126e6c02) & [36d2e45](https://github.com/SEPMFWS422A/time2meet/commit/36d2e4594d4d0e5d3bf6d4790ed9fe3cb8e9c3cf): <br/>
  - Kleine Anpassung der Struktur


Ticket [#21](https://github.com/SEPMFWS422A/time2meet/issues/21)
**Ziel:**  
- Die Datenbank soll mit der Anwendung verbunden werden  
- Beteiligte: Kürsat Darcan, Mohamed El Marraki, Timo Neuhaus (alle gleich beteiligt 33.3%)  
- Vorgehen:  
  - Recherche wurde von allen betrieben  
  - Pair Programming wurde verwendet, um die Datenbanken hinzuzufügen  

**Commits**

[f28372d](https://github.com/SEPMFWS422A/time2meet/commit/f28372d84a78790cbfc96963c7b554484a026ac5): <br/>
  - Initiale Erstellung der Datenbanken anbindung

[a5a44c6](https://github.com/SEPMFWS422A/time2meet/commit/a5a44c66571285d8792975fa6d080b4756a650e6): <br/>
  - Anpassung der Datenbanken verbindung

Ticket [#97](https://github.com/SEPMFWS422A/time2meet/issues/97)
**Ziel:**  
- Schema für User erstellen, das vorgibt, wie ein User aufgebaut ist  
- Beteiligte: Kürsat Darcan, Mohamed El Marraki, Timo Neuhaus (alle gleich beteiligt 33.3%)  
- Vorgehen:  
  - Im Team besprochen, welche Variablen/Parameter notwendig sind  
  - Schema entsprechend hinzugefügt  

**Commits**

[af0367e](https://github.com/SEPMFWS422A/time2meet/commit/af0367e3328deb7a150d73014db881de21615f8b): <br/>
  - Initiale Erstellung des User Schema

[649e2c8](https://github.com/SEPMFWS422A/time2meet/commit/649e2c84a5f7e765957746b3362efb1af70cbf19) & [1015f05](https://github.com/SEPMFWS422A/time2meet/commit/1015f05368055e2ece34866310ea96be8c8de79c): <br/>
  - Kleine Anpassung des User Schemas

Ticket [#99](https://github.com/SEPMFWS422A/time2meet/issues/99)
**Ziel:**  
- Schema für Events erstellen, das vorgibt, wie ein Event aufgebaut ist  
- Beteiligte: Kürsat Darcan, Mohamed El Marraki, Timo Neuhaus (alle gleich beteiligt 33.3%)  
- Vorgehen:  
  - In der Gruppe besprochen, welche Variablen/Parameter notwendig sind  
  - Schema entsprechend hinzugefügt  

**Commits**
[7f58152](https://github.com/SEPMFWS422A/time2meet/commit/7f581520ac8531e454fba992a0b7e5c50f6396b1): <br/>
  - Initiale Erstellung des Events Schema


Ticket [#101](https://github.com/SEPMFWS422A/time2meet/issues/101)

**Ziel:**  
- Schema für Umfragen erstellen, das vorgibt, wie eine Umfrage aufgebaut ist  
- Beteiligte: Kürsat Darcan, Mohamed El Marraki, Timo Neuhaus (alle gleich beteiligt 33.3%)  
- Vorgehen:  
  - In der Gruppe besprochen, welche Variablen/Parameter notwendig sind  
  - Schema entsprechend hinzugefügt  

**Commits**

[d5c7203](https://github.com/SEPMFWS422A/time2meet/commit/d5c7203a68af9c43d330606792c6a1fae2801aed): <br/>
  - Initiale Erstellung des Umfrage Schema

[0c14c0d](https://github.com/SEPMFWS422A/time2meet/commit/0c14c0d016ee0a4fd544e1ca8e49384255c15e41): <br/>
  - Kleine Anpassung des Umfrage Schemas

Ticket [#103](https://github.com/SEPMFWS422A/time2meet/issues/103)

**Ziel:**  
- Schema für Gruppen erstellen, das vorgibt, wie eine Gruppe aufgebaut ist  
- Beteiligte: Kürsat Darcan, Mohamed El Marraki, Timo Neuhaus (alle gleich beteiligt 33.3%)  
- Vorgehen:  
  - In der Gruppe besprochen, welche Variablen/Parameter notwendig sind  
  - Umsetzung durch Pair Programming  

**Commits**

[c1c8e92](https://github.com/SEPMFWS422A/time2meet/commit/c1c8e929a695689a893f470aa9587257e93325d0): <br/>
  - Initiale Erstellung der Gruppen Schema

Ticket [#124](https://github.com/SEPMFWS422A/time2meet/issues/124)

**Ziel:**  
- Bugfix: Nach Logout konnte man mit dem Zurück-Button wieder auf die Seiten zugreifen, ohne sich anzumelden  
- Beteiligte: Kürsat Darcan, Mohamed El Marraki (beide gleich beteiligt 50%)  
- Vorgehen:  
  - Recherche, wie man das Problem am besten löst  
  - Umsetzung durch gemeinsames Wissen

**Commits**

[0fd9568](https://github.com/SEPMFWS422A/time2meet/commit/0fd95687de0796ea9a0ffab097bb282463da446a): <br/>
  - Behebung des Bugs 
  - das hinzufügen des PreventBackNavigation
  - Anpassung des Middelware und Logout API