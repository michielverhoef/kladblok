# NOG ONDERHANDEN!

# Productvisie referentieimplementaties

Om een goede referentie implementatie (RI) te maken moet duidelijk zijn wat het doel is, waar deze aan moet voldoen, wat de grenzen zijn en hoe een RI met deze grenzen om dient te gaan.

## Doel van de referentie implementatie
Het doel van de RI is tweeledig:
- Aantonen dat de standaard in concept implementeerbaar is
- De RI kan gebruikt worden om een eigen implementatie te testen

Daarnaast is de RI open source en kan de code gebruikt worden om inspiratie op te doen voor een implementatie. NB. De RI is niet voorschrijvend. Het is dus niet verplicht om een implementatie of opslagstructuur/datamodel etc. uit de RI over te nemen. 

De voorwaarden waaronder de RI gebruikt mag worden staan beschreven in de [gebruiksvoorwaarden] (https://vng-realisatie.github.io/gemma-zaken/beheer/gebruiksvoorwaarden)

## Grenzen van de referentieimplementatie
De RI is een concept-implementatie van de API standaard zoals deze beschreven is de Open API specificatie en beschrijving van het gedragin de feature files. Er is dus niet geoptimaliseerd voor performance, robuustheid, betrouwbaarheid etc.

De RI bevat ook alleen een implementatie van de standaard, geen extra functionaliteit. Het is geen component wat in een productieomgeving ingezet kan en mag worden.

Dit betekent dat een RI alleen de endpoints van de standaard implementeert. Verwijzingen naar of gebruik maken van bijvoorbeeld andere API's worden geacht te werken/beschikbaar te zijn en kunnen bijvoorbeeld gestubd worden. Het is voor een RI niet per se noodzakelijk gebruik te maken van deze andere API's. Denk aan bijvoorbeeld een Medewerkers API, Autorisaties API, Notificaties API etc. In een echte implementatie zal de beschikbaarheid van dergelijke API's noodzakelijk zijn om het systeem te laten werken. Voor een RI is dit niet het geval.

==Omgaan met de referentieimplementatie 