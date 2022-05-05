# **Markdown**

Markdown ist eine vereinfachte Auszeichnungssprache, die von John Gruber und Aaron Swartz entworfen und im Dezember 2004 mit Version 1.0.1 spezifiziert wurde. Ein Ziel von Markdown ist eine leicht lesbare Ausgangsform bereits vor der Konvertierung. Als Auszeichnungselemente wurden daher vor allem Auszeichnungsarten verwendet, die in Plain text und E-Mails üblich sind. Auch andere Auszeichnungssprachen mit ähnlichen Zielen zur Lesbarkeit – wie reStructuredText oder Textile – hatten Einfluss auf die Syntax. Der MIME-Type lautet text/markdown.

Eine Markdown-Konvertierungssoftware wandelt Text in gültiges und W3C-konformes XHTML um. Die Referenzimplementierung in Perl steht unter einer BSD-artigen Lizenz. Inzwischen sind Implementierungen in den gängigsten Programmiersprachen wie PHP, Python oder JavaScript sowie R verfügbar.

## **Verbreitung**

Genutzt wird Markdown oder eine Markdown-ähnliche Syntax vorwiegend auf Entwicklerplattformen mit eher technikaffinem Publikum wie GitHub, Stack Overflow oder der Blogging-Plattform Ghost. Markdown wird häufig bei Readme-Dateien verwendet. Es kommt auch in populären webbasierten Tools wie der Projektmanagementsoftware Trello oder dem Instant-Messaging-Dienst Slack zum Einsatz.

Die meisten größeren Content-Management-Systeme, Wikis und Foren lassen sich durch Plug-ins um Markdown-Unterstützung erweitern. Es gibt Plugins für WordPress, Joomla oder MediaWiki. Auch Flat-File-Content-Management-Systeme wie Kirby setzen fast durchweg auf Markdown als Auszeichnungssprache. Viele statische Webseiten-Generatoren (static site generators, wie Jekyll, Hugo oder Hexo) nutzen Markdown als Auszeichnungssprache für den Inhalt. Markdown wird auch in anderer Software genutzt, z. B. im Software-Dokumentationswerkzeug Doxygen.

Es gibt viele Editoren für Markdown, die meist auch sofort ein HTML-Preview erzeugen – in einem zweiten Screen oder gleich im gerade editierten Text.

### **Auszeichnungsbeispiele**

Für die Auszeichnung von Text verwendet Markdown vor allem Satzzeichen und gestattet in einigen Fällen mehrere gleichwertige Methoden. Zeichen, die für gewöhnlich als Formatbefehle verstanden werden, können mit einem umgekehrten Schrägstrich (Backslash \) maskiert werden.

Autoren können bei Bedarf für komplexere Auszeichnungen XHTML-Blockelemente verwenden. Diese Elemente werden von der Konvertierungssoftware ohne Änderung in das Zieldokument übernommen. Dadurch ist es möglich, Bereiche des Dokuments in gewöhnlichem XHTML zu formatieren.


#### **Textgestaltung**

Absatz:
Erster Absatz.

Zweiter Absatz.

Kursiver Text:
*Kursiv*

Fetter Text_
**Fett**

Fetter & kursiver Text:
Fett kursiv

Alternative Schreibweisen für kursiv, fett und fett & kursiv:


Inline-Quelltext:
Der Command `ls` listet den inhalt eines Verzeichnisses auf.

## **Code-Block:**
```
const express = require('express')
const app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```

## **Ungeordnete Liste:**
+ Ein Punkt in einer ungeordneten Liste
+ Ein weiterer Punkt in einer ungeordneten Liste
+ Ein Unterpunkt, um vier Leerzeichen eingerück
     - Ein Unterpunkt, um vier Leerzeichen eingerückt
        - Ein Unterpunkt, um vier Leerzeichen eingerückt
        - Ein Unterpunkt, um vier Leerzeichen eingerückt
        - Test


## **Alternative Schreibweise für ungeordnete Listen:**

- Minus
+ plus
* Sternchen 

## **Geordnete Liste:**

1. Erster Punkt in einer geordneten Liste
2. Zweiter Punkt in einer geordneten Liste
3. Dritter Punkt in einer geordneten Liste

Überschriften:
# Überschrift in Ebene 1
## Überschrift in Ebene 2
### Überschrift in Ebene 3
#### Überschrift in Ebene 4
#### Überschrift in Ebene 5
##### Überschrift in Ebene 6

Alternative Schreibweise für Überschriften:

Überschrift in Ebene 1
============
Überschrift in Ebene 2
----------------------

##**Zitatblock:**

Dieses Zitat wird in ein HTML-Blockquote-Element gepackt.

>hello
>
>Monsif what a good weather **today**
>
>good things happing in good **time**
>
>weater

Horizontale Linie:

---------------------

Link:
[ LINk HERE ](https://www.markdownguide.org "Markdown")

Bild:
![Editor Pictur](https://images.unsplash.com/photo-1461749280684-dccba630e2f6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2338&q=80 "COD Pictur Wraap Wraaap ")









