# Übersicht



*Module* treten an verschiedenen Stellen im *UNIQVUE Manager* auf. Im *Session Editor* stehen alle *Module* zur Verfügung, um eine *Agenda* zu gestalten. Der *Toolbox Editor* enthält zusätzlich zu den Modulen, die auch im *Session Editor* existieren, weitere spezielle Module, die nur über die *Toolbox* erreichbar sind. In Abschnitt [Toolboxes](007_toolbox.md) wird darauf detailliert eingegangen. 


Module unterteilen sich grundsätzlich in zwei Kategorien, *Singleview* und *Multiview*. Alle Module teilen einen Attribut: 

**Thumbnail** 
<div style="display: flex; align-items: center;">
    <img src="img/Manager/Module/Thumbnail.PNG" width="350" style="float:left; height: fit-content;">
    <div>
        <ul>
            <li><b>Thumbnail:</b> Hierüber lässt sich definieren, was für ein Icon die Darstellung des Moduls im <i>Session Editor</i> haben soll. Die Standardeinstellung ist 'Default Icon'.</li>
        </ul>
    </div>
</div>

<div style="display: flex; align-items: center;">
    <img src="img/Manager/Module/CustomThumbnail.PNG" width="350" style="float:left; height: fit-content;">
    <div>
        <ul>
            <li>Ist 'Custom Thumbnail' ausgewählt, kann über den <i>Asset Browser</i> ein eigenes Icon ausgewählt werden.</li>
        </ul>
    </div>
</div>

    
<!-- ![ThumbnailParameter](img/Manager/Module/Thumbnail.PNG)

![ThumbnailParameter](img/Manager/Module/CustomThumbnail.PNG) -->

***
 **Singleview Module** 

 <div style="display: grid; grid-template: 150px / auto auto auto; grid-gap: 10px; padding: 10px;justify-content: center;
    align-items: center;">
  <div>
	<img src="img/Manager/Module/Titel_Module.PNG" width="250">
  </div>
  <div>
	<img src="img/Manager/Module/BarChart_Module.PNG" width="250">
  </div>
   <div>
	<img src="img/Manager/Module/Browser_Module.PNG" width="250">
  </div>
   <div>
	<img src="img/Manager/Module/Bullet_List_Module.PNG" width="250">
  </div>
   <div>
	<img src="img/Manager/Module/External_Source_Module.PNG" width="250">
  </div>
   <div>
	<img src="img/Manager/Module/HTML_Module.PNG" width="250">
  </div>
   <div>
	<img src="img/Manager/Module/Pause_Module.PNG" width="250">
  </div>
   <div>
	<img src="img/Manager/Module/Share_Price_Module.PNG" width="250">
  </div>
   <div>
	<img src="img/Manager/Module/Slideshowplus_Module.PNG" width="250">
  </div>
     <div>
	<img src="img/Manager/Module/Videoplayer_Module.PNG" width="250">
  </div>
</div>

Diese *Module* nehmen maximal ein Slot eines [Slot Layouts](006_sessions.html#slot-layout-editor) ein. 


![SingleView](img/Manager/SingleviewModul.PNG)
<!-- Alle Singleview *Module* teilen dieselben grundlegenden Eigenschaften: 



   - **Background Image:** Über den *Asset Browser* wird hier ein Hintergrundbild für dieses *Modul* geladen. Das Bild belegt dann das Display bzw. den gesamten Bereich in dem das Modul platziert wurde. 



   - **Size:** Hier wird die Größe der Darstellung des Fensters angegeben. Der Standardwert ist 0.75. Der Wert 1 entspricht Fullsize. 



   - **Title:** Titelvergabe eines *Moduls*. 



   - **Showtitle:** Durch Setzen des Hakens wird dieser Titel auch im Showroom angezeigt.   -->


**Multiview Module**

 <div style="display: grid;
    grid-template: 170px / auto / auto;
    padding: 4px;
    justify-content: start;
    align-items: center;">
  <div >
	<img style="width: max-content" src="img/Manager/Module/Timeline_Module.PNG" width="250">
  </div>
  <div  >
	<img style="width: max-content" src="img/Manager/Module/Storyboardplus_Module.PNG" width="250">
  </div>
  
</div>

*Multiview Module* können maximal 3 Slots einnehmen. Das Main Modul kann um jeweils ein weiteres Modul, links und rechts vom Main Modul, erweitert werden. Die Erweiterungsmodule lassen sich über die Pfeile im Main Modul ausklappen (siehe Abbildung).
<!-- Je nach Setup des Showrooms verhalten sich die *Multiview Module* anders. Das wirkt sich hauptsächlich auf die Anordnung der Fenster aus und wird angezeigt, sobald das *Modul* in der Session per Drag and Drop platziert wird. Zudem wird in den Eigenschaften angezeigt welche Platzierungen mit Ihrem Showroom-Setup möglich sind.  -->


![SingleView](img/Manager/MultiviewModul.PNG)

***