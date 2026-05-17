# 🎓 Udemig Education

Modern, responsive ve kullanıcı dostu bir eğitim platformu arayüzü.

Bu proje HTML5, SCSS ve JavaScript kullanılarak geliştirilmiştir. Projede modern web tasarım prensipleri uygulanmış ve responsive yapı sayesinde farklı ekran boyutlarında uyumlu bir deneyim hedeflenmiştir.

---

# 📸 Proje Önizlemesi

Udemig Education; yazılım eğitimleri, kurs kartları, hakkında bölümü, iletişim formu ve sosyal medya bağlantıları içeren modern bir landing page projesidir.

Projede bulunan ana bölümler:

- Header / Navbar
- Home Section
- Education Cards
- About Us
- Popular Courses
- Contact Form
- Footer

---

# 🚀 Kullanılan Teknolojiler

## Frontend

- HTML5
- SCSS (Sass)
- JavaScript

## Kütüphaneler

- Font Awesome

---

# 📂 Proje Klasör Yapısı

```bash
udemig-education
│
├── images
│   ├── backend-course.png
│   ├── backend-img.png
│   ├── contact-us.jpeg
│   ├── english-img.jpeg
│   ├── frontend-course-img.jpeg
│   ├── frontend-img.png
│   ├── native-img.png
│   └── udemig-logo.jpeg
│
├── js
│   └── main.js
│
├── styles
│   ├── _about.scss
│   ├── _contact.scss
│   ├── _courses.scss
│   ├── _educations.scss
│   ├── _footer.scss
│   ├── _header.scss
│   ├── _home.scss
│   ├── _mixin.scss
│   ├── _variables.scss
│   ├── style.scss
│   └── style.css
│
├── index.html
└── README.md
```

---

# 🎨 Proje Özellikleri

## ✅ Responsive Tasarım

Proje;

- Desktop
- Laptop
- Tablet
- Mobile

cihazlarla uyumlu olacak şekilde geliştirilmiştir.

SCSS mixin yapıları kullanılarak responsive media query sistemi oluşturulmuştur.

Örnek:

```scss
@include tablet {
  flex-direction: column;
}
```

---

## ✅ Modern Navbar Yapısı

- Fixed header yapısı
- Blur glassmorphism efekti
- Hover animasyonları
- Mobil menü sistemi

---

## ✅ SCSS Mimarisi

Projede modüler SCSS yapısı kullanılmıştır.

### Kullanılan SCSS Özellikleri

- Variables
- Mixins
- Nested Structure
- Extend
- Responsive Media Queries

Örnek:

```scss
@extend .flexBox;
```

---

## ✅ Flexbox Layout Sistemi

Sayfa yerleşimlerinde Flexbox kullanılmıştır.

Örnek kullanım:

```scss
.row {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

---

## ✅ Eğitim ve Kurs Kartları

Projede kullanıcıya kursları tanıtmak için kart yapıları kullanılmıştır.

İçerikler:

- Frontend Course
- Backend Course
- React Native Course
- English Course

---

## ✅ Contact Form

Kullanıcıların mesaj gönderebilmesi için iletişim formu tasarlanmıştır.

Form alanları:

- Name
- Surname
- Message

---

# ⚙️ Kurulum

Projeyi bilgisayarınıza klonlayın:

```bash
git clone <repo-link>
```

Proje klasörüne girin:

```bash
cd udemig-education
```

Daha sonra `index.html` dosyasını tarayıcıda çalıştırın.

---

# ▶️ SCSS Derleme

Eğer Sass kullanıyorsanız aşağıdaki komut ile SCSS dosyalarını CSS'e çevirebilirsiniz:

```bash
sass styles/style.scss styles/style.css --watch
```

---

# 📱 Responsive Breakpoints

Projede responsive yapı için mixin sistemi kullanılmıştır.

Örnek breakpoint yapıları:

```scss
@mixin tablet {
  @media (max-width: 768px) {
    @content;
  }
}
```

---

# 🧠 Öğrenilen Konular

Bu proje sayesinde aşağıdaki konular pratiğe dökülmüştür:

- Semantic HTML
- Responsive Web Design
- SCSS Modüler Yapısı
- Flexbox
- Position Kullanımı
- Fixed Header
- Mavigation
- Hover Animasyonları
- Glassmorphism Tasarım
- Form Yapıları

---

# 🔥 Geliştirilebilecek Özellikler

Projeye ileride eklenebilecek özellikler:

- Dark Mode
- Backend Entegrasyonu
- Gerçek Form İşlemleri
- Authentication Sistemi
- API Kullanımı
- Kurs Detay Sayfaları
- Slider Sistemi
- Animasyon Kütüphaneleri
- Çoklu Dil Desteği

---

# 📌 Notlar

- Proje eğitim amaçlı geliştirilmiştir.
- Responsive yapı için SCSS mixin sistemi kullanılmıştır.
- Font Awesome ikonları CDN üzerinden projeye dahil edilmiştir.

---

# 👨‍💻 Developer

Developed by Udemig Education Project and Mert Kocaturk.

---

# Ekran Görüntüsü

![](udemig-education.gif)
