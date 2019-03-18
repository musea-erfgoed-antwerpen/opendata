# opendata
 Open data

De dataset van het Museum Plantin-Moretus bestaat uit metadata en afbeeldingen en is op twee verschillende manieren toegankelijk: via de Adlib API die XML data produceert en als Open Dataset.

Alle objectbeschrijvingen (metadata) worden onder CC0 beschikbaar gesteld. Dit houdt in dat de data zonder toestemming mag worden gekopieerd, veranderd, verspreid en uitgevoerd, zelfs voor commerciële doeleinden. De afbeeldingen vallen onder de Vlaamse gratis open data licentie.

Het Museum Plantin-Moretus stelt het op prijs om genoemd te worden als bron van informatie. De juiste bronvermelding daarbij is: Museum Plantin-Moretus, Antwerpen.

Graag vernemen we welke toepassingen er met de data zijn ontwikkeld via search.museumplantinmoretus@stad.antwerpen.be

Adlib API

De Adlib API is te bereiken via http://search.museumplantinmoretus.be/Adlib.Internetserver.MPM.Webservice/wwwopac.ashx
De database kan met de Adlib API worden doorzocht met als resultaat XML bestanden. Er is een aparte website met documentatie over de Adlib API op http://api.adlibsoft.com

Voorbeelden van queries zijn:
http://search.museumplantinmoretus.be/Adlib.Internetserver.MPM.Webservice/wwwopac.ashx?database=collect&search=VV="Vos, Maerten De" geeft alle resultaten waarbij de vervaardiger Maerten De Vos is.

http://search.museumplantinmoretus.be/Adlib.Internetserver.MPM.Webservice/wwwopac.ashx?database=collect&search=OC="Prenten (grafiek)" geeft alle prenten weer.

Volgende velden worden worden aangeboden:
Beschrijvende velden:
<priref> 	De priref is het recordnummer van het object en de unieke identifier in de database
<object_number> 	Objectnummer
<alternative_number> 	Catalogusnummer
<title> 	Titel van het werk
<title.translation> 	Vertaalde titel van het werk
<description> 	Beschrijving van het werk
<creator> 	Vervaardiger van het werk
<creator.qualifier> 	Relatie van de vervaardiger tot het werk (naar, toegeschreven aan, …)
<creator.role> 	Functie van de vervaardiger (graveur, uitgever, …)
<production.date.start> 	Vroegste datum waarop het werk werd gemaakt
<production.date.start.prec> 	Precisie van de vroegste datum waarop het werk werd gemaakt (circa)
<production.date.end> 	Laatste datum waarop het werk werd gemaakt
<production.date.end.prec> 	Precisie van de laatste datum waarop het werk werd gemaakt (circa)
<production.place> 	Plaats waar het werk vervaardigd is
<production.period> 	Periode waarin het werk vervaardigd is
<object_name> 	Type (prent, tekening, aquarel, …)
<collection> 	Oude (vóór 1800) of moderne werken
<material> 	Gebruikte materialen
<technique> 	Gehanteerde technieken
<dimension.value> 	Afmetingen – waarde
<dimension.unit> 	Afmetingen – eenheid
<dimension.part> 	Afmetingen – deel
<inscription.content> 	Opschriften
<inscription.position> 	Positie opschriften
<acquisition.date> 	Datum verwerving

 
Bibliografische gegevens:
	
<documentation.page_reference> 	Deel, pagina, … van bibliografische gegevens
<brocade> 	Link naar brocade (bibliotheeksysteem Anet)
<documentation.title> 	Titel

 
Relaties
<related_object.reference> 	Objectnummer van een gerelateerd object
<related_object.title> 	Titel van een gerelateerd object
<part_of_reference> 	Objectnummer van het werk waarvan het object een deel is
<part_of_title> 	Titel van het werk waarvan het object een deel is

 
Media:
<reproduction.reference> 	Naam van het bijhorende mediabestand
<reproduction.identifier_URL> 	Link naar de afbeelding

Overige velden zijn niet relevant of slechts beperkt beschikbaar.

Linked Data

Sinds 2012 is de dataset van het museum ook beschikbaar op opencultuurdata.be en op opendata.antwerpen.be als CSV, json of xml.

download 	csv 	http://api.antwerpen.be/v1/cultuur/collectieprentenkabinet.csv
download 	json 	http://api.antwerpen.be/v1/cultuur/collectieprentenkabinet.json
download 	xml 	http://api.antwerpen.be/v1/cultuur/collectieprentenkabinet.xml

De datasets zijn ook beschikbaar als deelcollecties (oude en moderne tekeningen, oude en moderne prenten):
download 	xml 	http://mpm.opencultuurdata.be/MPM_moderndrawings.xml
download 	xml 	http://mpm.opencultuurdata.be/MPM_modernprints.xml
download 	xml 	http://mpm.opencultuurdata.be/MPM_olddrawings.xml
download 	xml 	

http://mpm.opencultuurdata.be/MPM_oldprints.xml
download 	xml 	

http://mpm.opencultuurdata.be/MPM_selection.xml
