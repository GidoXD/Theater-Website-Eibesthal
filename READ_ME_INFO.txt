Wenn ein neues Stück angelegt wird - folgende Schritte beachten!!!

Schritt: 1
	Im File "stuecke.js" die oben auskommentierte Vorlage kopieren, unterhalb einfügen und wie angeführt ausfüllen.

	"id" ist wichtig für alle Bilder, Poster und Flyer die für das Stück abgelegt werden
		Die Benennung ist wie folgt:		(Falls unklar, an vorherigen Stücken orientieren)
			Plakat/Poster	=	"id"-Plakat.jpg 
			Flyer		=	"id"-flyer.pdf 
			Bilder		=	"id"-bilder  		(Ordner mit diesem Namen anlegen und Bilder darin nummeriert ablegen 1-50 max)
 			Besetzung	=	"NAME"_"JAHR".png 	(den Namen wie in "besetzung" und das "jahr" des Stücks)
	"titel" gibt den Titel des Stücks an
	"jahr" gibt das Jahr des Stücks an und ist für die Position im Archiv und die Besetzung wichtig!
	"insta" führt zum Trailer des Stücks - hier soll der Insta-Trailer Link eingefügt werden
	"trailer" führt zum Trailer des Stücks - hier soll der YouTube-Trailer Link eingefügt werden
	"beschreibung" hier soll die Beschreibung für das Stück eingefügt werden <br> sorgt dafür das der Text auf der Website eine neue Zeile macht
		ohne Beschreibung wird die Detail-Seite des Stücks nicht aktiviert!!!
	"besetzung" hier sollen die Namen der Schauspieler und die Rolle angegeben werden (mit einem "-" getrennt)
	"termine" gibt die Termine des Stücks an (wenn ein Stück um 18 Uhr aufgeführt wird, wird es automatisch unterstrichen)
	"spielort" gibt den Spielort des Stücks an

Schritt: 2
	Im File "style.css" ganz oben die current Color wie gewollt ändern 
	(für Aktuelles Stück wichtig! - falls altes Stück hinzugefügt wird -> überspringen)
		--color-current-main: #------;
    		--color-current-sub: #------;

	und unterhalb mit den selben Farben und der passenden "id" einfügen 
	(fürs Archiv wichtig! - falls altes Stück hinzugefügt wird -> müssen nicht dieselben wie Aktuelles Stück sein)
		--color-"id"-main: #------;
   		--color-"id"-sub: #------;

Wenn ein Stück schon einmal zuvor aufgeführt wurde, muss eine andere "id" genommen werden!