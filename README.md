# Dimensjonstabelller
Støttetabeller til bruk i Power BI, EXCEL m.m.

Dimensjonstabeller inneholder attributter for å kategorisere og strukturere data. Hensikten med disse attributtene er å kunne filtere, gruppere og navngi data i andre kilder (faktatabeller). For å koble en dimensjonstabell til en faktatabell er man avhengig av en felles koblingsnøkkel (f. eks. kommunenummer). Dimensjonstabeller kan også benyttes for å finne korrespondanser mellom f. eks gamle og nye kommuner.

Ved å bruke felles, sentraliserte dimensjonstabeller sørger vi for at vi bruker de samme kategoriseringene i ulike analyser. I tillegg gjør det det enkelt å oppdatere tabellene ved endringer.

Typiske dimensjoner til vårt bruk vil være:
- regionale dimensjoner (grunnkrets, kommuner, fylker, ulike administrative og analytiske regioner)
- næringskoder (NACE)
- utdanningskoder
- alderskohorter
- sykdoms- og dødsårsakskoder
- m.m.

### For å lage en kobling til tabeller i xlsx-format fra Power Query (Excel eller Power BI):
1) Finn tabellen på GitHub
2) Høyreklikk på tabellnavnet og velg ***Kopier lenke***

![Kopier lenke](https://user-images.githubusercontent.com/86664605/148216859-32115cd6-e53a-4bef-964e-ca30c4f7c5ff.png)

3) Lim inn i en tekst editor og erstatt elementet ***blob*** med ***raw***
4) Velg ny kilde fra Web i Power Query og lim inn den redigerte lenken

![Erstatt blob med raw](https://user-images.githubusercontent.com/86664605/148217651-fa8c9719-32b5-401e-9482-357744dc8add.png)




Mangler det dimensjonstabeller, eller finner du feil? Ta kontakt på analyse.plan@viken.no
