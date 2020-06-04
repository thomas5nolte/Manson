<h1> Codebuch Charles Manson </h1>

<h2> Edgelist </h2>
Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. 
<p>Bis auf die ID idealerweise numerisch codiert (als Zahl).</p>
<table>  
<tr>         
    <td><b>Werte</b></td>  
    <td><b>Kommentar</b></td> 
</tr>
<tr>
    <td>
    from
    </td>
    <td>
    Definiert den Sender in gerichteten Netzwerken.<p> Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort</p>
    </td>
</tr>
<tr>
    <td>
    to
    </td>
    <td>
 	Definiert den Empfänger in ungerichteten Netzwerken.Entspricht ID in der Nodelist.<p>Keine Sonderzeichen, etc.</p> 
    </td>
</tr>
<tr>
    <td>
    relationship
    </td>
    <td>
Definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten. <p>Wenn zwei Arten der Beziehung bestehen werden auch zwei Einträge gemacht.</p>
    </td>
</tr>
<tr>
    <td>
    relationship
    </td>
    <td>
Definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten. <p>Wenn zwei Arten der Beziehung bestehen, werden auch zwei Einträge gemacht.</p>
  <p> 1 = Bekanntschaft </p> <p> 2 = Freundschaft </p> <p>3 = Abneigung</p> <p> 4 = Familie</p> <p>5 = Liebe/Ehe</p> <p>6 = Tötungsbeziehung (A hat B ermordet)</p> <p>7 = versuchte Tötung (A hat versucht B zu ermorden)</p>
   </td>
</tr>
<tr>
    <td>
    weight
    </td>
    <td>
	Ausprägung der Kantenstärke (Beziehungsstärke), definiert nach vorgegeben Skalen. <p>Skala 1-3 schwach bis stark </p>
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
	Jahr ENDE der Bekanntschaft (bzw. Art der relationship) um nach vor/nach Haft filtern zu können und Dauer zu bestimmen.
   </td>
</tr>
</table>






<h2> Nodelist </h2>
Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. 
<p>Ausprägungen der Attribute in der Regel numerisch definieren. </p>

<table>  
<tr>         
    <td><b>Werte</b></td>  
    <td><b>Kommentar</b></td> 
</tr>
<tr>
    <td>
    id	
    </td>
    <td>
    Eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  
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
	<p>1 = Mensch</p> 2 = Gruppierung
    </td>
</tr>
<tr>
    <td>
    sex
    </td>
    <td>
    Dichotome Ausprägung: male oder female. <p>Einfacher auch numerisch als <p>1 = männlich</p> oder <p>2 =  weiblich</p> zu kodieren. </p>
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
	<p>1 = lebend</p> 
	    <p>2 = natürlicher Tod</p> 
	    <p>3 = ermordet</p> 
	    <p>4 = Selbstmord</p> 
	    <p>5 = Verschwunden</p> 
	    <p>genaueres unbekannt</p>
	</td>
</tr>
<tr>
    <td>
    power
    </td>
    <td>
	Definiert als Macht des Akteurs <p>(1 = sehr gering, 5 = sehr hoch)</p>
</tr>
<tr>
    <td>
    relation_to_murder
    </td>
    <td>
	<p>1 = hat niemanden getötet</p> <p>2 = war bei Mord anwesend</p> <p>3 = hat jemanden getötet</p>
</tr>
<tr>
    <td>
    member
    </td>
    <td>
	<p>Manson Family Member</p> 
	    <p>1 = Nein</p>  
	    <p>2 = Ja</p>
</tr>
</table>

	
<b>99	definiert fehlende Werte</b>
