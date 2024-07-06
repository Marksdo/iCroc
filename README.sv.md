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

# iCroc - Croc CLI-app för iOS och macOS

Ladda ner [den senaste versionen från App Store](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Fullständigt omdesignad appgränssnitt och operativ logik.
- Uppgradera inbäddad croc-version till v10.0.8.
- Lägg till stöd för iOS- och macOS-handoff-funktion.
- Stöd för fler språk.

V1.1
---
- Omdesignad appikon.
- Buggfixar och prestandaförbättringar.

V1.0
---
Croc är ett verktyg som gör att två datorer enkelt och säkert kan överföra filer och mappar. Så vitt jag vet är croc det enda CLI-filöverföringsverktyget som gör allt detta:

- låter två datorer överföra data (med en relä)
- tillhandahåller end-to-end-kryptering (med PAKE)
- möjliggör enkla plattformsöverföringar (Windows, Linux, Mac)
- tillåter flera filöverföringar
- tillåter återupptagande av avbrutna överföringar
- ingen lokal server eller portvidarebefordran behövs
- ipv6-först med ipv4-fallback
- kan använda proxy, som tor

Kommandoradsapplikationen som detta är baserat på kan hittas här:

https://github.com/schollz/croc

## macOS aktivera iCroc i Inställningar
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Snabb filöverföring med iCroc
- Välj filer i Finder och använd sedan öppna med iCroc
- I Finder, välj filer och tryck ⌘+C för att kopiera, öppna sedan iCroc och tryck ⌘+V för att skicka filer
- Dra filer till iCroc

# ⚡ Handoff
- iOS- och macOS-enheter måste båda ha iCroc-appen installerad
- iOS- och macOS-enheter måste ha aktiverat handoff-funktionen
- När avsändaren genererar en kodfras kommer iCroc på den andra enheten automatiskt att få kodfrasen

# 🔮 Återuppta avbrutna uppgifter
- Avsändaren skickar om filen och mottagaren använder formatet ny kodfras@gammal kodfras, t.ex.: 4161-mambo-young-baby@7611-south-concept-satire
- Avsändaren skickar om filen med en anpassad token som tidigare kodfras

# 💾 Anpassad mottagningsmapp
- Mottagningsmappen sparas i ~/Downloads/'${code-phrase}'
- Använd '@folderName' för att spara i ~/Downloads/folderName, t.ex.: 8443-siren-mayor-origin@mypics
- Använd samma målmapp för att automatiskt återuppta avbrutna överföringsuppgifter