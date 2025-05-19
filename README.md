# Automate Python Practice tr-en
[![linkedin](https://img.shields.io/badge/LinkedIn-python--docs--tr-0A66C2?style=for-the-badge&logo=LinkedIn)](https://www.linkedin.com/in/veliulugut/) 
[![gmail](https://img.shields.io/badge/GMail-python--docs--tr-EA4335?style=for-the-badge&logo=Gmail)](mailto:veliulugut1@gmail.com)

> **Yazar Notu:**
>
> Bu döküman 19.05.2025 tarihinde [Python İle Sıkıcı İşleri Anında Bitir](https://www.buzdagikitabevi.com/python-ile-sikici-isleri-aninda-bitir-yeni-baslayanlar-icin-uygulamali-programlama)  ve  [YazBel](https://python-istihza.yazbel.com/index.html) kaynaklarından esinlenerek oluşturulmuştur.

> Bu proje, Python programlama dilini öğrenmek isteyenler için hem öğretici hem de uygulamalı bir kaynak olarak hazırlanmıştır. İçeriğinde, Python'un temel kavramları adım adım ele alan açıklamalar ve her konuyu pekiştirmeye yönelik uygulamalı alıştırmalar yer almaktadır.
> Yazım yanlışı veya kodlarda hata görmeniz halinde lütfen bildirin.

### İçindekiler

- [Giriş](#giris%E2%80%93)
- [Python ile Programlamanın Temelleri](#python-ile-programlamanin-temelleri)
  - [Operatörler](#python-ile-operat%C3%B6rler)
  - [Veri Tipleri](#veri-tipleri)



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


