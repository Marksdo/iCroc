# README.md
- [English](README.md)
- [Deutsch](README.de.md)
- [Spanish](README.es.md)
- [Finnish](README.fi.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [Indonesian](README.id.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)
- [Norwegian](README.nb.md)
- [Dutch](README.nl.md)
- [Polish](README.pl.md)
- [Portuguese](README.pt.md)
- [Swedish](README.sv.md)
- [ภาษาไทย](README.th.md)
- [Turkish](README.tr.md)
- [Ukrainian](README.uk.md)
- [Vietnamese](README.vi.md)

# iCroc - Croc CLI-sovellus iOS:lle ja macOS:lle

Lataa [uusin julkaisu App Storesta](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Uudista täysin sovelluksen käyttöliittymä ja toimintalogiikka.
- Päivitä sisäänrakennettu croc-versio v10.0.8:aan.
- Lisää tuki iOS & macOS handoff-ominaisuudelle.
- Tuki useammille kielille.

V1.1
---
- Sovelluskuvakkeen uudelleensuunnittelu.
- Virheenkorjaukset ja suorituskyvyn parannukset.

V1.0
---
croc on työkalu, joka mahdollistaa kahden tietokoneen yksinkertaisen ja turvallisen tiedostojen ja kansioiden siirron. Tietääkseni croc on ainoa CLI-tiedostonsiirtotyökalu, joka tekee seuraavat asiat:

- Mahdollistaa kahden tietokoneen tiedonsiirron (käyttäen välityspalvelinta).
- Tarjoaa päästä päähän -salausta (käyttäen PAKEa).
- Mahdollistaa helpon siirron eri käyttöjärjestelmien välillä (Windows, Linux, Mac).
- Mahdollistaa useiden tiedostojen siirron.
- Mahdollistaa keskeytyneiden siirtojen jatkamisen.
- Paikallista palvelinta tai porttiohjausta ei tarvita.
- IPv6-ensisijainen IPv4-varmennuksella.
- Voi käyttää välityspalvelinta, kuten Tor.

Komentorivisovellus, johon tämä perustuu, löytyy täältä:

https://github.com/schollz/croc

## macOS:lla aktivoi iCroc Asetuksissa
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Nopea tiedostojen lähetys iCrocilla
- Valitse tiedostot Finderissa ja käytä avaa iCrocilla.
- Finderissa valitse tiedostot ja käytä ⌘+C kopioidaksesi ne, avaa iCroc ja käytä ⌘+V lähettääksesi tiedostot.
- Vedä tiedostot iCrociin.

# ⚡ Handoff
- Sekä iOS- että macOS-laitteeseen on asennettava iCroc-sovellus.
- iOS- ja macOS-laitteissa on oltava Handoff-ominaisuus käytössä.
- Kun lähettäjä luo koodilauseen, toisen laitteen iCroc saa koodilauseen automaattisesti.

# 🔮 Keskeytyneiden tehtävien jatkaminen
- Lähettäjä lähettää tiedoston uudelleen ja vastaanottaja käyttää muotoa uusi koodilause@vanha koodilause, esim. 4161-mambo-young-baby@7611-south-concept-satire.
- Lähettäjä lähettää tiedoston uudelleen käyttäen aiempaa koodilauseen mukautettua tokenia.

# 💾 Mukautettu vastaanottokansio
- Vastaanottokansio tallennetaan osoitteeseen ~/Downloads/'${koodilause}'.
- Käytä '@kansionNimi' tallentaaksesi osoitteeseen ~/Downloads/kansionNimi, esim. 8443-siren-mayor-origin@mypics.
- Käyttämällä samaa kohdekansiota keskeytyneet tehtävät jatkuvat automaattisesti.