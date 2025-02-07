# 🏢 Shoe Store

Demo: https://shoestoreprojectdemo.netlify.app

🚀 **Modern ve şık bir e-ticaret platformu!** Kullanıcıların farklı marka ve modellerde sneaker satın alabileceği dinamik bir mağaza.

---

## 📌 Proje Hakkında

Bu proje, **HTML, CSS ve JavaScript** kullanılarak geliştirilen, tamamen **frontend odaklı** bir online ayakkabı mağazasıdır. Kullanıcılar ürünleri seçebilir, renk ve beden değiştirebilir ve bir ödeme ekranına yönlendirilir. Ancak şu an için gerçek bir ödeme altyapısı bulunmamaktadır.

---

## 📂 Proje Yapısı

```
Shoe-Store/
│── img/               # Ürün ve ikon görselleri
│── index.html         # Ana HTML dosyası
│── style.css          # CSS stilleri
│── app.js             # JavaScript dinamik işlemler
│── README.md          # Proje dokümentasyonu
```

---

## ⚙️ Kullanılan Teknolojiler ve Açıklamaları

### 🏷 1. HTML5 - Sayfa Yapısı

Bu projede **HTML5** kullanılarak modern bir e-ticaret sitesi oluşturulmuştur.

📌 **Kullanılan Yapılar:**
- **Navbar ve Menü:** `<nav>` etiketi ile oluşturuldu.
- **Ürün Listesi & Slider:** `<div>` ile kategoriler ve ürün detayları ayrıldı.
- **Form Alanları:** `<input>`, `<label>` gibi elementlerle ödeme ekranı oluşturuldu.
- **Footer:** `<footer>` etiketi ile oluşturuldu ve left-rigt olarak sınıflandırıldı.

---

### 🎨 2. CSS3 - Responsive ve Modern Tasarım

Tasarımın estetik ve kullanıcı dostu olması için **CSS3** kullanılmıştır.

📌 **Öne Çıkan CSS Özellikleri:**
- **Flexbox & Grid:** Sayfa düzenini oluşturmak için kullanıldı.
- **Animasyonlar & Geçiş Efektleri:** Kullanıcı deneyimini artırmak için `hover` ve `transition` efektleri.
- **Mobil Uyumluluk:** Küçük ekranlar için `media queries`.

---

### ⚡ 3. JavaScript (Vanilla JS) - Dinamik İşlevsellik

Projede **saf Vanilla JavaScript** kullanılmıştır.

📌 **Öne Çıkan Özellikler:**
- **Dinamik Ürün Değişimi:** Kullanıcı menüden bir kategori seçtiğinde ürün değişir.
- **Ödeme Ekranı Açma/Kapatma:** Kullanıcı "BUY NOW" butonuna bastığında ödeme ekranı açılır.
- **Renk & Beden Seçimi:** Kullanıcı bir renk seçtiğinde, ürün görseli değişir.

---

### 💰 4. Ödeme Altyapısı

Bu projede **gerçek bir ödeme altyapısı** bulunmamaktadır.

📌 **Simüle Edilen İşlemler:**
- Kullanıcı ödeme bilgilerini girer.
- "X" butonuna basınca JavaScript ile form kapanır.

📌 **Geliştirme İçin Öneriler:**
- **Stripe API** veya **PayPal API** gibi bir ödeme entegrasyonu eklenebilir.
- **Backend (Node.js, Python, .NET)** ile ödeme işlemleri gerçek veritabanına bağlanabilir.

🚀 **İyi alışverişler!** 🎉
