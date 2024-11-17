# Windows DOS Komutları

Bu proje, DOS komutlarını öğrenmek isteyen başlangıç seviyesindeki kullanıcılar için hazırlanmış bir rehber niteliğindedir. Komutlar kategorilere ayrılarak kullanım şekilleri ve örnekleriyle sunulmuştur.

## Klasör Komutları

#### **mkdir** Komutu
mkdir komutu, yeni bir klasör oluşturmak için kullanılır.
```
> Kullanım Şekli: mkdir Yeni_Klasör
```
![photo_2024-11-17_02-27-23](https://github.com/user-attachments/assets/22f3a6cf-bb6a-474a-959d-65d3a781566c)
![photo_2024-11-17_02-27-33](https://github.com/user-attachments/assets/e7a774e1-d58c-480b-a66a-9ea6d61f9798)

> [!IMPORTANT]
> Eğer klasör isminiz boşluk içeriyorsa, klasör adını tırnak işaretleri içine almayı unutmayın
```
> Kullanım Şekli: mkdir "Yeni Klasör"
```
<br>

#### **rmdir** Komutu 
rmdir komutu, belirtilen bir klasörü silmek için kullanılır.
```
> Kullanım Şekli : rmdir Silinecek_Klasör
```
![photo_2024-11-17_03-08-11](https://github.com/user-attachments/assets/e45916c0-3ceb-4950-887d-4974c40232ed)
![photo_2024-11-17_02-36-48](https://github.com/user-attachments/assets/d08b8fc0-28b3-4b73-b307-bccd2ea73db8)

> [!CAUTION]
> Klasörün içinde dosya varsa, rmdir komutu çalışmaz. Klasörü silebilmek için önce içindeki dosyaları silmeniz gerekebilir.
<br>

#### **cd** Komutu
Belirtilen klasöre geçiş yapar.
```
> Kullanım Şekli: cd Belgelerim
```
![photo_2024-11-17_02-36-51](https://github.com/user-attachments/assets/cce12c06-3987-445c-a2fa-bdbc74c91d1d)

> [!WARNING]
> Eğer klasör adı boşluk içeriyorsa, tırnak işaretleri kullanarak yazmalısınız.

![photo_2024-11-17_02-36-56](https://github.com/user-attachments/assets/fb98b16e-9c47-4124-a534-4965ea19ed06)

> [!TIP]
> Mevcut dizinden bir üst dizine çıkmak için `cd ..` komudunu kullanabilirsiniz.

## Dosya Komutları

#### **start** Komutu
Bir dosya veya uygulamayı başlatır.
```
> Kullanım Şekli : start uygulama.exe
```
![photo_2024-11-17_03-04-41](https://github.com/user-attachments/assets/c506113c-b5e3-460e-bcd5-5f8fd2d5eb89)
<br>

#### **dir** Komutu
Geçerli dizindeki dosya ve klasörleri listeler.
```
> Kullanım Şekli : dir
```
![photo_2024-11-17_02-45-39](https://github.com/user-attachments/assets/ec77c519-3ff4-4db5-afec-4c892ea94e04)
<br>

#### **tree** Komutu
Belirtilen bir yolun hiyerarşik dizin yapısını görüntüler.
```
> Kullanım şekli : tree
```
![photo_2024-11-17_02-47-45](https://github.com/user-attachments/assets/af661a79-c7fb-4bb0-9cef-6aa12dac2fc3)
<br>

#### **echo** Komutu
Belirtilen metni ekrana yazdırır veya bir dosyaya kaydeder.
```
> Kullanım Şekli : echo "Merhaba, Dünya!"
```
![photo_2024-11-17_02-49-29](https://github.com/user-attachments/assets/ebeed586-6159-45f4-aa04-ed1f4d984681)
![photo_2024-11-17_02-49-32](https://github.com/user-attachments/assets/92776085-5bc2-4e9e-bfdc-01fddc2d87e9)

> [!TIP]
> Eğer metni bir dosyaya yazdırmak isterseniz, > işaretini kullanarak yönlendirebilirsiniz.
<br>

#### **type** Komutu
Belirtilen dosyanın içeriğini görüntüler.
```
> Kullanım Şekli : type Dosya_Adi.txt
```
![photo_2024-11-17_02-51-03](https://github.com/user-attachments/assets/025cc70f-22db-48ff-8c9a-87c60e24d781)

> [!WARNING]
> Arama sırasında büyük ve küçük harf duyarlılığına dikkat edin. Metni tam yazmalısınız, aksi takdirde sonuç almayabilirsiniz.
<br>

#### **find** Komutu
Bir dosyada belirli bir metni arar.
```
> Kullanım şekli : find "Kelime" Dosya_Adi.txt
```
![photo_2024-11-17_02-52-55](https://github.com/user-attachments/assets/1b14e23e-1580-4f9a-88a9-4362d692657b)

> [!WARNING]
> Arama sırasında büyük ve küçük harf duyarlılığına dikkat edin. Metni tam yazmalısınız, aksi takdirde sonuç almayabilirsiniz.
<br>

#### **copy** Komutu
Bir dosyayı başka bir yere kopyalar.
```
> Kullanım Şekli : copy Ornek_Dosya.txt Yeni_Klasor
```
![photo_2024-11-17_02-54-25](https://github.com/user-attachments/assets/b77dd949-2a16-4576-83ff-355bf4c8ac85)
![photo_2024-11-17_02-54-27](https://github.com/user-attachments/assets/4ac9d68d-cce0-4400-968e-0fbda8440c85)

> [!IMPORTANT]
> Kopyalanacak dosyanın yolu tam olarak belirtilmelidir. Klasör adı boşluk içeriyorsa, tırnak işaretleri kullanın.
<br>

#### **move** Komutu
Bir dosyayı başka bir konuma taşır.
```
> move Ornek_Dosya.txt Hedef_Klasör
```
![photo_2024-11-17_02-55-49](https://github.com/user-attachments/assets/9c1d9121-94a8-4779-a02e-64a4648117bd)
![photo_2024-11-17_02-55-52](https://github.com/user-attachments/assets/05fcaa5a-0113-4b48-a647-2fef462d3543)

> [!WARNING]
> Taşıma işlemi, dosyayı orijinal konumundan kaldırır. Eğer yanlış yere taşırsanız, dosya kaybolabilir.
<br>

#### **ren** Komutu
Bir dosyanın veya klasörün adını değiştirir.
```
> Kullanım Şekli : ren Eski_Adi.txt Yeni_Adi.txt
```
![photo_2024-11-17_02-57-27](https://github.com/user-attachments/assets/b6e98379-2f59-4c1f-82c9-3a06cef0b7e9)
![photo_2024-11-17_02-57-33](https://github.com/user-attachments/assets/542508f2-9ede-48d6-a50b-a6d5e295291f)

> [!CAUTION]
> Dosya adı değiştirildiğinde, dosyanın uzantısı (örneğin .txt) değiştirilemez.
<br>

#### **del** Komutu
Belirtilen dosyayı kalıcı olarak siler.
```
> Kullanım Şekli : del Silinecek_Dosya.txt
```
![photo_2024-11-17_02-58-44](https://github.com/user-attachments/assets/20236bcc-7d87-40ac-837d-369082edc668)
![photo_2024-11-17_02-58-46](https://github.com/user-attachments/assets/fbecf2c0-03a5-46e0-8f2d-b804002d26c3)
<br>

## Sistem Komutları

#### **systeminfo** Komutu
Bilgisayarın sistem bilgilerini görüntüler.
```
> Kullanım Şekli : systeminfo
```
![photo_2024-11-17_03-00-00](https://github.com/user-attachments/assets/06040b2d-97ea-42ee-aced-041672de2231)
<br>

#### **ipconfig** Komutu
Ağ bağdaştırıcılarının yapılandırmalarını ve IP adreslerini gösterir.
```
>Kullanım şekli : ipconfig
```
![photo_2024-11-17_03-01-09](https://github.com/user-attachments/assets/728c2716-8909-4207-a976-b72219c53f1b)
<br>

#### **tasklist** Komutu
Çalışan işlemleri listeler.
```
> Kullanım Şekli : tasklist
```
![photo_2024-11-17_03-01-55](https://github.com/user-attachments/assets/0c7361ab-d5ea-4209-b1ac-2a16a6dbec70)
<br>

## Tarih ve Saat Komutları

#### **date /T** Komutu
Güncel tarihi görüntüler.
```
>Kullanım Şekli : date /T
```
![photo_2024-11-17_03-03-01](https://github.com/user-attachments/assets/5495895d-1b2f-4cef-a1eb-f01a0df42cba)
<br>

#### **time /T** Komutu
Güncel saati görüntüler.
```
> Kullanım Şekli : time /T
```
![photo_2024-11-17_03-03-03](https://github.com/user-attachments/assets/a27617e1-634f-494a-becd-826b76ab57c5)
<br>

## Disk Yönetimi ve Kapatma Komutları

#### **diskpart** Komutu
Disk bölümlerini ve yapılandırmalarını yönetmek için kullanılır.
```
> Kullanım Şekli : diskpart
```
![photo_2024-11-17_03-06-34](https://github.com/user-attachments/assets/e26e167f-d22e-4f78-9dda-5625102a15e7)

> [!WARNING]
> Disk bölümleme işlemleri dikkatli yapılmalıdır, yanlışlıkla veri kaybına neden olabilir.
<br>

#### **shutdown /s /t** Komutu
Bilgisayarı kapatır veya yeniden başlatır.
```
> Kullanım Şekli : shutdown /s /t 30
```
![photo_2024-11-17_03-06-37](https://github.com/user-attachments/assets/be98330e-c444-4e8e-9048-28ad729f1f4a)

> [!IMPORTANT]
> 30 saniye sonra bilgisayar kapanacaktır. Eğer işlem iptal edilmek isteniyorsa, shutdown /a komutunu kullanabilirsiniz.
