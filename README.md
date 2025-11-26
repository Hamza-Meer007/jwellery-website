# 💎 Jewelry Store E-Commerce Website

<div align="center">

![E-Commerce](https://img.shields.io/badge/E--Commerce-Website-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white)

_A fully-featured, modern jewelry store e-commerce website with multiple layouts and comprehensive shopping functionality_



</div>

---

## ✨ Features

### 🏠 **Multiple Homepage Layouts**

- **6 Unique Homepage Designs** - Choose from `index.html`, `index2.html`, `index3.html`, `index4.html`, `index5.html`, and `index6.html`
- Fully responsive and mobile-optimized
- Modern, clean aesthetics with smooth animations
- Elegant jewelry-focused design

### 🛒 **Complete Shopping Experience**

- **Product Pages**: Multiple product display options

  - Single Product - Standard product view with image gallery
  - Normal Product - Classic layout with details
  - External Product - External affiliate products
  - Group Product - Grouped product variations

- **Shop Layouts**: Flexible catalog views
  - Shop Grid - Grid-based product display
  - Shop with Right Sidebar - Filter and browse
  - Full Wide Shop - Maximum product visibility
  - Left Full Wide - Alternative wide layout
  - Right Full Wide - Right-aligned wide view

### 🎯 **E-Commerce Functionality**

- 🛍️ **Shopping Cart** - `cart.html` - Full cart management with quantity controls
- ✅ **Checkout** - `checkout.html` - Secure checkout process with multiple payment options
- ❤️ **Wishlist** - `wishlist.html` - Save favorite jewelry items for later
- 🔍 **Product Compare** - `compare.html` - Compare multiple products side-by-side
- 👤 **User Account** - `my-account.html` - Customer dashboard and order management
- 🔐 **Authentication** - `login-register.html` - User login and registration system

### 📝 **Content Pages**

- 📰 **Blog System**: Multiple blog layouts

  - Blog Grid - Grid-based blog posts
  - Blog with Left Sidebar - Traditional blog layout
  - Standard Blog - Classic blog layout
  - Single Post - Individual blog post view with comments

- 📄 **Additional Pages**
  - About Us - Company information and story
  - Contact - Contact form and location details
  - 404 Error - Custom error page

---

## 🚀 Quick Start

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Hamza-Meer007/jwellery-website.git
   cd jwellery-website
   ```

2. **Open in browser**

   - Simply open `index.html` in your browser
   - Or use a local development server:

   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve

   # Using PHP
   php -S localhost:8000
   ```

3. **Navigate to** `http://localhost:8000`

---

## 📁 Project Structure

```
📦 Jewelry Store E-Commerce
├── 📄 index.html                    # Main homepage
├── 📄 index2.html                   # Alternative homepage 2
├── 📄 index3.html                   # Alternative homepage 3
├── 📄 index4.html                   # Alternative homepage 4
├── 📄 index5.html                   # Alternative homepage 5
├── 📄 index6.html                   # Alternative homepage 6
│
├── 🛍️ Shop Pages
│   ├── shop.html                    # Main shop page
│   ├── shop-right-sidebar.html      # Shop with right sidebar
│   ├── shop-full-wide.html          # Full width shop
│   ├── shop-left-full-wide.html     # Left full wide layout
│   └── shop-right-full-wide.html    # Right full wide layout
│
├── 🎁 Product Pages
│   ├── single-product.html          # Single product view
│   ├── single-product-normal.html   # Normal product layout
│   ├── single-product-external.html # External product
│   └── single-product-group.html    # Grouped products
│
├── 🛒 E-Commerce Features
│   ├── cart.html                    # Shopping cart
│   ├── checkout.html                # Checkout process
│   ├── wishlist.html                # Wishlist
│   └── compare.html                 # Product comparison
│
├── 📰 Blog Section
│   ├── blog.html                    # Main blog page
│   ├── blog-grid.html               # Blog grid layout
│   ├── blog-left-sidebar.html       # Blog with sidebar
│   └── single-blog.html             # Single blog post
│
├── 👤 User Pages
│   ├── login-register.html          # Login/Register
│   └── my-account.html              # User dashboard
│
├── 📄 Other Pages
│   ├── about.html                   # About page
│   ├── contact.html                 # Contact page
│   └── 404.html                     # 404 error page
│
└── 📂 assets/
    ├── 📂 css/                      # Stylesheets
    │   ├── style.css                # Main stylesheet
    │   ├── plugins.css              # Plugin styles
    │   └── vendor/                  # Vendor CSS files
    │       ├── bootstrap.min.css
    │       └── font-awesome.css
    │
    ├── 📂 js/                       # JavaScript files
    │   ├── active.js                # Main JS file
    │   ├── ajax-mail.js             # AJAX mail handler
    │   ├── plugins.js               # Plugin scripts
    │   └── vendor/                  # Vendor JS files
    │       ├── jquery-3.3.1.min.js
    │       ├── bootstrap.min.js
    │       └── popper.min.js
    │
    ├── 📂 img/                      # Images
    │   ├── Product images
    │   ├── Blog images
    │   ├── Gallery images
    │   └── Icons and logos
    │
    └── 📂 fonts/                    # Font files
        └── Font Awesome fonts
```

---

## 🎨 Features Breakdown

### 🛍️ Shopping Cart System

The `cart.html` page provides:

- ➕ Add/remove products easily
- 🔢 Quantity adjustment with real-time updates
- 💰 Real-time price calculation and subtotal
- 🎟️ Coupon code application
- 🚚 Shipping cost calculator
- ♻️ Update cart functionality
- 🗑️ Remove items individually

### ✅ Checkout Process

The `checkout.html` includes:

- 📋 Comprehensive billing information form
- 🚚 Multiple shipping options
- 💳 Payment method selection
- 📊 Detailed order summary
- 🔒 Secure payment processing
- 📝 Order notes section
- ✉️ Email confirmation

### 👤 User Account Dashboard

Access via `my-account.html`:

- 📦 Complete order history
- 📍 Saved address management
- 👤 Profile settings and information
- 🔑 Password change functionality
- 💾 Account preferences
- 📥 Download invoices
- 🔔 Notification settings

### 📰 Blog System

Multiple layouts available:

- 📱 Grid view for modern appearance
- 📑 Sidebar layouts for traditional blogs
- 📄 Single post pages with comments section
- 🏷️ Category and tag filtering
- 🔍 Search functionality
- 📅 Archive by date
- 👤 Author profiles

---

## 🎯 Use Cases

- 💍 **Jewelry E-Commerce Store** - Complete online jewelry shopping platform
- 💎 **Diamond & Gemstone Shop** - Luxury jewelry marketplace
- 👑 **Fashion Accessories** - Rings, necklaces, bracelets, earrings
- 🎁 **Gift Shop** - Special occasion jewelry gifts
- 🏪 **Multi-vendor Marketplace** - Multiple jewelry seller platform
- 🛍️ **Boutique Store** - Exclusive designer jewelry collections

---

## 🔧 Customization

### Changing Homepage

To use a different homepage layout, simply rename your preferred index file:

```bash
# Example: Use index3 as main homepage
mv index.html index-backup.html
mv index3.html index.html
```

### Styling

Customize the appearance by modifying:

- **Main Styles**: `assets/css/style.css`
- **Plugin Styles**: `assets/css/plugins.css`
- **Bootstrap**: `assets/css/vendor/bootstrap.min.css`

### JavaScript

Modify functionality in:

- **Main Script**: `assets/js/active.js`
- **Plugins**: `assets/js/plugins.js`
- **AJAX Mail**: `assets/js/ajax-mail.js`

### Images

Replace product images in `assets/img/` directory to showcase your jewelry products.

---

## 🌐 Browser Support

| Browser            | Version                   |
| ------------------ | ------------------------- |
| ✅ Chrome          | Latest                    |
| ✅ Firefox         | Latest                    |
| ✅ Safari          | Latest                    |
| ✅ Edge            | Latest                    |
| ✅ Opera           | Latest                    |
| ✅ Mobile Browsers | iOS Safari, Chrome Mobile |

---

## 📱 Responsive Design

This website is fully responsive and optimized for:

- 📱 **Mobile devices** (320px - 767px)
- 📱 **Tablets** (768px - 1023px)
- 💻 **Desktops** (1024px - 1439px)
- 🖥️ **Large screens** (1440px and up)
- 📺 **4K displays** (2560px and up)

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript** - Interactive functionality
- **Bootstrap** - Responsive framework
- **jQuery** - DOM manipulation
- **Font Awesome** - Icon library
- **Owl Carousel** - Product sliders
- **AJAX** - Asynchronous operations

---

## 📋 Key Features

### Product Features

- 🖼️ Product image gallery with zoom
- ⭐ Product ratings and reviews
- 🎨 Color and size variations
- 📊 Stock availability indicator
- 🔔 Product availability notifications
- 💝 Add to wishlist
- 🔗 Social media sharing
- 📱 Quick view modal

### Navigation Features

- 🔍 Advanced search functionality
- 🗂️ Category filtering
- 💰 Price range filter
- 🎯 Sort by options (price, popularity, rating)
- 📱 Mobile-friendly menu
- 🛒 Mini cart in header
- 👤 User account dropdown

### Additional Features

- 📧 Newsletter subscription
- 💬 Live chat support (ready to integrate)
- 🌍 Multi-language support (ready)
- 💱 Multi-currency support (ready)
- 🔒 SSL ready
- 📊 Google Analytics ready
- 🎨 Multiple color schemes

---

## 🚀 Performance

- ⚡ Fast loading times
- 🗜️ Optimized images
- 📦 Minified CSS and JS
- 🔄 Lazy loading images
- 💾 Browser caching enabled
- 📱 Mobile-first approach

---

## 📞 Support

For support and inquiries:

- 📧 **Email**: support@jewelrystore.com
- 💬 **GitHub Issues**: [Open an issue](https://github.com/Hamza-Meer007/jwellery-website/issues)
- 📖 **Documentation**: Check the docs folder
- 🌐 **Website**: [Visit our website](#)

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Built with modern web development best practices
- Designed for optimal user experience
- Focused on performance and accessibility
- Special thanks to all contributors
- Inspired by leading e-commerce platforms

---

## 📸 Screenshots

### Homepage

![Homepage](assets/img/slide-img-1.jpg)

### Shop Page

Beautiful grid layout showcasing jewelry products with filtering options.

### Product Details

Detailed product view with image gallery, description, and add to cart functionality.

### Shopping Cart

Easy-to-use cart with quantity controls and coupon application.

---

## 🎓 Learning Resources

This project demonstrates:

- Responsive web design principles
- E-commerce website structure
- Modern CSS techniques
- JavaScript interactivity
- Bootstrap framework usage
- Front-end best practices

---

<div align="center">

**Made with ❤️ by Hamza Meer**

⭐ Star this repo if you find it helpful!

[⬆ Back to Top](#-jewelry-store-e-commerce-website)

</div>
