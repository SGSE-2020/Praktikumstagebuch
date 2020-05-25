# André Matutat Projekt Tagebuch



## Woche 1 

__20.04.2020 - 26.04.2020__

| Datum | Tätigkeit       | Dauer | Zusatz |
| ----- | --------------- | ----- | ------ |
| 20.04 | Kick Off        | 0.5h |        |
| 21.04 | Teambesprechung | 1.5h |        |
|21.04| Use Case Diagramm erstellt| 0.75h ||

*Gesamt: 2.75h*

## Woche 2 

__27.04.2020 - 03.05.2020__

| Datum | Tätigkeit                                             | Dauer  | Zusatz                    |
| ----- | ----------------------------------------------------- | ------ | ------------------------- |
| 27.04 | Kurzüberblick möglicher Scala Technologien verschafft | 2h | Akka HTTP, Play Framework |
| 28.04 | Teambesprechung | 1.5h |      |

*Gesamt: 3.5h* 



## Woche 3 

__04.05.2020 - 10.05.2020__

| Datum | Tätigkeit                  | Dauer | Zusatz                                                       |
| ----- | -------------------------- | ----- | ------------------------------------------------------------ |
| 05.05 | Teambesprechung            | 1.5h  |                                                              |
| 07.05 | Spezifikation erstellt     | 3h    |                                                              |
| 08.05 | gRPC eingelesen            | 0.5h  |                                                              |
| 10.05 | Teambesprechung            | 1.5h  |                                                              |
| 10.05 | Einführung Docker bekommen | 2h    | Groben Einblick von Docker, und Docker mit VS-Code von Benedikt Struzek bekommen. |

*Gesamt 8.5h* 

## Woche 4 

__11.05.2020 - 17.05.2020__

| Datum | Tätigkeit                                 | Dauer | Zusatz                                                       |
| ----- | ----------------------------------------- | ----- | ------------------------------------------------------------ |
| 12.05 | Tieferes einlesen in Akka                 | 1h    | Evtl. gar nicht nötig bzw. gar nicht passend für die Anwendung. Frontend besser mit Scala-js. react.js (erstmal) verworfen um Anzahl der neuen Technologien zu reduzieren. Evtl. react.js später auf Scala.js aufsetzen (soll angeblich recht einfach gehen) |
| 12.05 | Anpassung Diagramme (Akka raus Scala.js rein) | 0.25h |                                                              |
| 12.05 | Teambesprechung                           | 1.5h  |                                                              |
| 13.05 | Setup VS-Code für Scala und "Hello World" | 1h    | Teilweise noch Fehler beim Kompilieren. evtl auf VM wechseln. |
| 13.05 | Issues erstellt                         | 0.5h  | Als groben Fahrplan und ToDo List |
| 14.05 | Mit Scala FunSuite  experimentiert        | 0.5h  | Ähnelt "normalen" JUnit Tests.                               |
| 15.05 | Vortrag über Play und Scala.js angesehen |1h|<https://www.youtube.com/watch?v=NJVL2IsGXZ4>|
|16.05|Scala.js Hello World aufgesetzt|1h|"Nur" Skelett mit Ausgabe auf der Konsole, noch kein UI, kein HTML|
|17.05|Scala.js Hello World mit Button aufgesetzt|1h|Per HTML. Scala Code wird zu JavaScript und kann in HTML eingebunden werden. Das Vorhandene Skelett kann als Basis für SmartMarkt genutzt werden.|

*Gesamt 7.75h* 

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

Gesamt 19.5h 


## Woche 6 

__25.05.2020 - 31.05.2020__

| Datum | Tätigkeit                                                    | Dauer | Zusatz                                                       |
| ----- | ------------------------------------------------------------ | ----- | ------------------------------------------------------------ |
|25.05|gRPC lauffähige gemacht|0.5h|Play 2.8.2 nutzt Akka 2.6.5 grpc-runtime 0.8.2 verwendet Akka 2.6.4 und ist inkompatibel mit 2.6.5 => Akka auf 2.6.4 forcieren ```libraryDependencies += "com.typesafe.akka" %% "akka-discovery" % "2.6.5"```|
|26.05|grpc und REST kombiniert|2h|Es können jetzt sowohl REST als auch gRPC Anfragen auf den selben Port gestellt  werden|
|||||
|||||
|||||
|||||




__Gesamte Zeit ca tbd Stunden__ 

