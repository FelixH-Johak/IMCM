# IMCM - 3BHK

## Einleitung

### Markdown

*Markdown* ist eine auszeichnungssprache (*Markup Language*). Mit Auszeichnungssprachen werden Texte strukturiert. Einige Markup Languages sind z.b:
 
 - HTML (*Hypertext Markup Language*)
 - XML (*Extensible Markup Language*)
 - MD (*Markdown*)
 - YAML (*Yet another Markup Language*)

 Markdown ist heutzutage eine der beliebtesten Auszeichnungssprachen. Wenn eine README.md-Datei in einem Github-Repository vorhanden ist, wird sie automatisch auf der Hauptseite des Repositories angezeigt. Die README.md-Datei ist also die erste Anlaufstelle für Informationen über das Projekt.

 Um ein Github-Repository zu erstellen, sind folgende Schritte notwendig:

 - Im gewünschten Verzeichneis im Terminal (*bzw. Command Line Interface*)den Befehl `git init` ausführen.

>**Einschub zur Installation von Git:** Falls es bei der Eingabe von `git init` eine Fehlermeldung: *"Command not found"* erscheint, ist Git wahrscheinlich nicht installiert und der Befehl wird nicht erkannt. Bei der Installation wurd der Befehl der Umgebungsvariable `PATH` hinzugefügt. Darin sind die Bezeichnungen aller Programme enthalten, die vom Terminal aus aufgerufen werden können.

 - dann in GitHub-Desktop das lokale Repository hinzufügen. (*File > Add Local Repository*)
 - nun kann über die Schaltflächen **Commit to main** und **Push origin**   der aktuelle Veränderungen der Dateien ins Repository hochgeladen werden.



 ## Statische und Dynamische Websites

In den 1990er Jahren wurden Websites überwiegend statisch erstellt. Inhalte wurden als html-files auf einen Webserver hochgeladen. Bei jedem Aufruf der Website wurde das `html-file` dupliziert, unabhängig davon, wer die Seite besuchte. Solche Websites werden als statische Websites bezeichnet.

 ![alt text](image.png)
 

 Die Abbildung zeigt, die Funktionsweise von statischen Websites. Zuerst muss der Domain-Name über das Domain Name System (DNS) in die IP-Adresse des Webservers aufgelöst werden (Schritt 1 und 2 in der Abbildung dargestellt).  Danach schickt der Client eine https-Anfrage an den entsprechenden Webserver und erhält von diesem eine http-Antwort, die überlicherweise zuerst die `index.htm`  enthält (Schritt 3 und 4)

Ab den 2000er jahren setzten sich zunehmend dynamische Websites durch. Bei dynamischen Websites wird der Inhalt nicht mehr als statisches `html-file` auf dem Webserver gespeichert, sondern bei jedem Aufruf der Website dynamisch generiert. Dies ermöglicht personalisierte Inhalte und Interaktionen mit Datenbanken.

Der Ablauf der Seitenerstellung ist in der folgenden Abbildung dargestellt. Die URL-Auflösung mittels DNS-Anfrage funktioniert gleich wie bei statischen Websites (lila in der Grafik). Der Webserver braucht bei dynamischen Websites aber Unterstüzung durch eine serverseitige Programmier- bzw. Skriptsprache.

![alt text](image-3.png)