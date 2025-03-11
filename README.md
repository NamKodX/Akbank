# 🍕 Pizza Sipariş Sistemi - Akbank Bootcamp

## 📌 Proje Hakkında
Bu proje, **Akbank Bootcamp** kapsamında geliştirilen bir **pizza sipariş arayüzüdür**. Kullanıcıların **Tkinter tabanlı bir GUI** ile pizza siparişi vermesini sağlar. Kullanıcının seçtiği pizza ve soslar, bir veritabanına kaydedilir ve sipariş süreci takip edilebilir.

Ayrıca, **Tkinter öğrenilmesi** için hazırlanmış bir notebook dosyası da proje içerisinde bulunmaktadır.

---

## 📂 Dosya Yapısı
Proje dosyaları şunlardır:

- **`pizza_ordering.ipynb`** → Ana sipariş arayüzü ve işleyiş kodları
- **`Menu.txt`** → Kullanıcının seçebileceği pizza ve sos listesi
- **`Orders_Database.csv`** → Kullanıcı siparişlerinin kaydedildiği veritabanı
- **`tkinter.ipynb`** → Tkinter öğrenimi için hazırlanmış notebook
- **Görseller (siparis.PNG, python.png)** → Uygulama arayüzüne dair görseller

---

## 🔧 Kullanılan Kütüphaneler
Projede aşağıdaki Python kütüphaneleri kullanılmıştır:

- **Tkinter** (Grafik arayüz tasarımı)
- **csv** (Siparişlerin kaydedilmesi)
- **datetime** (Sipariş zamanlarının tutulması)
- **pandas** (Veri işleme ve okuma)

---

## ⚙️ Kurulum & Çalıştırma
Projeyi çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

### 1. Gerekli Kütüphaneleri Kurun:
```bash
pip install pandas
```
(Tkinter, Python ile birlikte gelir, ayrıca yüklenmesine gerek yoktur.)

### 2. Proje Dosyalarını Çalıştırın:
```bash
python pizza_ordering.py  # Pizza sipariş arayüzünü başlatır
```

### 3. Siparişleri Görüntüleyin:
- Kullanıcı seçimlerini yaptıktan sonra sipariş **Orders_Database.csv** içine kaydedilir.
- Seçili pizzalar ve soslar ile birlikte sipariş zamanı da kaydedilir.

---

## 📊 Örnek Sipariş Akışı
Aşağıda bir sipariş sürecinin örneği verilmiştir:

1. Kullanıcı **Margarita Pizza** ve **Mantar Sosu** seçer.
2. **Sipariş Ver** butonuna tıkladığında, seçim **Orders_Database.csv** içine kaydedilir.
3. Sipariş detayları ekranda gösterilir ve kullanıcı bilgilendirilir.

---

## 📚 Tkinter Öğrenme Rehberi
Eğer **Tkinter hakkında bilgi edinmek** istiyorsanız, proje içinde yer alan **`tkinter.ipynb`** notebook dosyasını kullanabilirsiniz. Bu rehberde şunlar anlatılmaktadır:

- Tkinter ile pencere oluşturma
- Buton ve etiket kullanımı
- Kullanıcıdan giriş alma
- Arayüz düzenleme ve özelleştirme

---

## 📝 Lisans & Katkıda Bulunma
Bu proje **Akbank Bootcamp** kapsamında geliştirilmiştir ve eğitsel amaçlarla paylaşılmaktadır. Geliştirmeye katkıda bulunmak isterseniz **pull request** gönderebilir veya issue açabilirsiniz!

🚀 **Hazırlayan:** namKodX

