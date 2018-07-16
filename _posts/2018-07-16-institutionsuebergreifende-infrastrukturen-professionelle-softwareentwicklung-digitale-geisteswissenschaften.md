---
layout: post
title: "Welche institutionsübergreifenden Infrastrukturen brauchen wir für eine professionelle Softwareentwicklung in den digitalen Geisteswissenschaften?"
date: 2018-07-16 13:00
categories: workshop dhd2018 infrastrukturen institutionen professionalität
# Full author list with affiliations
author: "Fabian Steeg (steeg@hbz-nrw.de), Sophie Schneider (sophie.schneider@fh-potsdam.de), Peter Gietz (peter.gietz@daasi.de)"
# Just the authornames as a comma-separated list for display in blog overview
authornames: "Fabian Steeg, Sophie Schneider, Peter Gietz"

# NOTE: To mark the blog post excerpt that should be displayed in the blog
# overview, use: <!--more-->
---

![Bahngleise mit unterschiedlichen Spurbreiten. Quelle: Gediminas, GFDL, https://commons.wikimedia.org/wiki/File:Rail_Baltica_Lietuva.jpg]({{ "/assets/blog/img/rails.png" | absolute_url }})

Welche Infrastrukturen, und wie viele? <br/>
<small>(Quelle: Gediminas, GFDL, [https://commons.wikimedia.org/wiki/File:Rail_Baltica_Lietuva.jpg](https://commons.wikimedia.org/wiki/File:Rail_Baltica_Lietuva.jpg), Ausschnitt bearbeitet).</small>
{: class="figure-legend"}

Im Rahmen der DHd 2018 fand am 27. Februar in Köln der Workshop
"Research Software Engineering und Digital Humanities. Reflexion,
Kartierung, Organisation." statt. Eine der Arbeitsgruppen dieses
Workshops hatte das Thema "Infrastruktur: Welche
institutionsübergreifenden Infrastrukturen brauchen wir für eine
professionelle Softwareentwicklung in den digitalen
Geisteswissenschaften?".

<!--more-->

## Was verstehen wir unter „Infrastrukturen"?

Im Kontext unserer angeregten Gruppendiskussion entstehen zahlreiche,
zum Teil fundamentale, Fragen. Womit beschäftigen wir uns konkret bzw.
womit sollten wir uns zukünftig stärker auseinandersetzen, wenn es um
die Infrastrukturen für Softwareentwicklung in den digitalen
Geisteswissenschaften geht? Sprechen wir hierbei von Standards für
Schnittstellen, von Metadatenstandards für den Datenaustausch? Von
einheitlichen Suchoberflächen? Oder ist das ein ganz anderer Bereich?
Sind Daten und Software grundsätzlich getrennte Themen mit
unterschiedlichen Ansprüchen an Infrastruktur? Oder gehen die
Anforderungen hier Hand in Hand?

Umfasst der Bereich DH-Software eher Werkzeuge zum Finden von
existierender Forschungssoftware oder Werkzeuge für die Entwicklung
neuer Software? Schon hier zeigt sich die Vielschichtigkeit des
Begriffes Infrastruktur, welcher sich auf so unterschiedlichen Ebenen
betrachten und interpretieren lässt. Eine Programmierschnittstelle ist
Infrastruktur. Ein Software-Repository für Forschungssoftware ist
Infrastruktur. Versionskontrolle und Ticket-Systeme sind Infrastruktur.
Und auch die professionelle Weiterbildung zu Themen der
Softwareentwicklung oder die von Stephan Janosch 
[*in seiner Workshop-Keynote*](https://dh-rse.github.io/workshop/dhd2018/2018/02/22/workshop-keynote.html)
beschriebenen RSE-Teams, die FachwissenschaftlerInnen nach Bedarf
unterstützen, stellen in gewisser Weise Infrastruktur dar.

Konkret lassen sich zwei Arten von Infrastrukturen unterscheiden:
privatwirtschaftliche Lösungen wie beispielsweise GitHub, die hohe
Nutzerzahlen aufweisen und sich weitestgehend etabliert haben, und
öffentlich finanzierte Angebote, die häufig noch im Aufbau sind und
nicht selten nur wenig Bekanntheit (insbesondere über die spezifische
Fachcommunity hinaus) erlangen. Hier stellt sich auch die Frage nach dem
aktuellen Stand der Dinge. Brauchen wir alternative Lösungen, die nicht
in privater Hand und damit eventuell nachhaltiger sind? Oder sind
privatwirtschaftliche Lösungen faktisch sogar nachhaltiger als
Infrastrukturen, die von befristeten Projektmitteln abhängen? Ein
pragmatischer Ansatz besteht hier in der Kombination von bestehenden und
neuen Lösungen wie etwa bei [*Zenodo*](https://zenodo.org/), welches eine
Integration von GitHub anbietet und so etablierte Entwicklungsworkflows
um fehlende Aspekte wie DOI-Vergabe für Software erweitert. Dass
Forschungsinfrastruktur nicht über Projektförderung nachhaltig werden
kann, wurde von vielen Förderern erkannt und es gibt mittlerweile neue
entsprechende Ansätze, wie etwa die Nationale Forschungsdateninfrastruktur 
(NFDI) und die Nachhaltigkeitsbestrebungen von [*DARIAH-DE*](https://de.dariah.eu/) 
und [*CLARIN-D*](https://www.clarin-d.net/de/).

## Welche Anforderungen werden an die Software-Infrastrukturen gestellt?

Weiterhin sind bestimmte Anforderungen und Probleme spezifisch an die
einzelnen Organisationen gebunden. So wird in der Gruppenbesprechung
etwa deutlich, dass z.B. in Akademien und Bibliotheken ein großer Bedarf
an Rechenleistung besteht, während Universitäten mit ihren eigenen
Rechenzentren hier meist keine Probleme haben. Möglichkeiten zur Nutzung
von Rechenleistung in Form von virtuellen Maschinen gibt es z.B. im Rahmen
von [*DARIAH-DE*](https://de.dariah.eu/virtuelle-maschinen)
und der [*GWDG*](https://www.gwdg.de/server-services/virtual-server).
Nicht nur an Rechnerkapazität fehlt es an mancher Stelle, teils
sind auch die Kompetenzen der Vermittler und Dienstleister, z.B. des
Bibliothekspersonals, noch ausbaufähig. Hier liegt großes Potential:
durch eine forcierte Aus- und Weiterbildung des Personals &ndash; gerade in
Bezug auf softwarespezifische Fragen der Fachwissenschaft &ndash; kann
ebenfalls indirekt wichtige Infrastruktur geschaffen werden.

## Worin bestehen die größten Herausforderungen?

Wiederholt taucht in der Arbeitsgruppe die Frage auf, ob generell
fehlende Infrastrukturen Probleme verursachen, oder ob andere Gründe,
wie beispielsweise eine geringe Nachnutzung bestehender Software,
hierfür anzuführen sind. Besteht etwa in einer Forschungs-, Förder- und
Publikationskultur, die stark auf Neuentwicklungen ausgerichtet ist, gar
kein großer Anreiz zur nachhaltigen Nutzung bestehender Lösungen? Liegen
die Probleme primär auf technischer Ebene oder auf organisatorischer?
Wer macht was, wer bezahlt es, wer bestimmt? Im Bereich der
Förderrichtlinien fehlen Unterstützungsmöglichkeiten für die Lösung
weniger umfangreicher Problemstellungen, nicht immer passen diese in den
Rahmen eines Projektes mit drei Jahren Laufzeit. Gerade in Anbetracht
der oben beschriebenen Heterogenität der Anforderungen sollten auch
kleinere Bedarfe gefördert werden können.

## Welche Angebote existieren bereits?

In der Gruppe angesprochene Infrastrukturangebote sind etwa die 
[*in DARIAH bereitgestellten Services*](https://de.dariah.eu/list-services), 
welche vielmals Infrastruktur nicht nur für Forschungsdaten, sondern auch für die
Softwareentwicklung bereitstellen. Weitere nationale und internationale
Maßnahmen sind etwa [*CLARIN-D*](https://www.clarin-d.net/de/),
die Nationale Forschungsdateninfrastruktur [*NFDI*](https://www.bmbf.de/de/empfehlungen-zum-management-von-forschungsdaten-3036.html)
und die European Open Science Cloud [*EOSC*](https://ec.europa.eu/research/openscience/index.cfm?pg=open-science-cloud).
Des Weiteren können auch spezialisierte Gruppen und Initiativen wie etwa
die [*AG eHumanities der Akademienunion*](http://www.akademienunion.de/arbeitsgruppen/ehumanities/),
die DHd AG [*Research Software Engineering in den Digital Humanities (DH-RSE)*](http://dig-hum.de/ag-research-software-engineering-den-digital-humanities), die DHd AG [*Datenzentren für die Geisteswissenschaften*](https://dhd-ag-datenzentren.github.io/), 
oder das Institut für Dokumentologie und Editorik [*IDE*](https://www.i-d-e.de/) 
im Sinne der oben beschriebenen fachspezifischen Anforderungen hilfreich sein.

## Ausblick

Unter den Teilnehmenden des gesamten RSE-Workshops stellt das
Bibliothekswesen laut einer im Vorfeld durchgeführten
[*Umfrage*](https://dh-rse.github.io/dhd-workshop-2018-presentation/#/step-4)
lediglich einen geringen Anteil dar, unsere Arbeitsgruppe jedoch bestand
etwa zur Hälfte aus MitarbeiterInnen beziehungsweise Studierenden aus dem
bibliothekarischen Bereich. Das Bibliothekswesen scheint also auch im
Bereich der Forschungssoftware seine Rolle als Infrastrukturanbieter
wahrnehmen zu wollen.

Insgesamt wird deutlich, dass die Arbeitsgruppe mehr Fragen als
Antworten gefunden hat. Dies zeigt aber auch, dass es hier noch
Handlungs- und Diskussionsbedarf auf den verschiedensten Ebenen gibt. Es
wurde schon viel Vorarbeit geleistet, häufig finden allerdings
schlichtweg Suchende nicht zu dem bestimmten Angebot, welches ihren
spezifischen Anforderungen gerecht wird. Hier könnte die Bereitstellung
und Bündelung von Informationen über die bestehenden Angebote helfen.
Auch dies ist eine mögliche Auffassung von Infrastruktur: nicht nur
Werkzeuge für konkrete Probleme und Aufgaben bereitzustellen, sondern
Wege zu solchen Lösungen und Werkzeugen aufzuzeigen und verfügbare Dinge
sichtbar zu machen.
