<h1> Codebuch Charles Manson </h1>

<h2> Edgelist </h2>
Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).
<table>  
<colgroup>   
    <col width="50%">  
    <col width="50%">
</colgroup>
<tr>         
    <td><b>Werte</b></td>  
    <td><b>Kommentar</b></td> 
</tr>
<tr>
    <td>
    from
    </td>
    <td>
    definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort
    </td>
</tr>
<tr>
    <td>
    to
    </td>
    <td>
 	  definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 
    </td>
</tr>
<tr>
    <td>
    relationship
    </td>
    <td>
Definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten. Wenn zwei Arten der Beziehung bestehen werden auch zwei Einträge gemacht.
    </td>
</tr>
<tr>
    <td>
    relationship
    </td>
    <td>
Definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten. Wenn zwei Arten der Beziehung bestehen werden auch zwei Einträge gemacht.
   1 = Bekanntschaft, 2 = Freundschaft, 3 = Abneigung, 4 = Familie, 5 = Liebe/Ehe, 6 = Tötungsbeziehung (A hat B ermordet), 7 = versuchte Tötung (A hat versucht B zu ermorden)"
   </td>
</tr>
<tr>
    <td>
    weight
    </td>
    <td>
	Ausprägung der Kantenstärke (Beziehungsstärke), definiert nach vorgegeben Skalen. Skala 1-3 schwach bis stark 
   </td>
</tr>
<tr>
    <td>
    year_beginning
    </td>
    <td>
	Jahr der Bekanntschaft (bzw. Art der relationship) um nach vor/nach Haft filtern zu können
   </td>
</tr>
<tr>
    <td>
    year_end
    </td>
    <td>
	Jahr ENDE der Bekanntschaft (bzw. Art der relationship) um nach vor/nach Haft filtern zu können und Dauer zu bestimmen
   </td>
</tr>
</table>






<h2> Nodelist </h2>
Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.

<table>  
<colgroup>   
    <col width="50%">  
    <col width="50%">
</colgroup>
<tr>         
    <td><b>Werte</b></td>  
    <td><b>Kommentar</b></td> 
</tr>
<tr>
    <td>
    id	
    </td>
    <td>
    eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  
    </td>
</tr>
<tr>
    <td>
    name
    </td>
    <td>
	Name oder Bezeichnung des Knotens. 
    </td>
</tr>
<tr>
    <td>
    type
    </td>
    <td>
	1 = Mensch, 2 = Gruppierung
    </td>
</tr>
<tr>
    <td>
    sex
    </td>
    <td>
		Dichotome Ausprägung: male oder female. Einfacher auch numerisch als 1 = männlich oder 2 =  weiblich zu kodieren.
   </td>
</tr>
<tr>
    <td>
    date_of_birth
    </td>
    <td>
	DD-MM-YYYY
   </td>
</tr>
<tr>
    <td>
    date_of_death
    </td>
    <td>
	DD-MM-YYYY
   </td>
</tr>
<tr>
    <td>
    type_of_death
    </td>
    <td>
	1 = lebend, 2 = natürlicher Tod , 3 = ermordet, 4 = Selbstmord, 5 = Verschwunden, genaueres unbekannt    </td>
</tr>
<tr>
    <td>
    power
    </td>
    <td>
	definiert als Macht des Akteurs (1 = sehr gering, 5 = sehr hoch)
</tr>
<tr>
    <td>
    relation_to_murder
    </td>
    <td>
	1 = hat niemanden getötet, 2 = war bei Mord anwesend, 3 = hat jemanden getötet
</tr>
<tr>
    <td>
    member
    </td>
    <td>
	Manson Family Member, 1 = Nein, 2 = Ja
</tr>
</table>

	
<b>99	definiert fehlende Werte</b>
