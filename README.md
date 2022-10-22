# CUPP - Ortak Kullanıcı Parolaları Profil Oluşturucu

[![Build Status](https://travis-ci.org/Mebus/cupp.svg?branch=master)](https://travis-ci.org/Mebus/cupp)
[![Coverage Status](https://coveralls.io/repos/github/Mebus/cupp/badge.svg)](https://coveralls.io/github/Mebus/cupp)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a578dde078ef481e97a0e7eac0c8d312)](https://app.codacy.com/app/Mebus/cupp?utm_source=github.com&utm_medium=referral&utm_content=Mebus/cupp&utm_campaign=Badge_Grade_Dashboard)
[![Rawsec's CyberSecurity Inventory](https://inventory.raw.pm/img/badges/Rawsec-inventoried-FF5050_plastic.svg)](https://inventory.raw.pm/)

 
## About

  Kimlik doğrulamanın en yaygın biçimi, bir kullanıcı adının birleşimidir.
  ve bir parola veya parola. Her ikisi de yerel olarak depolanan değerlerle eşleşirse
  saklanan tablo, kullanıcının bir bağlantı için kimliği doğrulanır. Şifre gücü
  şifreyi tahmin etme veya kırma ile ilgili zorluğun bir ölçüsü
  kriptografik teknikler veya kütüphane tabanlı otomatik testler yoluyla
  alternatif değerler.

  Zayıf bir parola çok kısa olabilir veya yalnızca alfasayısal karakterler kullanabilir,
  şifre çözmeyi basitleştirir. Zayıf bir şifre aynı zamanda kolayca bulunabilen bir şifre olabilir.
  doğum günü, takma ad, adres gibi kullanıcının profilini çıkaran biri tarafından tahmin edilen,
  bir evcil hayvanın veya akrabanın adı veya Tanrı, aşk, para veya şifre gibi yaygın bir kelime.

  Bu yüzden CUPP doğdu ve yasal gibi durumlarda kullanılabilir.
  sızma testleri veya adli suç soruşturmaları.


Requirements
------------

CUPP'yi çalıştırmak için Python 3'e ihtiyacınız var.

Hızlı başlangıç
-----------

    $ python3 cupp.py -h

## Ayarlar

  Usage: cupp.py [OPTIONS]

        -h      Yardım

        -i      Kullanıcı parolası profili oluşturma için etkileşimli sorular

        -w      Mevcut sözlüğün profilini çıkarmak için bu seçeneği kullanın,
                veya biraz pwnsauce yapmak için WyD.pl çıktısı :)

        -l      Depodan büyük kelime listeleri indirin

        -a      Varsayılan kullanıcı adlarını ve parolaları doğrudan Alecto DB'den ayrıştırın.
                Project Alecto, birleştirilmiş ve geliştirilmiş olan Phenoelit ve CIRT'nin saflaştırılmış veritabanlarını kullanır.

        -v      Programın sürümü



## Yapılandırma

   CUPP, talimatları içeren cupp.cfg yapılandırma dosyasına sahiptir.

## Örnek (Hızlı iletildi)

![cupp-example](screenshots/cupp-example.gif)

## Lisans

 Bu program ücretsiz bir yazılımdır; yeniden dağıtabilir ve/veya değiştirebilirsiniz
  tarafından yayınlanan GNU Genel Kamu Lisansı koşulları altında
  Özgür Yazılım Vakfı; Lisansın 3. sürümü veya
  herhangi bir sonraki sürüm.

  Bu program faydalı olacağı ümidiyle dağıtılmıştır,
  ancak HİÇBİR GARANTİ YOKTUR; zımni garanti bile olmadan
  SATILABİLİRLİK veya BELİRLİ BİR AMACA UYGUNLUK. Bkz.
  Daha fazla ayrıntı için GNU Genel Kamu Lisansı.

  GNU Genel Kamu Lisansının bir kopyasını almış olmalısınız
  bu programla birlikte; değilse, Özgür Yazılım'a yazın
  Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307 ABD

  See './LICENSE' for more information.

## Github içe aktarma


Bu proje, Mebus tarafından https://github.com/Mebus/cupp'a şu adresten aktarılmıştır:
http://www.remote-exploit.org/content/cupp-3.0.tar.gz
http://www.remote-exploit.org/articles/misc_research__amp_code/index.html
aracın daha da geliştirilmesini teşvik etmek.

## Orijinal yazar


 Ömer Faruk Aslancan Lakabı theomers_  
  https://youtube.com/theomers_  
  https://www.instagram.com/theomers_  


## Orjinal Yazar

  * Bosko Petrovic aka bolexxx  
  bole_loser@hotmail.com  
  http://www.offensive-security.com  
  http://www.bolexxx.net  

  * Mebus  
    https://github.com/Mebus/  

  * Abhro  
    https://github.com/Abhro/  

  * Andrea Giacomo  
    https://github.com/codepr

  * quantumcore  
    https://github.com/quantumcore
    

