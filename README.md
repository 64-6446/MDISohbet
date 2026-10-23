# MDI Sohbet

Görme engelliler için yapılmış, ekran okuyucuyla (TalkBack, AndroTalk, Jieshuo) rahat kullanılan
bir WhatsApp uygulaması. Android 10 ve üzeri, 64 bit telefonlar.

MDI Sohbet, WhatsApp Web gibi telefonunuza **bağlı cihaz** olarak eklenir. Telefonunuzdaki
WhatsApp ana cihaz olarak kalır; ikisi aynı anda çalışır.

## Neler yapar

- Her mesaj tek parça okunur; eylemler yukarı/aşağı kaydırarak seçilir: alıntılanan mesaja
  doğrudan gitme, yanıtla, tepki ver, ilet, kopyala, düzenle, yıldızla, sil, mesaj bilgisi
  (kim okudu, kim dinledi, kime teslim edildi).
- Sohbete girince odak "N okunmamış mesaj" ayracına gider; yarım bıraktığınız yerden sürer.
- Sesli mesaj: çift dokunarak çal/durdur, 10 saniye ileri/geri sar, hız (1, 1,5, 2 kat).
  Kayıt Telegram kalitesinde (48 kHz Opus); basılı tutup bırakınca gönderilir, yukarı
  kaydırınca kayıt kilitlenir.
- Fotoğraflar telefonda yapay zekâyla betimlenir ve içindeki yazı okunur (fotoğraf hiçbir
  sunucuya gönderilmez).
- Anketler (oylarıyla), sabitlenmiş mesajlar, gruplardaki olaylar (katıldı, ayrıldı…),
  durumlar, kanallar, gelen aramalar, arşiv, sessize alma, sabitleme.
- Uygulama kapalıyken de bildirim; bildirimden yanıtlama.

Yapılamayanlar: sesli/görüntülü arama ve tek seferlik fotoğraflar (WhatsApp bunlara bağlı
cihazlarda izin vermiyor). Aramaları telefondaki WhatsApp'tan açarsınız.

## Kurulum

1. Sağdaki **Releases** bölümünden son sürümün `MDISohbet.apk` dosyasını indirin.
2. Dosyayı açın. Telefon "bilinmeyen kaynak" izni isterse verin.
3. Uygulamayı açın, WhatsApp numaranızı yazın, **Eşleşme kodu al**'a basın.
4. Telefona WhatsApp'tan gelen "kodu girin" bildirimine dokunun (ya da WhatsApp → Bağlı
   cihazlar → Cihaz bağla → Telefon numarasıyla bağla) ve kodu girin. Kodu uygulamadaki
   **Kodu kopyala** düğmesiyle kopyalayıp yapıştırabilirsiniz.
5. Ayarlar sekmesinde **Pil kısıtlamasını kaldır**'a basın; yoksa telefon arka planda
   bağlantıyı kesebilir.

## Güncellemeler

Uygulama Play Store'da yoktur; güncellemeyi kendisi bulur. Yeni sürüm çıkınca uygulama size
sorar, onaylarsanız indirir, doğrular ve kurar. Ayarlar → **Güncellemeleri denetle** ile elle
de bakabilirsiniz. Güncellemeler aynı anahtarla imzalıdır; başkasının yaptığı sahte bir sürüm
telefonunuza kurulamaz.

WhatsApp bağlantı yöntemini değiştirdikçe uygulama her gün otomatik olarak denetlenir ve
gerekirse yeni sürüm çıkarılır.

## Bilmeniz gerekenler

- MDI Sohbet resmi bir WhatsApp uygulaması değildir ve WhatsApp ile bağlantısı yoktur.
  WhatsApp kullanım şartları resmi olmayan uygulamalara izin vermez; hesabın kısıtlanması
  ihtimali vardır. Kullanmak sizin tercihinizdir.
- Arada sunucu yoktur: bağlantı doğrudan telefonunuzdan WhatsApp'a yapılır. Mesajlarınız
  yalnızca telefonunuzda ve WhatsApp'ta durur, hiçbir yere gönderilmez, yedeklenmez.
- Bu nedenle Play Store'da yayınlanmaz; yalnızca buradan indirin. Başka sitelerdeki kopyalar
  bize ait değildir.

## İletişim

isikmurat201@gmail.com

© Murat Doğan Işık
