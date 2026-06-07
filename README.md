# Zonely Mobile

Bu repo sadece Zonely Mobile uygulamasinin indirme ve guncelleme dosyalarini barindirir.

- Indirme sayfasi: https://zonely-gen-tr.github.io/ZonelyMobile/
- Guncelleme manifesti: https://raw.githubusercontent.com/zonely-gen-tr/ZonelyMobile/main/updates/themes.json
- Android APK release dosyalari: https://github.com/zonely-gen-tr/ZonelyMobile/releases
- iOS IPA/TestFlight bilgisi manifestteki `platforms.ios` alanindan yayinlanir.

Kaynak kod bu repoda yayinlanmaz.
Android release asset'i domain icermeyen template APK'dir; domain'e ozel APK'yi `mobile-builder` PHP endpoint'i uretip imzalar.
