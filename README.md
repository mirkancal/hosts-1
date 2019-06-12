<h2 align="center"><a href="https://t.me/hostsTR" alt="Rahatsız Siteler Telegram Grubu"><img src="https://raw.githubusercontent.com/xorcan/hosts/master/xorcan.hosts.logo.jpg" width="250"></a></br>
<b>Türk Ad-list, Reklam Engelleme Listesi, HOSTS</b></h2><h4 align="center">Bahis, dolandırıcılık gibi rahatsız edici siteleri engeller.</h4>

<p align="center"><a href="https://www.gnu.org/licenses/gpl-3.0" alt="License: GPLv3"><img src="https://img.shields.io/github/license/xorcan/hosts.svg"></a> <a href="https://www.google.com/search?&q=t%C3%BCrk+adlist+xorcan" alt="Türkçe Ad-listler"><img src="https://img.shields.io/badge/t%C3%BCrk%C3%A7e-reklam%20listesi-f44b42.svg"></a>  <a href="https://github.com/xorcan/hosts/issues" alt="Hatalar"><img src="https://img.shields.io/github/issues/xorcan/hosts.svg"></a> 

## Kullanım

AdAway ile kullanınız. Android için tasarlanmıştır.

## Windows için Önerilen nedir?

- İnternet tarayıcınızda [uBlock Origin](https://github.com/gorhill/uBlock) kullanarak etkin bir şekilde element filtrelemesi yapabilirsiniz. Bunun için öncelikle tarayıcınız için olanını edinin:
- [Chrome için uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) -- 
[Firefox için uBlock Origin](https://addons.mozilla.org/tr/firefox/addon/ublock-origin/) -- 
[Opera için uBlock Origin](https://addons.opera.com/tr/extensions/details/ublock/)
- Ardından uBlock Origin > Kontrol Paneli > Süzgeç Listeleri > İçe Aktar (en altta) bölümünden açılan url ekleme kutusuna şu linki ekleyin:
1. ```https://raw.githubusercontent.com/xorcan/hosts/master/xhosts.txt```
- Ardından sağ üstte beliren "Değişiklikleri Kaydet" düğmesine tıklayarak sayfadan çıkabilirsiniz. 
- Artık ayarlar sayfasına girip "Güncelle" tuşuna basmanıza gerek yok. Liste diğer listelerin yaptığı gibi belli aralıklarla kendini güncelleyecektir. 
- NOT: Listenin hosts yapısı nedeniyle tüm reklamları engelleyemeyecektir. Sadece 3. taraflardan gelen reklamları engelleyebiliriz ve birçok durumda bu filtreleme yöntemi yeterli olur.

## Windows için Önerilmeyen nedir?

- Aşağıdaki adrese girerek listenin tamamını kopyalayın:
1. ```https://raw.githubusercontent.com/xorcan/hosts/master/xhosts.txt```
- Bilgisayarınızda C:\Windows\System32\drivers\etc konumundaki hosts dosyasını bulun.
- hosts dosyasını notepad++ ile açarak listeyi buraya yapıştırın ve kaydedip çıkın.
- Bilgisayarınızı yeniden başlatın.
- NOT: Windows için beyazliste'yi ekleyemeyeceğiniz için sadece xhosts.txt dosyasını kullanın.

## Android için (AdAway (Root)) (Adım 1/2)

Root erişim izniniz varsa telefonun kendi "hosts" dosyasını değiştirmelisiniz. Bu, batarya ve RAM tasarrufu sağlar.
Kök erişim (root) izniniz varsa AdAway uygulamasını kullanabilirsiniz. Host dosyaları ile reklam engelleyen ücretsiz bir uygulamadır.

- AdAway uygulamasını [buradan](https://f-droid.org/packages/org.adaway/) indirin. ("f-droid indir" linkinin altındaki "apk indir" linkine tıklayarak)
- Uygulamayı telefonunuza veya tabletinize kurun.
- Uygulamayı açın ve uygulama menüsünden "Host kaynakları" sekmesini açın.
- Sağ üst köşedeki '+' işaretine dokunun. Bir bağlantı girmeniz istenecektir.
- Aşağıdaki adresini kopyalayıp bu kısma yapıştırın ve ekleyin. (beyaz listeyle birlikte kullanınız.)
- (Bunlar benim önerilerim ve normal Android kullanıcıları için yeterlidir. Ben daha fazla istiyorum diyorsanız [şuraya](https://github.com/xorcan/hosts/blob/master/OTHERS.md) bakabilirsiniz.)

1. ```https://raw.githubusercontent.com/xorcan/hosts/master/xhosts.txt```
2. ```https://adaway.org/hosts.txt```
3. ```https://hosts-file.net/ad_servers.txt```
4. ```https://1hos.cf/```
5. ```https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext```
6. ```https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts```

- Ana menüye dönün, güncellemeleri denetleyip uygulayın. Cihazınızı yeniden başlatın.

## Beyazliste (AdAway için) (Adım 2/2)

- Bu listeyi cihazınıza indirerek, "Your lists" bölümünden "Import all" diyerek içeri alacaksınız. Bazı sitelerin düzgün çalışması için gereklidir.

1. ```https://raw.githubusercontent.com/xorcan/hosts/master/xwhite.txt```

## Eklememeniz gereken listeler (Yutulanlar)

Bu liste sağlayıcıyı kullanarak altta belirtilen listeleri de otomatik olarak kullanmış olursunuz. Endişe etmeyin, onlar da sürekli en güncel halinde olacaklar. Anlayacağınız bunları eklemenize gerek yok.

1. ```https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/ParsedBlacklists/Turk-adlist.txt```
2. ```https://raw.githubusercontent.com/biroloter/Mobile-Ad-Hosts/master/hosts```
3. ```https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts```
4. ```https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/ParsedBlacklists/AakList.txt```

## Özel Durumlar - Varsayılan Olarak Engelsiz:

1. **```s.youtube.com```**  : YouTube'un geçmiş kaydetmesini istemiyorsanız beyazliste'den çıkarın.
2. **```api.pinterest.com```**  : Pinterest'le işim yok nefret ediyorum ben diyorsanız beyazliste'den çıkarın.

## [Diğer listeler](https://github.com/xorcan/hosts/blob/master/OTHERS.md)

## Nasıl Rahastsız Site Bildireceğim?

Engellenmesini uygun gördüğünüz siteleri bildirin, listeye ekleyelim ki diğer insanlar bunlarla uğraşmasınlar. 

1. [Hatalar](https://github.com/xorcan/hosts/issues) kısmından bildirebilirsiniz.
2. [Posta](mailto:xorcan@yandex.com) ile bildirebilirsiniz.
3. [Anonim (girişsiz) posta](https://anonymousemail.me) ile ```xorcan@yandex.com``` adresine bildirebilirsiniz.
4. [Telegram](https://t.me/hostsTR) grubuna bildirebilirsiniz.

## Uyarı

Bu makaledeki uygulamaların gizlilik sözleşmelerini okuyunuz. Eğer ne yaptığınızı bilmiyorsanız bu işlemlerden uzak durun. Her cihazın yapısı farklıdır, oluşabilecek sorunlardan makale editörü sorumlu tutulamaz.

## License

[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

All responsibility belongs to the user. You can use, study share and improve it at your will. Specifically you can redistribute and/or modify it under the terms of the [GNU General Public License](https://www.gnu.org/licenses/gpl.html) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. 
