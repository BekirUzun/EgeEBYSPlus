# Ege Üniversitesi EBYS +
Ege Üniversitesi Öğrenci Giriş sisteminin arayüzünü değiştirir ve istediğiniz arkaplan resmini kullanmanıza olanak sağlar. Değişiklik yapılan sayfalar aşağıda listelenmiştir.
- Giriş Sayfası
- Anasayfa (girişten sonraki panel)
- Not Görüntüleme sayfası

## Not görüntüleme
Not görüntüleme sayfasındaki sütunların üzerine tılayarak küçültebilir, "+" sembolune basıp eski haline çevirebilirsiniz. Ayrıca çok kullanılmayan sütunlar (ders kodu, fakülte, grup no vs.) otomatik olarak küçültülmüştür.

## Arkaplan resmi
Arkaplanı değiştirmek için istediğiniz resmin doğrudan linkini yapıştırmalısınız. Link, güvenli internet protokolü (https://) kullanan bir sitenin barındırdığı fotoğraf linki olmalıdır. Varsayılan arkaplan resim linki: 

https://raw.githubusercontent.com/BekirUzun/EgeEBYSPlus/master/src/images/bg-1080p.png

**Not:** Bu eklenti sadece arayüzü değiştirir. Verileriniz ile ilgili herhangi bir değişiklik yapmaz. Ama dilerseniz notları %25 arttırma ile ilgili bir özellik isteği gönderebilirsiniz.

## Desteklenen Tarayıcılar
[![Chrome &#10004](https://img.shields.io/badge/Chrome-%E2%9C%94-green.svg?style=flat-square)](http://www.google.com/chrome/) -   [![Tampermonkey](https://img.shields.io/badge/Tampermonkey--green.svg?style=flat-square)](https://tampermonkey.net/) ile kullanılabilir (uyumsuzluk problemlerinden dolayı v1.0.0 yüklenmelidir)

[![Firefox &#10004](https://img.shields.io/badge/Firefox-%E2%9C%94-orange.svg?style=flat-square)](https://www.mozilla.org/firefox) - [![Greasemonkey](https://img.shields.io/badge/Greasemonkey--yellow.svg?style=flat-square)](http://www.greasespot.net/) ile kullanılabilir 

## Ekran Görüntüleri
![Giriş Sayfası][login]
![Anasayfa][dashboard]

## Kurulum
- [Tampermonkey](https://tampermonkey.net/) veya [Greasemonkey](http://www.greasespot.net/) yükleyin.
  - Greasemonkey için [Bu link](https://github.com/BekirUzun/EgeEBYSPlus/raw/master/ege-uni-ebys-plus.user.js)'e tıklayın.
  - Tampermonkey için [Bu link](https://raw.githubusercontent.com/BekirUzun/EgeEBYSPlus/d2970b705e8e44fa384fca9552104a2229ed693d/ege-uni-ebys-plus.user.js)'e tıklayın. 
- "Kur" veya "Devam et" gibi bir butona basıp kurulumu tamamlayın.


[login]: https://github.com/BekirUzun/EgeEBYSPlus/blob/master/src/images/ss-login.png "Giriş Sayfası"
[dashboard]: https://github.com/BekirUzun/EgeEBYSPlus/blob/master/src/images/ss-dashboard.png "Anasayfa"


