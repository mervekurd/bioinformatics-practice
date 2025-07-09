# Bash Komutları

## pwd
Çalışma klasörünü gösterir.

## ls
Klasördeki dosyaları listeler.

## cd klasör_adi
Belirtilen klasöre geçer.

## mkdir klasör_adi
Yeni klasör oluşturur.

## touch dosya.txt
Boş bir dosya oluşturur.

## echo "Merhaba"
Ekrana yazı yazar.

## cat dosya.txt
Dosyanın içeriğini terminalde gösterir.

## Listeleme
ls -d */
Sadeece klasörleri gösterir. Dosyaları göstermez.

ls -l | grep "^d"
Bu komut da sadece klasörleri listeler. (grep ile filtreleme yapar)

ls -d .*/ */
Hem normal klasörleri hem de nokta (.) ile başlayan gizli klasörleri gösterir.

ls -a
Bu komut tüm dosyaları listeler:
Normal dosyalar
Gizli dosyalar (nokta ile başlayanlar)
Ayrıca . (bulunduğun klasör) ve .. (üst klasör) de görünür.

ls -l
Dosyaları ve klasörleri gösterir. Klasörler d ile başlarken - ile başlayanlar dosyadır. 

## Silme
rm dosya_adi

| Komut              | Ne Yapar                                           |
| ------------------ | -------------------------------------------------- |
| `rm dosya.txt`     | Dosyayı siler                                      |
| `rm -i dosya.txt`  | Silmeden önce onay ister                           |
| `rm -f dosya.txt`  | Onay istemeden zorla siler                         |
| `rm -r klasor_adi` | Bir klasörü ve içindekileri siler (çok tehlikeli!) |



















