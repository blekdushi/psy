---
layout: page
title: Kapitel 5 (inkl. Zusatztext 1)
full_title: "Gesichtsverarbeitung"
published: true
vo: Kognitions- und Emotionspsychologie 1
vortragender: Leder
semester: 2020W
---

{% include vo_header.md %}

Forschungsfeld ist Teil der Kognitionspsychologie und seit den 1980er etabliert. Die offenen Fragen übersteigen bei weitem die seither gefundenen Ergebnisse dieser Grundlagenforschung.\
Besonders erforscht werden die komplexen Prozesse, mit denen Gesichter verarbeitet und erkannt werden. Gesichter dienen im Alltag dazu:
* Personen wiederzuerkennen
* Gemüts- und Gefühlsausdrücke zu lesen
* non-verbal zu kommunizieren

<a id="BruceYoung">
# Modell nach Bruce und Young

Dieses Subkapitel ist auch eine Zusammenfassung des **Zusatztext 1**:

<div style="background-color:lavender;margin-bottom:1em">Bruce, V., &amp; Young, A. (1986). Understanding face recognition. <i>British Journal of Psychology</i>, <i>77</i>(3), 305–327. <a href="https://doi.org/10.1111/j.2044-8295.1986.tb02199.x">https://doi.org/10.1111/j.2044-8295.1986.tb02199.x</a></div>

In den 80ern präsentierten Bruce und Young ein konsolidiertes Modell der Gesichtsverarbeitung, das die komplexen Erkennungsprozesse in funktionale Komponenten aufteilt:
* _structural encoding_ - piktorales, strukturelles Enkodieren
* _expression analysis_ - Gesichtsausdruck
* _facial speech analysis_ - Mimik
* _directed visual processing_
* _face recognition units (FRU)_
* _person identity nodes (PIN)_
* _name generation_
* _cognitive system_

TODO: jede Komponente beschreiben

**Structural encoding**
_view-centered descriptions_
_expression-independent descriptions_

# Gesichtswiedererkennung

Der [**Inversionseffekt (Face Inversion Effect)**](https://en.wikipedia.org/wiki/Face_inversion_effect) ist ein häufig verwendetes Instrument bei der Erforschung der Gesichtserkennung. Er kennzeichnet das Phänomen, dass das Erkennen eines Gesichts länger dauert, wenn es auf den Kopf gedreht ist (Yin, 1969). Bei anderen Objekten (z.B. Alltagsgegenständen) ist das nämlich nicht der Fall.

Biederman hat untersucht, ob die **Geons** der Objekterkennung auch für die Gesichtserkennung ausschlaggebend sind, kam aber eher zum gegenteiligen Schluss, nämlich dass sie keine wichtige Rolle dabei spielen.

In einem Experiment von Leder (1996) wurden Gesichtsfotos zu **Linienzeichnungen** transformiert. Das _structural encoding_ schien dafür nicht optimal ausgelegt zu sein, woraus man schlussfolgert, dass Gesichtserkennung nicht auf Linien als Informationsquelle basiert.

<a id="Gesichtskonfiguration">
Bei den Theorien zur Gesichtsverarbeitung gibt es Ansätze, die ein [_holistische Verarbeitung_](https://dorsch.hogrefe.com/stichwort/verarbeitung-holistische) annehmen und solche, die davon ausgehen, dass das Gesicht in seine Teile getrennt analysiert werden. Als konstituierenden Element für Gesichter werden _Augen_, _Nase_ und _Mund_ angenommen. Ihre Abstände und Anordnung in einem Gesicht nennt man **Gesichtskonfiguration**. Eines dieser Elemente alleine (z.B. nur Augen) ist nicht hinreichend für die Wiedererkennung. Außerdem erklären sie den Inversionseffekt nicht, weil Augen, Nase und Mund auf den Kopf gedreht trotzdem sehr gut erkannt werden.\
Für eine holistische Verarbeitung spricht auch eine Studie von Tanakah und Farah (1993), in der zwei Gesichter bis auf die Nase identisch waren. Danach wurde untersucht, was besser unterschieden werden konnte: wenn man beide Gesichter sieht oder nur die Nase. Den Vpn fiel die Unterscheidung mit den Gesichtern leichter.

Manche Forschungen machen sich die Einprägsamkeit und Auffälligkeit (**Distinctiveness**) eines Gesichts zu Nutze. Leder und Bruce haben die Frage untersucht, was mehr Einfluss auf Distinctiveness und den Inversionseffekt hat: (1) die Gesichtskonfiguration oder (2) die Form und das Aussehen der lokalen Komponenten (Nase, Mund...). Sie haben Gesichter genommen, die in vorhergehenden Studien als durchschnittlich "distinctive" bewertet wurden und diese dann am Computer auf zwei Arten mit dem Ziel verändert, dass sie mehr "distinctive" werden: Einerseits nur die Konfiguration, aber nicht die Komponenten selbst, und andererseits nur die Komponenten bei gleichbleibender Konfiguration. Danach haben die Vpn die Gesichter auf ihre Distinctiveness bewertet. Beide Arten der künstlich veränderten Gesichter waren in aufrechter Position mehr distinctive. Auf den Kopf gestellt verlor das konfigural veränderte Gesicht jedoch viel mehr an Distinctiveness als jenes mit veränderten Komponenten. In nachfolgenden Studien konnte man den Effekt reproduzieren.

TODO: Principal components analysis (PCA) von Hancock, Bruce & Burton

Konfigurale Merkmale erklären nur einige Aspekte der Gesichtserkennung. Bereits bekannte Gesichter können auch dann wiedererkannt werden, wenn sie stark verzerrt sind. Hinzu kommt, dass verzerrte Versionen dieser Gesichter Adaptionseffekte haben, sodass man danach leichte Verzerrungen sogar gegenüber dem Original bevorzugt. Eine Erklärung dafür ist, dass wir **Prototypen** als kognitive Repräsentation bilden, also so etwas wie einen Durchschnitt über alle Wahrnehmungen, die wir von einem Gesicht machen. Zum Beispiel hat ein Algorithmus aus mehreren Fotos von Bill Clinton ein Average gebildet und dieses wurde dann von den Vpn als am meisten mit Bill Clinton (im Vergleich zu den Fotos, die als Input für den Algorithmus dienten) assoziiert.

# Relevanz und Anwendungsbereiche

Ein Anwendungsgebiet für Gesichtserkennung und die Forschung dazu sind **Identifikationsparaden und Fahndungssysteme**. Trotz stetiger Verbesserungen haben Bilder von Überwachungskameras oft schlechte Auflösungen, sind farblos und zeigen die verdächtige Person in schlechtem Winkel. Hinzu kommt, dass Menschen zwar gut darin sind bekannte Gesichter, aber erstaunlich schlecht darin unbekannte Gesichter wiederzuerkennen. Für akademische Anwendungen wurde dafür der [Glasgow Face Matching Test (GFMT)](https://en.wikipedia.org/wiki/Glasgow_Face_Matching_Test) entwickelt. Selbst dann, wenn man das Zielgesicht neben anderen Gesichtern sieht und direkt vergleichen kann, erkennen nur 70% das richtige Gesicht. Diese schlechte Quote stellt Augenzeugenberichte und Gegenüberstellung in kriminalpolizeilichen Bereichen in Frage. Auch Kontrolleure bei der Einreise am Flughafen zeigten bei einer Studie eine 10% Fehlerquote (6% false negative / 14% false positive). Zusätzlich stellte sich heraus, dass Erfahrung und Anzahl der Dienstjahre keinen Einflusss auf die Fähigkeit zur Gesichtserkennung hatte und somit nicht erlern- oder trainierbar ist. \
Schönheitsoperationen können (klarerweise) die Wiedererkennung erschweren, bzw. die Gesichtsidentität verändern.

Ähnlich dazu haben Leder, Gerger und Forster (2011) erforscht, welche Effekte **Brillen** auf die Gesichtswahrnehmung haben. Effekte waren:
* Brillen hebt Vertrauenswürdigkeit
* Brillen machen weniger attraktiv
* Brillen behindern Wiedererkennung
* Brillen erhöhen die Einschätzung der Intelligenz

Ein weiteres Anwendungsgebiet sind **Face-Head-Modelle** (nach Vetter und Banz). Dabei handelt es sich um ein vom Computer anhand zahlreicher Fotos berechnetes Durchschnittsgesicht (**Morphing**). Der Computer hat auch diverse Dimensionen für Mimik (Lachen, Stirn runzeln), Hautfarbe, Nase, Mund, Wangenknochen, Geschlecht, Alter... herausgerechnet. Somit kann der Computer anhand von zweidimensionalen Fotos ein dreidimensionales Modell eines Gesichts konstruieren, dass dann auf den oben genannten Dimensionen beliebig variiert und animiert werden kann. Haupteinsatzzwecke dafür ist die Entertainment/Film Industrie.

Gesichter sollen zunehmend auch durch **automatisierte Gesichtserkennung** von Computern erkannt werden können (derzeit sind Pupillen und Fingerabdrücke jedoch noch besser für die Identifikation geeignet). Ein Teilgebiet davon ist das Erkennen des Gesichtsausdrucks. Das [Facial Action Coding System (FACS)](https://en.wikipedia.org/wiki/Facial_Action_Coding_System) hilft beim Erlernen von Gesichtsmuskulatur und ihre Rollen bei Gesichtsausdrücken.

**Prosopagnosie** wurde erstmals 1947 von Bodamer beschrieben. Menschen mit Prosopagnosie können keine Gesichter identifizieren. Sie können aber erkennen, dass es sich prinzipiell um ein Gesicht handelt und dieses auch strukturell beschreiben. Prosopagnosie kann erworben oder angeboren sein. Sie scheint im Zusammenhang mit Läsionen im Temporallappen (z.B. Schlaganfall) zu stehen. Da diese Störung isoliert auftreten kann, nimmt man an, dass bestimmte Gehirnregionen dediziert der Gesichtserkennung dienen:
* Fusiformes face area (FFA)
* Superior temporal sulcus (STS)
* Occipital face area (OFA)
