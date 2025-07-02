# Automate Python Practice 🐍 | Python Pratik Otomasyonu 🐍

<div align="center">

## 🌍 Language Selection | Dil Seçimi

[![🇹🇷 Türkçe](https://img.shields.io/badge/🇹🇷-Türkçe-red?style=for-the-badge)](#turkish-version)
[![🇺🇸 English](https://img.shields.io/badge/🇺🇸-English-blue?style=for-the-badge)](#english-version)

</div>

---

<div id="turkish-version"></div>

# 🇹🇷 Türkçe Versiyon

[![linkedin](https://img.shields.io/badge/LinkedIn-python--docs--tr-0A66C2?style=for-the-badge&logo=LinkedIn)](https://www.linkedin.com/in/veliulugut/) 
[![gmail](https://img.shields.io/badge/GMail-python--docs--tr-EA4335?style=for-the-badge&logo=Gmail)](mailto:veliulugut1@gmail.com)


![Profil](/images/profil.gif)


> **Yazar Notu:**
>
> Bu döküman 19.05.2025 tarihinde [Python İle Sıkıcı İşleri Anında Bitir](https://www.buzdagikitabevi.com/python-ile-sikici-isleri-aninda-bitir-yeni-baslayanlar-icin-uygulamali-programlama)  ve  [YazBel](https://python-istihza.yazbel.com/index.html) kaynaklarından esinlenerek oluşturulmuştur.

> Bu proje, Python programlama dilini öğrenmek isteyenler için hem öğretici hem de uygulamalı bir kaynak olarak hazırlanmıştır. İçeriğinde, Python'un temel kavramları adım adım ele alan açıklamalar ve her konuyu pekiştirmeye yönelik uygulamalı alıştırmalar yer almaktadır.
> Yazım yanlışı veya kodlarda hata görmeniz halinde lütfen bildirin.

### 📋 İçindekiler

- [🚀 Giriş](#giris)
- [🎯 Python ile Programlamanın Temelleri](#python-temelleri)
  - [➕ Python ile Operatörler](#operatorler)
  - [📊 Veri Tipleri](#veri-tipleri)
  - [🏷️ Değişkenler](#degiskenler)
  - [🖨️ print() Fonksiyonu](#print-fonksiyonu)
  - [⌨️ input() Fonksiyonu](#input-fonksiyonu)
  - [📏 len() Fonksiyonu](#len-fonksiyonu)
  - [🔄 str(), int(), float() Fonksiyonları](#str-int-float-fonksiyonlari)
  - [⚖️ Metin ve Sayı Denkliği](#metin-sayi-denkligi)
  - [📝 Alıştırma Soruları](#alistirma-sorulari)
- [🎮 Akış Kontrolü](#akis-kontrolu)
   - [🔍 Karşılaştırma Operatörleri](#karsilastirma-operatorleri)
   - [🧠 Boole Operatörleri](#boole-operatorleri)
   - [🔧 Akış Kontrolünün Elemanları](#akis-kontrolu-elemanlari)
   - [❓ İf Deyimleri](#if-deyimleri)
   - [↩️ else Deyimleri](#else-deyimleri)
    - [🔀 elif Deyimleri](#elif-deyimleri)
    - [🔄 while Döngüsü Deyimi](#while-dongusu)
    - [🛑 break Deyimleri](#break-deyimleri)
    - [⏭️ continue Deyimleri](#continue-deyimleri)
    - [🔁 for Döngüleri ve range() Fonksiyonu](#for-donguleri)
    - [📦 Modülleri İçe Aktarma](#moduller)

<a id="giris"></a>
## 🚀 Giriş

Python, tıpkı C,C++,Perl ya da Golang gibi bir programlama dilir. Bilgisayara ne yapması gerektiğini söylememizi sağlar; yani bir anlamda bilgisayarı kontrol etmenin bir yoludur.

Bu Dil, 1990'lı yılların başında Hollandalı geliştirici Guido van Rossum tarafından ortaya çıkarılmıştır. İsmi ilk bakışta bir yılandan geliyor gibi görünse de, aslında adını [Monthy Python's Flying Circus](https://en.wikipedia.org/wiki/Monty_Python%27s_Flying_Circus) adlı İngiliz komedi programından alır. Van Rossum bu programın hayranı olduğu için dilin ismini de buradan esinlenerek seçmiştir. Yine de, yıllar içinde Python dendiğinde yılan figürüyle anılması alışılmış bir durum haline gelmiştir.

Python'un öne çıkan en önemli özelliklerinden biri, öğrenme sürecinin diğer dillere kıyasla daha kolay olmasıdır. Bu yüzden, programlamaya yeni başlayanlar için oldukça uygun bir dildir. Daha önce kodlama deneyiminiz olmasa bile, Python ile başlamak oldukça iyi bir tercih olabilir.


<a id="python-temelleri"></a>
## 🎯 Python ile Programlamanın Temelleri

<a id="operatorler"></a>
### ➕ Python ile Operatörler

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


<a id="veri-tipleri"></a>
### 📊 Veri Tipleri

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

> 🔐 Python, dizgilerin nerede başladığını ve nerede bittiğini anlamak için tırnak işaretlerine güvenir.

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

> ❗ Bu hatanın nedeni, Python'un bir dizgi (str) ile bir tam sayıyı (int) doğrudan birleştiremiyor olmasıdır.

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

<a id="degiskenler"></a>
### 🏷️ Değişkenler

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

<a id="print-fonksiyonu"></a>
### 🖨️ print() Fonksiyonu
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


<a id="input-fonksiyonu"></a>
### ⌨️ input() Fonksiyonu
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

### 📏 len() Fonksiyonu
Python'da bir dizginin (string'in) uzunluğunu öğrenmek istiyorsanız, `len()`fonksiyonunu kullanabilirsiniz. Bu fonksiyon bir dizgi değeri ya da dizgi içeren bir değişken gönderildiğinde, dizginin `karakter sayısını`tam sayı (integer) olarak verir.

```py
mesaj = 'Her karanlık gecenin bir sabahı vardır.'

print(mesaj)
print(len(mesaj))

# Output:
# Her karanlık gecenin bir sabahı vardır.
# 42
```

### 🔄 str(), int(), float() Fonksiyonları
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

### ⚖️ Metin ve Sayı Denkliği
Python'da veri türleri çok önemlidir. Aynı görünüme sahip olsalar bile, farklı türdeki veriler Python tarafından farklı değerler olarak değerlendirilir. Bu durum, özellikle karşılaştırma `(==)` işlemlerinde belirgin şekilde ortaya çıkar.

| Karşılaştırma | Açıklama | Sonuç |
| -------- | ------- | ------ |
| `20 == '20'` | Sayı ile dizgi karşılaştırılamaz | `False` |
| `20 == 20.0 ` | Tam sayı ile kayan nokta aynı değeri taşıyor | `True` |
| `'20' == '20.0'` | Dizgiler aynı değil | `False` |
| `20.0 == 00.20.000`| Python, baştaki sıfırları dikkate almaz | `True` |


### 📝 Alıştırma Soruları

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

<a id="akis-kontrolu"></a>
### 🎮 Akış Kontrolü
Artık Python'daki temel komutları öğrendiniz ve bir programın, baştan sona bir dizi talimatı çalıştırmasıyla nasıl işlediğini biliyorsunuz. Ancak gerçek dünyadaki yazılımlar bu kadar basit değildir. Gerçek gücünü, kararlar alabilme ve tekrar eden görevleri gerçekleştirme yeteneğinden alır.

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


#### 🔍 Karşılaştırma Operatörleri
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

#### `==` VE  `=` Operatörleri Arasındaki Fark
Python'da `=` ve `==` operatörleri birbirinden tamamen farklı amaçlara hizmet eder, ancak görünüş olarak benzedikleri için sıkça karıştırılırlar.

- `=` operatörü bir atama operatörüdür. Sağ taraftaki değeri alır ve sol taraftaki değişkene atar.

```py
yaş = 24  # 24 değeri "yaş" değişkenine atanır
```

- `==` operatörü ise bir karşılaştırma operatörüdür. İki değerin birbirine eşit olup olmadığını kontrol eder ve sonuç olarak `True` ya da `False` döner.

```py
yaş == 24  # Eğer yaş gerçekten 24 ise, sonuç True olur
```

#### 🧠 Boole Operatörleri
Python'da `mantıksal ifadeleri` karşılaştırmak için üç temel boolean (mantıksal) operatör bulunur ve bunlar `and `, `or` ve `not` olarak adlandırılır. Bu operatörler, tıpkı karşılaştırma operatörleri gibi, bir ifadeyi değerlendirerek `True` ya da `False` sonucunu üretirler.

> `and` Operatörü (VE)

` and ` operatörü, iki boolean değeri birleştirir. Her iki değer de ` True ` olduğunda sonuç ` True ` olur. Eğer ifadelerden ` en az biri ` ` False ` ise sonuç ` False ` olur.
> Bu yüzden ` and `, iki koşulun `aynı anda sağlanması gerektiği `durumlarda kullanılır.

| A | B | A and B |
| -------- | ------- | ------ |
| True | True | True |
| True | False | False |
| False | True | False |
| False | False | False |


> `or ` Operatörü (VEYA)

` or ` operatörü de iki boolean değer alır. Bu operatörde, en az bir ifade ` True ` ise sonuç ` True ` olur. Yani sadece her iki ifade de False olduğunda sonuç ` False ` döner. or, alternatifli koşullarda oldukça kullanışlıdır.

| A | B | A or B |
| -------- | ------- | ------ |
| True | True | True |
| True | False | True |
| False | True | True |
| False | False | False |


> ❗ ` not ` Operatörü (DEĞİL)

` not ` operatörü, diğerlerinden farklı olarak tek bir boolean değeri alır. Bu nedenle tekli (unary) bir operatör olarak kabul edilir. Verilen boolean değerin tam tersini üretir: ` True ` ise ` False `, ` False ` ise ` True ` olur.


### 🔧 Akış Kontrolünün Elemanları
Python'da programın kontrol akışını yönetmek için çeşitli deyimler (örneğin ` if `,` while `,` for `) kullanılır. Bu deyimler genellikle bir koşul ile başlar ve ardından bir ` kod bloğu (clause) ` gelir. Bu yapılar sayesinde programlar, belirli durumlara göre farklı yollar izleyebilir. Ancak bu deyimlere geçmeden önce, koşul ve kod bloğu kavramlarını iyi anlamamız gerekir.


#### Koşullar (Conditions)
Daha önce öğrendiğimiz tüm boolean ifadeler (örneğin ` x > 5 `,` a == b `) aslında birer koşul olarak değerlendirilebilir. Akış kontrol deyimlerinde bu tür ifadeler, özel bir anlam kazanır ve doğrudan karar mekanizmasını belirler.

Bir koşul her zaman ` True ` ya da ` False ` olarak değerlendirilir. Akış kontrol deyimi, bu değere göre programın hangi yolu izleyeceğine karar verir. Bu nedenle, neredeyse tüm akış kontrol yapıları en az bir koşula ihtiyaç duyar.


#### Kod Blokları (Code Blocks)
Python'da, birden fazla kod satırı bir araya gelerek bir blok oluşturabilir. Bu bloklar, bir koşulun sağlandığı durumlarda çalıştırılacak olan komutları temsil eder.

Python'da blokların sınırları ` girintiler (indentation)` ile belirlenir. Diğer birçok programlama dilinde süslü parantez ` {} ` kullanılırken, Python'da kodun hizalanması oldukça kritiktir.

> Kod blokları için üç temel kural vardır:

1. Girinti arttığında yeni bir blok başlar.
Bir deyimin altına girintili şekilde yazılan tüm satırlar, o deyime ait bir bloktur.

2. Bloklar iç içe olabilir.
Bir blok içerisinde başka bir akış kontrol deyimi kullanılabilir. Bu durumda ikinci blok, birincinin içinde yer alır ve daha fazla girinti ile yazılır.

3. Girinti seviyesi azaltıldığında blok sona erer.
Girintinin sıfırlanması ya da bir üst bloğun girinti seviyesine eşitlenmesi, mevcut bloğun sonlandığı anlamına gelir.

```py
x = 10

if x > 5:
    print("x büyüktür 5")  # bu satır if bloğuna aittir
    if x > 8:
        print("x aynı zamanda 8'den de büyüktür")  # iç içe bir blok
print("Bu satır her zaman çalışır")  # if bloğu dışındadır
# Output:
# x büyüktür 5
# x aynı zamanda 8'den de büyüktür
```

<a id="if-deyimleri"></a>
### ❓ İf Deyimleri
Programlamada en sık kullanılan akış kontrol yapılarından biri `if` deyimidir . Bir `if `deyimi, belirli bir koşulun `doğru (True) `olup olmadığını kontrol eder. Eğer koşul doğruysa, bu deyimin hemen ardından gelen `girintili kod bloğu `çalıştırılır. Koşul `yanlış (False) `ise bu blok atlanır.

Basitçe söylemek gerekirse, `if `deyimi şu şekilde okunabilir:

> "Eğer bu koşul doğruysa, şu kodu çalıştır."

Python'da `if `yapısı aşağıdaki bileşenlerden oluşur :
 - `if` anahtar kelimesi
 - Değerlendirilecek bir koşul (boolean ifade)
 - Satırın sonunda iki nokta üst üste  ` : `
 - Bir alt satırdan başlayarak girintili biçimde yazılmış kod bloğu

 Örnek:
 Diyelim ki, bir kullanıcının adının  ` "Beyza" ` olup olmadığını kontrol etmek istiyorsunuz. `" name "` adında bir değişkene daha önce bir değer atanmış olsun:

```py
name = "Beyza"

if name == "Beyza":
    print("Merhaba Beyza!")
```

- `if name == "Beyza": `satırı koşulu kontrol eder.
- Bu satırın sonundaki  `: `işareti, bir kod bloğunun geleceğini belirtir.
- Koşul doğruysa, girintili şekilde yazılmış olan `print("Merhaba Beyza!") `satırı çalıştırılır.

> ❗❗ Python'da tüm akış kontrol yapılarında (if,elif,else,while,for...) iki nokta üst üste kullanılır ve bu yapıları girintili kod blokları takip eder. Girintileme Python'da sadece okunabilirlik değil, aynı zamanda sözdizilimsel bir zorunluluktur. 




![Akış Diyagramı Örneği-If Deyimi](/images/excalidraw_if.png)


### ↩️ else Deyimleri
Bir `if`deyimini, isteğe bağlı olarak bir `else` deyimi takip edebilir. `else`bloğu, yalnızca `if`koşulu `False` olduğunda çalıştırılır. Açık bir ifadeyle bu yapı:

> "Eğer şu koşul doğruysa bu kodu çalıştır, aksi takdirde bu kodu çalıştır."

şeklinde yorumlanabilir.

`else`deyimi herhangi bir koşul içermez. Sadece `if` (veya `elif`) koşulları karşılanmadığında devreye girer.

`else` Deyiminin Yapısı:
- `else`anahtar kelimesi
- Satır sonunda `:` işareti
- Sonraki satırdan başlayarak girintili bir kod bloğu

Örnek:
```py
name = 'Beyza'

if name == 'Beyza':
    print('Hello, Beyza!')
else:
    print('Hello, what is your name?')
```

Bu örnekte:
- Eğer `name == 'Beyza'` doğruysa, ilk blok çalışır.
- Aksi takdirde, `else`bloğu çalışır  ve alternatif mesaj verilir.

![Akış Diyagramı Örneği-Else Deyimi](/images/excalidraw_else.png)


### 🔀 elif Deyimleri
`if` ve `else` yapıları çoğu durumda yeterli olsa da, birden fazla olasılığı kontrol etmek gerekebilir. İşte bu noktada `elif` `(else if)` devreye girer.

`elif` deyimi, birden çok koşulu sıralı şekilde kontrol etmeyi sağlar. `Yalnızca kendisinden önceki tüm` if ve elif koşulları `False` ise çalıştırılır.

- `elif` Deyiminin Yapısı:
elif anahtar kelimesi

- Değerlendirilecek yeni bir koşul

- Satır sonunda `:` işareti

- Sonraki satırdan başlayarak girintili bir kod bloğu

Örnek:
```py
name = 'Beyza'
age = 10

if name == 'Beyza':
    print('Merhaba, Beyza!')
elif age > 12:
    print('Sen Beyza değilsin ama gençsin!')
```

Bu kodda:

- İlk koşul `(name == 'Beyza')` doğruysa, sadece o blok çalışır.

- Değilse, `elif age > 12` koşulu kontrol edilir.

- Eğer her iki koşul da False ise hiçbir satır çalıştırılmaz.

> Not: `elif` zincirinde sadece `ilk True` olan kod bloğu çalıştırılır. Diğerleri atlanır.


<a id="while-dongusu"></a>
### 🔄 while Döngüsü Deyimi
Python'da bir kod bloğunu belirli bir koşul sağlandığı sürece tekrar tekrar çalıştırmak istiyorsanız, `while` döngüsünü kullanabilirsiniz. `while` deyimi, koşul `True` olduğu sürece döngü içerisindeki kodları tekrarlar. Bu yapı, programlama dünyasında `döngü (loop)` olarak adlandırılır.

`while` Döngüsünün Yapısı:
- while anahtar kelimesi

- True ya da False olarak değerlendirilebilecek bir `koşul`

- Satır sonunda `:` (iki nokta üst üste)

- Sonraki satırdan itibaren girintili yazılmış bir `kod bloğu`

while ve if Arasındaki Fark:
Yüzeyde `while döngüsü, if deyimine` benzer görünebilir çünkü ikisi de bir koşulu değerlendirir. Ancak aralarındaki temel fark `davranış şekillerindedir`:

- `if` koşulu `bir kez` kontrol edilir. Koşul doğruysa yalnızca bir defa çalışır.

- `while` koşulu ise `her döngü başında yeniden` kontrol edilir ve koşul doğru olduğu sürece kod bloğu tekrar tekrar çalışır.

> Karşılaştırma Örnek:
`if`ile:
```py
spam = 0

if spam < 5:
    print('Merhaba, dünya!')

spam = spam + 1
```

`while` ile:
```py
spam = 0

while spam < 5:
    print('Merhaba, dünya!')
    spam = spam + 1
```

Her iki örnek de `spam` değişkeninin 5'ten küçük olup olmadığını kontrol eder. Ancak;

-  `if` yapısı yalnızca bir kez çalışır, ekrana sadece `bir defa` "Merhaba, dünya!" yazar.

-  `while` döngüsü ise `spam` değişkeni 5 olana kadar `beş kez` çalışır ve "Merhaba, dünya!" çıktısını `beş defa üretir`.

![Akış Diyagramı Örneği-While Döngüsü](/images/excalidraw_while.png)

### 🛑 break Deyimleri

Bazen bir `while` döngüsünden belirli bir koşul gerçekleştiğinde erken çıkmak isteyebiliriz. Bu durumda `break` deyimi devreye girer. `break`, döngü bloğu içinde bulunduğu noktadan itibaren `döngüyü tamamen sonlandırır` ve program akışı döngü dışındaki kodlarla devam eder.

`break` Deyiminin Yapısı:
Sadece `break` anahtar kelimesinden oluşur.

Genellikle bir `if` koşulu içinde kullanılır.

Örnek:
Aşağıdaki kod, kullanıcıdan isim girmesini isteyen ve `"isminizi"` kelimesi girildiğinde döngüyü sonlandıran bir programdır:

```py
while True:
    print('Lütfen isminizi yazınız.')
    name = input()
    if name == 'isminizi':
        break
print('Teşekkürler!')
```

Bu örnekte:

- Döngü sonsuz gibi görünse de, kullanıcı `"isminizi"` yazdığında `break` çalışır ve döngüden çıkılır.

- Döngü dışındaki `"Teşekkürler!"` mesajı yazdırılır.

![Akış Diyagramı Örneği-Break Deyimi](/images/excalidraw_break.png)

### ⏭️ continue Deyimleri
`continue` deyimi, döngü içinde bir koşul gerçekleştiğinde döngünün o anki yinelemesinin kalan kısmını atlamamızı sağlar. `continue` çalıştığında, döngü bloğunun kalan kısmı atlanır ve koşul yeniden değerlendirilerek döngü başa döner.

`continue` Deyiminin Yapısı:
- Sadece continue anahtar kelimesinden oluşur.

- Genellikle if blokları içinde kullanılır.

Örnek:
Aşağıda kullanıcıdan isim ve şifre isteyen bir sistem yer almakta. Eğer kullanıcı `"geç"` yazarak geçmek isterse, döngü o turu atlar ve başa döner:

```py
while True:
    print('Kullanıcı adınızı giriniz (çıkmak için "geç" yazınız):')
    username = input()
    if username == 'geç':
        continue
    print('Şifrenizi giriniz:')
    password = input()
    print(f'Hoşgeldiniz, {username}!')
    break
```
Bu örnekte:
- Kullanıcı `"geç"` yazarsa `continue` çalışır ve şifre sormadan tekrar kullanıcı adı istemeye geçilir.

Kullanıcı geçerli bir isim yazdığında sistem şifre sorar ve ardından döngüden çıkar.

break vs continue Karşılaştırması:

| Deyim | Ne Yapar ? |
| -------- | ------- |
| break | Döngüyü tamamen sonlandırır ve dışındaki koda geçer.
| continue |Döngü bloğunun kalan kısmını atlar, bir sonraki adıma geçer. |

<a id="for-donguleri"></a>
### 🔁 for Döngüleri ve range() Fonksiyonu
`while` döngüsü bir koşul `True` olduğu sürece çalışmaya devam eder. Ancak bazı durumlarda bir kod bloğunu belirli bir sayıda çalıştırmak isteriz. İşte bu tür durumlar için Python'da `for` döngüsü ve `range()` fonksiyonu kullanılır.

`for` Döngüsünün Yapısı
`for döngüsü`, `range()` fonksiyonuyla birlikte genellikle aşağıdaki yapıda kullanılır:

```py
for i in range(5):
    # Döngü bloğu
```

Bu yapı aşağıdaki öğeleri içerir:

- for anahtar kelimesi

- Döngüde kullanılacak bir sayaç değişkeni (örneğin i)

- in anahtar kelimesi

- range() fonksiyon çağrısı

- Satır sonunda : işareti

- Bir sonraki satırdan başlayan, girintili bir kod bloğu (döngü gövdesi)

⚠️ Not: break ve continue yalnızca for ve while döngüleri içinde kullanılabilir. Bu deyimler döngü dışında kullanılırsa Python hata verir.

## Uygulamalı Örnek: Gauss'un Hikayesi
Matematikçi Carl Friedrich Gauss çocukken sınıfta öğretmeni tarafından "0'dan 100'e kadar olan sayıları toplayın" göreviyle karşılaşır. Gauss kısa sürede bu toplamı hesaplamanın pratik bir yolunu bulur. Şimdi bu işlemi Python'da bir `for` döngüsü ile yapalım:

```py
total = 0
for num in range(101):
    total = total + num
print(total)
# Output: 5050
```
Bu kodda:
- `range(101)` ifadesi, 0'dan 100'e kadar olan tüm sayıları üretir (100 dahil).

- Her bir `num` değeri `total` değişkenine eklenir.

- Sonuçta 0 + 1 + 2 + ... + 100 toplamı hesaplanır.

- Ekrana `5050` yazdırılır.

<a id="moduller"></a>
### 📦 Modülleri İçe Aktarma
Python dilinde daha önce kullandığımız `print()`, `input()` ve `len()` gibi fonksiyonlar, `yerleşik (built-in)` fonksiyonlar olarak adlandırılır. Bu fonksiyonlar, Python tarafından varsayılan olarak sağlanır ve doğrudan kullanılabilir.

Bununla birlikte Python, sadece yerleşik fonksiyonlarla sınırlı değildir. Aynı zamanda `standart kütüphane (standard library)` adı verilen, çeşitli görevleri yerine getirmeye yönelik birçok hazır `modülle` birlikte gelir.

Her bir modül, programınıza dahil edilebilecek ve farklı görevler üstlenen fonksiyonlar içeren bir Python dosyasıdır.

## `import`Deyimi
Bir modülü içe aktarmak için şu yapıyı kullanırız:

```py
import modul_adi
```

İsteğe bağlı olarak, birden fazla modül virgül ile ayrılarak aynı anda da içe aktarılabilir:

```py
import modul1, modul2
```

Modül içindeki fonksiyonlara erişim şu şekilde sağlanır:
```py

modul_adi.fonksiyon_adi()
```

Örnek : `random`Modülü Kullanımı
```py
import random

for i in range(5):
    print(random.randint(1, 10))
# Output: 5 rastgele sayı (1-10 arası)
```

Bu örnekte:

- random.randint(1, 10) fonksiyonu, 1 ile 10 (her iki sınır dahil) arasında rastgele bir tam sayı üretir.

- Döngü bu işlemi 5 kez tekrar eder.

## `from ... import` Deyimi

```py
from random import *
```

Bu ifade, `random` modülündeki tüm fonksiyonları içe aktarır. Böylece fonksiyonları çağırırken modül adını yazmanıza gerek kalmaz:

```py
for i in range(5):
    print(randint(1, 10))
```

> ⚠️ Not: Ancak bu yöntem, hangi fonksiyonun nereden geldiğini anlamayı zorlaştırabilir. Özellikle büyük projelerde kodun okunabilirliği ve sürdürülebilirliği açısından şu kullanım önerilir:

---

<div id="english-version"></div>

# 🇺🇸 English Version

[![linkedin](https://img.shields.io/badge/LinkedIn-python--docs--en-0A66C2?style=for-the-badge&logo=LinkedIn)](https://www.linkedin.com/in/veliulugut/) 
[![gmail](https://img.shields.io/badge/GMail-python--docs--en-EA4335?style=for-the-badge&logo=Gmail)](mailto:veliulugut1@gmail.com)

![Profile](/images/profil.gif)

> **Author's Note:**
>
> This document was created on 19.05.2025, inspired by [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) and [YazBel](https://python-istihza.yazbel.com/index.html) resources.

> This project has been prepared as both an educational and practical resource for those who want to learn the Python programming language. It contains step-by-step explanations of Python's fundamental concepts and practical exercises to reinforce each topic.
> Please report any typos or errors in the code.

### 📋 Table of Contents

- [🚀 Introduction](#introduction-en)
- [🎯 Python Programming Fundamentals](#python-programming-fundamentals-en)
  - [➕ Python Operators](#python-operators-en)
  - [📊 Data Types](#data-types-en)
  - [🏷️ Variables](#variables-en)
  - [🖨️ print() Function](#print-function-en)
  - [⌨️ input() Function](#input-function-en)
  - [📏 len() Function](#len-function-en)
  - [🔄 str(), int(), float() Functions](#str-int-float-functions-en)
  - [⚖️ Text and Number Equivalence](#text-and-number-equivalence-en)
  - [📝 Practice Questions](#practice-questions-en)
- [🎮 Flow Control](#flow-control-en)
   - [🔍 Comparison Operators](#comparison-operators-en)
   - [🧠 Boolean Operators](#boolean-operators-en)
   - [🔧 Elements of Flow Control](#elements-of-flow-control-en)
   - [❓ If Statements](#if-statements-en)
   - [↩️ else Statements](#else-statements-en)
    - [🔀 elif Statements](#elif-statements-en)
    - [🔄 while Loop Statement](#while-loop-statement-en)
    - [🛑 break Statements](#break-statements-en)
    - [⏭️ continue Statements](#continue-statements-en)
    - [🔁 for Loops and range() Function](#for-loops-and-range-function-en)
    - [📦 Importing Modules](#importing-modules-en)

## 🚀 Introduction {#introduction-en}

Python is a programming language just like C, C++, Perl, or Golang. It allows us to tell the computer what to do; in other words, it's a way to control the computer.

This language was created in the early 1990s by Dutch developer Guido van Rossum. Although the name might seem to come from a snake at first glance, it actually takes its name from the British comedy show [Monty Python's Flying Circus](https://en.wikipedia.org/wiki/Monty_Python%27s_Flying_Circus). Van Rossum chose this name because he was a fan of the show. However, over the years, it has become common for Python to be associated with the snake figure.

One of Python's most prominent features is that the learning process is easier compared to other languages. Therefore, it's quite suitable for beginners in programming. Even if you have no previous coding experience, starting with Python can be a very good choice.

## 🎯 Python Programming Fundamentals {#python-programming-fundamentals-en}

### ➕ Python Operators {#python-operators-en}

In the Python programming language, there are operators used to perform mathematical operations. These operators allow us to perform operations such as addition, subtraction, multiplication, and division on numbers.

| Operator | Operation | Example | Output |
| -------- | ------- | ------ | ----- |
| ** | Exponentiation | `2 ** 3` | 8 |
| % | Modulus/remainder | `22 % 8` | 6 |  
| // | Floor division | `22 // 8` | 2 |
| / | Division | `22 / 8` | 2.75 |
| * | Multiplication | `2 * 3` | 6 |
| + | Addition | `2 + 3` | 5 |
| - | Subtraction | `2 - 3` | -1 |

The order of operations for Python math operators is similar to mathematics. First `**` and `%` operations, then `*`, `/`, `//` and `+`, `-` operations are performed. You can use parentheses to change the order of precedence.

> 💡 Whitespace (except indentation at the beginning of lines) is not important for Python.

 `>>> 2 + 3 * 6` =  20

`>>> (5-1) * (( 7 + 1 ) / ( 3 - 1 ))` = 16.0

> If you add words to numbers when performing operations with operators, you'll get an error.

`>>> 5 + File "<stdin>", line 1
SyntaxError: invalid syntax`

### 📊 Data Types {#data-types-en}

In Python, expressions allow multiple components (such as numbers and operators) to come together to produce a single value. The result of each expression is a value.

>💡 Remember: In Python, every value belongs to only one data type. Data types allow us to categorize these values.

🔢 Numeric Data Types
| Data Type | Description | Examples |
| -------- | ------- | ------ |
| int | Integers | 1, 2, 3, -4, 0 |
| float | Decimal numbers | 1.0, 2.5, -3.14, 0.0 |

- 20 -> is an int (integer) value.
- 20.0 -> is a float (decimal number) value.

> 🧪 Although 20 and 20.0 look visually similar, Python treats them as different data types.

📝 Strings
In Python, `strings` (or `str`) are used to represent text.
A string is a sequence of characters enclosed in single `(')` or double `(")` quotes:

````python
'Hello'
"I'm learning Python"
'12345'
"12345"
````
- '' -> This is an empty string. It contains no characters.
- 'Hello' -> This is a string consisting of 5 characters.

> 🔐 Python relies on quotation marks to understand where strings begin and end.

> ⚠️ Common Mistakes

If you forget one of the quotes when creating a string, Python will warn you with an error message.
```py
>>> 'Hello, World!
SyntaxError: EOL while scanning string literal
````
The reason for this error is that the string has started but hasn't been properly terminated. That is, the closing `'` mark is missing.

✅ Correct Usage
```py
>>> 'Hello, World!'
'Hello, World!'
```

# String Concatenation and Multiplication
Some operators in Python can have different meanings depending on the data type they're used with.

For example, the `+` operator:
- Performs addition for numbers.
- Performs concatenation for strings.

```py
>>> 'Veli' + 'Ulugut'
'VeliUlugut'
```

> If you use the `+` operator between a string and a number, you'll get an error.
```py
>>> 'Veli' + 20
Traceback (most recent call last):
  ...
TypeError: can only concatenate str (not "int") to str
```

> ❗ The reason for this error is that Python cannot directly concatenate a string (str) with an integer (int).

In this case, you need to convert the number to a string. You can use the `str()` function for this operation. You'll learn how this function works in later sections.
```py
>>> 'Veli' + str(20)
'Veli20'
```

# String Multiplication
If you want to repeat a string in Python, you can use the * operator. This operation multiplies the string by the number you specify.
```py
>>> 'Veli' * 3
'VeliVeliVeli'
```

The `*` operator performs multiplication when used on strings. However, when used on numbers, this operator performs multiplication.
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

> ⚠️ If you want to multiply strings with the `*` operator, the second operand must be an integer `(int)`. It cannot be used with `str` or `float` types.

### 🏷️ Variables {#variables-en}

A variable is like a name tag that can temporarily store a value in the computer's memory. If you want to use a value you obtained from an operation in your program later, you can save this value by assigning it to a variable.

### Variable Definition
Variables are names we use to access and represent data. Just like putting a label on a box, giving a name to data makes it easier for us to access that data.

> 📝 Assignment Statement
An assignment statement is used to store a value in a variable. This statement consists of 3 components:

```py
variable_name = value
```

The `=` sign here indicates the assignment operation. It assigns the value on the right to the variable name on the left. This operation is used to define a variable in Python.

```py
milkshake = 20

print(milkshake)
# Output: 20
```

### ♻️ Updating Variables
A variable is like a label that temporarily holds the value you previously stored. If you assign a new value to the same variable, the previous value is no longer kept in memory (it's deleted) and replaced by the new one.

```py
milkshake = 'Strawberry'
print(milkshake)
# Output: Strawberry

milkshake = 'vanilla milkshake'
print(milkshake)
# Output: vanilla milkshake
```
In this example, the milkshake variable first stores the expression 'Strawberry'. However, when the second assignment is made, 'vanilla milkshake' is assigned as the new value and the previous 'Strawberry' value becomes unused.
> 🧃 We can liken this to a box with a label on it. Initially, the box's label is "Strawberry", but later we remove the label and put "vanilla milkshake" in its place. Now when we want to see what the box contains, we only get the answer "vanilla milkshake".

### Variable Naming Rules and Tips
A variable's name is very important for the readability of your code. Just as labeling every box as just "stuff" during a move would be useless, using generic names like `data`, `info`, `stuff` in your code causes confusion.

For `someone else who will read your code (or future you)`, variable names should clearly indicate what data they contain.

#### ✅ Rules for Valid Variable Names
When naming variables in Python, you need to follow these 3 basic rules:

1. Variable names cannot contain spaces and must be a single piece.

2. Only letters, numbers, and underscore (_) characters can be used.

3. Cannot start with a number.

> ❗ Case Sensitivity

Python is case-sensitive for variable names.
```py
milkshake = 'Strawberry'
Milkshake = 'vanilla'
MILKSHAKE = 'chocolate'
```
The above three variables are different variables in Python.

| Style Name | Description | Example |
| -------- | ------- | ------ |
| snake_case | Underscores are used | `user_name`,`file_path` |
| camelCase | Words are combined, first word stays lowercase, others start with uppercase | `userName`, `filePath` |

PEP8 (Python's official style guide) recommends using snake_case. However, some developers—especially those with JavaScript backgrounds—prefer the camelCase style.

> 🧭 The important thing is to choose one style and stay consistent throughout the project. Remember "A style guide is a guide, not an absolute rule."

#### ✅ Valid variable names:
```py
user_age = 25
filePath = "/home/docs"
_totalAmount = 180.50
```

#### ❌ Invalid variable names:
```py
2value = 5        # Starts with a number (Invalid)
user name = "Ali" # Contains space (Invalid)
class = "Math"    # Special keyword in Python (Invalid)
```

### 🖨️ print() Function {#print-function-en}
In Python, we use the `print()` function to print text (string) or values to the screen. The main purpose of this function is to provide information to the user or visualize output.

```py
print("Isn't life too short?")

# Output: Isn't life too short?
```
> ### Printing Empty Lines

If you call the `print()` function `without any arguments`, it prints only an empty line.
```py
print("Line 1")
print()
print("Line 3")

# Output:
# Line 1

# Line 3
```

> 🎯 Note
>  - `print()` can print not only strings but also numbers and variables.
> - You can use either double quotes `(")` or single quotes `(')`. Both give the same result.

### ⌨️ input() Function {#input-function-en}
If we want to get data from the user in Python, the `input()` function is exactly what we need. When this function is executed, the program stops and waits for the user to type text from the keyboard and press the `Enter` key.

```py
userName = input("Enter your name: ")

# Output: Enter your name: Levi

print("Hello, " + userName)

# Output: Hello, Levi
```

> ⚠️ Note
> - The `input()` function always takes input as a string.
> - If you're expecting numeric data, you can process the input with converters like `int()` or `float()`. (We'll see this topic in later sections.)

### 📏 len() Function {#len-function-en}
If you want to learn the length of a string in Python, you can use the `len()` function. When this function is given a string value or a variable containing a string, it returns the `number of characters` in the string as an integer.

```py
message = 'Every dark night has a morning.'

print(message)
print(len(message))

# Output:
# Every dark night has a morning.
# 31
```

### 🔄 str(), int(), float() Functions {#str-int-float-functions-en}
Converting between different data types in Python is quite common. Especially inputs received from users with `input()` are always of string type. Therefore, sometimes it's necessary to convert strings to numbers or numbers to strings. The `str()`, `int()`, and `float()` functions are used for these conversions.

> #### str() Function - Converting Numbers to Strings
```py
print("I am " + str(24) + " years old.")
# Screen output: I am 24 years old.
```

> #### int() Function - Converting Strings to Integers
```py
age = input("Enter your age: ")
print(int(age) + 1)  # Increases the user's age by 1
# Screen output: 25
```

> #### float() Function - Converting Strings to Decimal Numbers
```py
numericalValue = "99.99"
print(float(numericalValue) + 0.01)  # Outputs 100.0
# Screen output: 100.0
```

#### Summary
| Function | Purpose | Example | Result |
| -------- | ------- | ------ | ----- |
| str() | Converts numbers to strings | str(24) | '24' |
| int() | Converts strings to integers | int('24') | 24 |
| float() | Converts strings to decimal numbers | float('24.5') | 24.5 |

### ⚖️ Text and Number Equivalence {#text-and-number-equivalence-en}
Data types are very important in Python. Even if they have the same appearance, data of different types are considered different values by Python. This situation becomes particularly evident in comparison `(==)` operations.

| Comparison | Description | Result |
| -------- | ------- | ------ |
| `20 == '20'` | Number cannot be compared with string | `False` |
| `20 == 20.0 ` | Integer and float carry the same value | `True` |
| `'20' == '20.0'` | Strings are not the same | `False` |
| `20.0 == 00.20.000`| Python ignores leading zeros | `True` |

### 📝 Practice Questions {#practice-questions-en}

1. Which of the following are operators and which are values?

```py
*
'levi'
- 
/
+
233
````

2. Which of the following is a variable and which is a string?

```py
milkShake
'milkShake'
```
3. What will be the value of the `milkShake` variable after the following code runs?

```py
milkShake = 25
milkShake = milkShake + 5
milkShake = milkShake * 2
```

4. Why is 100 an invalid variable name while name is a valid variable name?

### 🎮 Flow Control {#flow-control-en}
Now you've learned the basic commands in Python and know how a program works by executing a series of instructions from start to finish. However, real-world software is not that simple. It gets its real power from the ability to make decisions and perform repetitive tasks.

Programs often don't run in order, but skip some steps, repeat some steps, or follow alternative paths according to certain conditions. The structures that enable such behaviors are called flow control statements in Python.

#### 🧭 Why Flow Control?
Imagine if a program processed your weekend to-do list by just reading it from start to finish. It would try to do all the tasks in order without looking at whether it's raining or whether you're going out. Just as we make decisions in real life, our programs need to follow different paths according to conditions.

#### Flow Diagrams
To better understand these structures, software developers often use `flowcharts`. These diagrams visualize which steps a program follows under which conditions.

>🔷 Basic symbols in flowcharts:
 - `Start / End steps:` Rounded rectangles
 - `Process steps:` Straight rectangles
 - `Condition / Decision points:` Diamond shape (usually branches in two directions as "Yes / No")

![Flow Diagram Example](/images/excalidraw_picture_1.png)

#### 🔍 Comparison Operators {#comparison-operators-en}
Comparison operators (also called relational operators) are used to compare two values and produce a Boolean (logical) value as a result: `True` or `False`.

The basic comparison operators in Python are:

| Operator | Meaning | Example |
| -------- | ------- | ------ |
| `==` | Equal to? | `5 == 5` |
| `!=` | Not equal to? | `5 != 3` |
| `>` | Greater than | `5 > 3` |
| `<` | Less than | `5 < 3` |
| `>=` | Greater than or equal | `5 >= 5` |
| `<=` | Less than or equal | `5 <= 3` |

> ✅ Equality and Inequality (`==` and `!=`)

```py
42 == 42      # True
42 == 99      # False
2 != 3        # True
```

> 🔢 Numerical Comparisons (`<`, `>`, `<=`, `>=`)
These four operators work correctly only on numerical values (integers or decimals). Comparison is made as in the following examples:
```py
10 > 5        # True
3.5 <= 4.0    # True
7 >= 7        # True
1 < 0         # False
```

#### ⚠️ Work with Compatible Types
- Numbers should be compared with numbers, strings with strings.
- It's important that data types are compatible when making comparisons. Otherwise, you may get unexpected `False` results or error messages.

#### Difference Between `==` AND `=` Operators
In Python, the `=` and `==` operators serve completely different purposes, but they are often confused because they look similar.

- The `=` operator is an assignment operator. It takes the value on the right and assigns it to the variable on the left.

```py
age = 24  # The value 24 is assigned to the "age" variable
```

- The `==` operator is a comparison operator. It checks whether two values are equal and returns `True` or `False` as a result.

```py
age == 24  # If age is really 24, the result is True
```

#### 🧠 Boolean Operators {#boolean-operators-en}
In Python, there are three basic boolean (logical) operators for comparing `logical expressions`, and these are called `and`, `or`, and `not`. These operators, just like comparison operators, evaluate an expression and produce a `True` or `False` result.

> `and` Operator (AND)

The `and` operator combines two boolean values. The result is `True` when both values are `True`. If `at least one` of the expressions is `False`, the result is `False`.
> Therefore, `and` is used in situations where `two conditions must be met simultaneously`.

| A | B | A and B |
| -------- | ------- | ------ |
| True | True | True |
| True | False | False |
| False | True | False |
| False | False | False |

> `or` Operator (OR)

The `or` operator also takes two boolean values. In this operator, if at least one expression is `True`, the result is `True`. So the result returns `False` only when both expressions are False. or is quite useful in alternative conditions.

| A | B | A or B |
| -------- | ------- | ------ |
| True | True | True |
| True | False | True |
| False | True | True |
| False | False | False |

> ❗ `not` Operator (NOT)

The `not` operator, unlike the others, takes only one boolean value. Therefore, it is considered a unary operator. It produces the exact opposite of the given boolean value: `True` becomes `False`, `False` becomes `True`.

| A | not A |
| -------- | ------- |
| True | False |
| False | True |

### 🔧 Elements of Flow Control {#elements-of-flow-control-en}
Various statements (such as `if`, `while`, `for`) are used in Python to manage the control flow of the program. These statements usually start with a condition followed by a `code block (clause)`. Thanks to these structures, programs can follow different paths according to specific situations. However, before moving on to these statements, we need to understand the concepts of condition and code block well.

#### Conditions
All the boolean expressions we learned before (such as `x > 5`, `a == b`) can actually be evaluated as conditions. In flow control statements, such expressions gain special meaning and directly determine the decision mechanism.

A condition is always evaluated as `True` or `False`. The flow control statement decides which path the program will follow based on this value. Therefore, almost all flow control structures need at least one condition.

#### Code Blocks
In Python, multiple lines of code can come together to form a block. These blocks represent the commands that will be executed when a condition is met.

In Python, the boundaries of blocks are determined by `indentation`. While curly braces `{}` are used in many other programming languages, code alignment is quite critical in Python.

> There are three basic rules for code blocks:

1. A new block starts when indentation increases.
All lines written indented under a statement are a block belonging to that statement.

2. Blocks can be nested.
Another flow control statement can be used within a block. In this case, the second block is located inside the first and is written with more indentation.

3. The block ends when the indentation level is reduced.
Resetting the indentation or equalizing it to the indentation level of an upper block means that the current block is terminated.

```py
x = 10

if x > 5:
    print("x is greater than 5")  # this line belongs to the if block
    if x > 8:
        print("x is also greater than 8")  # nested block
print("This line always runs")  # outside the if block
# Output:
# x is greater than 5
# x is also greater than 8
# This line always runs
```

### ❓ If Statements {#if-statements-en}
One of the most frequently used flow control structures in programming is the `if` statement. An `if` statement checks whether a specific condition is `true (True)`. If the condition is true, the `indented code block` that immediately follows this statement is executed. If the condition is `false (False)`, this block is skipped.

Simply put, the `if` statement can be read as follows:

> "If this condition is true, run this code."

The `if` structure in Python consists of the following components:
 - `if` keyword
 - A condition to be evaluated (boolean expression)
 - Colon `:` at the end of the line
 - Indented code block starting from the next line

 Example:
 Let's say you want to check if a user's name is `"Beyza"`. Assume that a value has been previously assigned to a variable called `"name"`:

```py
name = "Beyza"

if name == "Beyza":
    print("Hello Beyza!")
```

- The line `if name == "Beyza":` checks the condition.
- The `:` at the end of this line indicates that a code block is coming.
- If the condition is true, the indented line `print("Hello Beyza!")` is executed.

> ❗❗ In Python, all flow control structures (if, elif, else, while, for...) use colons and these structures are followed by indented code blocks. Indentation in Python is not just for readability, but also a syntactic requirement.

![Flow Diagram Example-If Statement](/images/excalidraw_if.png)

### ↩️ else Statements {#else-statements-en}
An `if` statement can optionally be followed by an `else` statement. The `else` block is executed only when the `if` condition is `False`. In clear terms, this structure:

> "If this condition is true, run this code, otherwise run this code."

can be interpreted as.

The `else` statement does not contain any condition. It only comes into play when `if` (or `elif`) conditions are not met.

Structure of the `else` Statement:
- `else` keyword
- `:` sign at the end of the line
- An indented code block starting from the next line

Example:
```py
name = 'Beyza'

if name == 'Beyza':
    print('Hello, Beyza!')
else:
    print('Hello, what is your name?')
```

In this example:
- If `name == 'Beyza'` is true, the first block runs.
- Otherwise, the `else` block runs and gives an alternative message.

![Flow Diagram Example-Else Statement](/images/excalidraw_else.png)

### 🔀 elif Statements {#elif-statements-en}
Although `if` and `else` structures are sufficient in most cases, it may be necessary to check multiple possibilities. This is where `elif` `(else if)` comes into play.

The `elif` statement allows checking multiple conditions sequentially. It is executed `only if all` if and elif conditions before it are `False`.

- Structure of the `elif` Statement:
elif keyword

- A new condition to be evaluated

- `:` sign at the end of the line

- An indented code block starting from the next line

Example:
```py
name = 'Beyza'
age = 10

if name == 'Beyza':
    print('Hello, Beyza!')
elif age > 12:
    print("You're not Beyza but you're young!")
```

In this code:

- If the first condition `(name == 'Beyza')` is true, only that block runs.

- If not, the `elif age < 12` condition is checked.

- If both conditions are False, no line is executed.

> Note: In the `elif` chain, only the `first True` code block is executed. Others are skipped.

### 🔄 while Loop Statement {#while-loop-statement-en}
If you want to run a code block repeatedly as long as a certain condition is met in Python, you can use the `while` loop. The `while` statement repeats the code inside the loop as long as the condition is `True`. This structure is called a `loop` in the programming world.

Structure of the `while` Loop:
- while keyword

- A `condition` that can be evaluated as True or False

- `:` (colon) at the end of the line

- An indented `code block` starting from the next line

Difference between while and if:
On the surface, a `while loop may seem similar to an if statement` because both evaluate a condition. However, the fundamental difference between them is `their behavior`:

- `if` condition is checked `once`. If the condition is true, it runs only once.

- `while` condition is `rechecked at the beginning of each loop` and the code block runs repeatedly as long as the condition is true.

> Comparison Example:
With `if`:
```py
spam = 0

if spam < 5:
    print('Hello, world!')

spam = spam + 1
```

With `while`:
```py
spam = 0

while spam < 5:
    print('Hello, world!')
    spam = spam + 1
```

Both examples check whether the `spam` variable is less than 5. However;

-  The `if` structure runs only once, printing "Hello, world!" to the screen `only once`.

-  The `while` loop runs `five times` until the `spam` variable becomes 5 and produces the "Hello, world!" output `five times`.

![Flow Diagram Example-While Loop](/images/excalidraw_while.png)

### 🛑 break Statements {#break-statements-en}

Sometimes we want to exit a `while` loop early when a certain condition is met. In this case, the `break` statement comes into play. `break` `completely terminates the loop` from the point where it is located in the loop block and the program flow continues with the code outside the loop.

Structure of the `break` Statement:
Consists only of the `break` keyword.

Usually used within an `if` condition.

Example:
The following code asks the user to enter a name and terminates the loop when the word `"yourname"` is entered:

```py
while True:
    print('Please enter your name.')
    name = input()
    if name == 'yourname':
        break
print('Thank you!')
```

In this example:

- Although the loop seems infinite, when the user types `"yourname"`, `break` runs and exits the loop.

- The `"Thank you!"` message outside the loop is printed.

![Flow Diagram Example-Break Statement](/images/excalidraw_break.png)

### ⏭️ continue Statements {#continue-statements-en}
The `continue` statement allows us to skip the remaining part of the current iteration of the loop when a condition is met within the loop. When `continue` runs, the remaining part of the loop block is skipped and the loop returns to the beginning by re-evaluating the condition.

Structure of the `continue` Statement:
- Consists only of the continue keyword.

- Usually used within if blocks.

Example:
Below is a system that asks the user for a name and password. If the user wants to skip by typing `"skip"`, the loop skips that round and returns to the beginning:

```py
while True:
    print('Enter your username (type "skip" to skip):')
    username = input()
    if username == 'skip':
        continue
    print('Enter your password:')
    password = input()
    print(f'Welcome, {username}!')
    break
```
In this example:
- If the user types `"skip"`, `continue` runs and asks for the username again without asking for a password.

When the user types a valid name, the system asks for a password and then exits the loop.

break vs continue Comparison:

| Statement | What Does It Do? |
| -------- | ------- |
| break | Completely terminates the loop and moves to the code outside it.
| continue | Skips the remaining part of the loop block, moves to the next step. |

### 🔁 for Loops and range() Function {#for-loops-and-range-function-en}
A `while` loop continues to run as long as a condition is `True`. However, sometimes we want to run a code block a certain number of times. For such situations, the `for` loop and `range()` function are used in Python.

Structure of the `for` Loop
The `for loop` is usually used with the `range()` function in the following structure:

```py
for i in range(5):
    # Loop block
```

This structure includes the following elements:

- for keyword

- A counter variable to be used in the loop (for example i)

- in keyword

- range() function call

- : sign at the end of the line

- An indented code block starting from the next line (loop body)

⚠️ Note: break and continue can only be used within for and while loops. If these statements are used outside the loop, Python gives an error.

## Practical Example: Gauss's Story
When mathematician Carl Friedrich Gauss was a child, he was faced with the task "add the numbers from 0 to 100" by his teacher in class. Gauss quickly finds a practical way to calculate this sum. Now let's do this operation in Python with a `for` loop:

```py
total = 0
for num in range(101):
    total = total + num
print(total)
# Output: 5050
```
In this code:
- The expression `range(101)` generates all numbers from 0 to 100 (including 100).

- Each `num` value is added to the `total` variable.

- As a result, the sum 0 + 1 + 2 + ... + 100 is calculated.

- `5050` is printed to the screen.

### 📦 Importing Modules {#importing-modules-en}
Functions like `print()`, `input()` and `len()` that we used before in Python are called `built-in` functions. These functions are provided by Python by default and can be used directly.

However, Python is not limited to just built-in functions. It also comes with many ready-made `modules` for various tasks, called the `standard library`.

Each module is a Python file that contains functions that can be included in your program and perform different tasks.

## `import` Statement
To import a module, we use this structure:

```py
import module_name
```

Optionally, multiple modules can be imported at the same time, separated by commas:

```py
import module1, module2
```

Access to functions within the module is provided as follows:
```py
module_name.function_name()
```

Example: Using the `random` Module
```py
import random

for i in range(5):
    print(random.randint(1, 10))
# Output: 5 random numbers (between 1-10)
```

In this example:

- The random.randint(1, 10) function generates a random integer between 1 and 10 (both limits included).

- The loop repeats this operation 5 times.

## `from ... import` Statement

```py
from random import *
```

This expression imports all functions from the `random` module. This way, you don't need to write the module name when calling functions:

```py
for i in range(5):
    print(randint(1, 10))
```

> ⚠️ Note: However, this method can make it difficult to understand which function comes from where. Especially in large projects, the following usage is recommended for code readability and maintainability:

---

### 🔗 Quick Navigation

- [🇹🇷 Go to Turkish Version](#turkish-version)
- [🇺🇸 Go to English Version](#english-version)

---

**Made with ❤️ for Python learners | Python öğrenenler için ❤️ ile yapıldı**