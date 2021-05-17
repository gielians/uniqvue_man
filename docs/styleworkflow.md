# Style Workflow


Mit den konsistenten Bedienelementen, die sich rechts außen am Dokumentenfenster befinden, kann man einfach einen Style bearbeiten, erstellen, duplizieren oder löschen. 

Zur Erinnerung noch einmal Icons und ihre Funktion: 
<ul>
<li>Der Pfeil der nach links zeigt, führt zurück in das Menü von dem aus man gestartet ist. </p></li>
</p>
<li>Der Stift ist das Symbol, um eine ausgewählten Style zu bearbeiten. </p></li>
</p>
<li>Das Dokument mit dem Pluszeichen ist zum Erstellen eines neuen Styles. </p></li>
</p>
<li>Der Dokumentenstapel darunter ist zum Duplizieren einen ausgewählten Style. </p></li>
</p>
<li>Mit dem Mülleimersymbol löscht man einen ausgewählten Style. </p></li>
</ul>
***
 

**Erstellen eines neuen Styles:**  
<!---
![StyleList](../img/Manager/Gifs/Style_Create.gif)
--->
<video width="99%" height="540" autoplay loop muted markdown="1">
    <source src="../img/Manager/Gifs/Style_Create.webm" type="video/webm" markdown="1">
</video>

Sie erstellen eine neuen Style durch Klicken auf das Dokument mit dem Pluszeichen. Mit Doppelklick auf den Namen können Sie diesen ändern. Durch Klicken auf das Stiftsymbol oder durch Klicken auf den ‘Edit Style’ Button gelangen Sie zum Style Editor. Dieser öffnet sich in einem neuen Tab mit dem Namen des zu bearbeitenden Styles. Beliebig viele Tabs also Styles können gleichzeitig geöffnet sein. Das Sternsymbol (‘*’) erscheint außerdem im Style Namen, um einen Indikator dafür zu liefern, ob ein Style noch ungespeicherte Änderungen enthält. Zu sehen sind jetzt mehrere Spalten mit verschiedenen Eigenschaften.
 ***
Der Style Editor ist in 4 Bereiche eingeteilt, die die Eigenschften der grafischen Elemente des Showrooms auflisten:
<ul>
<li> <b>Home Screen</b></p></li>
</p>
<li> <b>Agenda & Modules</b></p></li>
</p>
<li> <b>DISC & Frames</b></p></li>
</p>
<li> <b>3D Background</b></p></li>
</ul>

![Placeholder](../img/Manager/Style_Editor.PNG)

***

**Einen Style anpassen:** 

Nehmen Sie Änderungen an den Fraben, den Fonts und den Icons der einzelnen grafischen Elementen nach Belieben vor. Dabei sind die Namen der einzelnen Eigenschaften quasi selbsterklärend. Bei den Fontgrößen beudeutet 1 = maximale Skalierung. Die maximale größe ist festgelegt und kann nicht geändert werden.

**Icons verknüpfen:** 

Unter den Kategorien *Widget* und *Toolbox* lassen sich ganze Icon-Sets ändern.
Wichtig dabei ist, dass die Icons als eine Tilemap vorliegen müssen. Eine Tilemap ist eine Textur, also Bildatei in Form eines Pngs, welche in vordefinierten Schrittweiten, horizontal und vertikal eingeteilt ist. Die Textur ist also in ein Gitter eingeteilt, dessen Zellen alle gleich groß sind und jeweils die Pixelinformation eines Icons enthalten. Die hier vordefinierte Schrittweite beträgt 256 x 256 Pixel. Nur so ist gewährleistet, dass die einzelnen Texturen jedes Icons korrekt "ausgeschnitten" werden. 
Durch Klicken auf die Schaltfläche ‘Browse’ öffnet sich *Asset Browser*, um ein entsrpechendes Icon-Set auszuwählen. In Kapitel [Asset Browser](assetbrowser.md) gibt es eine detaillierte Erklärung wie dieser funktioniert. 


**Styles Speichern und benennen:** 

Ist der Style nach Ihren Wünschen angepasst muss dieser gespeichert werden. Das Sternsymbol im Tab (‘*’) zeigt Ihnen an, ob es ungespeicherte Änderungen gibt. Durch klicken auf das Diskettensymbol oder Drücken der Tastenkombination STRG + S wird der Style gespeichert. Navigieren Sie zurück in die Style List hier können Sie durch Doppelklick auf den Namen des Listeneintrags den Namen ihres Styles ändern.

**Style freigeben:** 

Der Listeneintrag eines jeden Styles enthält die Spalte ‘Released’. Durch setzen des Hakens wird der Style der Liste der verfügbaren Styles angefügt und somit zur Zuweisung zu einer Session freigegeben. In Kapitel [Session Workflow](sessionworkflow.md) wird das genauer erklärt.  


**Tipps und Tricks**

Sie können einzelne Attribute im *Style Editor* mit den Tastenkombinationen `STRG + C` und `STRG + V` in den Zwischenspeicher kopieren und wieder einfügen. Hovern Sie dafür mit der Maus über den Namen des entsprechenden Attributs.

