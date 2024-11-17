# Linux Konsol Komutları
Bu proje, Linux terminal komutlarını öğrenmek isteyen başlangıç seviyesindeki kullanıcılar için hazırlanmış bir rehber niteliğindedir. Komutlar, kategorilere ayrılarak kullanım şekilleri ve örnekleriyle sunulmuştur.

## Klasör Komutları

#### **mkdir** Komutu
Yeni bir klasör oluşturmak için kullanılır.
```
> Kullanım Şekli: mkdir Yeni_Klasör
```
![photo_2024-11-17_18-23-48](https://github.com/user-attachments/assets/949abef8-5814-4d79-ba21-32a8f92d2c20)

> [!IMPORTANT]
> Eğer klasör adında boşluk olacaksa, klasör ismini çift tırnak içinde yazmanız gerekir.
```
> Kullanım Şekli: mkdir "Yeni Klasör"
```
> [!CAUTION]
> Eğer mevcut dizinde aynı isimde bir klasör zaten varsa, mkdir bir hata verir ve o klasörü tekrar oluşturmaz.
<br>

#### **rmdir** Komutu 
Mevcut ve boş bir klasörü silmek için kullanılır.
```
> Kullanım Şekli: rmdir Silinecek_Klasör
```
![photo_2024-11-17_18-23-50](https://github.com/user-attachments/assets/c4b46b0a-db6d-4021-a662-488502f1612e)

> [!CAUTION]
> Klasörün içinde dosyalar varsa, önce dosyaları ve alt klasörleri kaldırmanız gerekir. Tüm içerikleriyle bir klasörü silmek için `rm -r` kullanılabilir.
<br>

## Dosya Komutları
#### **touch** Komutu
Yeni bir dosya oluşturmak veya mevcut bir dosyanın tarih ve saat bilgilerini güncellemek için kullanılır.
```
> Kullanım Şekli: touch Ornek_Dosya.txt
```
![photo_2024-11-17_18-30-57](https://github.com/user-attachments/assets/bacd2c71-ef99-45ab-bcd6-105a62ebeeb5)

> [!CAUTION]
> Aynı isimde bir dosya varsa, dosya içeriği değişmez, yalnızca tarih ve saat bilgisi güncellenir.
<br>

#### **cp** Komutu
Bir dosyayı veya klasörü kopyalar.
```
> Kullanım şekli: cp Ornek_Dosya.txt Yeni_Klasor
```
![photo_2024-11-17_18-35-15](https://github.com/user-attachments/assets/f6d3e5a2-7cff-4901-93ac-6a75c5008519)
<br>

#### **mv** Komutu
Bir dosyayı veya klasörü taşır ya da yeniden adlandırır.
```
> Kullanım Şekli: mv Ornek_Dosya.txt Hedef_Klasor
```
![photo_2024-11-17_18-35-18](https://github.com/user-attachments/assets/7e2dc7f2-99a7-4826-aaa2-9282e3ffba00)
<br>

#### **rm** Komutu
Bir dosyayı veya klasörü siler.
```
> Kullanım Şekli: rm Ornek_Dosya.txt
```
![photo_2024-11-17_18-39-11](https://github.com/user-attachments/assets/f8b6f4bb-8fa5-4648-b69b-087f93543be0)
![photo_2024-11-17_18-40-17](https://github.com/user-attachments/assets/4c13d39b-a1be-4bac-a40a-d9296a97b8b1)
<br>

#### **cat** Komutu
Bir dosyanın içeriğini terminale yazdırır.
```
> Kullanım şekli: cat Ornek_Dosya.txt
```
![photo_2024-11-17_18-40-19](https://github.com/user-attachments/assets/43aabdd9-762e-4fd6-ac6d-1ae12f76ea18)
<br>

#### **head** Komutu
Bir dosyanın ilk birkaç satırını gösterir.
```
> Kullanım şekli: head Ornek_Dosya.txt
```
![photo_2024-11-17_18-49-56](https://github.com/user-attachments/assets/0891b6bb-02e4-4427-ac9e-8a90f5d33559)
<br>

#### **tail** Komutu
Bir dosyanın son birkaç satırını gösterir.
```
> Kullanım şekli: tail Ornek_Dosya.txt
```
![photo_2024-11-17_18-49-59](https://github.com/user-attachments/assets/8cf28553-c369-483c-adcf-198e558faabd)
<br>

## Navigasyon Komutları
#### **cd** Komutu
Farklı bir dizine geçiş yapmak için kullanılır.
```
> Kullanım Şekli: cd Belgelerim
```
![photo_2024-11-17_18-28-24](https://github.com/user-attachments/assets/d36c1398-e751-4b95-bcd9-c5ec4d775b69)

> [!WARNING]
> Eğer klasör adı boşluk içeriyorsa, tırnak işaretleri kullanarak yazmalısınız.

![photo_2024-11-17_19-02-58](https://github.com/user-attachments/assets/69e711c6-0161-49e2-ae65-c8d00f6b4f4c)

> [!TIP]
> Mevcut dizinden bir üst dizine çıkmak için `cd ..` komudunu kullanabilirsiniz.
<br>

#### **ls** Komutu
Mevcut dizindeki dosya ve klasörleri listeler.
```
> Kullanım Şekli: ls
```
![photo_2024-11-17_18-29-59](https://github.com/user-attachments/assets/0db33ce6-792b-4ff8-91a3-1a82defd2c2b)
<br>

#### **pwd** Komutu
Şu an içinde bulunduğunuz dizinin tam yolunu ekrana yazdırır.
```
> Kullanım Şekli: pwd
```
![photo_2024-11-17_18-30-54](https://github.com/user-attachments/assets/d51fe51d-2cf7-40b2-814f-557db22aacf8)
<br>

## Sistem Komutları
#### **whoami** Komutu
Hangi kullanıcı hesabıyla giriş yaptığınızı gösterir.
```
> Kullanım Şekli: whoami
```
![photo_2024-11-17_18-41-56](https://github.com/user-attachments/assets/6c685e47-0eb7-4fe1-8686-6c6358a010e5)
<br>

#### **uname** Komutu
İşletim sistemi hakkında bilgi verir.
```
> Kullanım Şekli: uname
```
![photo_2024-11-17_18-42-42](https://github.com/user-attachments/assets/62a906e3-5ee7-4f46-bf37-c34a9ad81edb)

> [!TIP]
> `uname -a`, sistem hakkında tüm bilgileri gösterir.
<br>

#### **df** Komutu
Disk kullanımını ve boş alan miktarını gösterir.
```
> Kullanım Şekli: df
```
![photo_2024-11-17_18-51-23](https://github.com/user-attachments/assets/f504b69d-b66a-4575-a127-f73c22132fd7)

> [!IMPORTANT]
> `df -h`, bilgileri insan tarafından okunabilir hale getirir (ör. GB, MB, KB).
<br>

#### **hostname** Komutu
Bilgisayarın ağ üzerindeki adını gösterir.
```
> Kullanım Şekli: hostname
```
![photo_2024-11-17_18-52-52](https://github.com/user-attachments/assets/893d2fff-576d-4f34-a4c8-e7c5ffef5f21)

> [!TIP]
> Sistem adını değiştirmek için yönetici haklarına ihtiyacınız vardır.
<br>

#### **uptime** Komutu
Sistemin ne kadar süredir çalıştığını ve kaç kullanıcının bağlı olduğunu gösterir.
```
> Kullanım Şekli: uptime
```
![photo_2024-11-17_18-53-56](https://github.com/user-attachments/assets/016df4d5-55d6-4b45-b411-0d71a97c4623)
<br>

#### **clear** Komutu
Terminal ekranını temizler. 
```
> Kullanım Şekli: clear
```
![photo_2024-11-17_18-55-10](https://github.com/user-attachments/assets/0356616d-0807-4172-8b59-0c1f716bfcaa)
![photo_2024-11-17_18-55-12](https://github.com/user-attachments/assets/0bd1f430-0e20-4e6e-97e5-4558b7152815)

> [!NOTE]
> Sadece görsel temizleme yapar, terminal geçmişini temizlemez.
<br>

## Geçmiş ve Performans Komutları
#### **history** Komutu
Daha önce çalıştırılan komutların listesini gösterir.
```
> Kullanım Şekli: history
```
![photo_2024-11-17_18-56-47](https://github.com/user-attachments/assets/45801af3-e056-4c7a-8ffb-6458d7ca8200)

> [!IMPORTANT]
> Komut geçmişini temizlemek isterseniz history -c kullanabilirsiniz.
<br>

#### **top** Komutu
Çalışan işlemleri gerçek zamanlı olarak gösterir.
```
> Kullanım Şekli: top
```
![photo_2024-11-17_18-56-58](https://github.com/user-attachments/assets/58b9afee-c907-42a1-bea1-3cb7e3ad473f)

> [!TIP]
> İşlemleri sıralamak veya belirli işlemleri sonlandırmak için kullanılabilir.
> [!WARNING]
> Yanlış işlemi sonlandırmaktan kaçınmak için dikkatli olmalısınız.
