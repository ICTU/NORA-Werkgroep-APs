# NORA-Werkgroep-APs
Werkmodel van de NORA werkgroep Architectuur Principes. Dit werkmodel is ontwikkeld in Archi en kan hiermee vanuit deze Github repository worden geopend (read only) en geauthoriseerde gebruikers kunnen het bijwerken. Hiervoor is het nodig om Archi te downloaden en de coArchi plugin te installeren. Hoe dit werkt, zie https://www.archimatetool.com/plugins/ en https://github.com/archimatetool/archi-modelrepository-plugin/wiki

Dit werkmodel is niet het officiële kanaal waarmee NORA wordt gecommuniceerd. Ga hiervoor naar https://www.noraonline.nl/wiki/NORA_online

Deze repository bevat een drietal folders:

## model
Deze bevat het Archi model zelf en kan vanuit Archi worden geopend. Dit is het meest actuele master bestand.

## csv
Export naar csv uit Archi en kan gebruikt worden als basis voor analyse:
elements.csv bevat alle elementen (zoals architectuurprincipes).
relations.csv bevat de relaties tussen de elementen.
properties.csv bevat attributen voor de elementen, bijvoorbeeld de architectuurlaag bij implicaties.
Deze export loopt mogelijk iets achter bij het actuele master bestand. Let op, bij export, kies semicolon als separator (;) en codering UTF-8.

## excel
Deze bevat een Excel sheet met data-koppelingen naar de drie bovengenoemde csv's, inclusief kruistabellen. Download deze Excel en ververs (Refresh) de data met de Refresh knop in de Data tab.

## xml
Export naar xml uit Archi (als Open Exchange Format). Dit formaat kan worden geopend in ArchiMate tools die dit open formaat ondersteunen (zoals BiZZdesign). In BiZZdesign Enterprise Studio, importeer het xml bestand met de functie 'Import ArchiMate model exchange file' (in het ArchiMate menu).

## png
PNG export van alle Views uit het Archimate model.

## word
Word mailmerge export van alle elementen uit het Archimate model.
