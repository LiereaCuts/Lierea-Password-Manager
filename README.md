Şifre Oluşturucu

Bu proje, güçlü ve rastgele şifreler oluşturmanıza yardımcı olan bir şifre oluşturucu uygulamasıdır. Kullanıcı, şifrenin uzunluğunu ve içereceği karakter türlerini seçebilir.

Özellikler

Kullanıcı belirlediği uzunlukta rastgele şifreler oluşturabilir.

Büyük harf, küçük harf, rakam ve özel karakter desteği.

Kullanıcı dostu arayüz.

Tek tıklamayla şifreyi panoya kopyalama.

Kurulum

Python'u yükleyin (Eğer yüklü değilse: Python İndir)

Gerekli kütüphaneleri yükleyin (Eğer gerekiyorsa):

pip install PyQt6

şifre_oluşturucu.py dosyasını çalıştırarak uygulamayı başlatın:

python şifre_oluşturucu.py

Derleme (Exe'ye Çevirme)

Eğer uygulamayı bağımsız bir .exe dosyası olarak çalıştırmak istiyorsanız:

pyinstaller --onefile --windowed --icon=icon.ico şifre_oluşturucu.py

Bu komut dist klasörü içinde şifre_oluşturucu.exe adlı çalıştırılabilir bir dosya oluşturacaktır.

Kullanım

Uygulamayı başlatın.

Şifrenin uzunluğunu seçin.

İçerilecek karakter türlerini belirleyin.

"Şifre Oluştur" butonuna basarak rastgele bir şifre oluşturun.

Şifreyi kopyalayarak kullanabilirsiniz.

Gereksinimler

Python 3.x

PyQt6 (Eğer GUI versiyonunu kullanıyorsanız)

Lisans

Bu proje açık kaynaklıdır ve kişisel/kamusal kullanım için serbesttir.

Not: Eğer herhangi bir hata alırsanız veya yeni özellikler eklemek isterseniz, bana bildirebilirsiniz! 😊
