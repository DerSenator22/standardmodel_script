# standardmodel_script
Script of the standardmodel lectures by Prof Straessner and Anja Robens


Es gibt einige Konventionen die zu beachten sind, wobei natürlich in
begründeten Fällen davon abgewichen werden kann.

## Stil des Quelltextes

* Bitte vermeide Zeilen die länger sind als *79 Zeichen*!
* Trenne Gleichungen im Quelltext mit *auskommentierten Leerzeilen* vom Rest
  ab.

  ```
  %
  \begin{equation}
  a^2+b^2=c^2
  \end{equation}
  %
  ```

* Vorlesungen werden durch einen Kommentar voneinander getrennt
  `% Vorlesung 2015-10-30`.
* Jedes Kapitel kommt in eine eigene Datei, eine Forsetzung einer Vorlesung
  wird mit `% Forts Vorlesung 2015-10-30` gekennzeichnet.

## Gestaltung des Dokuments

* Richte dich nach typographischen Regeln beispielsweise `z.\,B.` statt `z.B.`
  oder auch das entsprechende Makro `\zB`, für die imaginäre Einheit nutze
  bitte `\i` statt `i`, das gleich gilt für die Eulersche Zahl.
* Benutze *keine direkte Formatierung*, sonder nutze \name, \definiton, \emph
  oder führe entsprechende neue Makros ein.
* Tabellen*über*schriften und Bilder*unter*schriften, d.h. positioniere
  Beschriftungen ober- bzw. unterhalb.
* Nutze nur `\toprule, \midrule, \bottomrule` für Tabellen.
* Zahlen im Text werden bis zwölf normalerweise ausgeschrieben, außer es sind
  Messwerte o.ä. z.B.: vier Gleichungen aber 4×4-Matrix oder 6 TeV
* Setze Namen wie Higgs in \name{Higgs} und erstmalig Definitionen in
  \definition{Higgs-Feld}
* Zahlen und Einheiten werden mit \SI{Wert}{Einheitenbefehl, z.B. \GeV} 
  geschrieben. Einheiten mit \si{}

## Organisation

* Bitte nutze die Datei
  [who-texs-which-lecture.txt](who-texs-which-lecture.txt), um zu sehen wer
  für welche Vorlesung zuständig ist.
* Zusätzlich besteht immer auch die
  Möglichkeit, dass man wenn man gerade Lust hat direkt zu texen, dies auch
  „live“ in der Vorlesung tuen kann, dann sollte man das aber auch möglichst
  direkt nach der Vorlesung „commiten“ und „pushen“.
* Versuche bitte einigermaßen sinnvolle Commit-Kommentare zu schreiben und
  schreibe sie auf Englisch (danke an @basti :smile:) oder Deutsch.

## Und sonst so?

* **Habe Spaß!**