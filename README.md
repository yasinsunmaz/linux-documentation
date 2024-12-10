# Linux Command Documentation / Linux Komut Dokümanı
### Bulunan dizin yolunu göster
- pwd
### Listele
- ls
- ls -a --> Gizli nesneleri göster
- ls -l --> Detaylı alfabetik olarak listeleme
- ls -lt --> Detaylı tarihi göre listeleme
### Dizine değiştirme
- cd foldername
- cd .. --> Bİr önceki dizine geri döner
- cd - --> Önceki dizine geri döner
### Dizin oluştur
- mkdir foldername
- mkdir -p folderName/inFolderName --> İç içe klasör oluşturma
### Dosya oluştur
- touch dosyadi.uzanti
### Dosya içeriğini okuma
- cat filename
- cat > filename --> Dosya oluşturma
- cat -n 10 filename --> Dosyayı satır numarası ile yazdırma
### Terminali temizle
- clear veya cls
### Dosya silme işlemi
- rm filename
### Klasör silme işlemi
- rm -r foldername
- rm -rf fullFolderName --> Dolu klasörü silme
### Komut geçmişini getirme
- history
- history 10 --> Son 10 komutu listeler
### Uzun komutları kısaltma olarak ekleme
- alias ml=" echo \"merhaba\""
- Terminale ml yazınca "merhaba" sonucu geriye döner
### Dosya/Klasör kopyalama
- cp
- cp -r --> Klasör dolu ise -r recursive kullanılır
### Dosya izinleri verme
- chmod accessname filename
- r --> okuma
- w --> yazma
- x --> çalıştırma
- Kullanım: chmod -w filename --> Dosyanın yazma iznini kaldırır
- Kullanım: chmod +x filename --> Dosyanın çalışma izni verir
### Dosya/Klasör taşıma
- mv filename targetFolder
### Dosyanın ilk satırlarını varsayılan 10 satırı getirir
- head -n 5 filename
- head -c5 filename --> Dosyada gösterilecek karakter sayısı
### Dosyanın son satırlarını varsayılan 10 satırı getirir
- tail -n 5 filename
- tail -c5 filename --> Dosyada sondan gösterilecek karakter sayısı
- tail -f filename --> Dosya değişikliklerini takip etmek
### Dosya ile ilgili bilgi alma
- file filename
### Dosya ile ilgili detaylı bilgi alma
- stat filename
### Dosyayı parça parça okuma
- more filename --> Komuttan çıkmak için "q" ifadesi kullanılır
### Dosya içeriğini more komutundan daha fazla seçenek ile parça parça okumak için kullanılır
- less filename -->Komuttan çıkmak için "q" ifadesi kullanılır
### Filtreleme işlemleri, RegEx (düzenli ifadeler) kullanılarak da arama yapılabilir
- grep -i --> Bütük/küçük harf duyarlılığı kaldırarak arama yapar
- grep -in --> Ek olarak bulunan ifadenin hangi satırda olduğunu gösterir
- Kullanım: grep -i "searchText" filename
### Dosya içeriğini sıralı okumak için kullanılırü
- sort filename
- sort -R filename --> Dosya içeriğini rastgele sıralanmış olarak okuma
- sort -n filename --> Dosya içeriğini sayısal sıralanmış olarak okuma
### Dosya içeriğini satır numarası ekleyerek okuma
- nl filename
### Dosya içeriğini sayfalayarak okuma
- pr filename
### Komutların klavuzunu görüntüleme
- man commandName --> İlgili komutun klavuzunu getirir
### Kullanıcı root erişimi
- sudo ls /root
### Ekrana yazı yazdırma
- echo messageDetail
### Komut dosyasından çıkma
- exit
