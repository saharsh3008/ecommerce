# 🛒 E‑Commerce Website

A full-stack e-commerce platform built with PHP (Laravel optional), featuring a user-facing store and a robust admin dashboard.

---

## 🚀 Features

- **Customer Panel**: User registration, product browsing, cart & wishlist, checkout, order tracking  
- **Product Showcase**: Featured/latest products, filter by category/brand, price range slider  
- **Payment Methods**: Card payments, cash-on-delivery, coupon support  
- **Reviews & Ratings**: Users can rate & review products  
- **Admin Dashboard**:
  - Manage products, categories, brands, shipping, coupons, banners, media  
  - View and update orders with status control  
  - Manage users, blogs, notifications, and site settings  
  - Analytical dashboard with monthly earnings and activity summaries  

---

## 🧰 Tech Stack

- **Backend**: PHP (Laravel or vanilla PHP)  
- **Frontend**: HTML, CSS (Bootstrap/Tailwind), JavaScript  
- **Database**: MySQL
- **Tools**: Composer, npm, artisan CLI

---

## ⚙️ Setup & Run Locally

```bash
git clone https://github.com/saharsh3008/project_ecommerce.git
cd project_ecommerce

# Backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed

# Frontend
npm install
npm run dev

# Run
php artisan serve




