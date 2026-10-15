# Debby's Kitchen — Modern Food E-Commerce Website

> **Brand Motto:** *Serve You What You Want*  
> **Contact Line:** 08154866319  
> **WhatsApp Direct:** [https://wa.me/2348154866319](https://wa.me/2348154866319)  
> **Currency:** Nigerian Naira (₦)  
> **Location / Coverage:** Nigeria  

---

## 1. Project Overview

**Debby's Kitchen** is a modern, colorful, accessible, and mobile-responsive food e-commerce website designed for an authentic Nigerian culinary brand. The platform showcases a diverse range of Nigerian dishes—including classic party jollof rice, seasoned fried rice, native soups and swallow, spicy pasta, grilled meats, fish, crispy pastries, small chops, and chilled beverages.

The website provides an intuitive customer experience across all screen sizes, with dedicated product catalogues, meal specifications, category navigations, promotional packages, and direct contact options for placing food orders.

---

## 2. Technology Requirements & Architecture

- **Semantic HTML5:** Built strictly using clean, valid, semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`).
- **External CSS3 Only:** All styling is managed via modular external stylesheets.
- **Strictly No JavaScript:** Zero JavaScript files, zero `<script>` tags, zero `onclick` attributes, and zero client-side frameworks.
- **Pure CSS Mobile Navigation:** Responsive hamburger menu utilizing the accessible CSS checkbox pattern (`#nav-toggle` + sibling selector).
- **Responsive Layouts:** Implemented with fluid CSS Grid and Flexbox with responsive breakpoints (`320px`, `375px`, `768px`, `1024px`, `1440px`).
- **CSS Transitions & Effects:** Smooth hover elevations, button gradients, subtle badge shadows, and responsive scaling.
- **No Backend / Database:** Designed for local previewing by opening HTML files directly in any modern browser.

---

## 3. Project Structure

```text
debbys-kitchen/
│
├── index.html              # Homepage with hero, categories, popular meals, testimonials & CTA
├── shop.html               # 12-item product catalog with visual filters & search bar
├── categories.html         # 8 dedicated category sections with deep anchor jumps
├── product-details.html    # Detailed dish showcase (Jollof Rice & Chicken) with ingredients
├── cart.html               # Demonstration shopping cart with subtotals & empty state
├── about.html              # Brand story, mission, motto, 6 core values & food gallery
├── contact.html            # Contact channels, opening hours & accessible inquiry form
├── offers.html             # 5 promotional combo packages, discounts & newsletter preview
├── order.html              # Comprehensive meal ordering form with delivery/pickup options
│
├── style.css               # Global tokens, resets, header, footer, buttons & homepage
├── shop.css                # Shop layout, toolbar, product card grid
├── categories.css          # Category blocks, sticky jump bar, color accents
├── product-details.css     # Product gallery, portion & recipe specification boxes
├── cart.css                # Cart table, order summary card, empty cart layout
├── about.css               # Mission/motto cards, story layout, values grid, gallery
├── contact.css             # Contact channels, info cards, form layouts
├── offers.css              # Promotional cards, combo perks, newsletter banner
├── order.css               # Order form fieldsets, delivery toggles, order steps
│
├── logo.png                # Branded Debby's Kitchen badge with chef hat and motto
├── hero-food.jpg           # High-resolution feast spread
├── jollof-rice.jpg         # Authentic Nigerian jollof rice dish
├── fried-rice.jpg          # Vegetable seasoned fried rice
├── white-rice.jpg          # Steamed white rice with rich tomato stew
├── egusi-soup.jpg          # Traditional Nigerian melon seed Egusi soup
├── vegetable-soup.jpg      # Rich leafy Efo Riro vegetable soup
├── spaghetti.jpg           # Spicy Nigerian jollof spaghetti
├── fried-chicken.jpg       # Crispy golden fried spiced chicken
├── grilled-fish.jpg        # Charcoal grilled spiced whole fish
├── puff-puff.jpg           # Golden sweet fried puff-puff dough balls
├── meat-pie.jpg            # Flaky golden baked Nigerian meat pie
├── small-chops.jpg         # Party small chops finger food platter
├── food-banner.jpg         # Culinary herbs, spices and drinks banner
│
└── README.md               # Complete project documentation and guide
```

---

## 4. How to Open and Preview the Website

1. Navigate to the project directory:
   ```text
   c:\Users\Asus\Desktop\web dev\debbys-kitchen\
   ```
2. Double-click **`index.html`** to open it in your default web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
3. Alternatively, right-click `index.html` and choose **"Open with..."** and select your preferred browser.
4. All navigation links between pages are relative and work seamlessly offline without requiring a web server or internet connection.

---

## 5. How to Edit Product Prices

All food prices are displayed with the Nigerian Naira symbol (`&#8358;` or `₦`).

To change any price:
1. Open the corresponding HTML file in your code editor:
   - For homepage popular meals: `index.html`
   - For shop catalogue: `shop.html`
   - For product detail page: `product-details.html`
   - For category lists: `categories.html`
   - For combo deals: `offers.html`
   - For shopping cart: `cart.html`
2. Search for the product name or price (e.g., `&#8358;2,500`).
3. Update the number to your new price (e.g., change `&#8358;2,500` to `&#8358;3,200`).
4. Save the file and refresh your browser.

---

## 6. How to Replace Images

1. Place your new high-resolution image in the main `debbys-kitchen` project folder.
2. Ensure the filename matches the desired slot (e.g. `jollof-rice.jpg`), or update the `src` attribute in the HTML files:
   ```html
   <img src="your-new-image.jpg" alt="Description of the meal" class="product-card-img">
   ```
3. Recommended image dimensions:
   - **Hero Image (`hero-food.jpg`):** Minimum 1200 × 800 px (Landscape)
   - **Product Photos (`*.jpg`):** 800 × 600 px or square 800 × 800 px
   - **Logo (`logo.png`):** 512 × 512 px (PNG with transparent or circular background)

---

## 7. How to Update Contact Details

Debby's Kitchen contact details are standardized across all nine pages:

- **Telephone Number:** `08154866319`
- **Clickable Tel Link:** `tel:08154866319`
- **WhatsApp Link:** `https://wa.me/2348154866319` (Nigerian country code `234`)

To update the phone number globally:
1. Perform a find-and-replace across all `.html` files:
   - Find: `08154866319` → Replace with your new number.
   - Find: `2348154866319` → Replace with your new international WhatsApp number.

---

## 8. How to Change the Brand Color Palette

Brand colors are defined centrally using CSS Custom Properties in `style.css` on lines 15–26:

```css
:root {
  --primary-orange: #FF8A00;  /* Main buttons & highlights */
  --deep-orange:    #E85D04;  /* Accent hover states & prices */
  --tomato-red:     #E63946;  /* Badges & special calls to action */
  --fresh-green:    #2D6A4F;  /* Freshness & promo banners */
  --golden-yellow:  #FFC107;  /* Special offer badges & accents */
  --dark-charcoal:  #1F2933;  /* Headings & dark footer background */
  --cream:          #FFF8F0;  /* Warm background tint */
  --white:          #FFFFFF;  /* Clean card background */
  --light-gray:     #F4F5F7;  /* Section & input backgrounds */
}
```

Updating any hex code in `:root` will instantly cascade across all 9 pages and all stylesheets!

---

## 9. How to Add New Products

To add a new meal to `shop.html`:
1. Open `shop.html`.
2. Locate the `<div class="shop-products-grid">` container.
3. Duplicate one of the existing `<article class="shop-card">` blocks:
   ```html
   <article class="shop-card">
     <div class="shop-card-img-wrap">
       <img src="your-meal.jpg" alt="Dish Name" class="shop-card-img">
       <span class="shop-badge badge-orange">New</span>
     </div>
     <div class="shop-card-body">
       <span class="shop-card-category">Food Category</span>
       <h2 class="shop-card-title">Dish Name</h2>
       <p class="shop-card-desc">Description of ingredients, seasoning, and sides.</p>
       <div class="shop-card-price-row">
         <span class="shop-card-price">&#8358;2,800</span>
         <span class="shop-card-tag">Fresh Daily</span>
       </div>
       <div class="shop-card-actions">
         <a href="product-details.html" class="btn btn-outline btn-sm">View Details</a>
         <a href="order.html" class="btn btn-primary btn-sm">Order Now</a>
       </div>
     </div>
   </article>
   ```
4. Save and reload the shop page.

---

## 10. Navigation Sitemap

| Page | File | Purpose |
| :--- | :--- | :--- |
| **Home** | `index.html` | Hero, categories overview, 6 popular dishes, brand values, testimonials, and contact CTA. |
| **Shop** | `shop.html` | 12 product catalogue, visual search bar, category navigation, and ordering callouts. |
| **Categories** | `categories.html` | 8 distinct categories with sticky sub-navigation and jump anchors (`#rice-dishes`, etc.). |
| **Product Details** | `product-details.html` | Featured culinary specs (Jollof Rice & Chicken), ingredients, portion sizes, preparation notes. |
| **Shopping Cart** | `cart.html` | Demonstration cart table with quantities, delivery fee, order totals, and empty-cart preview. |
| **About Us** | `about.html` | Brand origin, mission statement, motto, 6 core values, and photo gallery. |
| **Contact** | `contact.html` | Phone, WhatsApp channel, operating hours, and customer enquiry form. |
| **Special Offers** | `offers.html` | 5 combo deals, savings badges, package breakdowns, and newsletter preview. |
| **Order Now** | `order.html` | Interactive food ordering request form, fulfillment toggle, and steps guide. |

---

## 11. Static Demonstrations Explained

In strict accordance with project specifications, no JavaScript or backend is employed:
- **Search Bar (`shop.html`):** Styled demonstration input showing visual search styling without live DOM filtering.
- **Shopping Cart (`cart.html`):** Static illustrative values (2 items, subtotal ₦8,000, total ₦9,000) showcasing how an e-commerce cart renders.
- **Contact & Order Forms (`contact.html`, `order.html`):** Semantic, accessible forms equipped with HTML5 inputs (`required`, `type="email"`, `type="tel"`, `type="date"`). Forms include visible notices explaining they are demonstrations.
- **Customer Reviews (`index.html`):** Sample placeholder testimonials clearly tagged as demonstration reviews.

---

## 12. Future Backend Integration Roadmap

When ready to connect this frontend to live production services:
1. **Form Processing:** Connect `form action` to a serverless backend, Formspree, EmailJS, or PHP handler.
2. **Dynamic Cart & Checkout:** Integrate a lightweight JavaScript state manager (or localStorage) and Paystack/Flutterwave for Nigerian Naira payments.
3. **Live Search & Filter:** Add JavaScript search filtering or backend product querying.
4. **Automated WhatsApp Order Dispatch:** Format form entries into pre-filled WhatsApp message URLs (`https://wa.me/2348154866319?text=Hello%20Debby's%20Kitchen...`).

---

*© 2026 Debby's Kitchen. All rights reserved. Serve You What You Want.*
