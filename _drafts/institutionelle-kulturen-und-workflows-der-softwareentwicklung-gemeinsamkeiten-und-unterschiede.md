---
layout: post
title: "Institutionelle Kulturen und Workflows der Softwareentwicklung: Gemeinsamkeiten und Unterschiede"
date: 2018-07-16 13:00
categories: workshop dhd2018 kultur community workflows
# Full author list with affiliations
author: Annette van Dyck-Hemming, Andrea Notroff (Berlin-Brandenburgische Akademie der Wissenschaften), Carolin Odebrecht (Humboldt-Universität zu Berlin), Nils Reichert (Herzog August Bibliothek Wolfenbüttel)
# Just the authornames as a comma-separated list for display in blog overview
authornames: Annette van Dyck-Hemming, Andrea Notroff, Carolin Odebrecht, Nils Reichert

# NOTE: To mark the blog post excerpt that should be displayed in the blog
# overview, use: <!--more-->
---

Im Rahmen der DHd 2018 fand am 27. Februar in Köln der Workshop
"Research Software Engineering und Digital Humanities. Reflexion,
Kartierung, Organisation." statt. Dieser Blogbeitrag berichtet über die
Arbeitsgruppe "Institutionelle Kulturen und Workflows der
Softwareentwicklung: Gemeinsamkeiten und Unterschiede" bei diesem
Workshop.

<!--more-->

## Verschiedene Umfelder

In den Digital Humanities kann es sehr verschieden sein, in welchem
fachlichen Kontext und an was für einer Institution ein
Softwareentwicklungsprojekt angesiedelt ist. In der Regel wird
DH-Software an der Schnittstelle mehrerer Fächer entwickelt:
geisteswissenschaftliche Disziplinen, Informatik, Schnittstellenfächer
wie Computerlinguistik und Korpuslinguistik. Diese fachlichen
Kooperationen involvieren zudem sehr unterschiedliche Institutionen, zum
Beispiel:

-   Akademische Institutionen (Universitäten, Akademien,
    Max-Planck-Institute, etc.)
-   GLAM/Gedächtnisinstitutionen (Galleries, Libraries, Archives,
    Museums)
-   Open-Source-Communities (die die Software entwickeln, die wir
    benutzen)
-   Privatwirtschaftliche Software-Entwicklungs-Unternehmen
    (Web-Agenturen, Freelancer, Software-Provider)
-   Geldgebende Institutionen

Alle diese Fächer und Institutionen haben ihre je eigenen Workflows und
Arbeitskulturen. Was in einem Umfeld gut funktioniert, kann in einem
anderen Umfeld auf Hindernisse stoßen. Wer sich an der Schnittstelle
bewegt, muss Anpassungs- und Übersetzungsleistungen für die
unterschiedlichen Gepflogenheiten leisten. In der Arbeitsgruppe wurden
folgende Erfahrungen zum Neben- und Miteinander verschiedener Umfelder
zusammengetragen, die wir hier zum Teil bewusst überspitzt formulieren:

-   Begriffe werden mit unterschiedlichen Bedeutungen benutzt (z.B.
    Information), oder unterschiedliche Begriffe für dasselbe.
-   Verschiedene Fächer haben unterschiedliche erkenntnistheoretische
    Voraussetzungen und Herangehensweisen.
-   In der fachinformatischen Ausbildung für Softwareentwicklung lernt
    man, in Gruppen mit klar verteilten Rollen zusammen zu arbeiten
    (z.B. Project Manager, Product Owner, Scrum Master, Software
    Architect, UX Designer, Backend Developer, Frontend Developer,
    Technical Writer). Der Idealtypus geisteswissenschaftlichen
    Arbeitens ist weiterhin das Ein-Personen-Projekt.
-   Ein Geisteswissenschaftler denkt bei der Datenmodellierung an eine
    passende epistemologische Modellierung seines
    Forschungsgegenstandes. Eine Softwareentwicklerin denkt zusätzlich
    zum Beispiel an Performance oder Schnittstellen zum Frontend.
-   Wenn ein "Beirat" eine Sitzung hat, werden fachpolitische Positionen
    verhandelt. Wenn ein "Team" ein Meeting hat, wird die gemeinsame
    Lösung eines Arbeitspakets explizit, bindend, ziel- und
    effizienzorientiert besprochen.
-   Der Grad der Kompetenz, DH-Projekte mit einem guten Ergebnis
    durchzuführen, hat nichts mit der erreichten institutionellen
    Etablierung in der Wissenschaftswelt zu tun (Prof., Assi, HiWi).
    Alle Beteiligten in einem Softwareentwicklungsprojekt müssen auf
    Augenhöhe miteinander reden.

## Umgangsweisen mit verschiedenen Umfeldern

Was braucht es, um in diesem Feld von Verschiedenheiten gute DH-Software
entwickeln zu können? In der Arbeitsgruppe wurden folgende Punkte
genannt:

-   Geisteswissenschaftliche Forschungsarbeit muss sich mehr auf
    Gruppenarbeit ausrichten, Fachdisziplinen müssen zusammenarbeiten.
-   Schnittstellenkompetenz ist auf allen Seiten nötig. Alle müssen sich
    auch mal in ein anderes Fach oder eine andere Institution
    hineinbegeben, um die dortigen Herangehensweisen zu verstehen.
-   Um sich zwischen stark unterschiedlichen Wissensdomänen zu verstehen
    und zusammenarbeiten zu können, muss man viele einfache
    Verständnisfragen stellen. Dafür muss der Raum da sein. Fragen
    stellen ist in diesem Kontext ein Zeichen für hohe interdisziplinäre
    Kompetenz und darf nicht die wissenschaftliche Anerkennung mindern.
-   Die Diskurskultur muss von traditionellen Rollenmustern (Prof.,
    Assi, HiWi) absehen.
-   In den Digital Humanities ist Softwareentwicklung oft auch
    Forschungsarbeit. Softwareentwickler\*innen sollten als
    Wissenschaftler\*innen anerkannt werden.
-   Synergetische Kulturen und Workflows sollten bereits in der
    DH-Ausbildung gelebt und vermittelt werden und in anderen
    Fachbereichen als Ausbildungsangebot bestehen.
-   Prozessualität: Da es in Wissenschaften um neue Forschungsfragen
    geht, muss Software besonders agil sein. Software sollte auf sich
    ändernde und neue Forschungsfragen und damit Anwendungsszenarien
    reagieren können. Nachhaltigkeit könnte gerade stetige Veränderung
    von Software bedeuten. Dazu gehört auch der Einsatz in
    möglicherweise initial nicht intendierten Kontexten oder für neue
    Anwendungszwecke.

## Gemeinsamkeiten

Bei den hier skizzierten Unterschieden wurde in der Arbeitsgruppe immer
wieder eingefordert, keine vereinfachenden Polarisierungen herzustellen.
Wenn man sich verschiedene Workflows auf einer abstrakten Ebene
anschaut, kann man die gleiche prinzipielle Vorgehensweise sehen:
Ausgangspunkt ist eine Frage oder ein Problem, die auf eine bestimmte
Art angeschaut werden (Theorie, Modell). Daraus leitet sich eine
passende Methode, ein passendes Tool oder eine passende Technologie ab,
um die Frage zu beantworten oder das Problem zu lösen. Am Ende steht ein
Ergebnis, welches Überprüfungen standhalten muss (Kritik, Review,
Reproduzierbarkeit, Tests). Dieser Ablauf wird oft mehrfach durchlaufen
(hermeneutischer Zirkel, agile Entwicklungsmethode).

## Neue Entwicklungen

Während der Diskussion wurden außerdem mehrere Beispiele genannt, wie
sich durch die Interdisziplinarität und Interkulturalität
geisteswissenschaftliche Forschungspraktiken ändern:

-   Es entstehen neue Forschungsfragen, z.B. nach Häufigkeiten. Durch
    digitale Methoden wird ein Zugriff auf viele Daten möglich, die
    häufig nicht mehr eigenständig hermeneutisch erfasst werden können
    (vgl. Corpus linguistics, distant reading). Damit können empirisch
    fundierte Aussagen über die Variation der Vielfalt eines Phänomens
    oder deren Distribution ermöglicht werden.
-   Digitale Tools wirken auf geisteswissenschaftliche Methoden zurück.
    Durch die Annotation von Texten kann einerseits nachvollzogen
    werden, was konkret mit einer bestimmten Kategorie ausgezeichnet
    wird, und eben auch, was nicht ausgezeichnet wird. Damit müssen
    Studien zum Beispiel rechtfertigen, welches Textsample angeschaut
    und annotiert wurde (Design, Balancing).
-   Digitale Tools legen die Messlatte für Nachvollziehbarkeit für
    hermeneutische Methoden höher. Mit Hilfe von Annotationen und
    Suchwerkzeugen werden alle Schritte der Analyse unstrittig und
    explizit nachvollziehbar gemacht.
-   Daten und Forschungsergebnisse werden immer zugänglicher. Dadurch
    werden eigene Ergebnisse besser vergleichbar, auch international.

## Aufgaben für die AG DH-RSE

Diese beispielhaften Aufzählungen für Unterschiede, Gemeinsamkeiten,
neue Entwicklungen und Handlungsbedarf sind aus einem explorativen
Gesprächskontext während der Arbeitsgruppe entstanden und behandeln vor
allem (epistemische) Kulturen. Sie bedürfen einer systematischen
Sichtung und weiterer Ergänzung. Dann können auch folgende Fragen
behandelt werden: Gibt es abstrahierbare Workflows, die eine gemeinsame
Basis für inter- und transdisziplinäre Zusammenarbeit bilden? Welche
Vorgehens- und Umgangsweisen für Softwareentwicklung funktionieren gut,
egal in welchen Fächern und Institutionen man sich bewegt? Wie wollen
wir zusammen arbeiten?

Dabei muss man nicht bei Null anfangen. Es gibt die Science&Technology
Studies und die Wissenschaftstheorie. Es gibt Forschung zu Fächer-,
Arbeits- und Organisationskulturen, zu interkultureller Kompetenz, zu
Gruppenbildungsprozessen. Und es gibt professionelle Praktiker\*innen,
von denen man sich viel Praxiskompetenz abholen kann, z.B. Coaches oder
Projektmanager\*innen.

## Sehr eklektische Lese-Tipps

-   J. Edmond, M. Doran, G. Nugent-Folan (2018): Is Software Production
    a Cultural Practice? Position Paper for 2018 Working Group. Trinity
    College Dublin Centre for Digital Humanities.\
    [*http://dh.tcd.ie/dh/wp-content/uploads/2018/03/Trinity-Centre-for-Digital-Humanities-Software-Culture-Working-Group-Position-Paper.pdf*](http://dh.tcd.ie/dh/wp-content/uploads/2018/03/Trinity-Centre-for-Digital-Humanities-Software-Culture-Working-Group-Position-Paper.pdf)\
    Diskussionspapier zu einem im September 2018 stattfindenden
    Workshop, das unter anderem folgende Dimensionen für die
    Untersuchung von Softwareentwicklungs-"Kulturen" vorschlägt:
    Individualism versus Collectivism, Masculinity versus Femininity,
    Uncertainty Avoidance.
-   Pierre Bourdieu und seine Konzepte des kulturellen Feldes.\
    Für eine mögliche Klärung des Begriffs "Kulturen": Strukturell
    sprechen wir über die an Personen und Institutionen gebundene
    Einschränkung von gedanklichen Entwicklungsmöglichkeiten, wie sie in
    der Wissenschaftstheorie oftmals diskutiert und in dieser Weise
    anschlussfähig zum ersten mal von Ludwik Fleck als Denkstil und
    Denkkollektiv formuliert wurde. Nicht nur, da diese auch immer erst
    Bedingung für brauchbare Wahrheiten sind, bestand Einigkeit darüber,
    dass mit der Beschreibung unterschiedlicher Kulturen keineswegs die
    Differenzen im Vordergrund stehen und damit umso größer wirken
    sollten, wie es etwa bei den Diskursen früherer Generationen a la
    C.P. Snows *The Two Cultures* der Fall war.
-   Silke Meyer (2011): Free Software, Free Society? Über die
    Reproduktion von Differenz in der Praxis von Free/Libre Open Source
    Software-Communities. Berlin.\
    [*http://www.diss.fu-berlin.de/diss/receive/FUDISS\_thesis\_000000095545*](http://www.diss.fu-berlin.de/diss/receive/FUDISS_thesis_000000095545)\
    Dissertation, die Linux-User-Groups als Kulturen untersucht --
    sicherlich aufschlussreich auch für andere Arbeitskulturen in der
    Softwareentwicklung. Hinterfragt zum Beispiel die Dichotomie von
    Nutzer\*innen und Entwickler\*innen und untersucht die
    Strukturierung von Zeit beim Programmieren.
-   Tom DeMarco (1997): The Deadline. A Novel about Project Management.
    New York.\
    Zusammenfassende Rezension:
    [*https://www.2uo.de/the-deadline/*](https://www.2uo.de/the-deadline/)\
    Ein in die Jahre gekommener IT-Management-Klassiker, der aber
    weiterhin einen relativ unterhaltsamen Einblick in bestimmte Ideale
    von Arbeitskulturen und -abläufen für große Softwareprojekte der
    Privatwirtschaft bietet.
-   Boris Müller (2018): Strategies for Design-Science Collaboration.\
    [*https://medium.com/@borism/strategies-for-design-science-collaborations-10199f3b8305*](https://medium.com/@borism/strategies-for-design-science-collaborations-10199f3b8305)\
    Blogbeitrag über die Kollaboration von Designer\*innen und
    Wissenschaftler\*innen, von dem sich Softwareentwickler\*innen auch
    etwas abschauen können - insbesondere, da Design auch ein Teil von
    Softwareentwicklung ist (UX/UI-Design).
-   Zita Küng (2005): Was wird hier eigentlich gespielt? Strategien im
    professionellen Umfeld verstehen und entwickeln. Heidelberg.\
    [*https://doi.org/10.1007/3-540-27808-7*](https://doi.org/10.1007/3-540-27808-7)\
    Eine von vielen existierenden Praxis-Übersetzungen von
    Organisationstheorie. These: Für das Verständnis von Organisationen
    sind Macht, Strategie, Spiel und Umwelt wichtig. Was tun, wenn man
    in einem "anderen Film" ist als die anderen, wie spielt man mit?

