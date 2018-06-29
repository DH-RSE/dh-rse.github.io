---
layout: post
title: "Best Practices der wissenschaftlichen Softwareentwicklung: Versuch einer Bestandsaufnahme"
date: 2018-06-29 13:23
categories: workshop dhd2018 best-practices
# Full author list with affiliations
author: "Andreas Wagner (Max-Planck-Institut für europäische Rechtsgeschichte/Akademie der Wissenschaften und der Literatur Mainz), Dominik Kasper (Akademie der Wissenschaften und der Literatur Mainz), Peter Dängeli (Cologne Center for eHumanities/Akademie der Wissenschaften und der Künste NRW)"
# Just the authornames as a comma-separated list for display in blog overview
authornames: "Andreas Wagner, Dominik Kasper, Peter Dängeli"

# NOTE: To mark the blog post excerpt that should be displayed in the blog
# overview, use: <!--more-->
---

Forschungssoftware(-entwicklung) als wissenschaftliche Methode heißt:
Software und ihre Entwicklung muss kritisch reflektiert und von der
*scientific community* kritisch evaluiert werden; sie muss publiziert
und dokumentiert sein und sie muss in ihrer Funktion reproduzierbar
sein. Dies auf praktikable Weise umzusetzen und bewährte, erfolgreiche
Verfahrensweisen, *Best Practices* (BP) genannt, zu vermitteln, ist eine
zentrale Aufgabe von *Research Software Engineering* (RSE).

<!--more-->

*Best Practices* richten sich dabei einerseits als Empfehlungen an RSEs,
die „neu einsteigen" und ihre Aktivitäten organisieren wollen,
andererseits aber auch an Akteurinnen und Akteure, die ihre bestehenden
Workflows prüfen und optimieren wollen.

Im Rahmen des RSE-Workshops bei der DHd2018 hat sich eine Gruppe von
sieben Teilnehmerinnen gefunden, die in Sachen *Best Practices der
wissenschaftlichen Softwareentwicklung* den Stand der Dinge und
wünschbare Entwicklungen diskutierten. Die Teilnehmerinnen sind in ihren
Heimat-Institutionen zum Teil in größere DH-Entwicklerteams eingebunden,
zum Teil dort aber auch ohne nennenswerten Kreis von
Ansprechpartnerinnen mit entsprechender technischer Expertise. Schon
früh war in den Gesprächen der Gruppe deutlich geworden, dass die klare
Identifikation und Verbreitung von *Best Practices* ein wichtiges
Desiderat darstellen, d. h. dass eben noch keine vorliegen. Oder anders
gesagt: Diejenigen Einrichtungen, an denen wissenschaftliche Software
entwickelt wird, haben es bisher möglicherweise vernachlässigt, ihre
Erfolgsrezepte aus dem Entwicklungsprozess zu kommunizieren. D. h., wenn
sie vorliegen, dann sind sie nicht wirklich bekannt -- und dann muss
ihre Bekanntmachung offenbar auch selbst im Rahmen der Vorbereitung von
Auskünften zu *Best Practices* thematisiert werden.

Um das weite Feld und unsere Gespräche etwas zu strukturieren, haben wir
drei Bereiche identifiziert, in denen über *Best Practices* gesprochen
werden kann: (a) Projektorganisation, (b) Software-Disposition, (c)
Coding.

In vielen Institutionen (z. B. ACDH[^1], AdWL Mainz[^2], CCeH[^3]) wird
aktuell Wissen und Dokumentation, die evtl. schon als Vorstufe von *Best
Practices* gelten kann, in den Bereichen (a) und (b) generiert. Dies
geschieht in der Regel, indem Teams sich regelmäßig treffen,
Kompetenz-Arbeitsgruppen bilden und Whitepapers oder (interne)
Wiki-Seiten schreiben. Mittelfristig ist von den jeweiligen
Institutionen offenbar zum Teil durchaus vorgesehen, solches Wissen zu
veröffentlichen, so die entsprechend angebundenen Teilnehmerinnen der
Gruppe. Erste Anfänge wurden hier bereits gemacht,[^4] aber die dafür
nötige redaktionelle Aufbereitung und Abstraktion von allzu spezifischen
Kontexten ist aufwendig und hat gegenüber der Forschungs- und
Entwicklungsarbeit meist niedrigere Priorität. Daher haben im Moment und
bis auf Weiteres „Einzelkämpferinnen" große Schwierigkeiten, Zugang zu
solchem Wissen zu finden. Oft bleiben diesen dann nur zeit- und z. T.
kostenaufwändige Optionen wie Einladungen von externen Expertinnen,
Teilnahme an nicht-fachwissenschaftlichen Konferenzen oder der Einkauf
von „Agentur-Know-How".

Vor diesem Hintergrund sollte ein Verband oder eine Arbeitsgruppe
sicherlich einerseits den großen und vielfältigen Bedarf ebenso wie die
Möglichkeiten (und die Verantwortung) beschreiben, die solche
Institutionen in gewisser Weise haben, zugleich aber eben auch
Unterstützung etwa in Form eines institutionsübergreifenden
Publikationsangebots (wie einer DHd-AG-Plattform) entwickeln, und nicht
zuletzt selbst an der Formulierung und Dokumentierung von *Best
Practices* mitwirken. Diese letztgenannte Mitwirkung ist sicherlich ein
wichtiger Weg, um auch die Erfahrungen von Entwicklerinnen
einzubeziehen, die nicht an einer aktiven Institution oder im Rahmen
eines gut vernetzten Kreises arbeiten. Umgekehrt könnte die
RSE-Plattform wiederum für die Einzelentwickler einen wichtigen Dienst
leisten, indem z. B. über Termine von Tagungen und Workshops sowie
wichtige Kompetenzen informiert wird.

Mit der Gründung der AG *Research Software Engineering in den Digital
Humanities* (im DHd-Verband) und einem ersten großen Workshop-Treffen
auf der DHd-Tagung 2018 in Köln, deren Ergebnisse in diesem und weiteren
Blogbeiträgen auf der AG-eigenen Website dokumentiert sind, wurde ein
erster wichtiger Schritt auf dem Weg der Vernetzung von RSEs und des
Wissenstransfers über eine AG-Plattform getan.

## Konkrete Themen und Fragen

Konkrete Themen und Fragen, bei denen Bedarf an *Best Practices*
besteht, haben wir in folgende, sich zum Teil überschneidende und
voneinander abhängige Bereiche gruppiert. Die Einteilung ist sicherlich
diskutabel und erweiterbar. Auch inhaltlich können die Ergebnisse einer
Workshop-Diskussion kaum den Anspruch auf Vollständigkeit haben, wir
hoffen damit aber einen ersten Beitrag zur oben angesprochenen
Verbreitung von Wissen über eine AG- bzw. RSE-Plattform leisten zu
können.

## (a) Projektorganisation (Projekt- und Zeitmanagement,
Kontrolle, Kollaboration, Hosting, Backup, Virtualisierung)

In diesem Bereich fehlt ein Überblick über Strategien des *Requirements
Engineering*: Wie werden die Anforderungen -- in Kooperation mit
Fachwissenschaftlerinnen und Partnerinnen -- an die Software definiert?
In welchem Prozess und mit welchen Beteiligten werden
architektur-relevante *Entscheidungen* getroffen -- und wie werden sie
dokumentiert?[^5]

Auch Diskussionen darüber, was selbst entwickelt, welche Software
nachgenutzt werden kann und unter welchen rechtlichen und technischen
Bedingungen diese Nachnutzung stattfinden darf, sowie was an externe
Dienstleister beauftragt werden soll, werden in vielen Projekten
geführt, sind aber kaum dokumentiert.

Viele Gruppen profitieren von *Kollaborations-Tools* wie Wikis,
Bugtracker, *Slack-/Hipchat-/RocketChat-/Mattermost*-Channels. Dies kann
auch ohne Projekt-Teams sinnvoll sein, um den Entwicklungsprozess, die
relevanten Entscheidungen und die verwendeten Ressourcen transparent zu
machen und ggf. zu publizieren. Wenn Tools zur expliziten
*Projektadministration* eingesetzt werden sollen, ist es wünschenswert,
auf Erfahrungen mit (und Empfehlungen zu) Projektmanagement-Systemen wie
z. B. *Redmine[^6]* und Kalender-Lösungen (z.B. *ownCloud/nextCloud*,
*MS* *Outlook*) zurückgreifen zu können; auch hier ist bislang wenig zu
finden. Interessant nicht nur für die Zusammenarbeit beim Code
schreiben, sondern auch in den Bereichen Administration und
Dokumentation, hier aber noch nicht überall durchgesetzt, ist die
Verbindung zwischen diesen Tools und dem im nächsten Punkt beschriebenen
*version control systems* (VCS).

*Data- und Computing-Leistungen* werden meistens bei (mehr oder weniger)
externen Partnern oder Dienstleistern gehostet (das können universitäre
Rechenzentren, Verbände wie die *GWDG[^7]* oder privatwirtschaftliche
Provider wie *Strato* sein). Es wäre von Vorteil, einen Überblick, wenn
schon nicht über die verschiedenen Angebote, so doch über die Kriterien,
zu haben, die man bei der Evaluation eines solchen Angebots
möglicherweise berücksichtigen sollte (Backup- und
Sicherheitsstrategien, Betriebs- und Virtualisierungssysteme,
*Docker[^8]*- oder *Vagrant[^9]*-Lösungen, Konfigurationsmanagement mit
*Puppet[^10]*, *Ansible[^11]* o. Ä., *Support Response Time*-Garantien
...).

## (b) Disposition/Deployment von Software (Ablage, Sicherung,
Verteilung, Versionierung, Zitierfähigkeit)

Jede substanzielle Arbeit an Programmcode oder Forschungsdaten sollte
*versionskontrolliert* erfolgen. Versionierung mit *Git[^12]* hat in den
letzten Jahren *Subversion, Mercurial/Hg* und ähnlichen Ansätzen den
Rang abgelaufen und ist zweifellos eine gute Wahl. Hier kann man
sicherlich bereits von einem sehr erfolgreich eingesetzten Werkzeug
sprechen. Ob *GitLab[^13]* (OpenSource, lokal installierbar), *GitHub*
(weltweit bekannt, ideal für weitere Kollaboration) oder andere
Plattformen (z.B. *Apache Allura, AWS CodeCommit, Bitbucket, Google
Cloud Source, SourceForge*, etc) eingesetzt werden, hängt letztlich vom
jeweiligen Team und Projekt ab, ebenso wie die Wahl eines einfachen oder
komplexeren *Branching-Modells[^14]* und die Nutzung von *Pull-Requests*
und *Code-Review*. Wünschenswert wäre hier sicher eine konkrete
Beschreibung wie genau und in welchem Umfang VCS bei der Durchführung
von verschiedenen Forschungs- und Entwicklungsvorhaben mit
unterschiedlichen Dimensionen zum Einsatz kommen.

Git und Plattformen wie GitHub eignen sich auch gut zur
*Release*-Verwaltung. Insbesondere bestehen auch
Integrationsmöglichkeiten mit FAIR-Datenrepositorien wie *Zenodo[^15]*.
Indem man einen Commit als Release taggt, macht (z. B.) GitHub Zenodo
automatisch auf diesen aufmerksam, und der betreffende Snapshot wird ins
Datenarchiv transferiert, wo er langfristig verfügbar und über einen
*Digital Object Identifier* (DOI) aufrufbar bleibt.[^16] Klar ist auch,
dass nach Möglichkeit auch die in den Projekten erhobenen, verwendeten
oder veränderten *Daten* versionskontrolliert verwaltet und publiziert
werden sollten. In vielen Fällen ist dies durchaus auf demselben Weg wie
die Verwaltung des Programmcodes machbar, schwieriger ist es mitunter
bei dezentral bearbeiteten Datenbankanwendungen.

Weniger Klarheit besteht bei dem Einsatz von Methoden, die sich in der
Softwareentwicklung im Allgemeinen großer Popularität erfreuen: Wir
waren uns einig, dass automatisierte *Tests* einen sehr aufwändigen
Prozess voraussetzen, der nur selten in vollem Projekt- und Code-Umfang
konsequent durchgeführt wird. Zumindest kritische Module und Funktionen
sollten aber wenn möglich automatisch getestet werden (Unit-,
Integrations- und andere Tests). Die AdWL Mainz führt generell
*Cross-Browser-Testings* bei Websites durch und hat gute Erfahrungen mit
automatisierten Test von in *Gherkin[^17]* geschrieben
*BDD[^18]*-Dokumenten über *behat[^19]* gemacht. Dennoch scheint *Code
Coverage* im RSE noch kein sehr aussagekräftiges oder anzustrebendes Maß
zu sein.

*Continuous Integration* und *Continuous Deployment* wird an
verschiedenen Stellen eingesetzt, ist aber dort zunächst auch noch in
einem Status der Erprobung und des (fortgeschrittenen) Experiments.
Einige Einrichtungen haben für die Entwicklung von Vorhaben
„Basis-Instanzen" einer Plattform eingerichtet, die dann
projektspezifisch angepasst wird: Solche Methoden werden z. B. mit
*Django[^20]*-Instanzen (ACDH), *eXist[^21]*-Instanzen (AdWL Mainz,
ACDH) und *TYPO3[^22]*-Instanzen (AdWL Mainz) praktiziert. Das „Cultural
Heritage Framework" aus Mainz[^23] und das Ediarum-System der BBAW[^24]
sind in ähnlicher Weise Base-Instanzen, die aber schon konkreter auf
geisteswissenschaftliche Projekte zugeschnitten sind.

Erfahrungen mit und Ergebnisse von solchen Methoden wären für die
Community gewiss äußerst interessant, ebenso wie Überlegungen zu der
Frage, nach welchen Faktoren sich bestimmt, wann sich der Einsatz der
genannten Methoden „lohnt": Teamgröße, Release-Häufigkeit, geplanter
Zeitrahmen, geplante Zielgruppe, Ansprüche der wissenschaftlichen
Projektleiterinnen,\...?

Aktuell scheint sich auf dem Feld der *Zitation* von Software ein
Vorschlag zu konkretisieren, der vielleicht das Zeug zu einer *Best
Practice* hat.[^25] Solche Bestrebungen gilt es aufzunehmen, kritisch zu
diskutieren und ggf. nach Kräften weiter bekannt zu machen.

## (c) Coding

Zwar ist allgemein bekannt, welche Rolle *Coding Guidelines* zur
Software-Entwicklung in der freien Wirtschaft spielen, jedoch geht es
dort vorrangig um interne Richtlinien, die gewährleisten sollen, dass
verschiedene Bearbeiter den Code des Unternehmens gut verstehen und
weiterentwickeln können. Aufgrund einer vielfältigeren Aufgaben- und
Methoden-Landschaft, einer abweichenden, stark auf individuellen
Erfahrungen basierenden Sozialisierung von Entwicklerinnen von
Forschungssoftware und aufgrund kleinerer Teams stehen solche Guidelines
im RSE oft nicht an erster Stelle. Bei der Definition von *Policies* und
*Best Practices* sowohl in den Institutionen als auch in der
Diskussionsgruppe waren und sind *Coding Guidelines* zwar konsensual als
ein wichtiges Thema benannt, aber in der Liste der Prioritäten eher
niedrig eingeordnet worden.

Jede Entwicklerin hat ihre präferierte Sprache, Entwicklungsumgebung und
*Coding Style*, und es scheint oft nicht möglich (mangels weiterer
Kompetenz in dieser Sprache), dort etwas zu vereinheitlichen. Allerdings
bringen einige Sprachen (wie *Go* oder *Elm*) verbindliche
Style-Vorgaben mit, andere (wie *Python* über *PEP8[^26]*) legen diese
doch nachdrücklich nahe. In solchen Fällen sollten diese denn auch
unbedingt berücksichtigt werden. Ebenso zu empfehlen ist der Einsatz von
sog. *Linting*-Werkzeugen, die sowohl sprachspezifisch verbindliche
Vorgaben kennen, als auch bei der Fehlerbehebung und Qualitätskontrolle
helfen.[^27] Darüber hinaus kann es eigentlich immer mindestens
bedenkenswert sein, sich an Standards für
Inline-Code-Dokumentation[^28], API Dokumentation[^29] u. ä. zu
orientieren - und dies auch selbst deutlich zu machen/zu dokumentieren.

Wo und wie -- außer im Quellcode -- eine *Dokumentation* der Software
erstellt und publiziert wird, ist noch weniger offensichtlich. Durch
GitHub haben README-Dateien im Markdown-Format an Popularität gewonnen,
daneben sind u. a. Wiki-Lösungen und HTML-Dokumentationen prominent.

Ein wichtiger Punkt betrifft die Absicherung der Software: Nach unserem
Eindruck gibt es einige allgemeine Methoden und *Best Practices* in der
allg. Softwareentwicklung, um die Sicherheit von Programmen und Diensten
systematisch möglichst weitgehend sicherzustellen. (Sanitization von
Benutzereingaben, Whitelists und Blacklists von Werten und Parametern,
Kontrolle der Datentypen, Exposition von Systeminformationen uvm.). Und
gewiss wird an vielen Stellen in mehr oder weniger systematischer Weise
auf die Sicherheit der erstellten Software geachtet. Es fehlt jedoch an
einer öffentlichen Darstellung, welche dieser Methoden sich wie im
Rahmen geisteswissenschaftlicher Projekte umsetzen lassen. Auch hier
besteht also ein großer Bedarf an der Formulierung von *Best Practices*.

Auf dem Feld der Entwurfsmuster[^30] ist zur Zeit noch kaum an *Best
Practices* zu denken, fehlen doch jegliche Erfahrungsberichte, die
Software und Prozesse in dieser Weise beschreiben.

## Allgemeine Rahmenbedingungen

Abschließend seien einige Beobachtungen über allgemeine Konstellationen
genannt, die die Erstellung und Etablierung von *Best Practices* unserer
Ansicht nach erschweren:

1.  Wie oben (im Punkt (a)) angedeutet, setzen *Best Practices*
    vermutlich technische und personelle Strukturen voraus, deren
    Entwicklung und Unterhaltung nicht ausreichend gewährleistet sind.
    Und auch auf der Seite der RSE selbst hängt die Etablierung von
    *Best Practices* an einer kontinuierlichen Arbeit und der
    persönlichen Kommunikation. Beides ist ohne eine **Verstetigung von
    Entwicklerinnenstellen** sowohl bei
    Infrastruktur-Partnerinstitutionen als auch in den RSE-Kontexten
    sehr schwer einzurichten.
2.  Große Konsortien, die theoretische vielfältige Stimmen und Bedarfe
    bündeln können, wie *CLARIN[^31]* und *DARIAH[^32]* erscheinen
    teilweise zu sehr *top-down* aufgebaut, viele Angebote und
    Vorschläge sind/scheinen zu generisch. Wünschenswert erschienen uns
    in diesem Kontext konkrete Berichte aus Einzelprojekten, die sich in
    diesen Konsortien und deren Angeboten realisieren ließen.

[^1]: Austrian Center for Digital Humanities:
    [*https://www.oeaw.ac.at/acdh/*](https://www.oeaw.ac.at/acdh/).

[^2]: Akademie der Wissenschaften und der Literatur Mainz:
    [*http://www.adwmainz.de/startseite.html*](http://www.adwmainz.de/startseite.html),
    hier insbesondere die Digitale Akademie:
    [*http://www.digitale-akademie.de*](https://www.digitale-akademie.de/).

[^3]: Cologne Center for eHumanities:
    [*http://cceh.uni-koeln.de/*](http://cceh.uni-koeln.de/).

[^4]: Vgl. dazu den von Torsten Schrade, Leiter der Digitalen Akademie
    Mainz, publizierten Vortrag + Konferenz-Papers: *Nachhaltige
    Softwareentwicklung in den Digital Humanities. Konzepte und
    Methoden.* 17.02.2017, DHd2017 Bern:
    [*Slides*](https://digicademy.github.io/2017-dhd-sustainable-software/)
    &
    [*Abstract*](http://www.dhd2017.ch/wp-content/uploads/2017/02/Abstractband_ergaenzt.pdf)
    (S. 168--171) und

[^5]: Vgl.
    [*http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions*](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)

[^6]: Siehe [*https://www.redmine.org/*](https://www.redmine.org/).

[^7]: Gesellschaft für wissenschaftliche Datenverarbeitung mbH
    Göttingen: [*https://www.gwdg.de/*](https://www.gwdg.de/).

[^8]: Siehe [*https://www.docker.com/*](https://www.docker.com/).

[^9]: Siehe
    [*https://www.vagrantup.com/*](https://www.vagrantup.com/).

[^10]: Siehe [*https://puppet.com/*](https://puppet.com/).

[^11]: Siehe [*https://www.ansible.com/*](https://www.ansible.com/).

[^12]: Siehe [*https://git-scm.com/*](https://git-scm.com/), eine
    sehr schlanke und gelungene Einführung findet sich hier:
    [*https://rogerdudler.github.io/git-guide/index.de.html*](https://rogerdudler.github.io/git-guide/index.de.html).

[^13]: Siehe [*https://about.gitlab.com/*](https://about.gitlab.com/).

[^14]: Vgl. [*https://git-scm.com/book/en/v2/Git-Branching-Branching-Workflows*](https://git-scm.com/book/en/v2/Git-Branching-Branching-Workflows).

[^15]: Siehe [*https://zenodo.org/*](https://zenodo.org/).

[^16]: Vgl.
    [*https://guides.github.com/activities/citable-code/*](https://guides.github.com/activities/citable-code/),
    siehe jetzt auch
    [*https://blogs.tib.eu/wp/tib/2018/03/21/konkrete-ratschlaege-fuer-nachhaltigere-wissenschaftliche-softwareprojekte/*](https://blogs.tib.eu/wp/tib/2018/03/21/konkrete-ratschlaege-fuer-nachhaltigere-wissenschaftliche-softwareprojekte/).

[^17]: Siehe
    [*https://github.com/cucumber/cucumber/wiki/Gherkin*](https://github.com/cucumber/cucumber/wiki/Gherkin).

[^18]: Behavior Driven Development, vgl. [*https://dannorth.net/introducing-bdd/*](https://dannorth.net/introducing-bdd/).

[^19]: A php framework for autotesting your business expectations,
    siehe
    [*http://behat.org/en/latest/*](http://behat.org/en/latest/).

[^20]: Siehe
    [*https://www.djangoproject.com/*](https://www.djangoproject.com/).

[^21]: Siehe [*http://exist-db.org/*](http://exist-db.org/).

[^22]: Siehe [*https://typo3.org/*](https://typo3.org/).

[^23]: Vgl. Schrade, Torsten: Sammlungs- und Editionsportale mit dem
    Cultural Heritage Framework der Digitalen Akademie. Vortrag im
    Rahmen des Workshops „Editionsportale" an der Universität Jena,
    03.-04.08.2017, URL:
    [*https://digicademy.github.io/2017-editionsportale-jena/*](https://digicademy.github.io/2017-editionsportale-jena/),
    Step 14-19.

[^24]: Vgl. ediarum - eine digitale Arbeitsumgebung für
    Editionsvorhaben, URL:
    [*http://www.bbaw.de/telota/software/ediarum*](http://www.bbaw.de/telota/software/ediarum).

[^25]: Vgl. Druskat, Stephan et al.: A standard format for CITATION
    files, URL:
    [*https://www.software.ac.uk/blog/2017-12-12-standard-format-citation-files*](https://www.software.ac.uk/blog/2017-12-12-standard-format-citation-files).

[^26]: Siehe
    [*https://www.python.org/dev/peps/pep-0008/*](https://www.python.org/dev/peps/pep-0008/).

[^27]: Siehe
    [*https://eslint.org/docs/about/*](https://eslint.org/docs/about/)
    als Beispiel für einen *JavaScript-Linter*, allgemein zu *lint* bzw.
    *linting*:
    [*https://de.wikipedia.org/wiki/Lint\_(Programmierwerkzeug)*](https://de.wikipedia.org/wiki/Lint_(Programmierwerkzeug)).

[^28]: Siehe
    [*https://dev.to/raddikx/dont-document-your-code-code-your-documentation*](https://dev.to/raddikx/dont-document-your-code-code-your-documentation)
    (vgl. auch die Diskussion in den Kommentaren),
    [*http://www.yacoset.com/Home/inline-documentation*](http://www.yacoset.com/Home/inline-documentation),
    [*https://make.wordpress.org/core/handbook/best-practices/inline-documentation-standards/*](https://make.wordpress.org/core/handbook/best-practices/inline-documentation-standards/).

[^29]: [*https://blog.readme.io/documenting-your-api-in-your-code-with-swagger/*](https://blog.readme.io/documenting-your-api-in-your-code-with-swagger/).

[^30]: Siehe
    [*https://de.wikipedia.org/wiki/Entwurfsmuster*](https://de.wikipedia.org/wiki/Entwurfsmuster).

[^31]: Siehe
    [*https://www.clarin-d.net/*](https://www.clarin-d.net/).

[^32]: Siehe [*https://de.dariah.eu/*](https://de.dariah.eu/).
