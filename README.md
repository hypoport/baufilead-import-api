# BaufiLead-Import API

BaufiLead-Import ist ein Service zum Import von Leads in BOXL für BHW Partner.
Es werden verschiedene Versionen der Schnittstelle unterstützt.

## HTTP-SOAP Service
Der Service ist unter folgendem Pfad aufrufbar für die jeweiligs genutzte Version der Schnittstellen.
```
https://dunkelboxl.hypoport.de/boxl-hv/service/baufiLeadImport/v01
https://dunkelboxl.hypoport.de/boxl-hv/service/baufiLeadImport/v02
```
## Security
Die Schnittstelle ist über HTTPS ansprechbar.
Weitere Sicherheitsdetails sind Bestandteil des jeweiligen Anbindungsprojekts.

## Versionen der Schnittstelle
Die WSDL-Dateien und XSD-Dateien (Anfrage und Anwort) finden sich für jede Version der Schnittstelle in einem eigenen Ordner.
Weiterhin enthält der Ordner jeweils einen gültigen SOAP-Beispiel-Request.

###Version 01
Datum: 26.06.2015
Kommentar:
- initiale Version

###Version 02
Datum: 26.06.2015
Kommentar:
- neu: kunde.geburtsDatum
