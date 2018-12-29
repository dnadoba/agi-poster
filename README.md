# Agile Development Fusion Model

---

_Das vorgestellte agile Software-Entwicklungs-Framework ist eine Fusion von verschiedenen agilen Methoden, wie Extreme Programming, Scrum und Kanban. Viele Startups beginnen mit einem Framework, welches sich annähernd als Scrum-Ban beschreiben lässt. Als Beispiel diene eine junge Firma, die eine innovative App für verschiedene mobile Plattformen entwickelt. Typischerweise wird ein Product Backlog gepflegt, welches Stories für kommende Features und für andere Tasks enthält. In wöchentlichen Sprints werden diese abgearbeitet. Dabie wird ein Kanban-Board mit den Spalten "Backlog" (Product Backlog), "To Do" (Sprint Backlog), "In Progress", "Blocked", "Testing" und "Done" geführt. Es gibt zusätzlich Swim Lanes für die einzelnen Plattformen. In einem wachsenden Unternehmen kann ein derartiger Ansatz zunehmend die Effizienz und Effektivität behindern. Es wichtiger eine längerfristige strategische Ausrichtung zu entwickeln, daraus mittelfristige Ziele anhand von Marktuntersuchungen und -vorhersagen zu definieren und diese in einzelne Projekte zu übersetzen. Diese Projekt konnten die Sprintzyklen nicht mehr einhalten und mussten zunehmend über viele Plattformen hinweg organisiert werden._

---


## Quellen

Das vorgestellte agile Software-Entwicklungs-Framework wurde durch das agile Modell und der Unternehmenskultur von Spotify inspieriert:

- [Spotify Engineering Culture (Part 1)](https://vimeo.com/85490944)
- [Spotify Engineering Culture (Part 2)](https://vimeo.com/94950270)


## Aufbau und Struktur

Der ehemalige einwöchige Sprint-Zyklus wird in veränderter Form beibehalten. Wöchentlich (Montag morgens) findet ein sogenanntes Quest Standup Meeting statt, bei dem die Quest-Leader den Fortschritt, die aktuellen Probleme und mögliche Verzögerungen ihrer Quests vortragen. Außerdem tragen die Acedmies den Fortschritt ihrer Bemühungen bezüglich _Groom, Evolve, Support_ vor. Im Quest Standup findet zusätzlich eine Abwandlung einer Retrospektive statt, indem Probleme, die auf Questebene stattgefunden haben, beleuchtet werden.

Monatlich Findet außerdem ein Quest Pipeline Meeting statt, bei dem neue Quests gepitcht werden. Außerdem werden genehmigte Quest für den Start vorbereitet, d.h. u.A. mit Quest-Party Membern bestückt.

#### Academy

- Zuständig für eine Plattform oder einen Bereich (bspw. iOS, Backend oder Business Development)
- Betreibt eigenständig Plattformpflege und Weiterentwicklung des Verantwortungsbereichs in Übereinstimmung mit den strategischen Zielen des Unternehmens (Groom, Evolve, Support)
- Betreibt ein wöchentliches Planning-Meeting, um Heroes Aufgaben für den aktuellen Zyklus zuzuordnen
- Betreibt ein wöchtenliches Mid-Term-Planning-/Review-/Retrospektive-Meeting

#### Hero

- Gehört einer Academy an
- Ist Experte auf dem Gebiet seiner Academy, bspw. der iOS Entwicklung

#### Quest

- Ein Pojekt mit bestimmter Laufzeit und mit Beitrag zu den strategischen Zielen des Unternehmens
- Ist spezifisch, planbar und messbar
- In einem montlichen Quest-Pipeline-Meeting werden freie Kapazitäten mit Quests bestückt

#### Quest-Guide

- Quest guides sind Heroes, die für die Dauer des Quests als Guide bestimmt wurden
- Behält den Überblick über den Quest-Fortschritt
- Stellt den Quest-Fortschritt im wöchentlichen Quest-Standup vor
- Koordiniert wöchentliche Meetings innerhalb der Quest, in denen wichtige technische und organisatorische Entscheidungen getroffen werden und in denen der aktuelle Fortschritt der einzelnen Heroes mitgeteilt wird
- Sorgt dafür, dass die Quest-Party ungestört arbeiten kann

#### Quest-Party

- Teilnehmer einer Quest
- Teilnehmer bearbeiten das Quest eigenverantwortlich
- Zusammengesetzt aus Mitgliedern verschiedener Akademien

#### Quest Pipeline Meeting

- Findet monatlich statt
- Dient dazu neue Quests zu pitchen und ggf. in die Pipeline aufzunehmen
- Hat eine Quest-Planning-Komponente: Es werden Quests aus der Pipeline ausgewählt, die als nächstes beginnen sollen, sobald die benötigten Kapazitäten frei werden

#### Quest Standup Meeting

- Findet wöchentlich am Montag Morgen statt
- Quest-Guides stellen den Status und Fortschritt, sowie ggf. Verzögerungen der aktuell laufenden Quests vor
- Academies berichten kurz über die Anstrengungen hinsichtlich Groom, Evolve und Support
- Bugtickets werden an die Acadmies verteilt (Bugtickets werden zentral gesammelt und erst beim nächsten Quest Standup aufgegriffen)
- Vorkommnisse der vergangen Woche werden reflektiert
- Es findet eine Retrospektive bezüglich des Quest-Prozesses statt


## Vergleich mit agilen Modellen

#### Scrum

###### Rollen

Es gibt starke Parallen zu den durch Scrum definierten Rollen, der Definition wird allerdings nicht strikt gefolgt:

| Status | Rolle |
|:-:|---|
| ⚠️ | __Scrum Team__ |
|   | Es gibt drei Arten von Scrum-Ähnlichen Teams. Zum einen gibt es Academies, die fest für einen Aufgabenbereich zuständig sind. Des Weiteren sind Quest-Parties Scrum Teams sehr ähnlich, bestehen jedoch nur für die Dauer der Quest. Der Prozess innerhalb einer Quest ähnelt jedoch dem Scrum Prozess. Zuletzt agiert auch das Team als ganzes, indem es das Product Backlog beeinflusst. Dies ist eigentlich kein Bestandteil von Scrum, wenn man jedoch den fortlaufenden Strom an Quests und die damit verbundenen monatlichen Pipeline-Meetings als eigenen Scrum-Zyklus auffasst, ist das Product Backlog vielmehr ein Sprint BAcklog dieser Zyklen. Dann wären die strategischen Ziele das eigentliche Product-BAcklog. |
| ⚠️ | __Product Owner__ |
|   | Einen Product Owner per reiner Scrum Definition gibt es nicht. In kleinen Firmen, die ein Produkt für sich selber Entwickeln übernehmen die CEOs diese Rolle. Da sie an Quest-Standups und Quest-Pipeline-Meetings teilnehmen und die strategischen Ziele vorgeben, sind sie Entscheider für die Weiterentwicklung und Ausprägung des Produkts. Innerhalb von Quests werden sie durch die Quest-Guides vertreten. Da sie jedoch nicht alleine das Product-BAcklog beeinflussen, sind sie keine Product Owner im klassischen Sinne von Scrum. Fasst man jedoch, wie oben beschrieben, die strategischen Ziele als eigentliches Product BAcklog auf, so sind die CEOs wiederrum eigenverantwortlich. |
| ⚠️ | __Scrum Master__ |
|   | Lead Entwickler in Acadmies und Quest-Guides von Quest-Parties nehmen Aufgaben in Bezug auf Prozess-Coaching und Überprüfung der Prozesseinhaltung wahr. Außerdem vermitteln Sie zwischen den Teams und den Product Ownern, bspw. betreffend interner Entscheidungen und deren Einfluss auf das Product Backlog. |
| ⚠️ | __Team Member__ |
|   | Sowohl in Academies als auch in Quests sind Heroes die Team-Mitglieder und erfüllen dort ähnliche Aufgaben, wie sie durch Scrum definiert sind. Dies beinhaltet die Priorisierung von Backlog Items während Planning Meetings und dem Berbeiten solcher Tickets. |

###### Ereignisse

Innerhalb der Academies werden typische Scrum Ereignisse verwendet, um Arbeitspakete zu planen. Quests halten den Wochenzyklus nicht ein und nutzen ihn lediglich für Statusberichte. Innerhalb von Quests gibt es eine lose Zusammenstellung von Tickets in einem Backlog, die während der Quest-Laufzeit abgearbeitet werden. Außerdem werden in quest-internen Weekly Meetings ausgehend davon für jeden Wochenzyklus grob Ziele für die Arbeitung dieser Arbeitspakete gesetzt. 

| Status | Ereignis |
|:-:|---|
| ⚠️ | __Sprints__ |
|   | Es finden 1-wöchige Sprints statt, die jedoch für Quests anders gehandhabt werden, als für Academy-Aufgaben. Academies folgen strikt dem 1-wöchigen Zyklus. Quests sind eigene Zyklen, wie Sprints für bestimmte Sub-Produkte innerhalb des Produkts. Gleichzeitig sind sie aber auch wie eine Ansammlung von Tickets (Quest-Product-Backlog), die über eine bestimmte Anzahl von 1-wöchigen Sprints erledigt werden. Deswegen wird innerhalb von Quests in wöchentlichen Zyklen gearbeitet und Quests nehmen an firmenweiten, wöchentlichen Meetings Teil |
| ⚠️ | __Sprint Planning__ |
|   | Innerhalb der Academies finden derartige Meetings statt, um Tickets aus dem Academy Backlog für den kommenden Sprint zu priorisieren und in das Sprint Backlog zu verschieben. Innerhalb von Quests finden wöchentliche Meetings statt, die aber nicht nur eine Planning-Komponente haben. Dort werden grob Arbeitspakete aus dem Quest-Backlog prioriesiert. |
| ⚠️ | __Sprint Review__ |
|   | Wöchentlich findet das Quest-Standup statt, in dem Quests einen Statusberichtabliefern und Teilprodukte in vortstellen. Academies berichten ebenfalls über ihre Anstrengungen und stellen, wenn passen Teilprodukte vor. Academies haben zusätzlich ein internes, wöchentliches Meeting, in dem Ergebnisse des Sprint und nötige Änderungen am Academy-Backlog besprochen werden. Diese Meeting erfüllt zusätzlich noch weitere Zwecke, unabhängig vom Sprint Review. |
| ⚠️ | __Daily Scrum__ |
|   | Es finden keine Daily-Planning-Meetings statt. Jedoch sind Mitarbeiter dazu in einen spezifischen Slack Channel ihre Tages-Ziele aufzulisten und den Stand (noch nicht begonnen, in Berabeitung, erledigt, blockiert) aktuell zu halten. |
| ⚠️ | __Retrospective__ |
|   | Es finden keine derdizierten Retrospektiven statt. Gibt es Bedarf den Quest-Prozess zu besprechen, so gibt es dazu im Quest-Standup die Möglichkeit. Dies wird jedoch übersprungen, sollte es keine Wortmeldungen geben. Innerhalb der Acedmies finden wöchentliche Meetings statt, um die academy-internen Arbeitsprozesse zu besprechen. |
| ⚠️ | __Product Backlog__ |
|   | Sowohl die gesamte Firma, also auch Academies Pflegen Backlogs, in denen noch zu erledigende Aufgaben/Tickets/Arbeitspakete gesammelt werden. Für die Firma liegen diese in der Form von Quests vor. Quests haben ebenfalls ein grobes Backlog, welches die Arbeitspakete enthält, durch deren Abarbeitung das das Quest erfüllt wird. Quests sind quasi ein eigener, unabhängiger Sprint. Daher sind Quest-Backlogs am ehesten mit Sprint Backlogs zu vergleichen. |
| ⚠️ | __Sprint Backlog__ |
|   | Quests folgen nicht dem Wochenzyklus und haben jedoch ein Backlog, welches die groben Arbeitsschritte erfasst, die für die Erfüllung des Quest-Ziels erledigt werden müssen. Wann diese Schritte erledigt werden und welche Reihenfolge dabei besteht wird nur grob innerhalb der wöchentlichen, quest-internen Meetings besprochen. Academies führen ein wochentliches Planning-Meeting durch, in dem Academy-Tickets aus dem Academy-Product-Backlog zur Bearbeitung innerhalb des betreffenden Zykluses ausgewählt werden und somit in das Sprint-BAcklog aufgenommen werden. |

###### Prinzipien

| Status | Prinzip |
|:-:|---|
| ✅ | __Scrums Teams sind selbstorganisiert__ |
|   | Scrum Teams entscheiden selbstbestimmt darüber, wie sie die anstehenden Aufgabe angehen und welche Werkzeuge sie einsetzen. Dies ist sowohl für Academies, also auch für Quest-Parties der Fall. |
| ✅ | __Scrums Teams sind interdisziplinär__ |
|   | Teams verfügenen über das Know-How, um ihre Aufgaben zu erledigen und sind dabei unabhängig von außenstehenden Personen. Dies ist sowohl für Academies, also auch für Quest-Parties der Fall. |



#### Kanban

- Academies verwalten Tickets auf einem öffentlichen Kanban-Board

#### Extreme Programming

###### Prinzipien

Das vorgestellte Modell stimmt im Wesentlichen mit den Prinzipien von Extreme Programming überein:

- __Simplicity:__ Academies pflegen und erweitern ihre Code-Base mit Hinsicht darauf, keinen unnötigen Code zu beinhalten. Statt ROI direkt zu maximieren, ist das oberste Ziel für Quests Retention zu verbessern. Die Anzahl der aktiven Nutzer ist ausschlaggebend für den Erfolg des Unternhemens. Code folgt dem Don't Repeat Yourself Prinzip.
- __Communication:__ Tägliche zusammenarbeit und Kommunikation wird durch gemeinsame Präsenzzeiten, zusammengelegte Arbeitsplätze und spezifische Slack-Channel für Academies, Quests, etc. gewährleistet. Kommunikation findet immer öffentlich statt und bietet somit Personen in die Kommunikation einzusteigen, sodass Wissen erweitert werden kann.
- __Feedback:__ Academies erstellen wöchentlich Beta Versionen. Außerdem gibt es eine Development-Umgebung, die das Produktiv-Backend spiegelt und dazu dient frühzeitig lauffähige Zwischenstände zu testen. Zusätzlich werden CI-Werkzeuge eingesetzt, um Tests und Linter möglichts früh (sobald ein PR geöffnet wird) und automatisiert laufen zu lassen. In der Zukunft sind automatisierte Beta-Builds geplant.
- __Respect:__ Academies arbeiten eigenverantwortlich und treffen Entscheidung bezüglich Architektur, eingesetzter Tools, Sprachen und Frameworks selbst. Geteilte Code-Ownership wird praktiziert, sodass jeder Mitarbeiter jederzeit jeden Code ändern kann. Qualität wird durch Peer-Reviews gewährleistet, bzw. bei Academy-Übergreifender Arbeit durch einen Fachkundigen Mitarbeiter.
- __Courage:__ Alle Mitarbeiter teilen das Verständnis, dass Fehler und Probleme möglichst schnell offengelegt werden müssen, um diese zu beseitigen, bevor es zu noch größerem Aufwand oder Schäden kommt. Es wird eine Atmosphäre gepflegt in der keine Eitelkeit aufkommt, sondern Sachlichkeit überwiegt. Fehler kommen vor, der richtige Umgang damit ist die Hauptsache.

###### Praktiken

| Status | Praktik |
|:-:|---|
| ✅ | __Räumlich zusammen sitzen (sit together)__ |
|   | Alle Academies sitzen in Tischgruppen nahe beieinander. Die Tischgruppen sind so angeordnet, dass Academy-Mitglieder zusammen sitzen. |
| ✅ | __Komplettes Team (whole team)__ |
|   | Mit Ausnahme von Außendienstmitarbeitern, befinden siche alle Angestellten im selben (Großraum-)Büro. |
| ✅ | __Informative Arbeitsumgebung (informative workspace)__ |
|   | Kommunikation erfolgt öffentlich und in geschriebener Sprache in gemeinsamen Slack-Channels. Github Reposistories verfügen über Dokumentation in Readmes und Wikis. Desweiteren gibt es einen gemeinsamen Datenspeicher und weitere Github Reposistories. |
| ✅ | __Energiegeladene Arbeit (energized work)__ |
|   | Es finden monatlich mehrere Teamevents statt, das Team wird mit kostenlosen Getränken und Snacks unterstützt. |
| ❌ | __Programmieren in Paaren (pair programming)__ |
|   | Es findet kein Parprogramming statt. Allenfalls gibt es vereinzelt Session, in denen zu zweit, an einem Computer, ein Problem gelöst wird. Code Reviews werden nach Erledigung eines Arbeitspakets durchgeführt. |
| ✅ | __Geschichten (stories)__ |
|   | User Stories sind Grundlage für alle Quests, die Einfluss auf den Endnutzer haben. |
| ✅ | __Wochenzyklus (weekly cycle)__ |
|   | Innerhalb der Academies, sowie in den Quest Parties wird im wochenzyklus gearbeitet und geplant. Dies wird durch wöchentliche gruppen-interne Meetings, sowie durch das Quest-Standup, bei dem beide Gruppen Bericht erstatten müssen, enforciert. |
| ❌ | __Quartalszyklus (quarterly cycle)__ |
|   | Quartalszyklen haben keinen direkten Einfluss auf das Projektmanagement und das agile Vorgehen. Allerdings finden monatlich Quest-Pipeline Meetings statt. Dort werden zukünftige Quests vorgestellt und entschiedene Quests auf frei werdende Kapazitäten geplant. |
| ❌ | __Freiraum (slack)__ |
|   | Aktuell gibt es während der Arbeit an Academy-Tasks und Quest-Tasks keine möglichkeit eigene Projekt oder Ideen zu verfolgen. |
| ⚠️ | __Zehn-Minuten-Build (ten-minute-build)__ |
|   | Dieses Prinzip wird nicht aktiv verfolgt. In der iOS Academy lassen sich aktuell alle Tests und dafür nötigen Schritte in weniger als 10 Minuten durchführen. Diese liegt vielleicht mitunter daran, dass die Testabdeckung noch nicht das gewünschte Level erreicht hat.|
| ⚠️ | __Kontinuierliche Integration (continuous integration)__ |
|   | Je nach Academy gibt werden CI Tools unterschiedloch stark verwendet. Diese Entwicklung voranzutreiebn obliegt den Academies. In der iOS Academy laufen Tests und Linter bereits automatisiert, bei PRs auf den MAster Branch. In der Zukunft sollen automatisierte Beta Builds folgen. |
| ❌ | __Testgetriebene Entwicklung (test-first programming)__ |
|   | Es wird nicht testgetrieben entwickelt. Tests werden geschrieben, nachdem der Produktiv Code läuft. |
| ✅ | __Inkrementeller Entwurf (incremental design)__ |
|   | Alle Code Bases werden kontinuierlich erweitert, refactored und die Architekturen werden langsam angepasst, um den immer neuen Anforderungen im schnelllebigen Markt gerecht zu werden. Dies schließt verwendeteProjektmanagementansätze, Programmier-Sprachen, Werkzeuge, Frameworks und Archtekturen ein. Die Mitarbeiter bilden sich stetig weiter und beobachten Best Practices in vergleichbaren Unternhemen. Acadmies halten Quick Design Session ab, um zu besprechen, wie bestimmte Elemente implementiert werden sollen. Code und Test Code erfüllen das Speaking Code Principle (ist selbstdokumendtierend). Außerdem folgt sämtlicher Code Design Styleguides, die durch Linter überprüft werden.  |

---

__Legende__:

✅ Stimmt überein, ist erfüllt

⚠️ Stimmt teilweise überein, ist teilweise erfüllt

❌ Stimmt nicht überein, ist nicht erfüllt
