---
layout: post
title: "Gute Dokumentation als Basis für nachhaltige Software"
date: 2018-07-02 13:00
categories: workshop dhd2018 dokumentation nachhaltigkeit
# Full author list with affiliations
author: "Carsten Thiel (Niedersächsische Staats- und Universitätsbibliothek Göttingen, DARIAH-DE), Julia Dolhoff (Johannes Gutenberg-Universität Mainz, Digitale Akademie Mainz)"
# Just the authornames as a comma-separated list for display in blog overview
authornames: "Carsten Thiel, Julia Dolhoff"
# NOTE: To mark the blog post excerpt that should be displayed in the blog
# overview, use: <!--more-->
---

Forschungssoftware wird meist zur kurzfristigen Erzeugung oder Verifikation von Forschungsergebnissen erstellt. Selbst wird sie aber meist nicht als Forschungsergebnis angesehen und nicht zuletzt deshalb nicht auf eine langfristige Nutzung hin entwickelt.
Als Grundproblem leidet sie daher oft an einem Mangel an systematischer, umfassender und verständlicher Dokumentation. Doch in letzter Konsequenz ist sie damit langfristig wertlos.

<!--more-->

## Warum ist das ein Problem?

Als eine der fundamentalen Ursachen für den Mangel an guter Dokumentation kann sicher die Orientierung auf direkt sicht- und messbare Ergebnisse gesehen werden. Die Priorität der Softwaredokumentation wird daher als niedrig eingestuft und der Fokus auf den Code gelegt um die eigentlichen Ziele zu erreichen. An dieser Sicht wird jedoch deutlich, dass fälschlicherweise eine zentrale Annahme darin besteht, dass Softwareentwicklung mit dem Schreiben von Programmcode gleichzusetzen sei. Hingegen muss ein viel größeres Gewicht auf Planung, Design und Dokumentation gelegt werden.
Gerade in der Forschungswelt, wo Befristungen für konkrete Forschungsvorhaben durch Drittmittelprojekte und Qualifikationsphasen der wissenschaftlichen Karriere eine zentrale Rolle spielen, leidet auch Software unter Kurzfristigkeit und hohem Turnover. Hinzu kommt die permanente Weiterentwicklung der verwendeten Technologien und Frameworks, die der technische Fortschritt der IT-Welt permanent mit sich bringt.
Die unter Gesichtspunkten der kurzfristigen Produktion von publikationsfähigen Forschungsergebnissen entstandene Forschungssoftware hat so massiv Defizite in Sachen Nachhaltigkeit.
Dies führt mittel- und langfristig zu neuen Problemen, die sich insbesondere in mangelhafter Wartbarkeit niederschlagen können. Ohne das durchgehende Verständnis für Designentscheidungen lässt sich Software zu einem späteren Zeitpunkt, erst Recht durch Dritte, nur schlecht an veränderte Anforderungen anpassen. Diese können funktionaler Art sein, wenn die Software für neue oder veränderte Forschungsfragen genutzt werden soll, aber auch technischer Natur sein. Veränderungen der genutzten externen Bibliotheken, Schnittstellen und Frameworks können so in aufwendige und teure Nacharbeit ausufern.

## Was tun?

Während die Frage der Nachnutzbarkeit einer bestimmten Software sicher nicht in jedem Fall von Anfang an als zentrales Kriterium angelegt werden kann, so muss doch eine stärkere Sensibilisierung erfolgen.
Eine fundamentale Forderung der Workshopgruppe ist daher die Verstärkung der Bedeutung, welche der Dokumentation und anderen qualitätssteigernden Maßnahmen zugewiesen wird.
Um dies umsetzen zu können, müssen die entsprechenden Techniken und Methoden einen vertiefenden Einzug in die Lehre erhalten und die Qualitätssteigerung von Forschungssoftware im Allgemeinen einen verstärkten und zentralen Fokus bekommen.
Die Implementierung von Best Practices aus der Softwareindustrie, die auch in der Welt der Open Source Software verbreitet und gelebt werden, müssen auch in der Forschung umgesetzt werden. Dazu gehören technische Maßnahmen, von Versionskontrolle über Code Linting bis hin zu Testsuiten und Code Analyse. Aber auch gelebte Maßnahmen wie Code Reviewing und regelmäßiges Refactoring sind hier zentrale Ansätze.
Um die Best Practices aus der Industrie gezielt in die Softwareentwicklungsroutinen der Wissenschaft zu integrieren, sind Workshops und/oder Schulungen für WissenschaftlerInnen zu empfehlen.
Letztlich muss auch die Frage zulässig sein, welche Programmiersprachen, Technologien, Frameworks und Bibliotheken allgemein für wissenschaftliche Software zum Einsatz kommen sollten. Eine Fokussierung auf wenige etablierte und gut getestete Lösungen wäre hier als mögliche Standardisierung denkbar. Gerade für Software, die institutionell gebunden ist und unabhängig von bestimmten Einzelpersonen langfristig gepflegt, betrieben und weiter gewartet werden soll, stellt dies eine zentrale Anforderung dar.
Entgegen verbreiteter Praxis kann es sinnvoll sein, nicht jede neue Technologie immer sofort einzusetzen. An dieser Stelle muss dann unter Umständen eine Abwägung zwischen Nachhaltigkeit und Wartbarkeit auf der einen Seite und Cutting-Edge-Technologie an der Speerspitze der Forschung andererseits erfolgen. Diese Abwägung kann dann für individuelle ForscherInnen mit einem konkreten und begrenzten Einsatzzweck anders ausfallen als für Institutionen oder Infrastrukturen. 
 
## Mögliche Lösungsansätze

Doch dabei gibt es eine Reihe von Empfehlungen und Möglichkeiten, für die Nachhaltigkeit von Software zu sorgen. Die [Recommendations to encourage best practices in research software
](https://softdev4research.github.io/recommendations/) verstehen sich als grundlegende Handlungsempfehlungen in Anlehnung an die FAIR Prinzipien zum Datenmanagement.
Als Sammlung von konkreten Empfehlungen an Softwareentwickler bietet sich z.B. die
[DARIAH Technical Reference](https://dariah-eric.github.io/technical-reference/) an, die eine Vielzahl von existierenden und gängigen Praktiken verbindet und damit als Einstiegspunkt dienen will.

Letztlich wird sich die Situation aber nur ändern, wenn die Bedeutung und damit der Wert von Forschungssoftware auch in politischen Gremien, von Förderern und Leitungsinhabern akzeptiert, gelebt und gefördert wird, wie es auch die [Handreichung zum Umgang
mit Forschungssoftware](https://doi.org/10.5281/zenodo.1172970) der Allianz-Initiative Digitale Information fordert.