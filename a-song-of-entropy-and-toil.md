## Prolog - oder was ist Entropie?
Ein inoffizieller Apendix der Hauptsätze der Thermodynamik lautet: `Du sollst dir kein Bildniss von Entropy machen`. Gegeen diesen Grundsatz werden wir nun verstoßen - was ist Entropie? 

Entropy ist in erster Linie ein Kunstwort und kommt aus dem algriechischen ἐντροπία entropía und lässt sich grob als "in Wendung" übersetzen. Entropie beschreibt eine fundamentale thermodynamische Zustansgrö0e und wird durch den zweiten Hauptsatz der Thermodynamik beschrieben: 

> Die Gesamtentropie in einem isolierten System kann nie kleiner werden, d.h. sie kann nur größer werden oder gleich bleiben. Ein System kann sich nicht mehr verändern, wenn die Entropie ihren Maximalwert erreicht hat, das System befindet dann sich im Gleichgewicht.

Mathematisch lässt sich dies als Faustformel durch `S = Q/T`  beschreiben - wobei Q die Wärmemänge bei reversiblem Prozess darstellt und T für die Temperatur steht. Konkret lässt sich die Formel also als "Entropie ist die Wärmemenge die als Temperatur an die Umgebung abgegeben wird" 

# Ein Lied von Entropie und Mühsahl

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Aha! There is no Agile Transformation. It is just a constant fight against entropy that keeps organizations away from functioning optimal. And a mean to do that most efficiently is the Improvement Kata. <a href="https://twitter.com/RealMikeRother?ref_src=twsrc%5Etfw">@RealMikeRother</a> <a href="https://twitter.com/jonsmart?ref_src=twsrc%5Etfw">@jonsmart</a></p>&mdash; Lars (@bob5ec) <a href="https://twitter.com/bob5ec/status/1537897257613217793?ref_src=twsrc%5Etfw">June 17, 2022</a></blockquote> 


Basierend auf dieser These lkann eine Organisation als isoliertes System angesehen werden. Das System als solches wird Verlangsamt durch diverse Faktoren wie: 
* Konstanter Wandel (jeder möchte VEränderung - keiner sich jedoch verändern)
* Kommunikation - je mehr Abhängigkeiten zwischen den Komponenten bestehen, desto träger wird das System (Boards, Gremien, Teamübergriefende- und Teaminterne Kommunikation, ...)
* Prozess Dschungel und starre Traditionen
* Historie - Vom Altsystem bis zu historischen Rollen und Artefakte 
* vieles mehr ...

Die meisten Punkte die hier auf die Entropie des Systems einwirken haben jedoch eine andere Ursache. Google drückt dies auf ihrer SRE (Site Reliability Engineering) website) aus durch den Begriff Toil (Mühsal):​​

> “So what is toil? Toil is the kind of work tied to running a production service that tends to be manual, repetitive, automatable, tactical, devoid of enduring value, and that scales linearly as a service grows. Not every task deemed toil has all these attributes, but the more closely work matches one or more of the following descriptions, the more likely it is to be toil:”
– [Google](https://landing.google.com/sre/sre-book/chapters/eliminating-toil/)

Automatisierung ist das Gegenmittel zu Toil - durch die Automatisierung der geringwertigen Arbeit bleibt mehr Zeit für die Arbeit mit höherem Wertzuwachs. Die Automatisierung sollte auch die Wiederholbarkeit und Zuverlässigkeit verbessern, indem alle Aufgaben automatisiert werden. Wenn die gleichen Aufgaben jedes Mal auf die gleiche Weise ausgeführt werden, gibt es keine Überraschungen methr. Manuelle Aufgaben hingegen führen zu einem hohen Maß an Variation und damit zu einem Mangel an Wiederholbarkeit.

## DevOps 
