<h2 align="center"><img alt="Rahatsız Siteler" src="https://raw.githubusercontent.com/xorcan/hosts/master/xorcan.hosts.logo.jpg" width="250"></br>
<b>Türk Ad-list, Reklam Engelleme Listesi, HOSTS</b></h2><h4 align="center">Bahis, dolandırıcılık gibi rahatsız edici siteleri engeller.</h4>

<p align="center"><a href="https://www.gnu.org/licenses/gpl-3.0" alt="License: GPLv3"><img src="https://img.shields.io/github/license/xorcan/hosts.svg"><img src=""><img src="https://img.shields.io/badge/t%C3%BCrk%C3%A7e-reklam%20listesi-f44b42.svg"><img src="https://img.shields.io/github/issues/xorcan/hosts.svg"></a>

## Kullanım

Adaway ile kullanınız. Android için tasarlanmıştır.

## Reklamları Nasıl Engelleyebilirim? - Windows

- ```https://raw.githubusercontent.com/xorcan/hosts/master/xhosts.txt``` adresinden listenin tamamını kopyalayın.
- Bilgisayarınızda C:\Windows\System32\drivers\etc konumundaki hosts dosyasını bulun.
- hosts dosyasını notepad++ ile açarak listeyi buraya yapıştırın ve kaydedip çıkın.
- Bilgisayarınızı yeniden başlatın.

NOT: Listemizin hosts yapısı nedeniyle tüm reklamları engelleyemeyecektir. Sadece 3. taraflardan gelen reklamları engelleyebiliriz ve aslında birçok durumda bu filtreleme yöntemi yeterli olur. Ancak internet tarayıcınızda reklam engelleyici kullanarak etkin bir şekilde element filtrelemesi de yapabilirsiniz.

## Reklamları Nasıl Engelleyebilirim? - Android (AdAway (Root))

Root erişim izniniz varsa telefonun kendi "hosts" dosyasını değiştirmelisiniz. Bu, batarya ve RAM tasarrufu sağlar.
Kök erişim (root) izniniz varsa AdAway uygulamasını kullanabilirsiniz. Host dosyaları ile reklam engelleyen ücretsiz bir uygulamadır.

- AdAway uygulamasını [buradan](https://f-droid.org/packages/org.adaway/) indirin.
 ("f-droid indir" linkinin altındaki "apk indir" linkine tıklayarak)
- Uygulamayı telefonunuza veya tabletinize kurun.
- Uygulamayı açın ve uygulama menüsünden "Host kaynakları" sekmesini açın.
- Sağ üst köşedeki '+' işaretine dokunun. Bir bağlantı girmeniz istenecektir.
- ```https://raw.githubusercontent.com/xorcan/hosts/master/xhosts.txt``` adresini kopyalayıp bu kısma yapıştırın ve ekleyin.
(beyaz listeyle kullanın)
- Ana menüye dönün, güncellemeleri denetleyip, uygulayın. Cihazınızı yeniden başlatın.

## Listeyi eklemek istiyorum

aşağıdaki bağlantıları aynı şekilde içeri alınız. bunlar önerilerim ve normal kullanıcılar için yeterlidir. ben daha fazla istiyorum diyorsanız [şuraya](https://github.com/xorcan/hosts/blob/master/OTHERS.md) bakabilirsiniz.

```https://raw.githubusercontent.com/xorcan/hosts/master/xhosts.txt```

```https://adaway.org/hosts.txt```

```https://hosts-file.net/ad_servers.txt```

```https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext```

```https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts```

## Eklememeniz gereken listeler (yutulanlar)

bu host sağlayıcıyı kullanarak alttaki belirtilen hostları da otomatik kullanmış olursunuz endişe etmeyin, onlar da sürekli en güncel halinde olacaklar. anlayacağınız bunları ayrıyeten eklemenize gerek yok.

```https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/ParsedBlacklists/Turk-adlist.txt```

```https://raw.githubusercontent.com/biroloter/Mobile-Ad-Hosts/master/hosts```

```https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts```

```https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/ParsedBlacklists/AakList.txt```

## Beyaz liste (Adaway)

Bu listeyi cihazınıza indirerek, "Your lists" bölümünden "Import all" diyerek içeri alacaksınız. Eklemeseniz de olur ama tavsiyemdir.

```https://raw.githubusercontent.com/xorcan/hosts/master/xwhite.txt```

## Özel durumlar - 👍 varsayılan olarak engelsiz :

1. **```s.youtube.com```**  : YouTube geçmiş kaydetmesini istemiyorsanız whitelist'ten çıkarın.

## [Diğer listeler](https://github.com/xorcan/hosts/blob/master/OTHERS.md)

## Bildir

Engellenmesini uygun gördüğünüz siteleri bildirin ekleyeyim. 

1. [Hatalar](https://github.com/xorcan/hosts/issues) kısmından bildirebilirsiniz.

2. [Posta](mailto:xorcan@yandex.com) ile bildirebilirsiniz.

3. [Anonim posta](https://anonymousemail.me) ile ```xorcan@yandex.com``` adresine bildirebilirsiniz.

4. [Telegram](https://t.me/hostsTR) grubuna bildirebilirsiniz.

## Uyarı - Disclaimer

Bu makaledeki uygulamaların gizlilik sözleşmelerini okuyunuz. Eğer ne yaptığınızı bilmiyorsanız bu işlemlerden uzak durun. Her cihazın yapısı farklıdır, oluşabilecek sorunlardan makale editörü sorumlu tutulamaz! Bu makaleyi kopyalayabilir, istediğiniz gibi düzenleyip yeniden paylaşabilirsiniz.

## License

[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

All responsibility belongs to the user. You can use, study share and improve it at your will. Specifically you can redistribute and/or modify it under the terms of the [GNU General Public License](https://www.gnu.org/licenses/gpl.html) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. 
