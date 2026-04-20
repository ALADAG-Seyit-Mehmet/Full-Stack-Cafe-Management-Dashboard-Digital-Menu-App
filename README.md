<div align="center">
  <h1>☕ Kafe QR Menu / Kafe QR Menü</h1>
  <p>🇬🇧 Modern, sleek, and fast digital QR menu and management system.</p>
  <p>🇹🇷 Modern, şık ve hızlı bir dijital QR menü ve yönetim sistemi.</p>
  
  <p>
    <a href="#-english">English</a> • <a href="#-türkçe">Türkçe</a>
  </p>
</div>

<br />

### 📸 Screenshots & Previews

<div align="center">
  <img src="qr_menu_mobile_ui_1776701184297.png" alt="Mobile QR Menu Interface" width="45%" />
  &nbsp; &nbsp; &nbsp;
  <img src="qr_menu_admin_dashboard_1776701198931.png" alt="Admin Dashboard Database Management" width="45%" />
</div>

<br />

---

# 🇬🇧 English

## 🌟 About the Project

**Kafe QR Menu** is a digital menu application developed for cafes and restaurants, accessible by scanning QR codes placed on tables. The project provides a stunning design for customers to browse products with prices, images, and descriptions, while offering a powerful admin panel for business owners to easily manage their inventory.

Developed using modern web technologies, it features an eye-catching user experience (glassmorphism UI patterns, premium color palette) and high performance.

## ✨ Features

### 📱 Customer Interface (QR Menu)
- **Modern & Sleek Design:** Luxurious, user-friendly appearance enhanced with subtle animations.
- **Categorized Menu:** Advanced filtering by hot drinks, cold drinks, desserts, etc.
- **Visual Fallback System:** Intelligent "No Image" placeholder logic for products with missing or failed images to ensure design integrity.
- **Mobile-First Layout:** Perfect, responsive look across all phones and tablets.

### ⚙️ Admin Dashboard
- **Secure Authentication:** Admin login powered by Supabase Authentication.
- **Inventory Management:** Add, edit, update prices, or delete products and categories in real-time.
- **Media Uploads:** Seamless product image uploads leveraging Supabase Storage.

## 🛠️ Technology Stack

- **Frontend:** [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Backend & Database:** [Supabase](https://supabase.com/) (PostgreSQL & Storage & Auth)
- **Styling:** Custom (Vanilla) CSS, CSS Variables, Glassmorphism Effects, Responsive Grid
- **Icons:** [Lucide React](https://lucide.dev/)
- **Routing:** [React Router v7](https://reactrouter.com/)

## 🚀 Setup & Installation

To run this project locally, follow these steps:

### 1. Requirements
Ensure you have [Node.js](https://nodejs.org/) (v18+ recommended) installed.

### 2. Clone the Repository
```bash
git clone <repository-url>
cd kafe
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Environment Variables
Create a `.env.local` file in the root directory and add your Supabase credentials:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 5. Start the Development Server
```bash
npm run dev
```
The application will start at `http://localhost:5173`.

## 📄 License

This project was developed for testing and personal use. All rights reserved and subject to the MIT license.

<br />
<br />

---

# 🇹🇷 Türkçe

## 🌟 Proje Hakkında

**Kafe QR Menü**, kafeler ve restoranlar için geliştirilmiş, masalardaki QR kodlar okutularak erişilebilen dijital bir menü uygulamasıdır. Proje, müşterilerin ürünleri fiyat, görsel ve açıklamalarıyla şık bir tasarımla inceleyebilmesini sağlarken; işletme sahiplerinin de bu ürünleri ve kategorileri kolayca yönetebileceği bir admin paneli sunar.

Modern web teknolojileri kullanılarak geliştirilmiş olup, göz alıcı bir kullanıcı deneyimi ("glassmorphism" tarzı UI, premium renk paleti) ve yüksek performans sunar.

## ✨ Özellikler

### 📱 Müşteri Arayüzü (QR Menü)
- **Modern ve Şık Tasarım:** Kullanıcı dostu, animasyonlarla desteklenmiş lüks görünüm.
- **Kategorilere Göre Menü:** Ürünleri sıcak içecekler, soğuk içecekler, tatlılar vb. olarak filtreleme.
- **Görsel Fallback Sistemi:** Olası görsel yükleme hatalarında veya görseli olmayan ürünlerde şık "Görsel Yok" görünümü.
- **Mobil Odaklı (Mobile-First) Düzen:** Telefon ve tabletlerde mükemmel görünüm.

### ⚙️ Yönetici Paneli (Admin Dashboard)
- **Güvenli Giriş Sistemi:** Supabase Authentication tabanlı admin girişi.
- **Ürün ve Kategori Yönetimi:** Yeni ürün ekleme, düzenleme, fiyat güncelleme ve silme.
- **Görsel Yükleme:** (Supabase Storage entegrasyonuyla) ürün görsellerini hızlıca sisteme dahil etme.

## 🛠️ Kullanılan Teknolojiler

- **Frontend:** [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Derleyici (Build Tool):** [Vite](https://vitejs.dev/)
- **Backend & Veritabanı:** [Supabase](https://supabase.com/) (PostgreSQL & Storage & Auth)
- **Stil & Tasarım:** Özel (Vanilla) CSS, CSS Variables, Glassmorphism Efektleri, Responsive Grid Layout
- **İkonlar:** [Lucide React](https://lucide.dev/)
- **Yönlendirme (Routing):** [React Router v7](https://reactrouter.com/)

## 🚀 Kurulum ve Çalıştırma

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### 1. Gereksinimler
Sisteminizde [Node.js](https://nodejs.org/) (önerilen v18+) yüklü olmalıdır.

### 2. Projeyi Klonlayın
```bash
git clone <proje-repo-adresi>
cd kafe
```

### 3. Bağımlılıkları Yükleyin
```bash
npm install
```

### 4. Çevresel Değişkenleri Ayarlayın
Proje ana dizininde `.env.local` adlı bir dosya oluşturun ve Supabase bilgilerinizi girin:

```env
VITE_SUPABASE_URL=sizin_supabase_proje_url_adresiniz
VITE_SUPABASE_ANON_KEY=sizin_supabase_anon_key_bilginiz
```

### 5. Geliştirme Sunucusunu Başlatın
```bash
npm run dev
```
Uygulama genellikle `http://localhost:5173` adresinde çalışmaya başlayacaktır.

## 📄 Lisans

Bu proje kişisel kullanım ve test amaçlı geliştirilmiştir. Tüm hakları gizlidir ve MIT lisansına tabidir.
