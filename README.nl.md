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

# iCroc - Croc cli-app voor iOS & macOS

Download [de nieuwste release van de appstore](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Volledig opnieuw ontworpen interface en operationele logica van de app.
- Geüpgrade ingebedde croc-versie naar v10.0.8
- Ondersteuning toegevoegd voor iOS & macOS handoff-functie
- Ondersteuning voor meerdere talen

V1.1
---
- App-pictogram opnieuw ontworpen
- Bugfixes en prestatieverbeteringen

V1.0
---
croc is een tool die het mogelijk maakt om eenvoudig en veilig bestanden en mappen tussen twee computers te verzenden. Voor zover ik weet, is croc de enige CLI-bestandsoverdrachtstool die het volgende kan:

- Laat twee computers gegevens overdragen (met behulp van een relay)
- Biedt end-to-end encryptie (met PAKE)
- Maakt eenvoudige cross-platform overdrachten mogelijk (Windows, Linux, Mac)
- Laat meerdere bestandsoverdrachten toe
- Laat het hervatten van onderbroken overdrachten toe
- Geen lokale server of port-forwarding nodig
- IPV6-prioriteit met IPV4 fallback
- Kan een proxy gebruiken, zoals tor

De command-line applicatie waarop dit gebaseerd is, is te vinden hier:

https://github.com/schollz/croc

## macOS activeer iCroc in Instellingen
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Snel bestanden verzenden met iCroc
- Selecteer bestanden in Finder en gebruik 'open met iCroc'
- Selecteer bestanden in Finder en gebruik ⌘+C om te kopiëren, open vervolgens iCroc en gebruik ⌘+V om bestanden te verzenden
- Sleep bestanden naar iCroc

# ⚡ Handoff
- iOS & macOS apparaten moeten beide de iCroc app geïnstalleerd hebben
- iOS & macOS moeten de Handoff-functie ingeschakeld hebben
- Wanneer de afzender een codezin genereert, ontvangt de iCroc op het andere apparaat automatisch de codezin

# 🔮 Onderbroken taken hervatten
- De afzender verstuurt het bestand opnieuw en de ontvanger gebruikt het nieuwe code-phrase@oude code-phrase format, bijv. 4161-mambo-young-baby@7611-south-concept-satire
- De afzender verstuurt het bestand opnieuw met een aangepaste token als vorige codezin

# 💾 Aangepaste ontvangstmappen
- Ontvangstmappen worden opgeslagen in ~/Downloads/'${code-phrase}'
- Gebruik '@folderName' om op te slaan in ~/Downloads/folderName, bijv. 8443-siren-mayor-origin@mypics
- Gebruik dezelfde doelmap om onderbroken overdrachtstaken automatisch te hervatten