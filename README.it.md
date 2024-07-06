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

# iCroc - App CLI di Croc per iOS e macOS

Scarica [l'ultima versione dall'App Store](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Ridisegna completamente l'interfaccia dell'app e la logica operativa.
- Aggiorna la versione integrata di croc a v10.0.8.
- Aggiungi il supporto per la funzione Handoff su iOS e macOS.
- Supporta più lingue.

V1.1
---
- Ridisegno dell'icona dell'app.
- Correzione di bug e miglioramenti delle prestazioni.

V1.0
---
croc è uno strumento che consente a due computer di trasferire file e cartelle in modo semplice e sicuro. A quanto ne so, croc è l'unico strumento CLI di trasferimento file che fa tutto quanto segue:

- Consente a due computer di trasferire dati (usando un relay).
- Fornisce crittografia end-to-end (usando PAKE).
- Facilita i trasferimenti multipiattaforma (Windows, Linux, Mac).
- Consente il trasferimento di più file.
- Consente di riprendere i trasferimenti interrotti.
- Non è necessario un server locale o l'inoltro delle porte.
- Priorità IPv6 con fallback IPv4.
- Può usare proxy, come Tor.

L'applicazione da riga di comando su cui si basa può essere trovata qui:

https://github.com/schollz/croc

## Attiva iCroc nelle Impostazioni di macOS
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Invia rapidamente file con iCroc
- Seleziona file nel Finder, quindi utilizza apri con iCroc.
- Nel Finder, seleziona file e usa ⌘+C per copiare, poi apri iCroc e usa ⌘+V per inviare i file.
- Trascina i file su iCroc.

# ⚡ Handoff
- Installa l'app iCroc su dispositivi iOS e macOS.
- Abilita la funzione Handoff su iOS e macOS.
- Quando il mittente genera una frase di codice, iCroc sull'altro dispositivo riceverà automaticamente la frase di codice.

# 🔮 Riprendi attività interrotta
- Il mittente rinvia il file e il ricevitore utilizza il formato nuova frase di codice@vecchia frase di codice es: 4161-mambo-young-baby@7611-south-concept-satire.
- Il mittente rinvia il file utilizzando il token personalizzato come frase di codice precedente.

# 💾 Cartella di ricezione personalizzata
- La cartella di ricezione sarà salvata in ~/Downloads/'${code-phrase}'.
- Utilizzare '@nomeCartella' per salvare in ~/Downloads/nomeCartella es: 8443-siren-mayor-origin@mypics.
- Utilizzare la stessa cartella di destinazione riprenderà automaticamente le attività di trasferimento interrotte.