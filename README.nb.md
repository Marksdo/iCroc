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

# iCroc - Croc cli-app for iOS og macOS

Last ned [den nyeste utgivelsen fra appstore](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Fullstendig redesignet hele appgrensesnittet og operasjonslogikken.
- Oppgrader innebygd croc-versjon til v10.0.8
- Legg til støtte for iOS & macOS handoff-funksjon
- Støtte for flere språk

V1.1
---
- Redesign av appikon
- Feilrettinger og ytelsesforbedringer

V1.0
---
croc er et verktøy som gjør det mulig for to datamaskiner å enkelt og sikkert overføre filer og mapper. Så vidt jeg vet er croc det eneste CLI-filoverføringsverktøyet som gjør alle følgende:

- tillater at to datamaskiner overfører data (ved hjelp av en relay)
- gir ende-til-ende-kryptering (ved hjelp av PAKE)
- muliggjør enkel plattformoverskridende overføringer (Windows, Linux, Mac)
- tillater flere filoverføringer
- tillater gjenopptakelse av avbrutte overføringer
- ingen lokal server eller portvideresending nødvendig
- ipv6-først med ipv4 fallback
- kan bruke proxy, som tor

Kommandolinjeapplikasjonen som dette er basert på kan finnes her:

https://github.com/schollz/croc

## macOS aktivere iCroc i Innstillinger
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Rask sending av filer med iCroc
- Velg filer i Finder og bruk "åpne med iCroc"
- Velg filer i Finder og bruk ⌘+C for å kopiere, åpne deretter iCroc og bruk ⌘+V for å sende filer
- Dra filer til iCroc

# ⚡ Handoff
- iOS og macOS-enheter må begge installere iCroc-appen
- iOS og macOS må ha Handoff-funksjonen aktivert
- Når avsender genererer kodefrase vil den andre enhetens iCroc automatisk motta kodefrasen

# 🔮 Gjenoppta avbrutt oppgave
- Avsender sender filen på nytt og mottaker bruker formatet ny kodefrase@gammel kodefrase, for eksempel: 4161-mambo-young-baby@7611-south-concept-satire
- Avsender sender filen på nytt ved å bruke tilpasset token som forrige kodefrase

# 💾 Tilpasset mottakermappe
- Mottakermappen vil lagres til ~/Nedlastinger/'${kodefrase}'
- Bruk '@mappenavn' for å lagre til ~/Nedlastinger/mappenavn, for eksempel: 8443-siren-mayor-origin@mypics
- Bruk samme målmappe for å automatisk gjenoppta avbrutte overføringsoppgaver