# 🛍️ LuLu Mall — Official Modern & Premium Website

A model, state-of-the-art web application built for **LuLu Mall** — South Asia’s premier luxury shopping, entertainment, and culinary landmark.

---

## 🌟 Key Features Built for LuLu Brand

### 1. 🏢 Multi-Mall Location Switcher
* Seamlessly toggle across flagship locations:
  - **LuLu Mall Kochi** (Flagship, 2.5M sq ft)
  - **LuLu Mall Bengaluru** (Global Mall, 1.0M sq ft)
  - **LuLu Mall Lucknow** (Amar Shaheed Path, 2.2M sq ft)
  - **LuLu Mall Thiruvananthapuram** (Akkulam, 2.0M sq ft)
  - **LuLu Mall Hyderabad** (Kukatpally, 600k sq ft)
* Dynamically updates operating hours, store counts, live parking availability, and address information.

### 2. 🛒 Signature LuLu Brand Showcases
* **LuLu Hypermarket**: Showcase for Asia's premier hypermarket, fresh farm produce, gourmet roastery, live deli, bakery, and digital flyer preview.
* **LuLu Connect**: Electronics and tech superstore with Apple, Sony, Samsung, AI laptops, OLED screens, and student exchange deals.
* **LuLu Celebrate**: Bridal and ethnic fashion hub featuring pure Kanchipuram silks, bespoke designer sherwanis, and bridal consultation.
* **Funtura Adventure Park**: 60,000 sq ft indoor thrill destination with family roller coasters, XD 7D dark ride, 8-lane bowling, and an interactive **Play Card Recharge Calculator**.

### 3. 🔍 Interactive Store Directory (300+ Brands)
* Real-time search with instant debounce.
* Categorized pills (All, LuLu Hypermarket, Fashion, Electronics, Luxury & Jewelry, Dining, Entertainment, Beauty, Services).
* Floor filter dropdown (Ground, Level 1, Level 2, Level 3, Level 4).
* Store cards with brand tags, floor unit codes, ratings, deal banners, "Locate on Floor Map", and "Store Details" modal with direct WhatsApp chat.

### 4. 🗺️ Interactive 2D Floor Plan Navigator
* Architectural SVG floor map with clickable units for Ground Floor, Level 1, Level 2, Level 3, and Level 4.
* Clicking any store in the directory automatically selects the correct floor level, scrolls to the map, and activates an animated pulse on that specific unit!
* Wayfinding legends for Escalators, Grand Central Atrium, Baby Care bays, and Emergency Exits.

### 5. 🎬 Cinépolis VIP Superplex & Interactive Seat Selector
* Movie showcases with ratings, duration, censor certificate, and formats (IMAX Laser 3D, 4DX, VIP Gold Class).
* Real-time **Interactive Seat Booking Modal**:
  - Curved IMAX laser screen visualization.
  - VIP Gold Class recliners (₹450) and Executive Prime seats (₹280).
  - Dynamic price calculation.
  - Instant booking pass confirmation.

### 6. 🍽️ Dining & Food Court Reservation
* Filter by cuisine: Heritage Malabar & Seafood, Cafes & Bakeries, and Grand Food Court (50+ global kiosks).
* Direct **Table Reservation** feature with instant confirmation toast.

### 7. 🎁 Exclusive Deals, Coupons & Promo Codes
* Promo cards with one-click **Copy Promo Code** and celebratory feedback.

### 8. 👑 LuLu Happiness VIP Loyalty Program
* Tiered rewards: **Silver Happiness**, **Gold Privileged**, and **Platinum Royal Club**.
* **Interactive Points & Cashback Calculator**: Drag monthly spending slider to view earned points and estimated annual savings.

### 9. 🚗 Smart Valet & Live Parking Sensor Tracker
* Real-time slot availability tracker (Basement 1, Basement 2, MLCP Level 1 & 2, EV Supercharger bays).
* Periodic occupancy fluctuation simulation for live realism.
* **Valet Ticket Retrieval Simulator**: Enter token (e.g. `LL-492`) to receive live vehicle status and dispatch time.

### 10. 🤖 Smart AI Concierge Chatbot ("LuLu Assistant")
* Floating 24/7 assistant widget with quick prompt chips.
* Rule-based natural language matching for stores (Zara, Apple, Sephora), hypermarket timings, parking, wifi, wheelchair accessibility, and tickets.

---

## 🚀 How to Run and Preview

### Option 1: Direct Browser Launch
Simply double-click `index.html` to open it directly in any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).

### Option 2: Python Local Server (Recommended)
Run the included launcher in PowerShell or terminal:
```bash
python start_server.py
```
This automatically starts a local server on `http://localhost:3000` and opens your browser.

---

## 📁 Project Architecture

```
googlegravity.1/
├── index.html              # Main website portal (HTML5 + Tailwind CSS + Lucide Icons)
├── css/
│   └── styles.css          # Custom luxury styling, glassmorphism, animations, seat matrix
├── js/
│   ├── data.js             # Structured LuLu Mall dataset (locations, stores, dining, movies)
│   └── app.js              # Application state, filters, interactive map, booking modals, chatbot
├── start_server.py         # Lightweight Python development server
└── README.md               # Documentation and feature guide
```

---

## 🎨 Brand Design Specifications
* **Primary Emerald Green**: `#006837` & `#004d25`
* **Warm Champagne Gold**: `#D4AF37`, `#F59E0B`, `#FDE68A`
* **Obsidian / Slate**: `#0b131e` & `#0f172a`
* **Typography**: *Outfit* (Modern Sans-Serif) & *Playfair Display* (Editorial Luxury Serif)
