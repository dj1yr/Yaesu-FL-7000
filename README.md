Leider sind die original Transistoren für die FL-7000 nicht mehr zu bekommen, der Ersatztyp MRF448 ist mittlerweile auch sehr teuer geworden, so das man sich aus wirtschaftlicher Sicht die Frage stellen muss, ob es sich lohnt die PA zu reparieren.

Als ich eine defekte FL-7000 bekam, habe ich mich daran gemacht, die original Boards mit Kicad neu zu erstellen und die Vorspannungserzeugung für DMOS RF-Typen auszulegen.
Die ersten Experimente machte ich mit SD2931-10, da ich diese gleich zur Hand hatte, die Ergebnisse waren auf Anhieb viel versprechend.
Für die Bestückung der neuen Boards werden alle HF Trafo´s weiter verwendet, die Terminals passen auch, so das eine Handvoll SMD Teile bestückt werden müssen.
Die Module passen 1:1 an die original Plätze, es müssen keine mechanischen Änderungen vorgenommen werden.

In der finalen Version habe ich dann ein MP VRF150 verbaut, die Verstärkung liegt, mit eingeschalteten Abschwächer der PA, im Schnitt 3-4db höher als das Original, sie erreicht bei 25W Ansteuerung locker 500W out bis 10m.

Zum Ruhestrom einstellen können die Jumper auf dem PA Board entfernt werden und für den Abgleich des jeweiligen Transistors gesteckt werden, ich habe bei meinen Modulen 250mA/Transistor eingestellt, für den Betrieb müssen dann wieder beide Jumper gesteckt werden.

Ich habe die PA Module auf dem Labortisch vermessen, diese Arbeiten mit gutem Wirkungsgrad ohne Probleme bis 6m, die IMD3 Werte entsprechen dem original.
Am Combiner habe ich die Kompensationskondensatoren am PA1 und PA2 eingang entfernt, das führte zu einer besseren Anpassung der PA-Module.

Nach Montage der neuen Module, sollte die PA komplett neu abgeglichen werden, gerade die Limits für die Ansteuerleistung müssen angepasst werden, so das die PA vielleicht auch mal eine Fehlbedienung überlebt.

