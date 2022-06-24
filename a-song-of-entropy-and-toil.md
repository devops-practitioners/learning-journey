## Prolog - oder was ist Entropie?
Ein inoffizieller Appendix der Hauptsätze der Thermodynamik lautet: `Du sollst dir kein Bildnis von Entropie machen`. Gegen diesen Grundsatz werden wir nun verstoßen - was ist Entropie? 

Entropie ist in erster Linie ein Kunstwort und kommt aus dem altgriechischen ἐντροπία entropía und lässt sich grob als "in Wendung" übersetzen. Entropie beschreibt eine fundamentale thermodynamische Zustansgrö0e und wird durch den zweiten Hauptsatz der Thermodynamik beschrieben: 

> Die Gesamtentropie in einem isolierten System kann nie kleiner werden, d.h. sie kann nur größer werden oder gleich bleiben. Ein System kann sich nicht mehr verändern, wenn die Entropie ihren Maximalwert erreicht hat, das System befindet dann sich im Gleichgewicht.

Mathematisch lässt sich dies als Faustformel durch `S = Q/T`  beschreiben - wobei Q die Wärmemenge bei reversiblem Prozess darstellt und T für die Temperatur steht. Konkret lässt sich die Formel also als "Entropie ist die Wärmemenge die als Temperatur an die Umgebung abgegeben wird" 

# Ein Lied von Entropie und Mühsal

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Aha! There is no Agile Transformation. It is just a constant fight against entropy that keeps organizations away from functioning optimal. And a mean to do that most efficiently is the Improvement Kata. <a href="https://twitter.com/RealMikeRother?ref_src=twsrc%5Etfw">@RealMikeRother</a> <a href="https://twitter.com/jonsmart?ref_src=twsrc%5Etfw">@jonsmart</a></p>&mdash; Lars (@bob5ec) <a href="https://twitter.com/bob5ec/status/1537897257613217793?ref_src=twsrc%5Etfw">June 17, 2022</a></blockquote> 


Basierend auf dieser These kann eine Organisation als isoliertes System angesehen werden. Das System als solches wird Verlangsamt durch diverse Faktoren wie: 
* Konstanter Wandel (jeder möchte VEränderung - keiner sich jedoch verändern)
* Kommunikation - je mehr Abhängigkeiten zwischen den Komponenten bestehen, desto träger wird das System (Boards, Gremien, Teamübergreifende- und Teaminterne Kommunikation, ...)
* Prozess Dschungel und starre Traditionen
* Historie - Vom Altsystem bis zu historischen Rollen und Artefakte 
* vieles mehr ...

Die meisten Punkte die hier auf die Entropie des Systems einwirken haben jedoch eine andere Ursache. Google drückt dies auf ihrer SRE (Site Reliability Engineering) Website) aus durch den Begriff Toil (Mühsal):

> “So what is toil? Toil is the kind of work tied to running a production service that tends to be manual, repetitive, automatable, tactical, devoid of enduring value, and that scales linearly as a service grows. Not every task deemed toil has all these attributes, but the more closely work matches one or more of the following descriptions, the more likely it is to be toil:”
– [Google](https://landing.google.com/sre/sre-book/chapters/eliminating-toil/)

Automatisierung ist das Gegenmittel zu Toil - durch die Automatisierung der geringwertigen Arbeit bleibt mehr Zeit für die Arbeit mit höherem Wertzuwachs. Die Automatisierung sollte auch die Wiederholbarkeit und Zuverlässigkeit verbessern, indem alle Aufgaben automatisiert werden. Wenn die gleichen Aufgaben jedes Mal auf die gleiche Weise ausgeführt werden, gibt es keine Überraschungen mehr. Manuelle Aufgaben hingegen führen zu einem hohen Maß an Variation und damit zu einem Mangel an Wiederholbarkeit.

## DevOps Kultur als Antwort 

<p align="center">
<img width=300 src="https://user-images.githubusercontent.com/8672357/175659600-b6771a3f-76ea-4baa-9718-e5a9175e79c8.png">
</p>

John Willis and Damon Edwards Entwickelten das Akronym [CAMS](https://itrevolution.com/devops-culture-part-1/) im Jahr 2010.ierbei steht das `A` für Automation. und liefert, wie wir bereits gelernt haben eine gute Antwort zu Toil - wie besiegt man jedoch Entropie? Eine Idee dazu liefert Jez Humble mit der Erweiterung das Akronyms zu [C.A.L.M.S](https://benjitrapp.github.io/cultures/2022-03-30-CALMS-devops/). Was bedeutet nun das `L` ? 

## `L` steht für Lean
Die Erweiterung von Jez Humble fügt hier einen weiteren Erfolgsfaktor zum Kampf gegen Entropie hinzu. Lean besteht aus den [fünf Schlüsselprinzipien von Lean](https://theleanway.net/The-Five-Principles-of-Lean). Die Lean-IT-Bewegung versucht, diese Konzepte auf die Welt der Softwareentwicklung auszuweiten. Die wichtigsten Texte sind [Lean Software Development von Tom & Mary Poppendieck](h[ttps://www.amazon.co.uk/Lean-Software-Development-Agile-Toolkit/dp/0321150783](https://www.oreilly.com/library/view/lean-software-development/0321150783/)) und [Lean Enterprise von Humble, Molesky und O'Reilly](https://www.oreilly.com/library/view/lean-enterprise/9781491946527/). Lean zielt auf FLOW ab - den reibungslosen Übergang der Arbeit von einem "Arbeitszentrum" zum nächsten in kürzester Zeit. Idealerweise mit so wenig Warteschlangen/Puffern wie möglich. 
