# Regnvejr Statestik

Programmet føre statstik over den faldende nedbør som er blevet indtastet.

Hvis du f.eks. indtaster at der er faldet 123,123 mm regn for mandag vil den skrive følgende i consolen: _Faldet nedbør for dag 1: 123,123 mm_

## Indtastinger

Dine indtastninger vil se sådan her ud:

- Indtast nedbør for Mandag kun i tal (regnes i mm): 5
- Indtast nedbør for Tirsdag kun i tal (regnes i mm): 500
- Indtast nedbør for Ondsdag kun i tal (regnes i mm): 1000000
- Indtast nedbør for Torsdag kun i tal (regnes i mm): 1234,92422
- Indtast nedbør for Fredag kun i tal (regnes i mm): 123324,52
- Indtast nedbør for Lørdag kun i tal (regnes i mm): 12341,94502852328547
- Indtast nedbør for Søndag kun i tal (regnes i mm): 12394502

## Resultater

Dit resultat vil se sådan her ud:

- Faldet nedbør for dag 1: 5 mm
- Faldet nedbør for dag 2: 500 mm
- Faldet nedbør for dag 3: 1000000 mm
- Faldet nedbør for dag 4: 1234,92422 mm
- Faldet nedbør for dag 5: 123324,52 mm
- Faldet nedbør for dag 6: 12341,945028523285 mm
- Faldet nedbør for dag 7: 12394502 mm



- Gennemsnitlig nedbør: 1933129,77 mm
- Højeste antal af nedbør: 12394502 mm
- Laveste antal af nedbør: 5 mm

## Syntaxer og forklarene linjer

Programmet vil der efter finde højeste nedbør og laveste nedbør samt gennemsnit skrevet ned til 3 decimaler

- ( Syntaxen for at finde højeste tal: faldetMiliMeter.Max() )
- ( Syntaxen for at finde Laveste tal: faldetMiliMeter.Min() )
- ( linjen for gennemsnit: faldetMiliMeterAverage = Math.Round(faldetMiliMeter.Average(), 3); )
