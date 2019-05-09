# GİTHUB METİN İŞARETLEME(MARKDOWN)

### Başlık Kullanımı

# En Büyük Başlık
## İkinci Büyük Başlık
### Üçüncü Büyük Başlık
#### Dördüncü Büyük Başlık
##### Beşinci Büyük Başlık
###### Altıncı Büyük Başlık
Yukarıdaki başlıkların büyüklüğü, önündeki diyez sayısı ile ters orantılı.


**koyu**


*italic*


***koyu ve italik***


**Koyu içinde *italik* yazı**


~~üstü çizili~~

### Alıntı:
Ahmet dedi ki:
>Bu bir alıntıdır.


### Kod Alıntısı:
Haydi kod alıntısı yapalım:
 `print("hello world")`


### Blok alıntı:
```
print(1)
print(2)
```

### Bağlantı Verme:
Google için [buraya](https://www.google.com) tıklayın:

Yukarıda köşeli parantez ve link için verilen normal parantez bitişik olmalı.


### Normal Url ile Bağlantı:

www.github.com   Geçerli url'lere doğrudan link veriliyor.

### Relative Bağlantı Verme:
[Relative link veriyorum:](main.py) -> İçinde bulunulan yolun sonuna, parantez içinde yazılan linki ekliyor.

Yukarıdaki relative link verme özelliği, ./ ve ../. gibi relative link verme işleçlerini destekliyor.

### Resim Ekleme:

![Fotoğrafta problem çıkarsa yayınlanacak yazı burada](https://avatars0.githubusercontent.com/u/1525981?s=200&v=4)

Yukarıdaki parantez içine resimin yolunu yazdık.

Köşeli parantez önündeki ünlem işareti önemli! 


### Sırasız(Başa gelen - ve boşluk ile), sıralı(Başa gelen sayı, sonrasında nokta ve sonrasında boşluk ile) ve içiçe listeler oluşturabilirsiniz:
#### Sırasız Liste
- Sırasız eleman 1
- Sırasız eleman 2
- Sırasız eleman 3

#### Sıralı Liste
1. Sıralı eleman 1
2. Sıralı eleman 2
3. Sıralı eleman 3

#### İçiçe Liste:
1. Birinci Seviye 1. Eleman
    - İkinci Seviye 1. Eleman
    - İkinci Seviye 2. Eleman 
      - Üçüncü Seviye 1. Eleman
      - Üçüncü Seviye 2. Eleman
    - İkinci Seviye 3. Eleman
2. Birinci Seviye 2. Eleman

Yukarıdaki girintileme işlemlerinde, bir elemanı üsttekinin alt seviyesine idirmek iöin girintileme kullanıldığına dikkat edin!

### Görev Listeleri Oluşturma - [ ] ile (Köşeli parantez içinde 1 adet boşluk karakteri var.)
- [x] Birinci Görev - Tamamlanan görevi işaretlemek için köşeli parantezler arasına x koyuyoruz.
- [ ] İkinci Görev
- [ ] Üçüncü Görev


### Emoji Kullanmak -   :emojikodu: (İki ikinokta arasına emoji kodu yazılarak yapılır.)
Mesela beğenme emojisi için :+1:, kalp emojisi için :heart: yazabilirsiniz.

### Alt Satıra Geçmek ve Paragraf Oluşturmak:
Özellikle işaretlenmemiş metinlerin bir alt satıra geçmesini sağlamak için bizim burada normal olarak bir alt satıra geçmemiz
yeterli olmuyor, onun yerine arada bir satır boşluk oluşturmamız lazım.

Burada 
yeni satıra geçilmedi.

Burada

yeni satıra geçildi.

### Kaçış Karakteri:  \
Metin işaretleme işleçlerinin önüne  \  koyarak o işleçin çalışmasını engelleyerek sadece karakter olarak algılanmasını sağlayabilirsiniz.

*italik*

\*italik\* engellendi, * işareti göründü.



```
```
def get_file_objects(folder_path, file_names):
    for file_name in file_names:
        file_path = folder_path + sep+ file_name
        with open(file_path) as f:
            yield f

def read_file_lines(file_objects):
    for file_object in file_objects:
        for line in file_object:
            yield line

def read_char(lines):
    for line in lines:
        for char in line:
            yield char
```

Çok iyi böyle 
