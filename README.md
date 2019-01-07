# Agile Development Fusion Model

---

_Das vorgestellte agile Software-Entwicklungs-Framework ist eine Fusion von verschiedenen agilen Methoden, wie Extreme Programming, Scrum und Kanban. Viele Startups beginnen mit einem Framework, welches sich annähernd als Scrum-Ban beschreiben lässt. Als Beispiel diene eine junge Firma, die eine innovative App für verschiedene mobile Plattformen entwickelt. Typischerweise wird ein Product Backlog gepflegt, welches Stories für kommende Features und für andere Tasks enthält. In wöchentlichen Sprints werden diese abgearbeitet. Dabie wird ein Kanban-Board mit den Spalten "Backlog" (Product Backlog), "To Do" (Sprint Backlog), "In Progress", "Blocked", "Testing" und "Done" geführt. Es gibt zusätzlich Swim Lanes für die einzelnen Plattformen. In einem wachsenden Unternehmen kann ein derartiger Ansatz zunehmend die Effizienz und Effektivität behindern. Es wichtiger eine längerfristige strategische Ausrichtung zu entwickeln, daraus mittelfristige Ziele anhand von Marktuntersuchungen und -vorhersagen zu definieren und diese in einzelne Projekte zu übersetzen. Diese Projekt konnten die Sprintzyklen nicht mehr einhalten und mussten zunehmend über viele Plattformen hinweg organisiert werden._

---


## Quellen

Das vorgestellte agile Software-Entwicklungs-Framework wurde durch das agile Modell und der Unternehmenskultur von Spotify inspieriert:

- [Spotify Engineering Culture (Part 1)](https://vimeo.com/85490944)
- [Spotify Engineering Culture (Part 2)](https://vimeo.com/94950270)


## Komponenten und Aufbau

Der ehemalige einwöchige Sprint-Zyklus wird in veränderter Form beibehalten. Wöchentlich (Montag morgens) findet ein sogenanntes Quest Standup Meeting statt, bei dem die Quest Guides den Fortschritt, die aktuellen Probleme und mögliche Verzögerungen ihrer Quests vorstellen. Ggf. werden Quests als beendet erklärt und neue Quests initiiert. Außerdem tragen die Academies den Fortschritt ihrer Bemühungen bezüglich _Evolve, Support, Progress, Maintain_ vor. Im Quest Standup findet zusätzlich eine Abwandlung einer Retrospektive statt, indem Prozess-Probleme, die auf Questebene stattgefunden haben, beleuchtet werden. 

Monatlich findet außerdem ein Quest Pipeline Meeting statt, bei dem neue Quests gepitcht werden und in dem das Quest Product Backlog bereinigt wird. Außerdem werden genehmigte Quest für den Start vorbereitet, u.A. indem ein Startdatum festgelegt wird, nachdem frei werdende Kapazitäten geschätzt wurden.

#### Academy

- Gilt als eigenständiger Bereich und ist selbstorganisiert
- Ist zuständig für eine Plattform oder eine Abteilung (bspw. iOS, Backend oder Business Development)
- Evolve, Support, Progress, Maintain:
	- __Evolve:__ Verbessert den Status Quo und vertieft Fachwissen der Academy Mitglieder für die Academy Domäne
	- __Support:__ Unterstützt Quest Parties, falls zusätzliches Know-How oder Domänen-Wissen benötigt wird
	- __Progress:__ Pflegt den Output von Quests in die Code Base ein, schlägt neue Quests vor
	- __Maintain:__ Betreibt Pflege und Weiterentwicklung des Verantwortungsbereichs in Übereinstimmung mit den strategischen Zielen des Unternehmens (dabei müssen große Arbeitspakete als Quests deklariert werden und gelten nicht also Academy-Tasks)
- Verwaltet ein eigenes Product Backlog (Academy Product Backlog) (enthält nur Tasks und Arbeitspakete mit Bezug auf Plattformpflege und -weiterentwicklung)
- Betreibt ein wöchentliches Planning Meeting, um Heroes Aufgaben für den aktuellen Zyklus zuzuordnen
- Betreibt ein wöchtenliches Meeting für Mid-Term-Planning, ein Review und eine Retrospektive
- Tasks werden auf einem internen Kanban Board festgehalten

#### Hero

- Gehört einer Academy an
- Ist Experte auf dem Gebiet seiner Academy, bspw. der iOS Entwicklung

#### Quest

- Ein Pojekt (großes Arbeitspaket) mit bestimmter Laufzeit und mit Beitrag zu den strategischen Zielen des Unternehmens
- Quests werden aus Taktiken abgeleitet, welche ihrerseits das Ziel haben, die strategischen Ziele des Unternehmens erfüllen
- Ist relevant, messbar (Fortschritt und Erfolg), zeit-gebunden und erreichbar
- In einem montlichen Quest Pipeline Meeting werden freie Kapazitäten mit Quests bestückt
- Betreibt ein wöchentliches Meeting für die Planung und ein Review, sowie die Besprechung von Interna (technische und organisatorische Entscheidungen)

#### Doomsday Quest

- Spezielles Quest, welches unverzüglich begonnen und durchgeführt werden muss, da es sonst das Fortbestehen des Produkts gefährdet
- Kann jederzeit initiiert werden
- Blockiert automatisch alle anderen Quests von denen Heroes abgezogen werden

#### Reactive Quests

- Spezielles Quest, welches nicht gepitcht werden muss und automatisch in das Product Backlog aufgenommen wird (mit hoher Priorität)
- Reagiert auf geänderte Anforderungen, die während einer bestehenden oder seit dem Abschluss einer Quest an einem relevanten Teilprodukt aufgekommen sind.

#### Bug/Issue Quests

- Spezielles Quest, welches nicht gepitcht werden muss und automatisch in das Product Backlog aufgenommen wird (mit hoher Priorität)
- Wird für größere Probleme initiiert, die nicht als Academy Task eingestuft werden können

#### Quest Guide

- Quest Guides sind Heroes, die für die Dauer des Quests als Leiter bestimmt werden
- Behält den Überblick über den Fortschritt des Quests und über KPIs, die den Quest_Erfolg messen
- Stellt den Fortschritt im wöchentlichen Quest Standup Meeting vor
- Betreibt eine Risiko-Analyse und kommuniziert Risiken
- Koordiniert die wöchentliche quest-internen Meetings
- Sorgt dafür, dass die Quest Party ungestört arbeiten kann (a.A. durch Maintenance von (internen) Tools)

#### Quest Party

- Gruppe an Teilnehmern einer Quest
- Zusammengesetzt aus Heros verschiedener Academies 
- Bearbeitet das Quest eigenverantwortlich und selbstorganisiert

#### Quest Backlog Meeting

- Findet monatlich direkt vor dem Quest Pipeline Meeting statt
- Durchführung des Product Backlog Groomings

#### Quest Pipeline Meeting

- Findet monatlich direkt im Anschluss an das Quest Backlog Meeting statt
- Dient dazu neue Quests vorzustellen und ggf. in das Product Backlog aufzunehmen
- Es werden Quests aus der Pipeline ausgewählt, die als nächstes beginnen sollen, sobald die benötigten Kapazitäten frei werden

#### Quest Standup Meeting

- Findet wöchentlich am Montag Morgen statt
- Quest Guides stellen den Status und Fortschritt, sowie ggf. Verzögerungen der aktuell laufenden Quests vor
- Academies berichten kurz über die Anstrengungen hinsichtlich Groom, Evolve und Support
- Bugtickets werden an die Acadmies verteilt (Bugtickets werden zentral gesammelt und erst beim nächsten Quest Standup vorgestellt)
- Vorkommnisse der vergangenen Woche werden reflektiert
- Es findet eine Retrospektive bezüglich des Quest-Prozesses statt


## Vergleich mit agilen Modellen

Das Agile Development Fusion Model vereint Komponenenten verschiedener agiler Methoden direkt oder in angepasster Form. Die Hauptgrundlagen stellen dabei Scrum, Kanban und Extreme Programming dar.

#### Scrum

###### Rollen

Es gibt starke Parallelen zu den durch Scrum definierten Rollen, der Definition wird allerdings nicht strikt gefolgt:

| Status | Rolle |
|:-:|---|
| ⚠️ | __Scrum Team__ |
|   | Es gibt zwei Arten von scrum-ähnlichen Teams. Zum einen gibt es Academies, die fest für einen Aufgabenbereich zuständig sind. Des Weiteren sind Quest Parties Scrum Teams sehr ähnlich, bestehen jedoch nur für die Dauer der Quest. Quests setzten sich über den Sprint Zyklus hinweg. Die Vorgehensweise innerhalb einer Quest ähnelt jedoch dem Scrum Prozess. Die Quest Party wird für die Dauer der Quest zu einem Scrum Team und strukturiert den internen Arbeitsfluss anhand der 1-wöchigen Sprints. |
| ❌ | __Product Owner__ |
|   | Einen Product Owner per reiner Scrum Definition gibt es nicht. In kleinen Firmen, die ein Produkt für sich selber entwickeln, übernehmen die CEOs und das gesamte Team diese Rolle. Da die CEOs an Quest Standups und Quest Pipeline Meetings teilnehmen und die strategischen Ziele vorgeben, sind sie Entscheider für die Weiterentwicklung und Ausprägung des Produkts. Sie beeinflussen jedoch nicht alleine das Product Backlog, alle Heros nehmen am Quest Pipeline Meeting teil. Innerhalb von Quests werden diese Interessen durch die Quest Guides vertreten. Daher gibt es keinen Product Owner im klassischen Sinne von Scrum. Die typischen Interessen eines Product Owners werden jedoch im Unternehmen durch verschiedene Personen verfolgt. Innerhalb von Quests, sowie Academies geschieht dies für die jeweiligen Teilprodukte vornehmlich, aber nicht auschschließlich, durch Quest Guides bzw. Academy Heads. |
| ⚠️ | __Scrum Master__ |
|   | Lead Entwickler bzw. Academy Heads und Quest Guides nehmen Aufgaben in Bezug auf Prozess-Coaching und Überprüfung der Prozesseinhaltung wahr. Außerdem vermitteln Sie zwischen den Teams und den CEOs, bspw. betreffend interner Entscheidungen und deren Einfluss auf das Product Backlog. |
| ⚠️ | __Team Member__ |
|   | Sowohl die Team-Mitglieder von Academies, als auch von Quests sind Heroes. Sie erfüllen dort Aufgaben, ähnliche derer, die durch Scrum definiert sind. Dies beinhaltet die Priorisierung von Backlog Items während verschiedener Planning Meetings und dem Bearbeiten zugehöriger Tickets. |

###### Ereignisse

Innerhalb der Academies werden typische Scrum Ereignisse verwendet, um Arbeitspakete zu planen und zu managen. Quests halten den Wochenzyklus in iherer Gesamtheit nicht ein, nutzen ihn jedoch für ihre interne Strukturierung, sowie für Reviews. Innerhalb von Quests gibt es eine lose Zusammenstellung von Arbeitspaketen in einem Backlog, die während der Quest-Laufzeit abgearbeitet werden. Außerdem werden in quest-internen, wöchentlichen Meetings grobe Ziele für die Arbeitung dieser Arbeitspakete während der geplanten Wochenzyklen gesetzt.

| Status | Ereignis |
|:-:|---|
| ⚠️ | __Sprints__ |
|   | Es finden 1-wöchige Sprints statt, die jedoch für Quests anders gehandhabt werden, als für Academies. Academies folgen strikt dem 1-wöchigen Zyklus. Quests sind eigene Zyklen, wie Sprints für bestimmte Sub-Produkte innerhalb des Produkts. Gleichzeitig sind sie aber auch wie eine Ansammlung von Tickets (Quest-Product Backlog), die über eine bestimmte Anzahl von 1-wöchigen Sprints erledigt werden. Deswegen wird innerhalb von Quests in wöchentlichen Zyklen gearbeitet und Quests nehmen an firmenweiten, wöchentlichen Meetings Teil. |
| ⚠️ | __Sprint Planning__ |
|   | Innerhalb der Academies finden Planning Meetings statt, um Tickets aus dem Academy Backlog für den kommenden Sprint zu priorisieren, Heroes zuzuteilen und in das Sprint Backlog zu verschieben. Innerhalb von Quests finden wöchentliche Meetings statt, die aber nicht nur eine Planning-Komponente haben. U.a. werden dort grob Arbeitspakete aus dem Quest Backlog prioriesiert und geplant. |
| ⚠️ | __Sprint Review__ |
|   | Wöchentlich findet das Quest Standup statt, in dem Quests einen Statusbericht abliefern und Teilprodukte in vortstellen. Academies berichten ebenfalls über ihre Anstrengungen und stellen, wenn passend, Teilprodukte vor. Academies haben zusätzlich ein internes, wöchentliches Meeting, in dem Ergebnisse des Sprints und nötige Änderungen am Academy-Backlog besprochen werden. Diese Meeting erfüllt zusätzlich noch weitere Zwecke, unabhängig vom Sprint Review. |
| ⚠️ | __Daily Scrum__ |
|   | Es finden keine Daily Scrums statt. Jedoch sind Mitarbeiter dazu angehalten in einen spezifischen Slack Channel ihre Tages-Ziele aufzulisten und den Stand (noch nicht begonnen, in Berabeitung, erledigt, blockiert) aktuell zu halten. |
| ⚠️ | __Retrospective__ |
|   | Es finden keine derdizierten Retrospektiven statt. Gibt es Bedarf den Quest-Prozess zu besprechen, so gibt es dazu im Quest Standup die Möglichkeit. Dies wird jedoch übersprungen, sollte es keine Wortmeldungen geben. Innerhalb der Acedmies finden wöchentliche Meetings statt, um die academy-internen Arbeitsprozesse zu besprechen. |
| ⚠️ | __Product Backlog__ |
|   | Sowohl die gesamte Firma, also auch Academies pflegen Backlogs, in denen noch zu erledigende Aufgaben/Tickets/Arbeitspakete gesammelt werden. Für das Unternehmen liegen diese in der Form von Quests vor. |
| ⚠️ | __Sprint Backlog__ |
|   | Quests folgen nicht dem Wochenzyklus, haben jedoch ein Backlog, welches die groben Arbeitsschritte erfasst, die für die Erfüllung des Quest-Ziels erledigt werden müssen. Wann diese Schritte erledigt werden und welche Reihenfolge dabei besteht wird nur grob innerhalb der wöchentlichen, quest-internen Meetings besprochen. Academies führen ein wochentliches Planning Meeting durch, in dem Academy-Tickets aus dem Academy Product Backlog zur Bearbeitung innerhalb des betreffenden Zykluses ausgewählt werden und somit in das Sprint Backlog aufgenommen werden. |

###### Prinzipien

| Status | Prinzip |
|:-:|---|
| ✅ | __Scrums Teams sind selbstorganisiert__ |
|   | Scrum Teams entscheiden selbstbestimmt darüber, wie sie die anstehenden Aufgaben angehen und welche Werkzeuge sie einsetzen. Dies ist sowohl für Academies, also auch für Quest Parties der Fall. |
| ✅ | __Scrums Teams sind interdisziplinär__ |
|   | Teams verfügenen über das Know-How, um ihre Aufgaben zu erledigen und sind dabei unabhängig von außenstehenden Personen. Dies ist sowohl für Academies, also auch für Quest Parties der Fall. |

#### Kanban

###### Kanban Board auf Unternehmens-Ebene

Auf Unternehmens-Ebene wird ein digitales Kanban-Board geführt. Die Einheit für Tickets sind dabei nicht Arbeitspakete oder Tasks, sondern Quests. Das "Quest Backlog" (Product Backlog) ist dabei nach Priorität geordnet. Weitere Spalten des Kanban-Boards sind "Running Quests" (In Progress) und "Accomplished Quests" (Done). Zwei zusätzliche Spalten dienen als Vortstufe für das Product Backlog und sind relevant für das Quest Pipeline Meeting. Diese sind "Quests Ready To Be Pitched" und "Quests Not Ready To Be Pitched". "Quests Ready To Be Pitched" werden während des Quest Pipeline Meetings vorgestellt und ggf. in das Product Backlog übernommen. Andernfalls müssen sie überarbeitet werden und wandern zunächst zurück in "Quests Not Ready Not To Be Pitched" oder sie werden verworfen. Ziel des Kanban-Boards ist hauptsächlich die Begrenzung des WIPs. Aufgrund von begrenzten Ressourcen können nur eine bestimmte Anzahl an Quests gleichzeitig laufen. Es sollen keine Hero-Engpässe entstehen. Auch sollen keine Heroes ohne Aufgabe sein, da für kein neues Quest alle benötigten Heroes zur Verfügung stehen. Kommen dennoch Stehzeiten vor, sind diese bereits minimiert und können für Academy-Arbeit verwendet werden. Außerdem bauen Quests oftmals auf anderen Quests auf. Wird ein Quest beendet, wird dies im Quest Standup Meeting verkündet und ein neues Quest wird gestartet.  

###### Kanban Board auf Academy-Ebene

Academies gelten als abgetrennte, selbst-verwaltete Bereiche. Als solche haben sie nach Scrum ein eigenes Product Backlog und verwalten ihre Arbeitspakete bzw. Tasks während der Sprints selbst. Für die Visualisierung und die Messung des Fortschritts betreiben Academies ihre eigenen digitalen und öffentlichen Kanban-Boards. Dabei gibt es die Spalten "Backlog" (Product Backlog), "To Do" (Sprint Backlog), "In Progress" und "Done". Sobald der Verantwortliche ein Ticket abgearbeitet hat, wird ein Pull Request geöffnet und ein Peer-Review angefordert. Solange bleibt die Karte in "In Progress". Während dem wöchentlichen Academy Planning Meeting wird die "To Do"-Spalte befüllt und den Tasks werden Heroes zugeteilt. Ziel des Kanban Boards ist nicht den WIP zu begrenzen und einen optimalen Durchfluss zu erreichen. Vielmehr ist die Planung der Prozess, der eine adäquate Auslastung der Heroes sicherstellt. Dabei werden bereits die Teilnahmen an Quests berücksichtigt. Zusätzlich sind die Arbeitspakete der Academies auf Wartungs- und Weiterentwicklungsaufgaben beschränkt. Tasks mit großem Umfang müssen darüber hinaus als Quest initiiert werden, da sie die (Quest-)Planung des gesamten Unternehmens beeinflussen. Academy-Tickets sind daher in ihrem Umfang begrenzt, wodurch es in der Regel nicht zu Durchflussproblemen kommt.

#### Extreme Programming

###### Prinzipien

Das vorgestellte Modell stimmt im Wesentlichen mit den Prinzipien von Extreme Programming überein:

- __Simplicity:__ Academies pflegen und erweitern ihre Code-Base mit Hinsicht darauf, keinen unnötigen Code zu beinhalten. Statt ROI direkt zu maximieren, ist das oberste Ziel für Quests die Retention zu verbessern. Die Anzahl der aktiven Nutzer ist ausschlaggebend für den Erfolg des Unternhemens. Code folgt dem Don't Repeat Yourself Prinzip.
- __Communication:__ Tägliche zusammenarbeit und Kommunikation wird durch gemeinsame Präsenzzeiten, zusammengelegte Arbeitsplätze und spezifische Slack-Channels für Academies, Quests, etc. gewährleistet. Kommunikation findet immer öffentlich statt und bietet somit Personen die Möglichkeit in die Kommunikation einzusteigen, sodass Wissen erweitert werden kann.
- __Feedback:__ Academies erstellen wöchentlich Beta Versionen. Außerdem gibt es eine Development-Umgebung, die das Produktiv-Backend spiegelt und dazu dient frühzeitig lauffähige Zwischenstände zu testen. Zusätzlich werden CI-Werkzeuge eingesetzt, um Tests und Linter möglichst früh (sobald ein Pull Request geöffnet wird) und automatisiert laufen zu lassen. In der Zukunft sind automatisierte Beta-Builds geplant.
- __Respect:__ Academies arbeiten eigenverantwortlich und treffen Entscheidung bezüglich Architektur, eingesetzter Tools, Sprachen und Frameworks selbst. Geteilte Code-Ownership wird praktiziert, sodass jeder Mitarbeiter jederzeit jeden Code ändern kann. Qualität wird durch Peer-Reviews gewährleistet, bzw. bei Academy-Übergreifender Arbeit durch einen Fachkundigen Mitarbeiter.
- __Courage:__ Alle Mitarbeiter teilen das Verständnis, dass Fehler und Probleme möglichst schnell offengelegt werden müssen, um diese zu beseitigen, bevor es zu noch größerem Aufwand oder Schäden kommt. Es wird eine Atmosphäre gepflegt in der keine Eitelkeit aufkommt, sondern Sachlichkeit überwiegt. Fehler kommen vor, der richtige Umgang damit ist entscheidend.

###### Praktiken

| Status | Praktik |
|:-:|---|
| ✅ | __Räumlich zusammen sitzen (sit together)__ |
|   | Alle Academies sitzen in Tischgruppen nahe beieinander. Die Tischgruppen sind so angeordnet, dass Academy-Mitglieder zusammen sitzen. |
| ✅ | __Komplettes Team (whole team)__ |
|   | Mit Ausnahme von Außendienstmitarbeitern, befinden sich alle Angestellten im selben (Großraum-)Büro. |
| ✅ | __Informative Arbeitsumgebung (informative workspace)__ |
|   | Kommunikation erfolgt öffentlich und in geschriebener Sprache in gemeinsamen Slack-Channels. Github Reposistories verfügen über Dokumentation in Readmes und Wikis. Des Weiteren gibt es einen gemeinsamen Datenspeicher und weitere Github Reposistories nur für Dokumentationszwecke oder digitale Kanban-Boards. |
| ✅ | __Energiegeladene Arbeit (energized work)__ |
|   | Mitarbeiter sind angehalten geregelte Arbeitszeiten einzuhalten. Während der Arbeitszeit werden Ablenkungen auf ein Minimum reduzuiert, indem hauptsächlich über Slack kommuniziert wird. Dadurch werden Kollegen nicht aus der Arbeit gerissen und können antworten, wenn sie sich nicht länger in einer Konzentrationphase befinden. Außerdem werden Mitarbeiter motiviert, indem monatlich mehrere Teamevents stattfinden und das Team mit kostenlosen Getränken und Snacks unterstützt wird. |
| ❌ | __Programmieren in Paaren (pair programming)__ |
|   | Es findet kein Parprogramming statt. Allenfalls gibt es vereinzelt Sessions, in denen zu zweit, an einem Computer, ein Problem gelöst wird. Code Reviews werden nach Erledigung eines Arbeitspakets durchgeführt. |
| ✅ | __Geschichten (stories)__ |
|   | User Stories sind Grundlage für alle Quests, die Einfluss auf den Endnutzer haben. |
| ✅ | __Wochenzyklus (weekly cycle)__ |
|   | Innerhalb der Academies, sowie in den Quests wird im wochenzyklus gearbeitet und geplant. Dies wird durch wöchentliche gruppen-interne Meetings, sowie durch das Quest Standup Meeting enforciert. |
| ✅ | __Quartalszyklus (quarterly cycle)__ |
|   | Ein Mal pro Quartal wird ein Meeting einberufen, in dem die Strategischen Ziele des Unternehmens gepflegt, überarbeitet und erweitert werden. Aus den strategischen Zielen leiten sich Taktiken ab, die wiederrum durch daraus entwickelten Quests realisert werden. |
| ❌ | __Freiraum (slack)__ |
|   | Aktuell wird nicht mit Pufferzeiten geplant, wobei bei der Planung der Länge von Quests jedoch versucht wird Probleme zu antizipieren. Geht es dann schneller voran, da Probleme nicht eintreten, so können Academy Tasks durchgeführt werden (auch aus dem Academy Product BAcklog). |
| ⚠️ | __Zehn-Minuten-Build (ten-minute-build)__ |
|   | Dieses Prinzip wird nicht aktiv verfolgt. In der iOS Academy lassen sich aktuell alle Tests und dafür nötigen Schritte in weniger als 10 Minuten durchführen. Dies liegt vielleicht mitunter daran, dass die Testabdeckung noch nicht das gewünschte Level erreicht hat.|
| ⚠️ | __Kontinuierliche Integration (continuous integration)__ |
|   | Je nach Academy gibt werden CI Tools unterschiedloch stark verwendet. Diese Entwicklung voranzutreiben obliegt den Academies. In der iOS Academy laufen Tests und Linter bereits automatisiert, bei Pull Requests auf den Master Branch. In der Zukunft sollen automatisierte Beta Builds folgen. |
| ❌ | __Testgetriebene Entwicklung (test-first programming)__ |
|   | Es wird nicht testgetrieben entwickelt. Tests werden geschrieben, nachdem der Produktiv Code läuft. |
| ✅ | __Inkrementeller Entwurf (incremental design)__ |
|   | Alle Code Bases werden kontinuierlich erweitert, refactored und die Architekturen werden fortwährend angepasst, um den immer neuen Anforderungen im schnelllebigen Markt gerecht zu werden. Dies schließt verwendete Projektmanagementansätze, Programmier-Sprachen, Werkzeuge, Frameworks und Archtekturen ein. Die Mitarbeiter bilden sich stetig weiter und beobachten Best Practices in vergleichbaren Unternhemen. Academies halten Quick Design Sessions ab, um zu besprechen, wie bestimmte Funktionalitäten implementiert werden sollen. Code und Test Code erfüllen das Speaking Code Principle (Code ist selbstdokumendtierend). Außerdem folgt sämtlicher Code Design Styleguides, die durch Linter überprüft werden. |

---

__Legende__:

✅ Stimmt überein, ist erfüllt

⚠️ Stimmt teilweise überein, ist teilweise erfüllt

❌ Stimmt nicht überein, ist nicht erfüllt
