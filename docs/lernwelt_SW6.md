<style>
.list{
    margin-top:10px;
}
</style>



# Lernwelt Plugin SW6
## Datenbank Modell

<br>
<div>
    <img src="../docs/_images/ERM (7).png" alt="Entity relationship model" width="auto" height="auto">
</div>


## Erläuterung
#### USER Entity
<div>
    - Lernwelt User wird erstellt, wenn <a href="">Lernwelt-Code</a> eingegeben wird [Hook bei Eingabe erzeugt User entity]<br><br>
    - Eintrag des <a href="">Lernwelt-Code</a> in Datenbank.<br><br>
    - <a href="">Lernwelt-Code</a> beinhaltet Informationen (Zugangsdauer, Nutzer Gruppe).<br><br>
    - Beifügen von Informationen bei Erstellung des <a href="">Lernwelt-Code</a> (Keine Redundante Daten)<br><br>

</div>

#### LernweltContent Entity
contentTyp definiert die Art des Inhaltes
Mögliche values:

        -image (Bild)
        -video (Video)
        -audio (Audio)
        -tut (Tutortial) 
        -text (Text)
        -site (Seiten Template)


#### LernweltCategories Entity

- Diese Entität beinhaltet einen Kategorie Namen<br>
- sowie eine "restrictionGroup" zur steuerung des Zugriffs auf bestimmte Bereiche.
<a href="#/Roadmap#lernwelt-restricted-content">(Funktion für geplantes Feature).</a>


<hr>

## Nutzer UML
<div>
    <img src="../docs/_images/lernweltZugriff.png" alt="Entity relationship model" width="auto" height="auto">
</div>

