# Python Temel Kavramlar 🐍

Bu repository, Python programlama dilinin temel kavramlarını öğrenmek için hazırlanmış pratik örnekleri ve alıştırmaları içermektedir.

## 📚 İçerik

### Bölüm 1: Veri Tipleri
- **Kullanıcı Girişi ve Veri Tiplerini Dönüştürme**
  - `input()` fonksiyonu kullanımı
  - `int()`, `float()`, `str()` tip dönüşümleri
  - F-string ile formatlı çıktı

- **Sayısal İşlemler**
  - Integer ve float veri tipleri
  - Aritmetik hesaplamalar
  - Ortalama hesaplama

- **String İşlemleri**
  - String indeksleme `[0]`, `[-1]`
  - `len()` fonksiyonu
  - String ters çevirme `[::-1]`

### Bölüm 2: Operatörler
- **Aritmetik Operatörler**
  - Toplama (+), Çıkarma (-), Çarpma (*)
  - Bölme (/), Mod (%)

- **Karşılaştırma Operatörleri**
  - Büyük/küçük karşılaştırmaları (`>`, `<`)
  - Koşullu yapılar (`if`/`else`)

- **Mantıksal Operatörler**
  - `and`, `or`, `not` operatörleri
  - Boolean değerlerle çalışma

### Bölüm 3: Mini Projeler
- **Alışveriş Sepeti Uygulaması**
  - Çoklu ürün fiyat toplama
  - Koşullu indirim hesaplama
  - Pratik uygulama örneği

- **Yaş Hesaplayıcı ve Kategori Belirleyici**
  - Doğum yılından yaş hesaplama
  - Çoklu koşul yapıları (`elif`)
  - Yaş gruplarına göre kategorilendirme

## 🚀 Nasıl Kullanılır

1. Repository'yi klonlayın:
```bash
git clone https://github.com/Software-Guardians/Python-Basic-Template-1
```

2. Jupyter Notebook'u çalıştırın:
```bash
jupyter notebook
```

3. `python-basics.ipynb` dosyasını açın ve hücreleri çalıştırın.

## 📋 Gereksinimler

- Python 3.6+
- Jupyter Notebook

## 🎯 Öğrenme Hedefleri

Bu çalışmaları tamamladıktan sonra şunları öğrenmiş olacaksınız:

- ✅ Python'da temel veri tiplerini kullanma
- ✅ Kullanıcıdan input alma ve işleme
- ✅ Aritmetik ve mantıksal işlemler yapma
- ✅ String manipülasyon teknikleri
- ✅ Koşullu yapıları kullanma
- ✅ Basit problem çözme becerileri

## 💡 Örnekler

### Veri Tipi Örneği
```python
name = input("İsminizi giriniz:\n")
age = int(input("Yaşınızı giriniz:\n"))
height = float(input("Boyunuzu giriniz:\n"))
print(f"Merhaba, {name}. Yaşınız: {age}. Boyunuz: {height}")
```

### Koşullu Yapı Örneği
```python
age = int(input("Yaşınızı giriniz:\n"))
if age > 18:
    print("Ehliyet alabilirsiniz")
else:
    print("Ehliyet alamazsınız")
```

### String İşlemi Örneği
```python
my_string = "Merhaba Dünya"
print(f"İlk karakter: {my_string[0]}")
print(f"Son karakter: {my_string[-1]}")
print(f"Uzunluk: {len(my_string)}")
print(f"Tersi: {my_string[::-1]}")
```

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Commit yapın (`git commit -am 'Yeni özellik eklendi'`)
4. Branch'inizi push yapın (`git push origin feature/yeni-ozellik`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakınız.

## 🔗 Bağlantılar

- [Python Resmi Dokümantasyonu](https://docs.python.org/3/)
- [Jupyter Notebook Dokümantasyonu](https://jupyter-notebook.readthedocs.io/)

---

⭐ Bu repository'yi faydalı bulduysanız star vermeyi unutmayın!

**Yazar:** [Emrullah Enis Çetinkaya](https://github.com/emrullah-enis-ctnky)  
**İletişim:** eniscetinkaya951@gmail.com
