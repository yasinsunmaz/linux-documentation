# Linux Command Documentation
## Bulunan dizin yolunu göster
- pwd
- Listele
 - ls
 - ls -a --> Gizli nesneleri göster
 - ls -l --> Detaylı alfabetik olarak listeleme
 - ls -lt --> Detaylı tarihi göre listeleme
- Dizine değiştirme
 cd foldername
 cd .. --> Bİr önceki dizine geri döner
 cd - --> Önceki dizine geri döner
- Dizin oluştur
 mkdir foldername
 mkdir -p folderName/inFolderName --> İç içe klasör oluşturma
- Dosya oluştur
 touch dosyadi.uzanti
- Terminali temizle
 clear veya cls
- Dosya silme işlemi
 rm filename
- Klasör silme işlemi
 rm -r foldername
 rm -rf fullFolderName --> Dolu klasörü silme
- Komut geçmişini getirme
 history
 history 10 --> Son 10 komutu listeler
- Uzun komutları kısaltma olarak ekleme
 alias ml=" echo \"merhaba\""
 Terminale ml yazınca "merhaba" sonucu geriye döner
- Dosya/Klasör kopylama
 cp
 cp -r --> Klasör dolu ise -r recursive kullanılır
- Dosya/Klasör taşıma
 mv filename targetFolder
- Dosyanın ilk satırlarını varsayılan 10 satırı getirir
 head -n 5 filename
- Dosyanın son satırlarını varsayılan 10 satırı getirir
 tail -n 5 filename
- Filtreleme işlemleri, RegEx (düzenli ifadeler) kullanılarak da arama yapılabilir
 grep -i --> Bütük/küçük harf duyarlılığı kaldırarak arama yapar
 grep -in --> Ek olarak bulunan ifadenin hangi satırda olduğunu gösterir
 Kullanım: grep -i "searchText" filename
- Komutların klavuzunu görüntüleme
 man commandName --> İlgili komutun klavuzunu getirir
- Dosya izinleri verme
 chmod accessname filename
 r --> okuma
 w --> yazma
 x --> çalıştırma
 Kullanımı: chmod -w filename --> Dosyanın yazma iznini kaldırır
 Kullanımı: chmod +x filename --> Dosyanın çalışma izni verir
- Komut dosyasından çıkma
 exit
- Ekrana yazı yazdırma
 echo messageDetail


 

