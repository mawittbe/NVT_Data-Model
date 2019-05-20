Ontologie für nonverbales Theater
===================
Im Rahmen des Digitalisierungsprojekts [\"Nonverbales Theater im ehemaligen Ostteil Berlins 1970-1991\"](http://www.mimecentrum.iti-germany.de/nonverbalestheater) an der [Mediathek für Tanz und Theater](https://mimecentrum.iti-germany.de/de/mediathek) des [Deutschen Zentrums des Internationalen Theaterinstituts](https://www.iti-germany.de/home/) entsteht eine Linked-Data Ontologie für die Beschreibung von Objekten und Zusammenhängen des kulturellen Erbes im Bereich darstellende Künste mit Fokus auf nonverbale Formen von Theater. Das Projekt ist gefördert durch das Förderprogramm Digitalisierung von Objekten des kulturellen Erbes Berlin des Forschungs- und Kompetenzzentrums Digitalisierung Berlin (digiS). Die Entwicklung findet in Zusammenarbeit mit Julia Beck vom [Fachinformationsdienst Darstellende Kunst(FID)](https://www.performing-arts.eu/) und Prof. Dr. Bernhard Thull von der Hochschule Darmstadt statt.

Ziel des Projekts ist die Entstehung einer Ontologie für die Beschreibung von Objekt-, Ereignis- und Produktionszusammenhängen im Bereich darstellende Künste. Die Ontologie-Entwicklung orientiert sich an existierenden Modellen wie dem Europeana Data Model (EDM), dem vom Fachinformationsdienst Darstellende Kunst (FID) verwendeten erweiterten EDM-Modell und frbroo.


Vorhaben des Projekts
===================
* Erstellung eines Modells zur einfachen und effizienten Abbildung von Kulturdaten aus dem Bereich der darstellenden Künste,
  dazu gehört die Abbildung von
  * **Produktionen**
  * **Aufführungen** und anderen Ereignissen wie Konferenzen, Ausstellungen etc.
  * **Spielorten** und deren zugehörigen **Städten** und  **Ländern**
  * **Mitwirkungen** von **Personen** und **Companies/Ensembles**
  * **Dokumentierenden Objekten** wie Fotografien, Videoaufzeichnungen, Audiomitschnitten usw.
  * **Künstlerischen Objekten** wie Masken, Kostümen, Requisiten, Skizzen, Modellen usw.
* Mapping der im Digitalisierungsprojekt \"Nonverbales Theater im ehemaligen Ostteil Berlins 1970-1991\" verzeichneten und digitalisierten Objekte des kulturellen Erbes im entwickelten Datenmodell
* Ablage der entstandenen Metadaten online, zugänglich über einen SPARQL-Endpunkt
* Erstellung von Mappings für die Weitergabe der Daten im Europeana Data Model(EDM) sowie für den Fachinformationsdienst Darstellende Kunst(FID)

Das GitHub-Repositorium enthält:
* Beispieldaten für vollständige Zusammenhänge von Entitäten (Produktionen, Ereignisse, Personen, Ensembles, Spielorte, dokumentierende Objekte, künstlerische Objekte, Digitalisate)
* Handbuch für die Verzeichnungsarbeit zu Identifiern, Titeln etc.
* Mappingdokumente sowie entstandene RDF-Daten aus Karma
* Die Ontologie sowie Inferenzregeln für Kompatibilität mit anderen Modellen
* [HTML Dokumentation](https://mawittbe.github.io/NVT_Data-Model/index-en.html) der Ontologie, erstelt mit [widoco](https://github.com/dgarijo/Widoco)
