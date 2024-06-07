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

## Nasıl Kayıt Olunur?

Referansım dolu, bu yüzden tekrar referansa ihtiyacım yok. Arkadaşınızdan davet kodu isteyin!

## Nasıl Kullanılır

1. Bilgisayarınıza python ve git'in yüklü olduğundan emin olun.

# How to Use

1. Make sure your computer was installed python and git.

2. Clone this repository
   ```shell
   git clone https://github.com/akasakaid/blumtod.git
   ```
3. Go to blumtod
   ```
   cd blumtod
   ```
4. Install python library
   
   Windows
   ```
   pip install -r requirements.txt
   ```

   or 

   ```
   python -m pip install -r requirements.txt
   ```

   Linux

   ```
   pip3 install -r requirements.txt
   ```

   or

   ```
   python3 -m pip install -r requirements.txt
   ```

5. Get Telegram data
   
   1. Active web inspecting in telegram app, How to activate follow the video [https://youtu.be/NYxHmck_GjE](https://youtu.be/NYxHmck_GjE)
   2. Goto pixeltap bot and open the apps
   3. Press `F12` on your keyboard to open devtool or right click on app and select `Inspect`
   4. Goto `console` menu and copy [javascript code](#javascript-command-to-get-telegram-data-for-desktop) then paste on `console` menu
   5. If you don't receive error message, it means you successfully copy telegram data then paste on `data.txt` (1 line for 1 telegram data)
   
   Example telegram data

   ```
   query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

   6. If you want to add more account. Just paste telegram second account data in line number 2.
   
   Maybe like this sample in below

   ```
   1.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   2.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

6. Run the bot
   
   Windows
   
   ```shell
   python bot.py
   ```

   Linux

   ```shell
   python3 bot.py
   ```

# Play Game Configuration

Edit `config.json` to set your point that your want !


# Video Guide to Get Data

The require data is same like [pixelversebot](https://github.com/akasakaid/pixelversebot) so you can watch same tutorial / video guide to get data !

Here : [https://youtu.be/KTZW9A75guI](https://youtu.be/KTZW9A75guI)

# Javascript Command to Get Telegram Data for Desktop

```javascript
copy(Telegram.WebApp.initData)
```

# Run for 24/7 

You can run the script bot for 24/7 using vps / rdp. You can use `screen` application in vps linux to running the script bot in background process

# Discussion

If you have an question or something you can ask in here : [@sdsproject_chat](https://t.me/sdsproject_chat)

# Support

To support me you can buy me a coffee via website in below

- https://trakteer.id/fawwazthoerif/tip
- https://sociabuzz.com/fawwazthoerif/tribe

# Thank you < 3
