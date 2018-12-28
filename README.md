# Agile Development Fusion Model

---

_Das agile Software-Entwicklungs-Framework von Stocard ist eine Fusion von verschiedenen agilen Methoden, wie Scrum, Kanban und Xtreme Programming. Stocard startet mit einem Modell, welches sich annähernd als Scrum-Ban beschreiben lässt. Dabei wurden Tickets auf Plattformen aufgeteilt. In einwöchigen Sprints wurden diese relativ kleinen Tasks abgerabeitet. Wenn mehrere Plattformen beteiligt waren, wurde das Ticket der Plattform mit dem höchsten Arbeitsanteil zugewiesen. Mit dem Wachstum Unternehmens stellten sich immer mehr Probleme ein, welche eine effiziente und agile Arbeitweise erschwerten. Es wichtiger eine längerfristige strategische Ausrichtung zu entwickeln, daraus mittelfristige Ziele anhand von Marktuntersuchungen und -vorhersagen zu definieren und diese in einzelne Projekte zu übersetzen. Diese Projekt konnten die Sprintzyklen nicht mehr einhalten und mussten zunehmend über viele Plattformen hinweg organisiert werden._

---


## Quellen

Das vorgestellte agile Software-Entwicklungs-Framework wurde durch das agile Modell und der Unternehmenskultur von Spotify inspieriert:

- [Spotify Engineering Culture (Part 1)](https://vimeo.com/85490944)
- [Spotify Engineering Culture (Part 2)](https://vimeo.com/94950270)


## Aufbau und Struktur

Der ehemalige einwöchige Sprint-Zyklus wird in veränderter Form beibehalten. Wöchentlich (Montag morgens) findet ein sogenanntes Quest Standup Meeting statt, bei dem die Quest-Leader den Fortschritt, die aktuellen Probleme und mögliche Verzögerungen ihrer Quests vortragen. Außerdem tragen die Acedmies den Fortschritt ihrer Bemühungen bezüglich _Groom, Evolve, Support_ vor. Im Quest Standup findet zusätzlich eine Abwandlung einer Retrospektive statt, indem Probleme, die auf Questebene stattgefunden haben, beleuchtet werden.

Monatlich Findet außerdem ein Quest Pipeline Meeting statt, bei dem neue Quests gepitcht werden. Außerdem werden genehmigte Quest für den Start vorbereitet, d.h. u.A. mit Quest-Party Membern bestückt.

##### Academy

- Zuständig für eine Plattform oder einen Bereich (bspw. iOS, Backend oder Business Development)
- Betreibt eigenständig Plattformpflege und Weiterentwicklung des Verantwortungsbereichs in Übereinstimmung mit den strategischen Zielen des Unternehmens (Groom, Evolve, Support)
- Betreibt ein wöchentliches Planning-Meeting, um Heroes Aufgaben für den aktuellen Zyklus zuzuordnen
- Betreibt ein wöchtenliches Retrospektive-Meeting

##### Hero

- Gehört einer Academy an
- Ist Experte auf dem Gebiet seiner Academy

##### Quest

- Ein Pojekt mit bestimmter Laufzeit und mit Beitrag zu den strategischen Zielen des Unternehmens
- Ist spezifisch, planbar und messbar
- In einem montlichen Quest-Pipeline-Meeting werden freie Kapazitäten mit Quests bestückt

##### Quest-Guide

- Behält den Überblick über den Quest-Fortschritt
- Stellt den Quest-Fortschritt im wöchentlichen Quest-Standup vor
- Koordiniert wöchentliche Meetings innerhalb der Quest, in denen wichtige technische und organisatorische Entscheidungen getroffen werden und in denen der aktuelle Fortschritt der einzelnen Heroes mitgeteilt wird
- Sorgt dafür, dass die Quest-Party ungestört arbeiten kann

##### Quest-Party

- Teilnehmer einer Quest
- Teilnehmer bearbeiten das Quest eigenverantwortlich
- Zusammengesetzt aus Mitgliedern verschiedener Akademien

##### Quest Pipeline Meeting

- Findet monatlich statt
- Dient dazu neue Quests zu pitchen und ggf. in die Pipeline aufzunehmen
- Hat eine Quest-Planning-Komponente: Es werden Quests aus der Pipeline ausgewählt, die als nächstes beginnen sollen, sobald die benötigten Kapazitäten frei werden

##### Quest Standup

- Findet wöchentlich am Montag Morgen statt
- Quest-Guides stellen den Status und Fortschritt, sowie ggf. Verzögerungen der aktuell laufenden Quests vor
- Academies berichten kurz über die Anstrengungen hinsichtlich Groom, Evolve und Support
- Bugtickets werden an die Acadmies verteilt (Bugtickets werden zentral gesammelt und erst beim nächsten Quest Standup aufgegriffen)
- Vorkommnisse der vergangen Woche werden reflektiert
- Es findet eine Retrospektive bezüglich des Quest-Prozesses statt


## Vergleich mit agilen Methoden

##### Scrum

- Academies betreiben wöchentliche Planning-Meetings für Academy-Tickets
- Academies betreiben wöchentliche Reviews/Retrospektiven


- Quick planning sessions
- Keine Daily Meetings

##### Kanban

- Academies verwalten Tickets auf einem öffentlichen Kanban-Board

##### Extreme Programming

###### Prinzipien

Das vorgestellte Modell stimmt im Wesentlichen mit den Prinzipien von Extreme Programming überein:

- __Simplicity:__ Academies pflegen und erweitern ihre Code-Base mit Hinsicht darauf, keinen unnötigen Code zu beinhalten. Statt ROI direkt zu maximieren, ist das oberste Ziel für Quests Retention zu verbessern. Die Anzahl der aktiven Nutzer ist ausschlaggebend für den Erfolg des Unternhemens.
- __Communication:__ Tägliche zusammenarbeit und Kommunikation wird durch gemeinsame Präsenzzeiten, zusammengelegte Arbeitsplätze und spezifische Slack-Channel für Academies, Quests, etc. gewährleistet. Kommunikation findet immer öffentlich statt und bietet somit Personen in die Kommunikation einzusteigen, sodass Wissen erweitert werden kann.
- __Feedback:__ Academies erstellen wöchentlich Beta Versionen. Außerdem gibt es eine Development-Umgebung, die das Produktiv-Backend spiegelt und dazu dient frühzeitig lauffähige Zwischenstände zu testen. Zusätzlich werden CI-Werkzeuge eingesetzt, um Tests und Linter möglichts früh (sobald ein PR geöffnet wird) und automatisiert laufen zu lassen. In der Zukunft sind automatisierte Beta-Builds geplant.
- __Respect:__ Academies arbeiten eigenverantwortlich und treffen Entscheidung bezüglich Architektur, eingesetzter Tools, Sprachen und Frameworks selbst. Geteilte Code-Ownership wird praktiziert, sodass jeder Mitarbeiter jederzeit jeden Code ändern kann. Qualität wird durch Peer-Reviews gewährleistet, bzw. bei Academy-Übergreifender Arbeit durch einen Fachkundigen Mitarbeiter.
- __Courage:__ Alle Mitarbeiter teilen das Verständnis, dass Fehler und Probleme möglichst schnell offengelegt werden müssen, um diese zu beseitigen, bevor es zu noch größerem Aufwand oder Schäden kommt. Es wird eine Atmosphäre gepflegt in der keine Eitelkeit aufkommt, sondern Sachlichkeit überwiegt. Fehler kommen vor, der richtige Umgang damit ist die Hauptsache.

###### Praktiken

| Status | Prinzip |
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
|   | Alle Code Bases werden kontinuierlich erweitert, refactored und die Architekturen werden langsam angepasst, um den immer neuen Anforderungen im schnelllebigen Markt gerecht zu werden. Dies schließt verwendeteProjektmanagementansätze, Programmier-Sprachen, Werkzeuge, Frameworks und Archtekturen ein. Die Mitarbeiter bilden sich stetig weiter und beobachten Best Practices in vergleichbaren Unternhemen. |