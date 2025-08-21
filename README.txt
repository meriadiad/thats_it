TODO:
	- verschiebe legacy repo auf ein branch des WS25/26 repos. 
	- consolidate versions -> one thatsit repo, different versions on branches
	- remove unnecessary images
WS 25/26 Änderungen:
	- Original in meriadiad/thats_it_ws_24_25_ss_25
	- thatsit.tex aufgeteilt in:
		- main.tex
			- Diese Datei wird kompiliert um die pdf zu erhalten. Sie bindet alle weiteren .tex Dateien ein und enthält ansonsten nur titlepage bis table of contents.
		- body.tex
			- Bindet die sections ein.
		- header.tex
			- Enthält packages, styles, new commands.
	- Ordner /nebenfaecher, /neue_texte und /text verschoben in /kapitel/.
	- Neue commands in header.tex definiert, die anstelle der Ordnernamen in .tex Dateien verwendet werden.
	- Semester-/Nebenfachbezeichnungen in den tex. Dateinamen entfernt.
