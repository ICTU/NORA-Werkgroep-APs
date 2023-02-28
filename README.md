# NORA-Werkgroep-APs
Werkmodel van de [NORA werkgroep Architectuur Principes](https://www.noraonline.nl/wiki/Werkgroep_NORA_Architectuur_Principes). Dit werkmodel is ontwikkeld in Archi en kan hiermee vanuit deze Github repository worden geopend (read only) en geauthoriseerde gebruikers kunnen het bijwerken. Hiervoor is het nodig om Archi te downloaden en de coArchi plugin te installeren. Hoe dit werkt, zie https://www.archimatetool.com/plugins/ en https://github.com/archimatetool/archi-modelrepository-plugin/wiki

Gebruik niet de nieuwe Specialization feature van Archi, deze wordt nog niet ondersteund i.c.m. coArchi.

Dit werkmodel is niet het officiële kanaal waarmee NORA wordt gecommuniceerd. Ga hiervoor naar https://www.noraonline.nl/wiki/NORA_online

Deze repository bevat een aantal folders. De [model] folder bevat het Archimate master model. De andere folders zijn exports / afgeleide producten uit dit model.

## model
Deze bevat het Archimate model zelf en kan alleen vanuit Archi worden geopend. Dit is dus het master model. Alle andere folders zijn handmatige exports en afgeleiden uit dit model en zijn daarom niet gegarandeerd geheel up to date. Pas bestanden in deze folder nooit handmatig aan!

## csv
Export naar csv uit Archi en kan gebruikt worden als basis voor analyse:
elements.csv bevat alle elementen (zoals architectuurprincipes).
relations.csv bevat de relaties tussen de elementen.
properties.csv bevat attributen voor de elementen (niet gebruikt in dit model).
Let op, bij export uit Archi, kies semicolon als separator (;) en codering UTF-8.

## excel
Deze bevat een Excel sheet met data-koppelingen naar de drie bovengenoemde csv's, inclusief kruistabellen. Logica zit geheel in PowerQuery. Download deze Excel en ververs (Refresh) de data met de Refresh knop in de Data tab.

## xml
Export naar xml uit Archi (als Open Exchange Format) en naar .archimate (Archi formaat). Het XML formaat kan worden geopend in ArchiMate tools die dit open formaat ondersteunen (zoals BiZZdesign). In BiZZdesign Enterprise Studio, importeer het xml bestand met de functie 'Import ArchiMate model exchange file' (in het ArchiMate menu). Let op: Download het bestand vanuit de RAW view (en vanuit hier Save as...).

## png
PNG export van alle Views uit het Archimate model.

## word
Word mailmerge exports. Bron hiervoor is de [excel]. Bestanden eindigend op [...Output.docx] bevatten de export.

## PowerBI rapport op de CSV export
Experimenteel [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWU5M2VjMjMtNjU5Yy00NDNmLWIwNjUtMTg3NzFhNTFmMWNkIiwidCI6ImUyMjQ0NWVmLTJkOTYtNDY1My04OTlkLWRhMWQxNGVjYzNiYyIsImMiOjl9) die het makkelijk maakt door de NORA principes te bladeren

