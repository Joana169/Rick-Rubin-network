# Datensatz Rick Rubin #
erstellt von Diana Ginzburg, Nora Greß, Paula Mader und Joana Langhauser

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Rick Rubin | Artist | GRAMMY.com: für die Eingrenzung; Grammy-Daten
Spotify: Leider-Titel
Wikipedia für Geburtsjahre


Das Netzwerk ist ein *ungerichtetes multimodales Akteursnetzwerk*. Es werden folgende Daten erhoben:


**Umgang mit fehlgenden Werten**
Fehlende Werte werden nicht erfasst.

# EDGE-Attribute

**id**  
eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  

**from**
Name oder Bezeichnung einer der an der Produktion betieligtne Personen

**to**
Name oder Bezeichnung einer der an der Produktion betieligtne Personen

**album title**  
definiert den Album-Titel

**song title**
definiert den Songtitel des Songs aus der Zusammenarbeit

**genre**  
definiert das Genre des Lieds, beziehungsweise Albums:
1=Rock
2=Country
3=Pop
4=Soul

**year of publishing**
definiert das Jahr der Veröffentlichung des Albums

**grammy category**
definiert die Grammy-Kategorie, in der gewonnen wurde
1=Album Of The Year
2=Best Rock Album
3=Best Country Album


# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten.

**name**
Name oder Bezeichnung einer der an der Produktion betieligtne Personen

**grammy number**
definiert die Anzahl der gewonnenen Grammys innerhalb der gesamten Karriere bis zum Zeitpunkt der Datenerhebung

**sex**    
Bitte geben Sie ihr Geschlecht an:  
1 = weiblich  
2 = männlich
3 = divers
  
**year of birth***    
definiert das Geburtsjahr der Person (bei Bands: Lead Sänger*in)

**NA***    
definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus..
##
