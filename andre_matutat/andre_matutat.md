# André Matutat Projekt Tagebuch



## Woche 1 

__20.04.2020 - 26.04.2020__

| Datum | Tätigkeit       | Dauer | Zusatz |
| ----- | --------------- | ----- | ------ |
| 20.04 | Kick Off        | 0.5h |        |
| 21.04 | Teambesprechung | 1.5h |        |
|21.04| Use Case Diagramm erstellt| 0.75h ||

*Gesamt Woche: 2.75h*

## Woche 2 

__27.04.2020 - 03.05.2020__

| Datum | Tätigkeit                                             | Dauer  | Zusatz                    |
| ----- | ----------------------------------------------------- | ------ | ------------------------- |
| 27.04 | Kurzüberblick möglicher Scala Technologien verschafft | 2h | Akka HTTP, Play Framework |
| 28.04 | Teambesprechung | 1.5h |      |

*Gesamt Woche: 3.5h* 



## Woche 3 

__04.05.2020 - 10.05.2020__

| Datum | Tätigkeit                  | Dauer | Zusatz                                                       |
| ----- | -------------------------- | ----- | ------------------------------------------------------------ |
| 05.05 | Teambesprechung            | 1.5h  |                                                              |
| 07.05 | Spezifikation erstellt     | 3h    |                                                              |
| 08.05 | gRPC eingelesen            | 0.5h  |                                                              |
| 10.05 | Teambesprechung            | 1.5h  |                                                              |
| 10.05 | Einführung Docker bekommen | 2h    | Groben Einblick von Docker, und Docker mit VS-Code von Benedikt Struzek bekommen. |

*Gesamt Woche: 8.5h* 

## Woche 4 

__11.05.2020 - 17.05.2020__

| Datum | Tätigkeit                                 | Dauer | Zusatz                                                       |
| ----- | ----------------------------------------- | ----- | ------------------------------------------------------------ |
| 12.05 | Tieferes einlesen in Akka                 | 1h    | Evtl. gar nicht nötig bzw. gar nicht passend für die Anwendung. Frontend besser mit Scala-js. react.js (erstmal) verworfen um Anzahl der neuen Technologien zu reduzieren. Evtl. react.js später auf Scala.js aufsetzen (soll angeblich recht einfach gehen). UPDATE: Playframework läuft auf Akka |
| 12.05 | Anpassung Diagramme (Akka raus Scala.js rein) | 0.25h |                                                              |
| 12.05 | Teambesprechung                           | 1.5h  |                                                              |
| 13.05 | Setup VS-Code für Scala und "Hello World" | 1h    | Teilweise noch Fehler beim Kompilieren. evtl auf VM wechseln. |
| 13.05 | Issues erstellt                         | 0.5h  | Als groben Fahrplan und ToDo List |
| 14.05 | Mit Scala FunSuite  experimentiert        | 0.5h  | Ähnelt "normalen" JUnit Tests.                               |
| 15.05 | Vortrag über Play und Scala.js angesehen |1h|<https://www.youtube.com/watch?v=NJVL2IsGXZ4>|
|16.05|Scala.js Hello World aufgesetzt|1h|"Nur" Skelett mit Ausgabe auf der Konsole, noch kein UI, kein HTML|
|17.05|Scala.js Hello World mit Button aufgesetzt|1h|Per HTML. Scala Code wird zu JavaScript und kann in HTML eingebunden werden. Das Vorhandene Skelett kann als Basis für SmartMarkt genutzt werden.|

*Gesamt Woche: 7.75h* 

## Woche 5 

__18.05.2020 - 24.05.2020__

| Datum | Tätigkeit                                                    | Dauer | Zusatz                                                       |
| ----- | ------------------------------------------------------------ | ----- | ------------------------------------------------------------ |
| 18-05 | HTTP Requests mit Scala.js getestet. Multi Page getestet.    | 0.5h  | Sehr ähnlich zu JavaScript requests. Keine extra Bib nötig. Getestet mit openweathermap.api. Multi Page problemlos möglich. |
| 18.05 | Scala.js und JSON experimentiert                             | 1h    | Einfaches Auslesen eines JSON Attributes ohne Object-Klasse nicht möglich. |
| 18.05 | Recherchieren der Systemanforderungen für den Service        | 0.5h  |                                                              |
| 19.05 | Teambesrpechung                                              | 1.5h  |                                                              |
| 19.05 | Erstellen der Zentralen Portals mit temporären Links.        | 0.5h  | css fehlt noch                                               |
| 20.05 | Aufsetzten der HTML Grundstruktur                            | 0.25h |                                                              |
| 20.05 | Einarbeiten in Async Calls in Scala.js                       | 2h    | Stickwort: Future. Noch nicht geschafft Future mit API Calls zu verknüpfen. |
| 21.05 | Grobes UI für home und login implementiert                   | 1h    |                                                              |
| 21.05 | Getestet ob Values auch bei Seitenwechsel erhalten werden können. | 0.75h | Nein- Scala.js eignet sich nicht für MPA => Umstrukturierung der Webseite auf SPA |
| 21.05 | Frontend zu SPA umgebaut. Methoden Gerüst aufgesetzt. Navigator erstellt. |1.5h||
| 21.05 | Setup Play Framework |0.5h||
| 21.05 | Testen von GET und POST Requests mit Play |1h||
| 22.05 | Frontend Docker (mit Alexander Bergmann) |1.5h||
| 23-05 | API mit Dummy Daten erstellt und Verbindung zum Frontend hergestellt |3h||
| 24.05 | Getestet wie man Java libs in Play importiert und verwendet |0.5h||
| 24.05 | Versucht grpc (Serverseitig) aufzusetzen. |1h|Vielzahl an Versionsproblemen. Tutorials oft unvollständig, veraltet o.ä|
| 24.05 | Weiter versuche gRPC aufzusetzten |2h|Dummy Service nur mit gRPC geht. Es sollte aber auch möglich sein gRPC und HTTP in einen Play Service zu verbinden. => Stackoverflow Beitrag erstellt|
| 24.05 | .proto Datei definiert |0.5h|Noch nicht eingebunden (grpc läuft noch nicht)|

Gesamt Woche: 19.5h 


## Woche 6 

__25.05.2020 - 31.05.2020__

| Datum | Tätigkeit                                                    | Dauer | Zusatz                                                       |
| ----- | ------------------------------------------------------------ | ----- | ------------------------------------------------------------ |
|25.05|gRPC lauffähige gemacht|0.5h|Play 2.8.2 nutzt Akka 2.6.5 grpc-runtime 0.8.2 verwendet Akka 2.6.4 und ist inkompatibel mit 2.6.5 => Akka auf 2.6.4 forcieren ```libraryDependencies += "com.typesafe.akka" %% "akka-discovery" % "2.6.5"```|
|26.05|grpc und REST kombiniert|2h|Es können jetzt sowohl REST als auch gRPC Anfragen auf den selben Port gestellt  werden|
|26.05|Teambesprechung|1.5h||
|26.05|Spezifikation anpassen|1h|ERD Modell, Unstimmigkeiten behoben, veraltete Informationen aktualisiert.|
|26.05|Backend Dockerisiert|1.5h||
|27.05|Zentralesportal dockerisiert|0.25h||
|28.05|Datenbankskript erstellt und in docker-compose eingebunden|3h|Skript wird nur ausgeführt wenn der var/ Ordner im Container nicht exisitert. ggf. Container starten, rm var - r -> Container stürzt ab, neu starten -> Skript wird ausgeführt|
|29.05|Versucht im Backend Daten aus der DB abzufragen|1.5h|Connection Refused.|
|29.05|Versucht JSON-Files in Scala.js zu parsen|1h|Object -> JSON geht, JSON-> Object noch nicht.|
|29.05|Home-Page und Article-Page erstellt|3h|CSS fehlt, teilweise werden Eingaben noch nicht aktualisiert (Review, Anzahl der Artikel die gekauft werden wollen etc.)|
|29.05|Lager-Page erstellt|0.5h|CSS fehlt|
|30.05|Alle Dummy Pages erstellt|5h|Es fehlt: CSS, Abfragen an die DB, Funktionalitäten teilweise noch verbuggt|
|30.05|ein paar Funktionalitäten Implementiert, ein wenig css gemacht|1h|LogOut passt jetzt die Seite. Suchleisten filtern jetzt die Ergebnisse (dummy daten) ohne die komplette Seite neu zu laden. Buttons funktionieren jetzt auch nachdem sie neugeladen wurden.|
|31.05|Refactore Frontend-Code|1.5h||

Gesamt Woche: 24.25h 

## Woche 7 

__01.06.2020 - 07.06.2020__

| Datum | Tätigkeit                                                    | Dauer | Zusatz                                                       |
| ----- | ------------------------------------------------------------ | ----- | ------------------------------------------------------------ |
|01.06|Einkaufswagen zur HashMap umgebaut|1h||
|01.06|Fehler behoben, durch den nur die Startwerte von Textfelder o.ä gelesen wurden|1h|Um aktuelle Werte zu bekommen, DOM-Element per JQuery aufrufen.|
|02.06|Teambeasprechung|1.5h||
|02.06|Frontend Dummy fertiggestellt|1h|Alle Funktionen sind dummy artig implementiert. Dummy Daten müssen jetzt durch Anbindung an das Backend ersetzt werden|
|04.06|Versucht Integrationstest in Scala.js zu schreiben|1h|Tests können compliliert werden, werden aber nicht mit *sbt test* ausgeführt.|
|04.06|Projekt für CI vorbereitet|0.5h||
|05.06|Teambresprechung|1h||
| 06.06 | GET Anfragen an das Backend eingebunden. Ausgabe der Antwort nur auf der Shell | 1h | Die Antworten müssen noch korrekt geparsed werden. |
|07.06|Bugs beim Deployment in der Cloud behoben|2h|Backend war nicht erreichbar|
|07.06|Add bootstrap|2h|Navigations bar wird gut dargestellt. ArticleDiv versuche gescheitert.|

Gesamt Woche:  12h 

## Woche 8 

__08.06.2020 - 14.06.2020__

| Datum | Tätigkeit                                                    | Dauer | Zusatz                                                       |
| ----- | ------------------------------------------------------------ | ----- | ------------------------------------------------------------ |
| 09.06 | Teammeeting                                                  | 1.5h  |                                                              |
| 09.06 | Backend mit Datenbank verbunden                              | 3h    |                                                              |
| 09.06 | Erste Dummy Daten durch DB Abfragen ersetzt                  | 3h    |                                                              |
| 09.06 | getAllOrderAbfrage implementiert                             | 1h    | Auffrischen von SQL Befehlen                                 |
| 10.06 | Alle Schnittstellen an die DB angebunden und Fertiggestellt  | 10h   |                                                              |
| 11.06 | Versucht in Scala.js JSON mithilfe der Json lib des PlayFrameworks zu parsen | 2h    | kein erfolg                                                  |
| 11.06 | Datenbank für CI aufgesetzt                                  | 4h    | Datenbank läuft, aber es backend findet die DB nicht.        |
| 12.06 | Datenbank korrekt verbunden                                  | 2h    | Tabellen wurden nicht in der Datenbank sondern im "oberverzeichnis" erstellt. Erstellen der Tabellen wurde in das Backend ausgelagert. |
| 12.06 | Daten (endlich) im Frontend geparsed (GET Requests)          | 2h    | Mehrere Libs zusammengeflastert, mithilfe von switch case Typsicherheit hergestellt (nicht schön aber läuft) |
| 13.06 | GRPC-Client Verbindung mit Bürgerbüro hergestellt            | 4h    | Verbindung funktioniert. Die A-Synchrone Bearbeitungen noch nicht. |
| 14.06 | Username und Adresse bei Bestellungen und Reviews anzeigen |1h|Name und Adresse sind noch Dummy Daten aus den Backend, muss ersetzt werden durch die Daten vom grpc User des Bürgerbüros.|
| 14.06 | fix bug in myOrder request |1h||
| 14.06 | DB wird jetzt vollständig im Backend erstellt. Dockerfile für DB fällt weg |1h||
| 14.06 | Login Daten werden jetzt an das Bürgerbüro geschickt, um das Firebasetoken zu erhalten. |0.5h||

Gesamt Woche:  36h 


## Woche 9 

__15.06.2020 - 21.06.2020__

| Datum | Tätigkeit                                                    | Dauer | Zusatz                                                       |
| ----- | ------------------------------------------------------------ | ----- | ------------------------------------------------------------ |
| 15.06 | Bug gefixed durch den die Artikelübersicht nicht geöffnet wurden, wenn die Serachbar benutzt wurde. | 0.5h  |                                                              |
| 15.06 | POST Requests im Frontend eingebunden                        | 4h    |                                                              |
| 16.06 | Auf HTTPS umgestellt                                         | 1h    |                                                              |
| 18.06 | Überblick über ToDos verschafft, prioritäten gesetzt und entsprechend per GitHub Issues dokumentiert | 2h    | Fokus wir auf die Einbindung von Grpc Client und RabbitMQ gesetzt. Zweite Priorität liegt dann in besserer Fehlerbehandlung und Loging im Backend. Niedrigste Priorität haben Fleißarbeiten wie optimieren von Features, optimieren des UI sowie Security issues. |
| 21.06 | Fix bug in GRPC makeOrder                                    | 1h    |                                                              |

Gesamt Woche:  8.5h

## Woche 10

__22.06.2020 - 28.06.2020__

| Datum | Tätigkeit                                       | Dauer | Zusatz                                                       |
| ----- | ----------------------------------------------- | ----- | ------------------------------------------------------------ |
| 23.06 | Refactoring Backend                             | 4h    | Auslagern von DB abfragen. Ungebrauchte Routen entfernt. Hinzufügen von Documentation. |
| 23.06 | Implementierung von Fehlerbehandlung im Backend | 1h    |                                                              |
| 23.06 | Team Meating                                    | 1.5h  |                                                              |
| 28.06 | Smaller Changes                                 | 1h    |                                                              |
| 28.06 | Team Metating                                   | 1.5h  |                                                              |
| 28.06 | Implement Login with Future                     | 2h    | Noch nicht Final getestet, da Service unerreichbar           |
| 28.06 | Fix Service mit Benedikt                        | 2h    | Fehler im Proxy                                              |
| 29.06 | Kleinere Fehler beim Login behoben              | 2h    | Kamen überwiegend durch den wechsel zu richtigen UserIDs zu stande. |


Gesamt Woche:  16h

## Woche 11

__29.06.2020 - 02.07.2020__

| Datum | Tätigkeit                                              | Dauer | Zusatz |
| ----- | ------------------------------------------------------ | ----- | ------ |
| 29.06 | Fix Bugs in Frontend jsons und beim parsen von jsons   | 2h    |        |
| 29.06 | Username wird jetzt bei Review und allOrders angezeigt | 1h    |        |
| 29.06 | Fehler bei der Aktualisierung von Treupunkte behoben   | 0.5h  |        |
| 29.06 | Kleinere UI Änderungen                                       | 1h |        |
| 29.06 | Fix Login bugs                                               | 2h |        |
| 29.06 | ISBN als Secret angelegt und integriert (noch buggy)         | 0.5h |        |
| 29.06 | Bank Verbindung implementiert (noch nicht in grpc) (noch buggy) | 1h    |        |
| 30.06 | Berechnung der Summe ins Backend verlagert (noch nicht in grpc) | 0.5h  ||
| 30.06 | Bankverbindung fertiggestellt |2.5h|Finaler Test fehlt noch, da Bank noch mit Dummydaten arbeitet|
| 30.06 | Team Meeting |1.5h||
| 01.07 | Spezifikation angepasst |0.5h||
|01.07|Präsentations Vorbereitung|1h||
|01.07|Funktionalitäten üperprüft|0.5h||
| 01.07 | Story Vorstellung Besprechung                                | 2h    |                                                              |
|01.07|Präsentation Besprechung|1h||
|01.07|Präsentation überarbeitet|0.5h||
|01.07|Probleme mit der Bankverbindung gefixed|2h|Teilweise falsche Rückgabewerte erhalten, Teilweise falsche Werte übergeben|
|01.07|Service für Präsentation vorbereitet|0.5h|Dummy Daten gelöscht, Artikel erstellt etc.|
|01.07|RabbitMQ eingebaut|2h|Dummydaten als prove of concept. Nachricht kann gesendet und empfangen werden. Richtige Funktionalität noch nicht implementiert.|
|02.07|Generalprobe|1h||


Gesamt Woche:  21.5h

__Gesamte Zeit __: ca. 160 Stunden

