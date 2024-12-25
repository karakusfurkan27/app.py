### README: Kod Açıklaması ve Kullanımı

Bu README dosyası, verilen Python kodunun açıklamasını ve işlevlerini detaylı bir şekilde anlatmak için hazırlanmıştır. Kod, temel veri türlerini ve Python programlamada kullanılan bazı özellikleri tanıtan bir örnektir.

---

### **Kodun İşlevi**
Kod, Python dilinde farklı veri türlerini ve bazı kaçış dizilerini (escape sequence) kullanarak veri tanımlama, yazdırma ve türlerini kontrol etme işlemlerini göstermektedir.

---

### **Kodun Açıklaması**

#### **1. Kullanıcıdan Giriş Alma**
```python
name = input('What is your name?')
print('Hi', name)
```
- Kullanıcıdan adını alır ve ekrana selam mesajı yazdırır.

---

#### **2. Büyük Tamsayı Değeri (Integer)**
```python
sampleInteger = 123123123123123123123123123123123123
print(sampleInteger)
print(type(sampleInteger))
```
- Çok büyük bir tamsayı (`sampleInteger`) tanımlanır.
- Değer ve veri tipi ekrana yazdırılır. Python'da tamsayıların boyut sınırlaması olmadığını gösterir.

---

#### **3. İkili (Binary) Sayılar**
```python
sampleBinary = 0B1010
sampleBinary = 0b1010
print(sampleBinary)
print(type(sampleBinary))
```
- İkili sayı formatında bir değer tanımlanır (`0b` ya da `0B` ile başlar).
- Değer ve tipi ekrana yazdırılır.

---

#### **4. Sekizlik (Octal) Sayılar**
```python
sampleOctave = 0o543
print(sampleOctave)
print(type(sampleOctave))
```
- Sekizlik tabanda bir sayı tanımlanır (`0o` ile başlar).
- Değer ve veri tipi ekrana yazdırılır.

---

#### **5. Onaltılık (Hexadecimal) Sayılar**
```python
sampleHexadecimal = 0X2F3
print(sampleHexadecimal)
print(type(sampleHexadecimal))
```
- Onaltılık sayı formatında bir değer tanımlanır (`0x` ya da `0X` ile başlar).
- Değer ve veri tipi ekrana yazdırılır.

---

#### **6. Ondalık Sayılar (Float)**
```python
sampleFloat = 4.2
print(sampleFloat)
print(type(sampleFloat))
```
- Ondalık bir sayı tanımlanır ve tipi yazdırılır.

---

#### **7. Bilimsel Gösterim (Scientific Notation)**
```python
sampleBigFloat = 1.8E23
print(sampleBigFloat)
print(type(sampleBigFloat))

sampleSmallFloat = 2.3E-54
print(sampleSmallFloat)
print(type(sampleSmallFloat))
```
- Büyük (`E23`) ve küçük (`E-54`) ondalık sayılar bilimsel gösterimle tanımlanır.
- Değerler ve türleri ekrana yazdırılır.

---

#### **8. Kaçış Dizileri (Escape Sequences) ve Unicode Karakterler**
```python
sampleString = "This is \"stupid\" exsample for printing"
sampleString += '\ \x61\', \'\xAE\' and \'\uA7B5\' characters'
sampleString += "\t becasue it is for presenting escape sequence"
print(sampleString)
```
- Bir metin, kaçış dizileriyle yazdırılır.
  - `\"`: Çift tırnak ekler.
  - `\x61`: ASCII karakteri 'a' (hexadecimal kod).
  - `\xAE`: Tescilli işaret sembolü (®).
  - `\uA7B5`: Unicode karakter.
  - `\t`: Tab boşluğu ekler.
- Sonuç ekrana yazdırılır.

---

#### **9. Yorum Satırı**
```python
00000000000000000000000000000000000000000000000000000
# 53 tane 0 olucak
```
- 53 sıfırlı bir dizi içeren yorum satırı bulunmaktadır.

---

### **Kullanım Talimatları**
1. Python 3.6 veya üstü bir sürümün yüklü olduğundan emin olun.
2. Kodu bir Python IDE'sine veya metin düzenleyiciye yapıştırın.
3. Çalıştırarak, çıktıları gözlemleyin.

---

### **Notlar**
- Kod, Python'da veri türlerinin kullanımına yönelik öğretici bir örnektir.
- Unicode ve kaçış dizileri, metinlerin yazdırılmasında özelleştirme sağlar. 
- Tamsayı ve ondalık sayı formatları, veri türleri arasındaki esnekliği gösterir.
