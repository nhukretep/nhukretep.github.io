---
layout: post
title:  "Mein Einstieg in E-Government"
date:   2018-02-28 20:30:00 +0000
categories: blog
---



Seit Anfang des Jahres mache ich Station in mehreren Behörden und öffentlichen Einrichtungen mit dem Fokus **eGovernment und Digitalisierung**. Im Folgenden möchte ich Infos und Materialien teilen, die bei meiner Arbeit entstehen. Weitere Eindrücke poste ich auf **[Twitter](https://twitter.com/nhukretep)**.

## Station 1: Gemeinde

Vom 19. bis 23. Februar 2018 war ich in einer kleinen Gemeinde in Baden-Württemberg. In den einzelnen Ämtern konnte mit den jeweiligen Mitarbeiterinnen und Mitarbeitern über ihre Aufgaben mit Blick auf Digitalisierung und eGovernment reden und dabei Herausforderungen und Chancen diskutieren. 

Themen waren u.a.:

* Die **Herausforderungen für kleine Kommunen**, mit begrenzten Ressourcen den Überblick zu behalten und Prioritäten zu setzen
* Fehlende Anlaufstellen bei Fragen und Problemen
* Die Rolle des kommunalen Rechenzentrums als Dienstleister
* Eigene Webseite vs. service-bw.de: Welche Infos und Dienstleistungen sollten über welches Angebot laufen?


Ergebnis der Woche war eine Handreichung, die kleinen Kommunen einen Überblick über Digitalisierung und eGovernment Themen verschaffen soll. Auch Vorschläge für konkrete Schritte zur kurz-, mittel- und langfristigen Vorgehensweise sind enthalten.

## Station 2: Landratsamt

Vom 26. Februar bis zum 9. März 2018 war ich bei einem Landratsamt in Baden-Württemberg. Hier ging es um die Einführung der **E-Akte**. Konkret habe ich mich mit der Frage beschäftigt, wie die **Einführung auf Fachdienst-Ebene** vorbereitet werden kann. Entstanden ist ein Muster-Einsatzkonzept, das anhand eines Fragenkatalogs den konkreten Einsatz der E-Akte für den jeweiligen Fachdienst erarbeitet.

## Station 3: Metropolregion Rhein-Neckar

Bei der Metropolregion Rhein-Neckar in Mannheim war ich vom 12. März bis zum 20 April. Ziel der 6 Wochen war die Konzeption einer Kooperationsplattform zur interkommunalen Zusammenarbeit. Der dabei entstandene Prototyp lässt sich unter [digitale-mrn.de](https://www.digitale-mrn.de) aufrufen.

*Im Magazin "Econo Rhein-Neckar" ist zur Kooperationsplattform der Metropolregion Rhein-Neckar ein Artikel erschienen, der [hier](https://www2-mannheimer-morgen.morgenweb.de/anzeigen/beilagen/201805_econo/index.html#page_46) gelesen werden kann.*

#### Doodle und die öffentliche Verwaltung

Während in der privaten Wirtschaft Online-Werkzeuge wie Doodle zur Terminfindung oder Dropbox zum Teilen von Dokumenten weit verbreitet sind, ist deren Nutzung in der öffentlichen Verwaltung problematisch. Das liegt insbesondere an fehlendem Datenschutz, weshalb solche Tools in vielen Verwaltungen nicht erlaubt sind. Rechtssichere Alternativen gibt es jedoch auch keine, was zur Folge hat, dass Doodle und Co. in der öffentlichen Verwaltung entweder gar nicht oder im rechtlichen Graubereich verwendet werden. 

Alternativen zu schaffen, wäre technisch kein Problem. Beispielsweise gibt es mit [bitpoll](https://github.com/fsinfuhh/BitPoll) eine Open Source Lösung der Fachschaft Informatik an der Uni Hamburg, die als Doodle-Alternative geeignet und von der öffentlichen Verwaltung zur Terminfindung betrieben werden könnte. Auch für anderen Online-Werkzeuge gibt es solche Möglichkeiten.

#### Projekt Kooperationsplattform

![screenshot-plattform](media\screenshot-plattform.png)Wie die meisten Verwaltungen stehen auch die Kommunen der Metropolregion Rhein-Neckar vor Problem Doodle nicht nutzen zu können, weshalb jetzt eine Kooperationsplattform geschaffen werden soll, die solche Online-Werkzeuge für eine Nutzung in der öffentlichen Verwaltung verfügbar macht.

> #### Die Metropolregion Rhein-Neckar
>
> Die [Metropolregion Rhein-Neckar](https://m-r-n.com) beschäftigt sich bereits seit über 10 Jahren mit eGovernment und der Digitalisierung der öffentlichen Verwaltung.  Ein Team von ca. 10 Personen arbeitet dort unter der Leitung von Marco Brunzel auf allen Feldern der öffentlichen Digitalisierung – von Bau über Verkehr bis hin zur Verwaltungsprozessen. Die Rhein-Neckar Region ist digitale Modellregion der Bunderegierung und Erprobungslabor vieler neuer Ideen.
>
> Das Besondere an der Arbeit der Metropolregion ist die enge Zusammenarbeit zwischen den Städten und Gemeinden. In mehreren Arbeitskreisen, die sich regelmäßig treffen und von Brunzels Team koordiniert werden, werden Erfahrungen ausgetauscht und gemeinsame Projekt vorangetrieben. Eines der bekanntesten Ergebnisse dieser Zusammenarbeit ist der Handwerkparkausweis, der in jeder Kommune der Region beantragt werden kann und dann für alle Städte und Gemeinden Gültigkeit besitzt.

An diesem Projekt durfte ich 6 Wochen im Team der Metropolregion mitarbeiten und herausgekommen ist ein Konzept, das aufzeigt, wie eine solche Plattform umgesetzt werden könnte. Mithilfe von Interviews und Workshops konnten u.a. drei Prämissen für das Projekt abgeleitet werden:

* *Datenschutz:* Die Datenschutzvorkehrungen der Plattform sollen höchsten Standards entsprechen, um eine sicher Nutzung zu gewährleisten.
* *Open Source:* Statt eine eigene Lösung neu zu bauen sollen vorhandene Open Source Lösungen verwendet werden.
* *Modularität:* Um einen stetigen Ausbau der Plattform zu ermöglichen soll eine modulare Architektur genutzt werden, die erlaubt weitere Funktionalitäten ohne großen Aufwand hinzuzufügen.

#### Module der Plattform

Die gewünschten Funktionalitäten der Plattform wurden in einer Prioritätenliste zusammengefasst. Zu den wichtigsten Modulen gehören demnach geschlossene Projekträume, eine Daten-Cloud zum Teilen von Dokumenten, eine gemeinsame Dokumentenbearbeitung und ein Tool zur Terminfindung. Weiterhin sind Umfragen, Wikis und Pads von Nutzen. Auch über Werkzeuge zur Prozessmodellierung, zum Erstellen von Mindmaps und zum Live-Voting sowie für Projektmanagement wurde nachgedacht.

Der Prototyp wurde in Kooperation mit einem lokalen Rechenzentrum umgesetzt und besteht aus Open Source Lösungen, die auf einem Dashboard gebündelt wurden. Er lässt sich unter der folgendem [Link](https://www.digitale-mrn.de) abrufen.

#### Weiteres Vorgehen

Zur Zeit sucht die Metropolregion Rhein-Neckar nach Partnern für weitere Schritte, nach Möglichkeit soll die Plattform schon bald die Arbeit der Arbeitskreise unterstützen.
