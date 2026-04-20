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

**primary genre**  
definiert das primäre Genre des Lieds, beziehungsweise Albums:
1=Rock
2=Country
3=Pop
4=Soul
5=Contemporary
6=Mainstream
7=Alternative
8=Indie
9=Rap

**secondary genre**  
definiert das sekundäre Genre des Lieds, beziehungsweise Albums:
1=Rock
2=Country
3=Pop
4=Soul
5=Contemporary
6=Mainstream
7=Alternative
8=Indie
9=Rap

**year of publishing**
definiert das Jahr der Veröffentlichung des Albums

**first grammy category**
definiert die Grammy-Kategorie, in der gewonnen wurde
1=Album Of The Year
2=Best Rock Album; Rock Album
3=Best Country Album;Best Country & Western Album
4=Best Pop Vocal Album; Pop Vocal Album
5=Best Contemporary Folk Album
6=Best Historical Album
7=Best Alternative Music Album
8=Best Urban Contemporary Album

**second grammy category**
definiert die weitere Grammy-Kategorie, in der gewonnen wurde
1=Album Of The Year
2=Best Rock Album; Rock Album
3=Best Country Album;Best Country & Western Album
4=Best Pop Vocal Album; Pop Vocal Album
5=Best Contemporary Folk Album
6=Best Historical Album
7=Best Alternative Music Album
8=Best Urban Contemporary Album

**grammy year**
definiert das Jahr der Grammy-Auszeichnung

**number of grammys per album**
definiert die Anzahl der Grammys für ein Album (wenn ein Album in mehreren Kategorien gewonnen hat)

**grammy nomination number (album)**
definiert die Anzahl der Grammy-Nominierungen für ein Album (inklusive der gewonnen Nominierungen)

**years**
1 = Zeitraum 1965 bis 1975
2 = Zeitraum 1975 bis 1985
3 = Zeitraum 1985 bis 1995
4 = Zeitraum 1995 bis 2005
5 = Zeitraum 2005 bis 2015
6 = Zeitraum 2015 bis 2025


# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten.

**name**
Name oder Bezeichnung einer der an der Produktion betieligtne Personen (Producer oder Artist)

**grammy number (album)**
definiert die Anzahl der gewonnenen Grammys für Alben innerhalb der gesamten Karriere bis zum Zeitpunkt der Datenerhebung. Grammys für Songs etc. werden nicht erhoben.

**number of grammy nominations per album**
definiert die Anzahl der Grammy-Nominierungen für Alben innerhalb der gesamten Karriere bis zum Zeitpunkt der Datenerhebung. Grammy-Nominierungen für Songs etc. werden nicht erhoben.

**role**    
definiert die Rolle der Person als Producer oder Artist.
1 = Producer
2 = Artist

**sex**    
definiert das Geschlecht der Person. 
1 = weiblich  
2 = männlich
3 = divers
  
**year of birth***    
definiert das Geburtsjahr der Person (bei Bands: Lead Sänger*in)

**NA***    
definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus..
##










