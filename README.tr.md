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

# iCroc - iOS ve macOS için Croc CLI uygulaması

[App Store'dan en son sürümü indirin](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Tüm uygulama arayüzünü ve işletim mantığını tamamen yeniden tasarlayın.
- Gömülü croc sürümünü v10.0.8'e yükseltin.
- iOS ve macOS handoff özelliğini ekleyin.
- Daha fazla dili destekleyin.

V1.1
---
- Uygulama simgesi yeniden tasarlandı.
- Hata düzeltmeleri ve performans iyileştirmeleri.

V1.0
---
croc, iki bilgisayarın dosya ve klasörleri basit ve güvenli bir şekilde aktarmasına olanak tanıyan bir araçtır. Bildiğim kadarıyla, croc aşağıdakilerin hepsini yapan tek CLI dosya aktarım aracıdır:

- iki bilgisayarın veri aktarmasına izin verir (bir röle kullanarak)
- uçtan uca şifreleme sağlar (PAKE kullanarak)
- kolay platformlar arası aktarımı sağlar (Windows, Linux, Mac)
- birden fazla dosya aktarımına izin verir
- kesintiye uğrayan aktarımı yeniden başlatmaya izin verir
- yerel sunucu veya port yönlendirme gerekmez
- ipv4 geri dönüşümlü ipv6-öncelikli
- tor gibi proxy kullanabilir

Bu uygulamanın temel alındığı komut satırı uygulaması burada bulunabilir:

https://github.com/schollz/croc

## macOS'de Ayarlarda iCroc'u etkinleştirin
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 iCroc ile hızlı dosya gönderme
- Finder'da dosyaları seçin ve ardından iCroc ile açın
- Finder'da dosyaları seçin ve ⌘+C ile kopyalayın, ardından iCroc'u açın ve ⌘+V ile dosyaları gönderin
- Dosyaları iCroc'a sürükleyin

# ⚡ Handoff
- iOS ve macOS cihazlarının her ikisinde de iCroc uygulaması yüklü olmalıdır
- iOS ve macOS cihazlarında Handoff özelliği etkin olmalıdır
- Gönderen kod ifadesi oluşturduğunda, diğer cihazın iCroc'u otomatik olarak kod ifadesini alır

# 🔮 Kesintiye uğrayan görevi yeniden başlat
- Gönderen dosyayı yeniden gönderir ve alıcı yeni kod ifadesi@eski kod ifadesi formatını kullanır, örn: 4161-mambo-young-baby@7611-south-concept-satire
- Gönderen, dosyayı önceki kod ifadesi olarak özel jeton kullanarak yeniden gönderir

# 💾 Özel alma klasörü
- Alma klasörü ~/Downloads/'${code-phrase}' içinde kaydedilir
- '@folderName' kullanımı, ~/Downloads/folderName içinde kaydedilir, örn: 8443-siren-mayor-origin@mypics
- Aynı hedef klasör kullanımı, kesintiye uğrayan aktarım görevlerini otomatik olarak yeniden başlatır