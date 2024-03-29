<h2 align="center"><a href="https://t.me/hostsTR" alt="Rahatsız Siteler Telegram Grubu"><img src="https://raw.githubusercontent.com/xorcan/hosts/master/xorcan.hosts.logo.jpg" width="250"></a></br>
<b>Türk Ad-list, Reklam Engelleme Listesi, HOSTS</b></h2><h4 align="center">Bahis, dolandırıcılık gibi rahatsız edici siteleri engeller. <a href="https://github.com/xorcan/hosts/blob/master/README-EN.md">English</a></h4>

<p align="center"><a href="https://www.gnu.org/licenses/gpl-3.0" alt="License: GPLv3"><img src="https://img.shields.io/github/license/xorcan/hosts.svg"></a> <a href="https://www.google.com/search?&q=t%C3%BCrk+adlist+xorcan" alt="Türkçe Ad-listler"><img src="https://img.shields.io/badge/t%C3%BCrk%C3%A7e-reklam%20listesi-f44b42.svg"></a>  <a href="https://github.com/xorcan/hosts/issues" alt="Hatalar"><img src="https://img.shields.io/github/issues/xorcan/hosts.svg"></a> 

## Kullanım

AdAway ile kullanınız. Android için tasarlanmıştır.

## Windows için Önerilen nedir?

- İnternet tarayıcınızda [nano adblocker](https://github.com/NanoAdblocker/NanoCore2) kullanarak etkin bir şekilde element filtrelemesi yapabilirsiniz. Bunun için öncelikle tarayıcınız için olanını edinin:
- [Chrome için nano adblocker](https://chrome.google.com/webstore/detail/nano-adblocker/gabbbocakeomblphkmmnoamkioajlkfo) -- 
[Firefox için nano adblocker](https://addons.mozilla.org/en-US/firefox/addon/nano-adblocker-firefox/)

Opera için öncelikle şunu indirin:
[Opera için Chrome eklentilerini indirme eklentisi](https://addons.opera.com/en/extensions/details/install-chrome-extensions/)
Ardından sanki Chrome tarayıcınıza yüklüyormuş gibi şuradan "Opera'ya ekle" diyeceksiniz:
[Opera için nano adblocker](https://chrome.google.com/webstore/detail/nano-adblocker/gabbbocakeomblphkmmnoamkioajlkfo)

- Ardından nano adblocker > Kontrol Paneli > Süzgeç Listeleri > İçe Aktar (en altta) bölümünden açılan url ekleme kutusuna şu linkleri ekleyin:
1. ```https://raw.githubusercontent.com/xorcan/hosts/master/xhosts.txt```
2. ```https://raw.githubusercontent.com/xorcan/hosts/master/xelement.txt```
3. ```https://raw.githubusercontent.com/xorcan/hosts/master/xips.txt```

![bunun gibi](https://i.postimg.cc/636NpJVx/screenshot-2019-08-04-at-11-39-17.png)

- Ardından sağ üstte beliren "Değişiklikleri Kaydet" düğmesine tıklayarak sayfadan çıkabilirsiniz. 
- Artık ayarlar sayfasına girip "Güncelle" tuşuna basmanıza gerek yok. Liste diğer listelerin yaptığı gibi belli aralıklarla kendini güncelleyecektir. 

## "Reklam Engelleyicini Kapat" Uyarılarına Karşı Çözüm

"Adblock'unuzu kapatın" uyarılarına karşı nano defender kullanabilirsiniz
- [Firefox için nano defender](https://addons.mozilla.org/tr/firefox/addon/nano-defender-firefox/) -- 
[Chrome için nano defender](https://chrome.google.com/webstore/detail/nano-defender/ggolfgbegefeeoocgjbmkembbncoadlb)

### Opera için fazladan adım gerekir:

Öncelikle şunu yüklemelisiniz:
- [Opera için Chrome eklentilerini indirme eklentisi](https://addons.opera.com/en/extensions/details/install-chrome-extensions/)

Ardından sanki Chrome tarayıcınıza yüklüyormuş gibi şuradan "Opera'ya ekle" diyeceksiniz:
- [Chrome için nano defender](https://chrome.google.com/webstore/detail/nano-defender/ggolfgbegefeeoocgjbmkembbncoadlb)

### Chrome ve Opera için fazladan adım gerekir:

nano adblocker ayarlarına gidin.
"Deneyimli kullanıcıyım" seçeneğini aktif edin.
Hemen yanında çıkan dişli işaretine tıklayın:

![şu işaret](https://i.postimg.cc/9f7DY9sQ/screenshot-2019-08-04-at-11-20-07.png)

Açılan sekmede "userResourcesLocation" yazan satırı bulun.
"unset" yazan yeri silip şu satırı yazın ("1." olmadan):

1. ```https://gitcdn.xyz/repo/NanoAdblocker/NanoFilters/master/NanoFilters/NanoResources.txt```

![şöyle olacak](https://i.postimg.cc/cC412tkY/screenshot-2019-08-04-at-11-24-44.png)

Değişiklikleri kaydet deyin ve çıkın.
[Şu adresteki](https://jspenguin2017.github.io/uBlockProtector/#extra-installation-steps-for-ublock-origin) kırmızıyla belirtilen kısımlara tıklayarak hepsine abone olun:

![bunun gibi](https://i.postimg.cc/BZYJt6wY/screenshot-2019-08-04-at-11-33-05.png)

## Ayarlamalarınız Bittiğinde Şöyle Görünmelidir:

![1](https://i.postimg.cc/fbNN10JL/screenshot-2019-08-04-at-11-11-29.png)
![2](https://i.postimg.cc/PqQjHrwM/screenshot-2019-08-04-at-11-11-45.png)
![3](https://i.postimg.cc/bN48H5P1/screenshot-2019-08-04-at-11-36-55.png)

## Windows için Önerilmeyen nedir?

- Aşağıdaki adrese girerek listenin tamamını kopyalayın:
1. ```https://raw.githubusercontent.com/xorcan/hosts/master/xhosts.txt```
- Bilgisayarınızda C:\Windows\System32\drivers\etc konumundaki hosts dosyasını bulun.
- hosts dosyasını notepad++ ile açarak listeyi buraya yapıştırın ve kaydedip çıkın.
- Bilgisayarınızı yeniden başlatın.
- NOT: Windows için beyazliste'yi ekleyemeyeceğiniz için sadece xhosts.txt dosyasını kullacaksınız.

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
4. ```https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext```
5. ```https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts```
6. ```https://someonewhocares.org/hosts/hosts```
7. ```https://raw.githubusercontent.com/xorcan/disconnect.me-lists/master/simple_malvertising.txt```

- Ana menüye dönün, güncellemeleri denetleyip uygulayın. Cihazınızı yeniden başlatın.

## Beyazliste (AdAway için) (Adım 2/2)

- Bu listeyi cihazınıza indirerek, "Your lists" bölümünden "Import all" diyerek içeri alacaksınız. Bazı sitelerin düzgün çalışması için gereklidir. Eğer liste başlayıp hemen bitmişse eklemenize gerek yok.

1. ```https://raw.githubusercontent.com/xorcan/hosts/master/xwhite.txt```

## Eklememeniz gereken listeler (Yutulanlar)

Bu liste sağlayıcıyı kullanarak altta belirtilen listeleri de otomatik olarak kullanmış olursunuz. Endişe etmeyin, onlar da sürekli en güncel halinde olacaklar. Anlayacağınız bunları eklemenize gerek yok.

1. ```https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/ParsedBlacklists/Turk-adlist.txt```
2. ```https://raw.githubusercontent.com/biroloter/Mobile-Ad-Hosts/master/hosts```
3. ```https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts```
4. ```https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/ParsedBlacklists/AakList.txt```

## [Diğer listeler](https://github.com/xorcan/hosts/blob/master/OTHERS.md)

## Özel Durumlar

Burada belirtilen durumlar dosyalarda bulunmadığı için manuel olarak ayarlamalıdır. Şu kurallara göre uygulayınız:

- karalisteye eklemek için: "adaway > your" lists alanına girin. altta "blacklist" seçili olduğundan emin olduktan sonra "+ (uçan buton)" işaretine tıklayıp belirtilen kısmı yazın.
- beyazlisteye eklemek için: "adaway > your" lists alanına girin. altta "whitelist" seçili olduğundan emin olduktan sonra "+ (uçan buton)" işaretine tıklayıp belirtilen kısmı yazın.

### seçmeli karaliste

1. ```ads.facebook.com``` Facebook reklamları için.

## Rahatsız Siteyi Nasıl Bildireceğim?

Engellenmesini uygun gördüğünüz siteleri bildirin, listeye ekleyelim ki diğer insanlar bunlarla uğraşmasınlar. 

1. [Hatalar](https://github.com/xorcan/hosts/issues) kısmından bildirebilirsiniz.
2. [Posta](mailto:xorcan@yandex.com) ile bildirebilirsiniz.
3. [Anonim (girişsiz) posta](https://anonymousemail.me) ile ```xorcan@yandex.com``` adresine bildirebilirsiniz.
4. [Telegram](https://t.me/hostsTR) grubuna bildirebilirsiniz.

## Uyarı

Bu makaledeki uygulamaların gizlilik sözleşmelerini okuyunuz. Eğer ne yaptığınızı bilmiyorsanız bu işlemlerden uzak durun. Her cihazın yapısı farklıdır, oluşabilecek sorunlardan makale editörü sorumlu tutulamaz.

## Lisans

[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

Tüm sorumluluk kullanıcıya aittir. Kullanabilir, çalışabilir ve paylaşmayı istediğiniz gibi geliştirebilirsiniz. Özellikle, Özgür Yazılım Vakfı tarafından yayımlanan [GNU Genel Kamu Lisansı](https://www.gnu.org/licenses/gpl.html) koşulları altında, lisansın 3. sürümü veya daha sonraki sürümlerinde yeniden dağıtabilir ve/veya değiştirebilirsiniz.
