
# Pörssisähkö

Yksinkertainen verkkosivu, joka näyttää reaaliaikaisen ja verollisen pörssisähkön hinnan, sekä tulevat tunnit, joista hintatieto on saatavilla. Verkkosivun toiminta perustuu spot-hinta.fi -ohjelmointirajapintaan.



## Verkkosivu löytyy osoitteesta:

https://sähkö.pinarbo.org/

## Tuki

Verkkosivu tukee yleisimpiä uudenaikaisia selainohjelmistoja, kuten Google Chromea, Firefoxia sekä Microsoft Edgeä. Jos sinulla on kehitysehdotus, jolla voisimme parantaa käyttäjäkokemusta, kerro siitä tämän Github -projektin [Issues](https://github.com/0skari/Porssisahko/issues) -osiossa.

## Toiminta
Suurimmalla kirjasimella sivun yläosassa on reaaliaikainen, tämän hetkinen sähkönhinta (snt/kWh). Tämän alapuolella on tulevien tuntien kellonajat, joiden yhteydessä sähkönhinnat (eur/kWh).

Hinnat ovat selkeyden vuoksi värikoodattu:

```
🔴 Yli 18snt/kWh
🟠 Alle 18snt/kWh
⚪ Alle 7snt/kWh
🟢 Alle 3snt/kWh
```
Verkkosivun alareunassa näkyy päivämäärä sekä kellonaika. Verkkosivu päivittyy automaattisesti minuutin välein. Seuraavaksi alkavan vuorokauden sähkön tuntihinnat tulevat verkkosivulle näkyviin kello 15:een mennessä.
