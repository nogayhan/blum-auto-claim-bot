# Blum Auto Claim Bot

## İçerikler
- [BlumBot](#blumtod)
- [İçerik Listesi](#table-of-contents)
- [Özellikler](#özellikler)
- [Nasıl Kayıt Olunur?](#nasıl-kayıt-olunur)
- [Nasıl Kullanılır](#nasıl-kullanılır)
- [Oyun Oynama Ayarları](#oyun-oynama-ayarları)
- [Video Rehberi](#verileri-alma-videosu)
- [Javascript ile Token Alma](#masaüstü-için-telegram-verilerini-alma-javascript-komutu)
- [Botu 7/24 Aktif Tutma](#724-çalıştırma)
- [Teşekkürler <3](#teşekkürler-3)

## Özellikler

- [x] Otomatik Talep
- [x] Otomatik Oyun Oynama (kullanıcıdan rastgele giriş) [Oyun Oynama Ayarları](#oyun-oynama-ayarları) bölümüne bakın
- [x] Otomatik Bonus Referans Talebi
- [x] Otomatik Görev Tamamlama
- [x] Çoklu Hesap Desteği
- [ ] Günlük Otomatik Talep

# Nasıl Kayıt Olunur?

[https://t.me/BlumCryptoBot/app?startapp=ref_DGPPXW1x6y](https://t.me/BlumCryptoBot/app?startapp=ref_DGPPXW1x6y) Referans Linkimi Kullanarak Beni Destekleyebilirsiniz.

# Nasıl Kullanılır

1. Bilgisayarınıza python ve git'in yüklü olduğundan emin olun.

2. Repoyu Klonlayın
   ```shell
   git clone https://github.com/nogayhan/blum-auto-claim-bot.git
   ```
3. blum-auto-claim-bot alanına gidin
   ```
   cd blum-auto-claim-bot
   ```
4. Python kütüphanelerini yükleyin
   
   Windows
   ```
   pip install -r requirements.txt
   ```

   yada

   ```
   python -m pip install -r requirements.txt
   ```

   Linux

   ```
   pip3 install -r requirements.txt
   ```

   yada

   ```
   python3 -m pip install -r requirements.txt
   ```

5. Get Telegram data
   
   Telegram uygulamasında web denetlemeyi etkinleştirin. Nasıl etkinleştirilir, videoya bakın: https://youtu.be/NYxHmck_GjE
   pixeltap botuna gidin ve uygulamayı açın.
   Klavyenizde F12 tuşuna basarak geliştirici aracını açın veya uygulamaya sağ tıklayıp İncele seçeneğini seçin.
   Konsol menüsüne gidin ve javascript kodunu kopyalayıp konsol menüsüne yapıştırın.
   Hata mesajı almazsanız, telegram verilerini başarıyla kopyaladığınız anlamına gelir ve data.txt dosyasına yapıştırın (1 satırda 1 telegram verisi).
   
   Örnek Telegram Verisi

   ```
   query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

   6. Daha fazla hesap eklemek isterseniz, ikinci hesap verilerini ikinci satıra yapıştırın.
   
   Aşağıdaki örnekte olduğu gibi:

   ```
   1.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   2.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

6. Botu çalıştırın:
   
   Windows
   
   ```shell
   python bot.py
   ```

   Linux

   ```shell
   python3 bot.py
   ```

# Oyun Oynama Ayarları

config.json dosyasını düzenleyerek istediğiniz puanı ayarlayın.


# Video Rehberi


Buradan : [https://youtu.be/KTZW9A75guI](https://youtu.be/KTZW9A75guI)

# Javascript ile Token Alma

```javascript
copy(Telegram.WebApp.initData)
```

# Botu 7/24 Aktif Tutma

Botu 7/24 çalıştırmak için vps/rdp kullanabilirsiniz. Linux vps'de screen uygulamasını kullanarak botu arka planda çalıştırabilirsiniz.


# Thank you < 3
