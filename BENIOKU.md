# Muha One Dark Teması

"[Sözdizimi Vurgulamayın](https://tonsky.me/blog/syntax-highlighting/)" makalesinde özetlenen ilkeleri takip ederek, One Dark Pro temalı ve sözdizimi vurgulama karmaşıklığı azaltılmış koyu bir temadır.

## Özellikler

- Ana varyant için One Dark Pro'nun Darker (Daha Koyu) temasına dayanmaktadır
- Farklı estetik tercihler için GNOME varyantını da içerir
- Görsel gürültüyü azaltmak ve odaklanmayı artırmak için basitleştirilmiş sözdizimi vurgulama
- Tüm kullanıcı arayüzü renkleri temel One Dark Pro temasından devralınmıştır
- Uzun süreli kodlama oturumları için uygun koyu tema

## Kurulum

1. VSCodium veya Visual Studio Code yükle
2. Eklentiler görünümünü aç (Ctrl+Shift+X)
3. "Muha One Dark" ifadesini ara
4. Kur'a tıkla

Alternatif olarak komut satırından da kurabilirsin:

```sh
 code --install-extension quiomax.muha-one-dark
```

## Kullanım

Kurulumdan sonra temayı şu şekilde etkinleştirebilirsin:

1. Komut Paletini aç (Ctrl+Shift+P)
2. "Preferences: Color Theme" yazın
3. "Muha One Dark" veya "Muha One Dark Gnome" seç

## Renk Şeması ve Sözdizimi Vurgulama

Bu tema, görsel karmaşıklığı azaltmak için basitleştirilmiş bir renk paleti kullanır:

- **Mor (#C678DD)**: Anahtar kelimeler ve dil yapıları (static, void, const, typedef, struct, enum, return, if, else, vb.)
- **Mavi (#61AFEF)**: Fonksiyon isimleri, metodlar, değişkenler, parametreler ve makrolar
- **Koyu Yeşil (#98C379)**: Dizeler (strings) ve tırnak içindeki metinler
- **Kahverengi/Turuncu (#D19A66)**: Sabitler, sayılar ve sabit değerler (NULL, true, false)
- **Kırmızı (#E06C75)**: Etiketler ve işaretleme (markup) öğeleri
- **Açık Gri (#ABB2BF)**: Tip tanımlamaları, sınıf isimleri, yapı isimleri (kullanıcı tanımlı tipler, GObjectClass, AdwApplication gibi kütüphane tipleri)
- **Soluk Gri (#5C6370)**: Açıklamalar

## Önemli Renk Farklılıkları

- **Yerleşik C tipleri vs Kütüphane Tipleri**: `int`, `char`, `float` gibi yerleşik tipler mor renkte iken, `GObjectClass`, `AdwApplication` gibi kütüphane tipleri açık gri renkte görünür
- **Değişkenler vs Tipler**: `GObjectClass *object_class` gibi bildirimlerde hem tip (`GObjectClass`) hem de değişken (`*object_class`) açık gri renkte görünür, bu basitleştirme ilkesini takip eder
- **Enum değerleri**: `PROP_DEVICE_SERIAL` gibi enum sabitleri açık gri renkte görünür ve normal değişkenlerden ayrılır
- **Makrolar**: `G_OBJECT_CLASS` gibi kütüphane makroları mavi renkte görünür çünkü bunlar fonksiyon benzeri yapılar olarak kabul edilir

## Felsefe

Bu tema, sözdizimi vurgulama konusunda azalan yaklaşımı takip eder. Mümkün olan her token'ı farklı renklerle vurgulamak yerine, bu tema renk paletini azaltarak kod yapısına ve içeriğine odaklanılmasına yardımcı olur.

Yaklaşım, fazla sözdizimi vurgusun üretkenliği azaltabileceğini, kod okumayı bozacak görsel gürültü yaratabileceğini savunan Nikita Prokopov'un "Sözdizimi Vurgulamayın" makalesinden esinlenmiştir.

## Varyantlar

- `Muha One Dark`: One Dark Pro'nun Darker temasına dayanmaktadır
- `Muha One Dark Gnome`: One Dark Pro'nun GNOME varyantına dayanmaktadır

## Lisans

Bu tema GNU Genel Kamu Lisansı Sürüm 3.0 veya sonrası (GPL-3.0-or-later) altında yayınlanmıştır.

Lisans metninin tamamı için [LİSANS](./LICENSE) dosyasına bakabilirsin.

## Simge Atıfı

Tema simgesi SVG Repo'dan alınan iki SVG simgesinin birleşiminden oluşur:
- [Moon Fog Icon](https://www.svgrepo.com/svg/526040/moon-fog) - CC Attribution altında lisanslanmıştır
- [Atom Icon](https://www.svgrepo.com/svg/341623/atom) - GPL altında lisanslanmıştır

## Katkıda Bulunma

Katkılara açığım! Birleştirme İsteği göndermekten çekinme. Büyük değişiklikler için önce bir hata bildirimi açarak neyi değiştirmek istediğini tartışman benim için iyi olur.

## Hakkında

Bu tema, kullanıcı arayüzü için One Dark Pro renk şemasını devralır. Sözdizimi vurgulamanın görsel karmaşıklığını azaltmak ve daha odaklı bir kodlama deneyimi sağlamak amacıyla oluşturulmuştur.
