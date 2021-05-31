# Asset Browser

![Assetbrowser](/img/Manager/AssetBrowser_2.PNG)

***

Zur besseren Übersicht sind die Bereiche oben farbig umrandet. Der *Asset Browser* ist wie folgt aufgebaut:


* Links befindet sich die Ordnerstruktur. Diese ist vertikal zweigeteilt. Oben sieht man den Projektordner, in dem der Asset Browser geöffnet ist, der sog. **Current Folder**. Darunter sieht man die allgemeine Ordnerstruktur, die nach den eigenen Wünschen angepasst werden kann. Hier wählt Sie aus, wo die Datei gespeichert werden soll. Neue Ordner können hier angelegt werden, um eine eigene Struktur aufzubauen. Darunter ist das sog. **Repository** zu sehen. Dabei handelt es sich um ein Verzeichniss, in dem Dateien liegen, die über andere Sessions hinaus verwendet werden können.

* In der Mitte sieht man das Hauptfenster. Hier werden die Dateien des ausgewählten Ordners aufgelistet. 

* Im Inspektor Fenster auf der rechten Seite, werden aktuelle Attribute einer ausgewählten Datei angezeigt. Zusätzlich dazu wird eine Miniaturvorschau in Form eines Icons oder eines Thumbnails bereitgestellt. Bei Videos ist es zudem möglich über einen Slider eine Stelle des Videos als Thumbnail auszuwählen.

***
Der *Asset Browser* öffnet sich an allen Stellen im *Session Manager*, an denen Sie auf den Button mit der Beschriftung 'Browse' klicken. Der *Asset Browser* verhält sich konsistent und ist kontextbezogen. Das bedeutet zum einen, dass der *Asset Browser* automatisch nach entsprechenden Dateien filtert. Möchte Sie zum Beispiel ein Video im Modul 'Video' laden, so werden auch nur Videodateien angezeigt. Entsprechend werden keine Bild- oder Audiodateien angezeigt. Zum anderen zeigt der *Asset Browser* an, wo er geöffnet wurde. Öffnen Sie ihn beim Bearbeiten einer *Toolbox*, so befindet sich der *Asset Browser* innerhalb dieser Ebene. Der Name der aktuellen Bearbeitungsebene (*Toolbox*, *Session*, *Style* oder *Team*) wird links in der Ordnerstruktur angezeigt. Oben im Bild sieht man, das 'New Session' geöffnet ist, entprechend ist unter **Current Folder** ebenfalls 'New Session' als übergeordnetes Verzeichnis zu sehen. Das ist sozusagen der Dateienpool speziell für diese Session.

Verknüpfen Sie ein Asset aus den Ordnern 'Public' oder 'User' im Verzeichnis **Repository**, ändert sich der Button 'Select File', unten rechts im Asset Browser zu 'Add & Select File'. Das hat den Hintergrund, dass hier lediglich eine Referenz erzeugt wird! Die Ordner 'Public' und 'User' sind dafür gedacht allgemein zugängliche Daten wie bspw. einen Imagefilm verfügbar zu halten. Daten aus diesen Ordnern werden also nicht in eine Session importiert. Für den Fall jedoch, dass ein Original später im 'Public' Ordner gelöscht werden sollte, bleibt das zugewiesene Asset in einer *Session, Toolbox, Style* davon unberührt!

**Hinweis:** Der Assetsbrowser unterstützt eine maximale Dateiengröße von 2 GB!

<!---
![AessetBrowserVerzeichnisse](../img/Manager/Gifs/Assetbrowser_AddAndSelect.gif)
--->

<div class="row post-image-bg" markdown="1">
    <video width="99%" height="540" autoplay loop muted markdown="1">
        <source src="../img/Manager/Gifs/Assetbrowser_AddAndSelect.webm" type="video/webm" markdown="1">
    </video>
</div>
