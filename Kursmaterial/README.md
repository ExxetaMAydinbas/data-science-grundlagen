# Kursaufteilung

Der Kurs ist für 5 Tage konstruiert und das Kursmaterial deckt alle auf der [Website](https://www.gfu.net/seminare-schulungen-kurse/reporting__business_intelligence_und_berichtswesen_sk94/data-science-business-akademie-python-praxiswoche-zertifizierung_s2046.html) aufgelisteten Theman ab. 
- Die Aufteilung der Themen auf die 5 Tage ist in der Power Point [GFU_Python_5Tage](/.pptx) dargestellt. 
- Der gesamte theoretische Hintergrund ist ebenfalls in dieser Präsentation zusmmengetragen. Insbesondere am Tagesanfang -und ende lohnt sich ein Blick auf die Präsentation, um alle Teilnehmer mitzunehmen, wo man gerade ist und was als nächstes geplant ist. 
- Die Präsnetationsfolien sind ansonsten eher als Nachschlagewerk gedacht - sie sind teils auch noch auf Englisch.
- Ansonsten kann man sich gemäß der Nummerierung an den Notebook-Templates entlanghangeln. 

Anmerkung: Auch für die Teilnehmer ist es hilfreich jeweils am Anfang des Tages die Notebook-Templates für den Tag zu erhalten, da sich mehr auf das Mittippen der Programmierung fokussiert werden kann.


# Cheat Sheets
- sind dem Ordner [cheatsheets](../cheatsheets/) zu entnehmen und den Teilnehmern im laufe der Schulung zu übergeben
Anmerkung: Hier werden mehr Cheat Sheets bereitgestellt als für den Kurs notwendig. Es kann auch sinnvoll sein, nur einen Teil der Cheat Sheets bereitzustellen.


# Exercises
- Übungen kann man immer direkt in die Notebooks eingebauen
- Für das Data Handling / Wrangling mit pandas wurde im Nachinein die Übung [04_Exercise_Group](/Exercises_deutsch/) von den Teilnehmern selbstständig durchgeführt und - soweit möglich - ebenfalls die Übung [05_Exercise_Apply](/Exercises_deutsch/); 
- In diesem Ordner [Exercises_deutsch](/Exercises_deutsch/) befinden sich noch weitere Übungen; je nach Fähigkeit der Teilnehmer kann man hier entsprechend auch andere Übungen oder mehr Übungen wählen. 
- Im Ordner [Exercises_English](/Exercises_English/) werden die gleichen Übungen auf Englisch bereitgestellt.
- Als finale Übung besteht die Aufgabe, das Notbook für die Regression zu kopieren und in der Kopie die Datenaufbereitung so anzupassen, dass im Nachgang diverse Klassifikationsalgorithmen trainiert werden können. Es lohnt sich vorher die einzlenne Schritte die geändert werden müssen im Flipchart zusammenzutragen.


# Zusatzmaterial auf Nachfrage

Folgende Themen wurden während der Schulung nachgefragt und sollten womöglich in den Kursinhalt aufgenommen werden:
- Joinen / Mergen von Daten
- Umgang mit Multi-Index (insbesondere wenn es zweistufige Spaltenüberschriften gibt wie z.B.  als Ergebnis eines groupby(...).agg('col_1': ['mean', 'min', 'max']))
- Apply und lambda-functions (kann im Rahmen der apply-Exercise eineführt und erklärt werden)


# Final Exam

Zur Bearbeitung der ersten 8 Aufgaben benötigen verhältnismäßig fitte Teilnehmer bereits bis zu 1:00h bis 1:15h. Das bereitstellen von Bonusaufgaben hat sich als sinnvoll herausgestellt, um die Geräuschkulisse niedrig zu halten.
Die Unterlagen sind zu finden unter  [Final Exam](../FinalExam/)


# Verbessungspotential in den Unterlagen / Übungen
Es würde sich anbieten 
- für reshaping (melt ud pivotize) relevantere Besipieldaten zu verwenden (mit Story dahinter).
- joins / merge, apply, lambda-functions, multi-indexing in die Tempaltes miteinzubauen
- die Präsentationsfolien sprachlich zu vereinheitlichen (alles englisch oder alles deutsch).
