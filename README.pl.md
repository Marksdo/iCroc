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

# iCroc - Aplikacja CLI Croc na iOS i macOS

Pobierz [najnowszą wersję z App Store](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Całkowicie przeprojektowano interfejs aplikacji i logikę operacyjną.
- Zaktualizowano wersję wbudowaną Croc do v10.0.8.
- Dodano obsługę funkcji handoff w iOS i macOS.
- Obsługa większej liczby języków.

V1.1
---
- Przeprojektowanie ikony aplikacji.
- Naprawiono błędy i poprawiono wydajność.

V1.0
---
Croc to narzędzie, które pozwala dwóm komputerom w prosty i bezpieczny sposób przesyłać pliki i foldery. O ile mi wiadomo, Croc jest jedynym narzędziem do przesyłania plików CLI, które wykonuje wszystkie poniższe czynności:

- umożliwia przesyłanie danych między dwoma komputerami (za pomocą przekaźnika)
- zapewnia szyfrowanie end-to-end (za pomocą PAKE)
- umożliwia łatwe przesyłanie międzyplatformowe (Windows, Linux, Mac)
- umożliwia przesyłanie wielu plików
- umożliwia wznawianie przerwanych transferów
- nie wymaga lokalnego serwera ani przekierowania portów
- preferuje ipv6 z fallbackiem do ipv4
- może korzystać z proxy, np. tor

Aplikację wiersza poleceń, na której się opiera, można znaleźć tutaj:

https://github.com/schollz/croc

## macOS aktywuj iCroc w Ustawieniach
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Szybkie wysyłanie plików z iCroc
- Wybierz pliki w Finderze, a następnie użyj opcji otwórz za pomocą iCroc
- W Finderze wybierz pliki i użyj ⌘+C, aby skopiować, następnie otwórz iCroc i użyj ⌘+V, aby wysłać pliki
- Przeciągnij pliki do iCroc

# ⚡ Handoff
- Urządzenia iOS i macOS muszą mieć zainstalowaną aplikację iCroc
- Urządzenia iOS i macOS muszą mieć włączoną funkcję Handoff
- Gdy nadawca wygeneruje kod, aplikacja iCroc na drugim urządzeniu automatycznie otrzyma kod

# 🔮 Wznawianie przerwanych zadań
- Nadawca ponownie wysyła plik, a odbiorca używa formatu nowy kod@stary kod, np.: 4161-mambo-young-baby@7611-south-concept-satire
- Nadawca ponownie wysyła plik, używając niestandardowego tokena jako poprzedniego kodu

# 💾 Niestandardowy folder odbioru
- Folder odbioru zostanie zapisany w ~/Downloads/'${kod}'
- Użyj '@nazwaFolderu', aby zapisać w ~/Downloads/nazwaFolderu, np.: 8443-siren-mayor-origin@mypics
- Użycie tego samego folderu docelowego automatycznie wznowi przerwane zadania przesyłania