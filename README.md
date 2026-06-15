Sooncoming — Electronics E-Commerce Platform
> A full-featured e-commerce platform built for **Sooncoming.co.ke** — an online electronics store serving the Kenyan market.
---
🛍️ About the Project
Sooncoming is a production-ready e-commerce web application built with Laravel/PHP. The platform was live at sooncoming.co.ke and handled real transactions for electronics and gadgets including mobile phones, tablets, iPads, computers, headphones, and accessories.
---
✨ Features
🛒 Customer Side
User registration and login (with email verification)
Product listings with categories, filters, and search
Product detail pages with images and specifications
Shopping cart — add, update, remove items
Wishlist — save products for later
Order tracking — real-time order status updates
Multiple checkout options:
M-Pesa STK Push (Pay Now — instant mobile payment prompt)
M-Pesa Paybill (manual payment via paybill number)
Pay on Delivery (cash on delivery option)
⚙️ Admin Panel
Product management (add, edit, delete products)
Category and inventory management
Order management and status updates
Customer management
Payment verification and tracking
Sales dashboard and reporting
---
💳 Payment Integration
Method	Provider	Type
STK Push	M-Pesa (Safaricom)	Instant mobile prompt
Paybill	M-Pesa (Safaricom)	Manual payment
Pay on Delivery	Cash	On delivery
---
🛠️ Tech Stack
Layer	Technology
Backend	Laravel (PHP)
Frontend	Blade Templates, HTML, CSS, JavaScript
Database	MySQL
Payment	M-Pesa Daraja API (STK Push)
Storage	Laravel Storage
Auth	Laravel Auth
---
📱 Product Categories
📱 Mobile Phones
💻 Computers & Laptops
📟 Tablets & iPads
🎧 Headphones & Audio
🔌 Accessories & Peripherals
---
🚀 Getting Started (Local Setup)
```bash
# Clone the repository
git clone https://github.com/muchahi/sooncoming-website.git
cd sooncoming-website

# Install dependencies
composer install
npm install

# Set up environment
cp .env.example .env
php artisan key:generate

# Set up database
php artisan migrate
php artisan db:seed

# Run the app
php artisan serve
```
---
🔐 Environment Variables
Set these in your `.env` file:
```env
DB_DATABASE=sooncoming
DB_USERNAME=root
DB_PASSWORD=

MPESA_CONSUMER_KEY=your_key
MPESA_CONSUMER_SECRET=your_secret
MPESA_SHORTCODE=your_shortcode
MPESA_PASSKEY=your_passkey
```
---
👨‍💻 Developer
Brian Muchahi  
Full-Stack & Mobile Developer  
📧 muchahibrian2@gmail.com  
📍 Nairobi, Kenya  
🔗 github.com/muchahi
---
> *Built and deployed for the Kenyan market with M-Pesa payment integration and full e-commerce functionality.*
