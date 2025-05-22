# Automate Python Practice tr-en
[![linkedin](https://img.shields.io/badge/LinkedIn-python--docs--tr-0A66C2?style=for-the-badge&logo=LinkedIn)](https://www.linkedin.com/in/veliulugut/) 
[![gmail](https://img.shields.io/badge/GMail-python--docs--tr-EA4335?style=for-the-badge&logo=Gmail)](mailto:veliulugut1@gmail.com)

> **Yazar Notu:**
>
> Bu döküman 19.05.2025 tarihinde [Python İle Sıkıcı İşleri Anında Bitir](https://www.buzdagikitabevi.com/python-ile-sikici-isleri-aninda-bitir-yeni-baslayanlar-icin-uygulamali-programlama)  ve  [YazBel](https://python-istihza.yazbel.com/index.html) kaynaklarından esinlenerek oluşturulmuştur.

> Bu proje, Python programlama dilini öğrenmek isteyenler için hem öğretici hem de uygulamalı bir kaynak olarak hazırlanmıştır. İçeriğinde, Python'un temel kavramları adım adım ele alan açıklamalar ve her konuyu pekiştirmeye yönelik uygulamalı alıştırmalar yer almaktadır.
> Yazım yanlışı veya kodlarda hata görmeniz halinde lütfen bildirin.

### İçindekiler

- [Giriş](#giriş)
- [Python ile Programlamanın Temelleri](#python-ile-programlamanın-temelleri)
  - [Python ile Operatörler](#python-ile-operatörler)
  - [Veri Tipleri](#veri-tipleri)
  - [Değişkenler](#değişkenler)
  - [print() Fonksiyonu](#print-fonksiyonu)
  - [input() Fonksiyonu](#input-fonksiyonu)
  - [len() Fonksiyonu](#len-fonksiyonu)
  - [str(), int(), float() Fonksiyonları](#str-int-float-fonksiyonları)
  - [Metin ve Sayı Denkliği](#metin-ve-sayı-denkliği)
  - [Alıştırma Soruları](#alıştırma-soruları)
- [Akış Kontrolü](#akış-kontrolü)
   - [Karşılaştırma Operatörleri](#karşılaştırma-operatörleri)
 


## Giriş

Python, tıpkı C,C++,Perl ya da Golang gibi bir programlama dilir. Bilgisayara ne yapması gerektiğini söylememizi sağlar; yani bir anlamda bilgisayarı kontrol etmenin bir yoludur.

Bu Dil, 1990'lı yılların başında Hollandalı geliştirici Guido van Rossum tarafından ortaya çıkarılmıştır. İsmi ilk bakışta bir yılandan geliyor gibi görünse de, aslında adını [Monthy Python's Flying Circus](https://en.wikipedia.org/wiki/Monty_Python%27s_Flying_Circus) adlı İngiliz komedi programından alır. Van Rossum bu programın hayranı olduğu için dilin ismini de buradan esinlenerek seçmiştir. Yine de, yıllar içinde Python dendiğinde yılan figürüyle anılması alışılmış bir durum haline gelmiştir.

Python'un öne çıkan en önemli özelliklerinden biri, öğrenme sürecinin diğer dillere kıyasla daha kolay olmasıdır. Bu yüzden, programlamaya yeni başlayanlar için oldukça uygun bir dildir. Daha önce kodlama deneyiminiz olmasa bile, Python ile başlamak oldukça iyi bir tercih olabilir.


## Python ile Programlamanın Temelleri

### Python ile Operatörler

Python programlama dilinde, matematiksel işlemleri gerçekleştirmek için kullanılan operatörler bulunmaktadır. Bu operatörler, sayılar üzerinde toplama, çıkarma, çarpma ve bölme gibi işlemleri yapmamıza olanak tanır.

| Operatör | İşlem | Örnek | Çıktı |
| -------- | ------- | ------ | ----- |
| ** | Üs | `2 ** 3` | 8 |
| % | Modülüs/kalan | `22 % 8` | 6 |  
| // | Tam değer bölümü | `22 // 8` | 2 |
| / | Bölme | `22 / 8` | 2.75 |
| * | Çarpma | `2 * 3` | 6 |
| + | Toplama | `2 + 3` | 5 |
| - | Çıkarma | `2 - 3` | -1 |

Python matematik operatörlerinin işlem sırası matematiktekilere benzerdir. Önce `**` ve `%` işlemleri, ardından `*`, `/`, `//` ve `+`, `-` işlemleri yapılır. İşlem önceliği sırasını değiştirmek için parantez kullanabilirsiniz.

> 💡 Boşluk (satır başındaki girinti hariç) Python için önemli değildir.

 `>>> 2 + 3 * 6` =  20

`>>> (5-1) * (( 7 + 1 ) / ( 3 - 1 ))` = 16.0

> Operatör ile işlemler yaparken sayıya kelime eklerseniz hata alırsınız.

`>>> 5 + File "<stdin>", line 1
SyntaxError: invalid syntax`


### Veri Tipleri

Python'da ifadeler, birden fazla bileşenin (örneğin sayılar ve operatörler) bir araya gelerek tek bir değer üretmesini sağlar. Her ifadenin sonucu bir değerdir.

>💡 Unutmayın: Python'da her değer, yalnızca bir veri tipine aittir. Veri tipleri, bu değerleri kategorize etmemizi sağlar.

🔢 Sayısal Veri Tipleri
| Veri Tipi | Açıklama | Örnekler |
| -------- | ------- | ------ |
| int | Tam sayılar | 1, 2, 3, -4, 0 |
| float | Ondalık sayılar | 1.0, 2.5, -3.14, 0.0 |

- 20 -> bir int (tam sayı) değeridir.
- 20.0 -> bir float (ondalık sayı) değeridir.

> 🧪 Her ne kadar 20 ile 20.0 görsel olarak benzer görünse de, Python bunları farklı veri tipleri olarak değerlendirir.

📝 Dizgiler (Strings)
Python'da metinleri temsil etmek için `dizgiler` (strings ya da `str`) kullanılır.
Bir dizgi, tek `(')` veya çift `(")` tırnak içine alınan karakterler dizisidir:

````python
'Merhaba'
"Python öğreniyorum"
'12345'
"12345"
````
- '' -> Boş bir dizgidir. İçinde hiç bir karakter bulunmamaktadır.
- Merhaba' -> 7 karakterden oluşan bir dizgidir.

> 🔐 Python, dizgilerin nerede başlayıp nerede bittiğini anlamak için tırnak işaretlerine güvenir.

> ⚠️ Sık Yapılan Hatalar

Eğer bir dizgiyi oluştururken tırnaklardan birini unutursanız, Python sizi bir hata mesajı ile uyarır.
```py
>>> 'Hello, World!
SyntaxError: EOL while scanning string literal
````
Bu hatanın sebebi, dizginin başladığı halde düzgün bir şekilde bitirilmemiş olmasıdır. Yani `'` işaretinin kapanışı eksiktir.

✅ Doğru Kullanım
```py
>>> 'Hello, World!'
'Hello, World!'
```

# Dizgi Birleştirme ve Çoğaltma
Python'daki bazı operatörlerin anlamı, kullanıldıkları veri tipine göre değişiklik gösterebilir.

Örneğin `+` operatörü:
- Sayılar için toplama işlemi yapar.
- Dizgiler üzerinde ise birleştirme (concatenation) işlemi yapar.

```py
>>> 'Veli' + 'Ulugut'
'VeliUlugut'
```

> `+` operatörünü bir dizgi ile sayı arasında kullanırsanız hata alırsınız.
```py
>>> 'Veli' + 20
Traceback (most recent call last):
  ...
TypeError: can only concatenate str (not "int") to str
```

> ❗ Bu hatanın nedeni, Python’un bir dizgi (str) ile bir tam sayıyı (int) doğrudan birleştiremiyor olmasıdır.

Bu durumda sayıyı dizgiye çevirmek gerekir. Bu işlem için `str()` fonksiyonunu kullanabilirsiniz. İlerleyen bölümlerde bu fonksiyonun nasıl çalıştığını öğreneceksiniz.
```py
>>> 'Veli' + str(20)
'Veli20'
```

# Dizgi Çoğaltma
Python'da bir dizgiyi tekrar etmek istiyorsanız * operatörünü kullanabilirsiniz. Bu işlem, dizgiyi belirttiğiniz sayı kadar çoğaltır.
```py
>>> 'Veli' * 3
'VeliVeliVeli'
```

`*` operatörü, dizgiler üzerinde kullanıldığında çoğaltma işlemi yapar. Ancak bu operatör, sayılar üzerinde kullanıldığında çarpma işlemi yapar.
```py
>>> 'Alice' * 'Bob'
Traceback (most recent call last):
  ...
TypeError: can't multiply sequence by non-int of type 'str'

>>> 'Alice' * 5.0
Traceback (most recent call last):
  ...
TypeError: can't multiply sequence by non-int of type 'float'
```

> ⚠️ `*` operatörü ile dizgi çoğaltmak istiyorsanız, ikinci operand mutlaka tam sayı `(int)` olmalıdır. `str` veya `float` tipleri ile kullanılamaz.

### Değişkenler

Bir değişken (variable), bilgisayarın belleğinde bir değeri geçici olarak saklayabileceğiniz bir isim etiketi gibidir. Programınızda bir işlem sonucu elde ettiğiniz değeri daha sonra tekrar kullanmak istiyorsanız, bu değeri bir değişkene atayarak saklayabilirsiniz.

### Değişken Tanımlama
Değişkenler, bir veriye ulaşmak ve onu temsil etmek için kullandığımız isimlerdir. Tıpkı bir kutunun üzerine etiket yapıştırmak gibi, veriye bir isim vererek o veriye daha kolay ulaşmamızı sağlar.

> 📝 Atama Deyimi (Assignment Statement)
Bir değeri bir değişkende saklamak için atama deyimi kullanılır. Bu deyim 3 bileşenden oluşur:

```py
değişken_ismi = değer
```

Buradaki `=` işareti, atama işlemini belirtir. Yani soldaki değişken ismine sağdaki değeri atar. Bu işlem, Python'da bir değişken tanımlamak için kullanılır.

```py
milkshake = 20

print(milkshake)
# Output: 20
```

### ♻️ Değişkenlerin Güncellenmesi
Bir değişken, daha önce sakladığınız değeri geçici olarak tutan bir etiket gibidir.Eğer aynı değişkene yeni bir değer atarsanız, yeni bir değer atarsanız, önceki değer artık bellekte tutulmaz yani silinir ve yerini yenisi alır.

```py
milkshake = 'Strawberry'
print(milkshake)
# Output: Strawberry

milkshake = 'vanilla milkshake'
print(milkshake)
# Output: vanilla milkshake
```
Bu örnekte milkshake değişkeni önce 'Strawberry' ifadesini saklıyor. Ancak ikinci atama yapıldığında, 'vanilla milkshake' yeni değer olarak atanıyor ve önceki 'Strawberry' değeri artık kullanılmaz hale geliyor.
> 🧃 Bunu, üzerinde etiket olan bir kutuya benzetebiliriz. İlk başta kutunun etiketi "Strawberry" iken, daha sonra etiketi söküp yerine "vanilla milkshake" yapıştırıyoruz. Artık kutunun ne içerdiğini görmek istesek, yalnızca "vanilla milkshake" cevabını alırız.


### Değişken İsimlendirme Kuralları ve İpuçları
Bir değişkenin adı, kodunuzun okunabilirliği için çok önemlidir. Tıpkı taşınma sırasında her kutuyu sadece "eşya" diye etiketlemenin hiçbir işe yaramayacağı gibi, kodunuzda da `data`, `info`, `stuff` gibi genel geçer isimleri kullanmak kafa karışıklığına neden olur.

`Kodunuzu okuyacak başka biri (veya gelecekteki siz)` için, değişken isimleri içerdikleri verinin ne olduğunu açıkça belirtmelidir.

#### ✅ Geçerli Değişken İsimleri için Kurallar
Python'da değişken isimleri verirken aşağıdaki 3 temel kurala uymanız gerekir:

1. Değişken ismi boşluk içeremez ve tek parça olmalıdır.

2. Sadece harfler, sayılar ve alt çizgi (_) karakteri kullanılabilir.

3. Sayı ile başlayamaz.

> ❗ Büyük/Küçük Harf Duyarlılığı

Python, değişken isimlerinde büyük/küçük harfe duyarlıdır.
```py
milkshake = 'Strawberry'
Milkshake = 'vanilla'
MILKSHAKE = 'chocolate'
```
Yukarıdaki üç değişken Python'da farklı değişkenlerdir.

| Stil Adı | Açıklama | Örnek |
| -------- | ------- | ------ |
| snake_case | Alt çizgi kullanılır | `user_name`,`file_path` |
| camelCase | Kelimeler birleştirilir, ilk kelime küçük kalır, diğerleri büyük harfle başlar | `userName`, `filePath` |
>
> 
>
PEP8 (Python'un resmi stil kılavuzu), snake_case kullanımını önerir. Ancak bazı geliştiriciler —özellikle JavaScript geçmişine sahip olanlar— camelCase stilini tercih eder.

> 🧭 Önemli olan tek bir stil seçip, proje boyunca tutarlı kalmaktır. "Stil kılavuzu bir rehberdir, mutlak kural değil" unutmayın.

#### ✅ Geçerli değişken isimleri:
```py
user_age = 25
filePath = "/home/docs"
_totalAmount = 180.50
```

#### ❌ Geçersiz değişken isimleri:
```py
2value = 5        # Sayı ile başlıyor (Geçersiz)
user name = "Ali" # Boşluk içeriyor (Geçersiz)
class = "Math"    # Python'da özel bir anahtar kelime (Geçersiz)
```

### print() Fonksiyonu
Python'da bir metni(dizgi/string) ya da değeri ekrana yazdırmak için `print()`fonksiyonunu kullanırız. Bu fonksiyonun temel görevi, kullanıcıya bilgi vermek veya çıktıyı görselleştirmektir.

```py
print("Hayat çok kisa değil mi ? ")

# Output: Hayat çok kisa değil mi ?
```
> ### Boş Satır Yazdırmak

Eğer `print()`fonksiyonunu `hiçbir argüman vermeden`çağırırsanız, sadece bir boş satır yazdırır.
```py
print("Satır 1")
print()
print("Satır 3")

# Output:
# Satır 1

# Satır 3
```

> 🎯 Not
>  - `print()` sadece dizgileri değil, sayıları ve değişkenleri de yazdırabilir.
> - İster çift tırnak `(")` ister tek tırnak `(')` kullanabilirsiniz. İkisi de aynı sonucu verir.


### input() Fonksiyonu
Python'da kullanıcıdan veri almak istiyorsak ìnput() fonksiyonu tam olarak ihtiyacımız olan şeydir. Bu fonksiyon çalıştırıldığında program durur ve kullanıcının klavyesinden bir metin girip Ènter`tuşuna basmasını bekler.

```py
userName = input("Adınızı girin: ")

# Output: Adınızı girin: Levi

print("Merhaba, " + userName)

# Output: Merhaba, Levi
```

> ⚠️ Not
> - ìnput()`fonksiyonu her zaman girdiyi bir dizgi (string) olarak alır.
> - Sayısal bir veri bekliyorsanız, girişi `int` ya da `float()` gibi dönüştürücülerle işleyebilirsiniz. (Bu konuyu ilerleyen bölümlerde göreceğiz.)

### len() Fonksiyonu
Python'da bir dizginin (string'in) uzunluğunu öğrenmek istiyorsanız, `len()`fonksiyonunu kullanabilirsiniz. Bu fonksiyon bir dizgi değeri ya da dizgi içeren bir değişken gönderildiğinde, dizginin `karakter sayısını`tam sayı (integer) olarak verir.

```py
mesaj = 'Her karanlık gecenin bir sabahı vardır.'

print(mesaj)
print(len(mesaj))

# Output:
# Her karanlık gecenin bir sabahı vardır.
# 42
```

### str(), int(), float() Fonksiyonları
Python'da farklı veri türleri arasında dönüşüm yapmak oldukça yaygındır. Özellikle kullanıcıdan alınan girişler `input()` her zaman dizgi (string) tipindedir. Bu yüzden bazen dizgileri sayıya ya da sayıları dizgiye çevirmek gerekir. İşte bu dönüşümleri yaparken `str()`, `int()` ve `float()` fonksiyonları kullanılır.

> #### str() Fonksiyonu - Sayıyı Dizgiye Çevirme
```py
print("Ben " + str(24) + " yaşındayım.")
# Ekran çıktısı: Ben 24 yaşındayım.
```

> #### int() Fonksiyonu - Dizgiyi Tam Sayıya Çevirme
```py
yas = input("Yaşını gir: ")
print(int(yas) + 1)  # Kullanıcının yaşını 1 artırır
# Ekran çıktısı: 25
```

> #### float() Fonksiyonu - Dizgiyi Ondalık Sayıya Çevirme
```py
sayisalDeger = "99.99"
print(float(sayisalDeger) + 0.01)  # 100.0 çıktısını verir
# Ekran çıktısı: 100.0
```

#### Özet
| Fonksiyon | Görevi | Örnek | Sonuç |
| -------- | ------- | ------ | ----- |
| str() | Sayıyı dizgiye çevirir | str(24) | '24' |
| int() | Dizgiyi tam sayıya çevirir | int('24') | 24 |
| float() | Dizgiyi ondalık sayıya çevirir | float('24.5') | 24.5 |

### Metin ve Sayı Denkliği
Python’da veri türleri çok önemlidir. Aynı görünüme sahip olsalar bile, farklı türdeki veriler Python tarafından farklı değerler olarak değerlendirilir. Bu durum, özellikle karşılaştırma `(==)` işlemlerinde belirgin şekilde ortaya çıkar.

| Karşılaştırma | Açıklama | Sonuç |
| -------- | ------- | ------ |
| `20 == '20'` | Sayı ile dizgi karşılaştırılamaz | `False` |
| `20 == 20.0 ` | Tam sayı ile kayan nokta aynı değeri taşıyor | `True` |
| `'20' == '20.0'` | Dizgiler aynı değil | `False` |
| `20.0 == 00.20.000`| Python, baştaki sıfırları dikkate almaz | `True` |


### Alıştırma Soruları

1. Aşağıdakilerden hangileri operatör, hangileri değerlerdir ?

```py
*
'levi'
- 
/
+
233
````

2. Aşağıdakilerden hangisi bir değişken, hangisi bir dizgidir(string) ?

```py
milkShake
'milkShake'
```
3. aşağıdaki kod çalıştıktan sonra `milkShake` değişkeninin değeri ne olur ?

```py
milkShake = 25
milkShake = milkShake + 5
milkShake = milkShake * 2
```

4. 100 geçersiz bir değişken ismi iken name neden geçerli bir değişken ismidir?

### Akış Kontrolü
Artık Python’daki temel komutları öğrendiniz ve bir programın, baştan sona bir dizi talimatı çalıştırmasıyla nasıl işlediğini biliyorsunuz. Ancak gerçek dünyadaki yazılımlar bu kadar basit değildir. Gerçek gücünü, kararlar alabilme ve tekrar eden görevleri gerçekleştirme yeteneğinden alır.

Programlar çoğu zaman sırayla değil, belli koşullara göre bazı adımları atlar, bazı adımları tekrarlar ya da alternatif yollar izler. İşte bu tür davranışlara olanak tanıyan yapılar, Python'da akış kontrol deyimleri olarak adlandırılır.


#### 🧭 Neden Akış Kontrolü?
Düşünün ki bir program, hafta sonu yapılacaklar listenizi sadece baştan sona okuyarak işleseydi. Havanın yağmurlu olup olmadığına, dışarı çıkıp çıkmayacağınıza hiç bakmadan tüm işleri sırayla yapmaya çalışırdı. Gerçek hayatta nasıl kararlar alıyorsak, programlarımızın da şartlara göre farklı yollar izlemesi gerekir.


#### Akış Diyagramları
Bu yapıları daha iyi anlayabilmek için yazılımcılar genellikle `akış diyagramları (flowchart)` kullanır. Bu diyagramlar, bir programın hangi adımları hangi koşullarda takip ettiğini görselleştirir.


>🔷 Akış diyagramlarındaki temel semboller:
 - `Başlangıç / Bitiş adımları:` Yuvarlatılmış dikdörtgenler
 - `İşlem adımları:` Düz dikdörtgenler
 - `Koşul / Karar noktaları:` Baklava dilimi (genellikle "Evet / Hayır" şeklinde iki yönlü dallanır)

![Akış Diyagramı Örneği](/images/excalidraw_picture_1.png)


#### Karşılaştırma Operatörleri
Karşılaştırma operatörleri (diğer adıyla ilişkisel operatörler), iki değeri karşılaştırmak için kullanılır ve sonuç olarak Boolean (mantıksal) bir değer üretir: `True` veya `False`.

Python'daki temel karşılaştırma operatörleri şunlardır:

| Operatör | Anlamı | Örnek |
| -------- | ------- | ------ |
| `==` | Eşit mi? | `5 == 5` |
| `!=` | Eşit değil mi? | `5 != 3` |
| `>` | Büyüktür | `5 > 3` |
| `<` | Küçüktür | `5 < 3` |
| `>=` | Büyük eşit | `5 >= 5` |
| `<=` | Küçük eşit | `5 <= 3` |

> ✅ Eşitlik ve Eşitsizlik (`==` ve `!=`)

```py
42 == 42      # True
42 == 99      # False
2 != 3        # True
```

> 🔢 Sayısal Karşılaştırmalar (`<`, `>`, `<=`, `>=`)
Bu dört operatör yalnızca sayısal değerler (tam sayılar veya ondalıklar) üzerinde doğru çalışır. Aşağıdaki örneklerde olduğu gibi karşılaştırma yapılır:
```py
10 > 5        # True
3.5 <= 4.0    # True
7 >= 7        # True
1 < 0         # False
```

#### ⚠️ Uyumlu Türlerle Çalışın
- Sayılar sayılarla, dizgiler dizgilerle karşılaştırılmalıdır.
- Karşılaştırma yaparken veri türlerinin uyumlu olması önemlidir. Aksi takdirde beklenmeyen `False` sonuçları ya da hata mesajları alabilirsiniz.

