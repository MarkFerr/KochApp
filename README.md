# KochApp

Hallo,

Danke schonmal für's Testen/ Benutzen der App.

Wenn irgendwelche Probleme oder Fehler(wird es auf jeden fall geben) auftreten, kannst du mir einfach schreiben.

Wenn du Ideen zum Design hast kannst du sie mir auch gerne schicken.

Ich suche übrigens noch nach einem passenden Namen, also nur her mit den Vorschlägen ;).

---

- [Zu den neuen Features](#neue-features) (neuste Version v0.3)

- [Login, Konto erstellen, Passwort vergessen](#login)

- [Wahl der Gerichtart](#wahl-der-gerichtart)

- [Übersicht Gerichte](#übersicht-gerichte)

- [Gericht im Detail](#gericht-im-detail)

- [Gericht planen von der Detailansicht](#gericht-planen-von-der-detailansicht)

- [Gericht hinzufügen](#gericht-hinzufügen)

- [Sortieren](#gerichte-sortieren)(v0.10)

- [Filtern](#gerichte-filtern)(v0.10)

- [Drawer](#drawer)(v0.10)

- [Kalender](#kalender)

- [Gericht planen vom Kalender](#gericht-planen-vom-kalender)

- [Einkaufsliste](#einkaufsliste)

- [Gerichtbrowser](#browser)(v0.10)

- [Benutzerprofil](#benutzerprofil)(v0.10)

---

(Sorry für alle Rechtschreibfehler)

---

Fangen wir mit der Installation an.

Dazu musst du die aktuelle .apk Datei runterladen und deine Entwickleroptionen einschalten, dann die .apk datei öffnen.
Die App sollte sich nun installieren.

Hier noch eine kleine Anleitung dazu: https://www.wikihow.com/Install-APK-Files-from-a-PC-on-Android

---

Nun zur app selbst. Ich werde hier kurz alle Funktionen zeigen und kurz beschreiben. Du kannst natürlich auch einfach loslegen und dich in der App austoben. Es sollte alles selbsterklärend sein.

# Login

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Login_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/KontoErstellen_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/PasswortZuruecksetzen_270_600.png)
  
  Ich gehe mal davon aus, dass du dich schonmal irgendwo angemeldet hast. Wenn du dir ein Konto erstellst, musst du keine echte E-mail adresse verwenden, aber dann Funktioniert auch nicht die "Passwort vergessen" Funktion.

Wenn du dein Passwort vergessen hast, einfach auf den Text "Passwort vergessen" clicken, deine E-Mail-Adresse eingeben und auf eine E-Mail von Firebase warten.

[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Wahl der Gerichtart

  ![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/gerichtart_uebersicht_270_600.png)

  Es gehen jetzt alle Gerichtarten!(v0.10)
  
  Drückt man auf "Hauptgerichte" öffnet sich die Übersicht der Hauptgerichte ([Übersicht Gerichte](#übersicht-gerichte))
  
  Wenn man von der linken Seite des Bildschirms nach rechts wischt oder auf das Drawer-Symbol in der Ecke oben links drückt, öffnet sich der [Drawer](#drawer)


[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

  ---
  
# Übersicht Gerichte

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Gerichte_mit_FIlter_und_so_270_600.png)

Hier hat man die Übersicht aller erstellten Gerichte der ausgewählten Gerichtart. Über den "+"-Button kann man [Gerichte hinzufügen](#gericht-hinzufügen).

Man kann sich eine [Detailiertere Ansicht](#hauptgericht-im-detail) eines bestimmten Gerichts anzeigen lassen, indem man auf diese Gericht drückt. Drückt im Action-Bar auf ![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/sortieren_20_20.png) 
kann man die Gerichte nach wunsch [sortieren](#gerichte-sortieren). Mit ![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/filtern_20_20.png) kann man die gerichte [filtern](#gerichte-filtern) (Das symbol wird in Zukunft warscheinlich geändert). 

Außerdem kann man das Bild des entsprechenden Gerichts ändern oder das Gericht löschen, indem man länger auf das Gericht drückt.



[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Gericht im Detail

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Detailansicht_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/gerichtOptionen_270_600.png)

Hier sieht man das gewählte Gericht im Detail. Man kann die Personenanzahl, für die man Kochen möchte, ändern. Entsprechend passen sich die Zutaten, die benötigt sind, an.

Drückt man auf den Button oben rechts in der Ecke, öffnet sich ein Menü. Hier kann man das Bild vom Gericht ändern, das Gericht bearbeiten, das Gericht löschen und einen Termin bestimmen, an dem man das Gericht essen möchte ([Gericht planen](#gericht-planen-von-der-detailansicht)).



[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Gericht planen von der Detailansicht

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Gericht_Planen_vonDetail_270_600.png)

In diesem Fenster kann man ein Datum wählen und die Personenzahl, für die man das Gericht Plant. Drückt man auf "Set Date" wird ein Eintrag für dieses Gericht im [Kalender](#kalender) gemacht.


[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Gericht hinzufügen

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Gericht_hinzufuegen_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/gericht_hinzufuegen2_270_600.png)


Hier muss man alle Felder nach Belieben ausfüllen, um das Gericht zu beschreiben. Ich glaube das einzige was hier erklärt werden muss, ist die letzte Eigenschaft "Privat". Wenn man dieses Häckchen setzt, sagt man, dass sonst keiner auf dieses Gericht zugreifen kann. Momentan kann das sowieso keiner, aber ich möchte noch eine art Gerichtbrowser hinzufügen, mit dem man dann Gerichte speichern kann.

Über den "+" Button kann manseine Zutaten hinzufügen und bearbeiten

![Zutaten](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Zutaten_hinzufuegen_270_600.png)
![Zutaten](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Zutaten_hinzufuegen_u_entfernen_270_600.png)


[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Gerichte sortieren

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/sortieren_270_600.png)

Man die Gerichte Alphabetisch sortieren oder entsprechend der Kochzeit.

Wenn du hier wünsche oder Ideen hast, wie man noch sortieren könnte, sag bescheid ;)


[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Gerichte filtern

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/filtern_270_600.png)

Hier kann man die Gerichte Filtern. Ist eigendlich alles selbsterklärend. Man kann hier auch mehrere sachen zum filtern angeben.

Wenn du hier wünsche oder Ideen hast, wie man noch filtern könnte, sag bescheid ;)



[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Drawer

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/new_drawer_270_600.png)

Unter dem Benutzernamen und der Email-Adresse sieht man den Downloadcounter. Dieser Zeigt an, wie viele seiner Gerichte aus dem Browser gespeichert wurden.

Mit dem Drawermenü kann man zwischen den Hauptfunktionen der App navigieren. Das Design ist noch nicht sonderlich weit entwickelt, aber dafür funktionieren fast alle Funktionen.

- Über [Gerichte](#wahl-der-gerichtart) kommt man zur Wahl der Gerichtart.

- [Kalender](#kalender) öffnet den Kalender, wer hätte das gedacht.

- [Einkaufsliste](#einkaufsliste) -> [Einkaufsliste](#einkaufsliste).

- [Browser](#browser)

- [Profil](#benutzerprofil)

- "Einstellungen" funktionieren noch nicht.

Unten sieht man die Aktuelle Versionsnummer.


[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Kalender

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Kalender3_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Kalender2_270_600.png)


Der Kalender ist noch etwas Fehlerbefallen aber die Grundfunktionen funktioinieren schonmal.

Die grünen Punkte Zeigen einen Eintrag an. Wählt man einen dieser Tage aus, werden einem die geplanten Gerichte für den Tag angezeigt.

Drückt man auf diese komische Einkaufswagen-Symbol werden (wie da drüber auch zu lesen ist) alle Zutaten der Ausgewählten Woche zur [Einkaufsliste](#einkaufsliste) hinzugefügt.

Mit dem "+"-Button kann man für den ausgewählten Tag ein [Gericht planen](#gericht-planen-vom-kalender).

Man kann nicht in der Vergangenheit planen und auch nur bis zu 3 Monate in die Zukunft.


[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Gericht planen vom Kalender

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Kalender_planen_270_600.png)

Hier kann man die Anzahl der Leute bestimmen, für die man Kochen möchte. 

Achtung! Sobald man auf ein Gericht dürckt, wird das Gericht geplant, sofern die Vorraussetzungen stimmen. Da sollte ich vielleicht noch ein Bestätigungs-Button hinzufügen (gerne feedback dazu).


[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Einkaufsliste

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Einkaufsliste1_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Einkaufsliste2_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/Einkaufsliste3_270_600.png)

Die einkaufsliste zeigt alle benötigten Zutaten die man entweder händisch oder über den Einkaufswagen-Button in der Kalender-Ansicht hinzugefügt hat. Haben die Zutaten den gleichen Namen und die gleiche Einheit, wird die Anzahl addiert und es entstehen keine Zwei einträge.

Wählt man eine Zutat aus, wird das häckchen der Zutat gesetzt. Drückt man jetzt auf "Liste Aktualisieren" werden alle "abgehakten" Zutaten entfernt.

Achtung! Man darf nicht direkt auf die Box drücken, sonst funktioniert das mit dem löschen irgendwie nicht... da bin ich noch dran.


[Zu den neuen Features](#neue-features)

[Back to top](#kochapp)

---

# Browser

## Übersicht

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/browser1_270_600.png)

Hier kann man wie bei der Wahl der Gerichtart, die Art des Gerichtes angeben, wonach man suchen möchte. Man kann auch "alles Durchsuchen".

## Gerichte

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/browser4_270_600.png)

Hier kann man wie in der Übersicht der Gerichte ein bestimmtes gericht auswählen, um es im Detail zu betrachten. Man kann auch die Gerichte [filtern](#gerichte-filtern) oder [sortieren](#gerichte-sortieren)

## Gericht im Detail

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/browser2_270_600.png)
![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/browser3_270_600.png)

Schaut man sich ein Gericht im Detail an kann man es zu seinen Gerichten hinzufügen. Dazu muss man einfach auf den Button Unten-Rechts klicken und angeben, in welcher Kategorie man das Gericht speichern möchte.


[Zu den neuen Features](#neue-features)

[Back to Top](#kochapp)

---

# Benutzerprofil

![](https://github.com/MarkFerr/KochApp/blob/main/Screenshots/profil_270_600.png)

Im Benutzerprofil sieht man seinen Benutzernamen, seine angegebene E-Mail Adresse und seinen ShareCode. Den Benutzernamen kann man ändern, in dem man auf den Button neben dem Benutzernamen drückt.

Der ShareCode gibt euch die Möglichkeit eure Gerichte,Einkaufsliste und Kalender (Kalender geht noch nicht) mit Leuten zu teilen. Wenn du also einen ShareCode erstellst, kannst du diesen an die Leute geben,
mit denen du alles Teilen möchtest geben. Diese geben den Code dann unten ein und drücken auf "ShareCode Einlesen". Jetzt sind eure Konten verbunden und ihr seht bei den Gerichten die Gerichte von allen,
die den Code eingegeben haben. Eure Einkaufsliste wurde auch verknüpft (da haben sich vielleicht noch ein paar Fehler versteckt, also am Besten erstmal genau drauf achten, ob es stimmt was da steht).


[Zu den neuen Features](#neue-features)

[Back to Top](#kochapp)

---

So das wars dann auch endlich mit der Beschreibung.

Wie gesagt wenn irgendwas nicht geht, irgendwie besser gehen sollte, oder einfach Optisch nicht passt, schreib mir.

Viel spaß damit und ich hoffe es läuft nicht zu viel schief.

--- 

[Back to top](#kochapp)

---

# Neue Features

## v0.02 Bugfix

Jetzt sollte es gehen Leon

## v0.10 BigUpdate

Es ist viel Inhalt dazu gekommen, also haben sich bestimmt auch viele Fehler eingeschlichen...

### Neuheiten:

- Restlichen Gerichte sind funktionsfähig

- [Gerichte filtern](#gerichte-filtern)

- [Gerichte sortieren](#gerichte-sortieren)

- [Gerichtbrowser](#browser)

- [Benutzerprofil](#benutzerprofil)

- ShareCode!

### Anpassungen und Fixes:

- Versionsnummer und Downloadcounter ist jetzt im [Drawer](#drawer) sichtbar

- Fehler, dass man nicht alle Zutaten gesehen hat, ist behoben

- Fehler beim Umrechnen der mengen der Zutaten, ist behoben


## v0.3 Update nach kleinem Absturz der Database

Ich bezweifle mal das das hier eh jemand lies, also schreibe ich nur kurz Was alles neu ist und dokumentiere das dann alles wenn ich mal richtig Lust drauf hab

### Neuheiten

#### Einstellungen

Man kann jetzt sachen einstellen.

- in den Präferenzen kann man sachen wie Sprache(nur Deutsch), Standard Sortiermethode der Gerichte und die Standard Personenzahl, für die man normalerweise Kocht festlegen
- Zutaten werden in Kategorien eingeteilt ( zb Äpfel in Obst und gemüse) man kann Inhalt und Reihenfolge(durch drag & drop (Speichern nicht vergessen!!)) der Kategorien in den einstellungen ändern.

#### Kategorien

- Zutaten werden in Kategorien eingeteilt
- Die einkaufsliste wird nach der Reihenfolge, die in den einstellungen eingestellt(??) ist, sortiert (komischer satz..)

#### Bekannte bugs 

Ich bin noch nicht dazu gekommen alles so richtig zum Laufen zu bekommen...

- Die Zutaten von Leuten in seiner Share-Code-Gruppe werden in der Einkaufsliste meistens doppelt angezeigt...
- Kalender ist noch etwas komisch und verwirrend ( warscheinlich auch fehlerbefallen)
- und viele mehr





