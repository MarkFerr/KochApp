# KochApp

Hallo,

Danke schonmal für's Testen/ Benutzen der App.

Wenn irgendwelche Probleme oder Fehler(wird es auf jeden fall geben) auftreten, kannst du mir einfach schreiben.

Wenn du Ideen zum Design hast kannst du sie mir auch gerne schicken.

Ich suche übrigens noch nach einem passenden Namen, also nur her mit den Vorschlägen ;).

---

- [Zu den neuen Features](#neue-features) (aktuelle Version v0.01)

---

(Sorry für alle Rechtschreibfehler)

-------

Fangen wir mit der Installation an.

Dazu musst du die aktuelle .apk Datei runterladen und deine Entwickleroptionen einschalten, dann die .apk datei öffnen.
Die App sollte sich nun installieren.

Hier noch eine kleine Anleitung dazu: https://www.wikihow.com/Install-APK-Files-from-a-PC-on-Android

---

Nun zur app selbst. Ich werde hier kurz alle Funktionen zeigen und kurz beschreiben. Du kannst natürlich auch einfach loslegen und dich in der App austoben. Es sollte alles selbsterklärend sein.

# Login, Konto erstellen, Passwort vergessen:

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Login_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/KontoErstellen_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/PasswortZuruecksetzen_270_600.png)
  
  Ich gehe mal davon aus, dass du dich schonmal irgendwo angemeldet hast. Wenn du dir ein Konto erstellst, musst du keine echte E-mail adresse verwenden, aber dann Funktioniert auch nicht die "Passwort vergessen" Funktion.

Wenn du dein Passwort vergessen hast, einfach auf den Text "Passwort vergessen" clicken, deine E-Mail-Adresse eingeben und auf eine E-Mail von Firebase warten.

---

# Wahl der Gerichtart

  ![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/gerichtart_uebersicht_270_600.png)

  Hier geht leider erst der Button "Hauptgerichte" aber die anderen werden prinzipiell genauso funktionieren, wenn sie fertig sind.
  
  Drückt man auf "Hauptgerichte" öffnet sich die Übersicht der Hauptgerichte ([Übersicht Hauptgerichte](#übersicht-hauptgerichte))
  
  Wenn man von der linken Seite des Bildschirms nach rechts wischt oder auf das Drawer-Symbol in der Ecke oben links drückt, öffnet sich das Drawer-Menü (Link zu Drawer abteil)

  ---
  
# Übersicht Hauptgerichte

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Hauptgericht_uebersicht_270_600.png)

Hier hat man die Übersicht aller erstellten Hauptgerichte. Über den "+"-Button kann man [Gerichte hinzufügen](#gericht-hinzufügen).

Man kann sich eine [Detailiertere Ansicht](#hauptgericht-im-detail) eines bestimmten Gerichts anzeigen lassen, indem man auf diese Gericht drückt.

Außerdem kann man das Bild des entsprechenden Gerichts ändern oder das Gericht löschen, indem man länger auf das Gericht drückt.

---

# Hauptgericht im Detail

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Detailansicht_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/gerichtOptionen_270_600.png)

Hier sieht man das gewählte Gericht im Detail. Man kann die Personenanzahl, für die man Kochen möchte, ändern. Entsprechend passen sich die Zutaten, die benötigt sind, an.

Drückt man auf den Button oben rechts in der Ecke, öffnet sich ein Menü. Hier kann man das Bild vom Gericht ändern, das Gericht bearbeiten, das Gericht löschen und einen Termin bestimmen, an dem man das Gericht essen möchte ([Gericht planen](#gericht-planen,-von-der-detailansicht)).

---

# Gericht planen, von der Detailansicht

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Gericht_Planen_vonDetail_270_600.png)

In diesem Fenster kann man ein Datum wählen und die Personenzahl, für die man das Gericht Plant. Drückt man auf "Set Date" wird ein Eintrag für dieses Gericht im [Kalender](#kalender) gemacht.

---

# Gericht hinzufügen

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Gericht_hinzufuegen_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/gericht_hinzufuegen2_270_600.png)


Hier muss man alle Felder nach Belieben ausfüllen, um das Gericht zu beschreiben. Ich glaube das einzige was hier erklärt werden muss, ist die letzte Eigenschaft "Privat". Wenn man dieses Häckchen setzt, sagt man, dass sonst keiner auf dieses Gericht zugreifen kann. Momentan kann das sowieso keiner, aber ich möchte noch eine art Gerichtbrowser hinzufügen, mit dem man dann Gerichte speichern kann.

Über den "+" Button kann manseine Zutaten hinzufügen und bearbeiten

![Zutaten](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Zutaten_hinzufuegen_270_600.png)
![Zutaten](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Zutaten_hinzufuegen_u_entfernen_270_600.png)

---

# Drawermenü

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Drawer_270_600.png)

Mit dem Drawermenü kann man zwischen den Hauptfunktionen der App navigieren. Das Design ist noch nicht sonderlich weit entwickelt, aber dafür funktionieren fast alle Funktionen.

Über [Gerichte](#wahl-der-gerichtart) kommt man zur Wahl der Gerichtart.

[Kalender](#kalender) öffnet den Kalender, wer hätte das gedacht.

[Einkaufsliste](#einkaufsliste) -> [Einkaufsliste](#einkaufsliste).

"Einstellungen" funktionieren noch nicht.

In späteren Versionen sieht man hier dann warscheinlich auch die Versionsnummer.

---

# Kalender

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Kalender3_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Kalender2_270_600.png)


Der Kalender ist noch etwas Fehlerbefallen aber die Grundfunktionen funktioinieren schonmal.

Die grünen Punkte Zeigen einen Eintrag an. Wählt man einen dieser Tage aus, werden einem die geplanten Gerichte für den Tag angezeigt.

Drückt man auf diese komische Einkaufswagen-Symbol werden (wie da drüber auch zu lesen ist) alle Zutaten der Ausgewählten Woche zur [Einkaufsliste](#einkaufsliste) hinzugefügt.

Mit dem "+"-Button kann man für den ausgewählten Tag ein [Gericht planen](#gericht-planen,-vom-kalender).

Man kann nicht in der Vergangenheit planen und auch nur bis zu 3 Monate in die Zukunft.

---

# Gericht planen, vom Kalender

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Kalender_planen_270_600.png)

Hier kann man die Anzahl der Leute bestimmen, für die man Kochen möchte. 

Achtung! Sobald man auf ein Gericht dürckt, wird das Gericht geplant, sofern die Vorraussetzungen stimmen. Da sollte ich vielleicht noch ein Bestätigungs-Button hinzufügen (gerne feedback dazu).

---

# Einkaufsliste

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Einkaufsliste1_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Einkaufsliste2_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Einkaufsliste3_270_600.png)

Die einkaufsliste zeigt alle benötigten Zutaten die man entweder händisch oder über den Einkaufswagen-Button in der Kalender-Ansicht hinzugefügt hat. Haben die Zutaten den gleichen Namen und die gleiche Einheit, wird die Anzahl addiert und es entstehen keine Zwei einträge.

Wählt man eine Zutat aus, wird das häckchen der Zutat gesetzt. Drückt man jetzt auf "Liste Aktualisieren" werden alle "abgehakten" Zutaten entfernt.

Achtung! Man darf nicht direkt auf die Box drücken, sonst funktioniert das mit dem löschen irgendwie nicht... da bin ich noch dran.

---

So das wars dann auch endlich mit der Beschreibung.

Wie gesagt wenn irgendwas nicht geht, irgendwie besser gehen sollte, oder einfach Optisch nicht passt, schreib mir.

Viel spaß damit und ich hoffe es läuft nicht zu viel schief.

--- 

[Back to top](#kochapp)

---

# Neue Features

## "versionsnummer hier hin"

