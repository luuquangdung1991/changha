1) Die notwendige Software : 
- Für IDE kannst du gern Visual Studio ( ich benutze Visual Studio ) oder Interllij 
- Als Programmiersprache verwenden wir java  und Framework "Spring Boot"
- Lädst JDK 22 sowie Maven

2) Was wir planen : 
- Im ersten Schritt , erstellen wir eine einfache Web Anwendung mit java und Framework 
- Für die Persistierung der Daten können wir relation Datenbank wie MySQL oder PostgreSQL benutzen
- In nahen Zukunft werden wir eine pipeline aufbauen um einen laufähige JAR aufzubauen und in Artifactory zu deploy. 
Anschließend wird der neueste JAR genommen und in Docker verwendet . 
- Im Frondend Teil konzentrieren uns nur auf mobile Ansicht . Da unsere Benutzern die App meisten nur mit Handy benutzen.

3) Wir haben 2 Branches ( main und prod )
   - Bei Implementierung einer Feature bitte von main abzweigen und Branchname soll mit diesem Patter "CH-<Name der Feature>" .
   - Am Ende der Monat wird der main in prod gemergt .
   
