#KN04
## Aufgabe A 
### Einstellungen DB Instanz
<img src="/KN04/img/Aufgabe_A_Config1.png">
<img src="/KN04/img/Aufgabe_A_Config2.png">
<img src="/KN04/img/Aufgabe_A_CloudInit.png">

### Einstellungen Web instanz
<img src="/KN04/img/Aufgabe_A_Config1.png">
<img src="/KN04/img/Aufgabe_A_Config2.png">
<img src="/KN04/img/Aufgabe_A_WebCloudInit.png">

### Liste mit Details der Instanzen
<img src="/KN04/img/Aufgabe_A_InstanzenListe.png">

### Ressourcen auf der Web instanz
<img src="/KN04/img/Aufgabe_A_ApacheWebsite.png">
<img src="/KN04/img/Aufgabe_A_Info.png">
<img src="/KN04/img/Aufgabe_A_DB.png">
<img src="/KN04/img/Aufgabe_A_Adminer.png">

## Aufgabe B
S3-Buckets werden als warmer Speicher definiert. Es gibt noch andere Arten von S3-Speicher, die jedoch als kalter Speicher bezeichnet werden.

Wenn die Instanz gelöscht wird, werden auch die Dateien auf dem Volume gelöscht.

Das Volume selbst existiert noch, aber der Mount-Bind zur Instanz existiert nicht mehr. Da die Dateien auf der Instanz gelöscht wurden, ist dies auch mit den Dateien auf dem Volume geschehen. Sie können nun das Volume zu einer anderen Instanz hinzufügen und einen neuen Mount-Bind erstellen

Übersetzt mit www.DeepL.com/Translator (kostenlose Version)

### Vor und Nach Instanzlöschung
<img src="/KN04/img/Aufgabe_B_Volume1.png">
<img src="/KN04/img/Aufgabe_B_Volume2.png">

