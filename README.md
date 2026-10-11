<div align="center">

# 🍽️ Restro — Modern Culinary Experience

<p align="center">
  <strong>Crafted for Unforgettable Dining Moments • Fine Dining Experience for Bistro Royale, NY</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React 19" />
  <img src="https://img.shields.io/badge/Vite_8-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite 8" />
  <img src="https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS v4" />
  <img src="https://img.shields.io/badge/Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Motion" />
  <img src="https://img.shields.io/badge/Lenis_Scroll-FF5D01?style=for-the-badge&logo=scrollpack&logoColor=white" alt="Lenis Scroll" />
  <img src="https://img.shields.io/badge/Lucide_Icons-F56565?style=for-the-badge&logo=lucide&logoColor=white" alt="Lucide Icons" />
  <img src="https://img.shields.io/badge/Oxlint-3B82F6?style=for-the-badge&logo=oxc&logoColor=white" alt="Oxlint" />
</p>

<p align="center">
  <a href="#-about-the-project">📖 About</a> •
  <a href="#-key-features">✨ Features</a> •
  <a href="#-sections-deep-dive">🧩 Sections</a> •
  <a href="#-components-architecture">🧱 Components</a> •
  <a href="#-signature-dishes-menu">🍱 Menu</a> •
  <a href="#-project-structure">📂 Structure</a> •
  <a href="#-getting-started">🚀 Quick Start</a> •
  <a href="#-author--contact">📬 Contact</a>
</p>

---

</div>

## 📌 Table of Contents

- [📖 About the Project](#-about-the-project)
- [✨ Key Features](#-key-features)
- [🎨 Color Palette & Design System](#-color-palette--design-system)
- [🧩 Sections Deep Dive (`src/sections`)](#-sections-deep-dive-srcsections)
  - [1. 🌟 Hero Section (`HeroSection.jsx`)](#1--hero-section-herosectionjsx)
  - [2. 📖 Story & Heritage (`About.jsx`)](#2--story--heritage-aboutjsx)
  - [3. 📊 Excellence Metrics (`Stats.jsx`)](#3--excellence-metrics-statsjsx)
  - [4. 🍝 Interactive Dish Gallery (`Dishes.jsx`)](#4--interactive-dish-gallery-dishesjsx)
  - [5. 👨‍🍳 Culinary Highlights (`Features.jsx`)](#5--culinary-highlights-featuresjsx)
  - [6. 📅 3-Step Reservation Funnel (`BookingProcess.jsx`)](#6--3-step-reservation-funnel-bookingprocessjsx)
  - [7. ⏰ Hours & Availability (`Timing.jsx`)](#7--hours--availability-timingjsx)
  - [8. 💬 Guest Stories & Reviews (`TestimonialSection.jsx`)](#8--guest-stories--reviews-testimonialsectionjsx)
  - [9. ❓ Interactive Accordion FAQs (`FAQs.jsx`)](#9--interactive-accordion-faqs-faqsjsx)
  - [10. 🎯 Floating Dish Call-To-Action (`CTA.jsx`)](#10--floating-dish-call-to-action-ctajsx)
- [🧱 Components Architecture (`src/components`)](#-components-architecture-srccomponents)
  - [🧭 Navigation Bar (`Navbar.jsx`)](#-navigation-bar-navbarjsx)
  - [🌊 Smooth Scrolling Engine (`LenisScroll.jsx`)](#-smooth-scrolling-engine-lenisscrolljsx)
  - [🎭 Viewport Motion Wrapper (`Animated.jsx`)](#-viewport-motion-wrapper-animatedjsx)
  - [🦶 Luxury Footer (`Footer.jsx`)](#-luxury-footer-footerjsx)
- [🍱 Signature Dishes Menu](#-signature-dishes-menu)
- [⏰ Hours of Operation](#-hours-of-operation)
- [📂 Project Structure](#-project-structure)
- [🛠️ Tech Stack & Libraries](#️-tech-stack--libraries)
- [🚀 Getting Started](#-getting-started)
- [📜 Available Scripts](#-available-scripts)
- [📬 Author & Contact](#-author--contact)

---

## 📖 About the Project

> [!NOTE]
> **Restro** is a high-end, responsive restaurant web application engineered for **Bistro Royale, NY**. It delivers a seamless digital experience that captures culinary elegance, interactive gastronomy showcases, and seamless table booking.

Designed with **React 19**, **Tailwind CSS v4**, **Motion**, and **Lenis Smooth Scroll**, the project blends high performance with rich aesthetics:
- ⚡ **Zero-lag inertial scrolling** powered by Lenis
- 🔄 **Spring-physics dish rotations** on user hover
- 💫 **Scroll-driven micro-interactions** that bring sections to life
- 🪟 **Glassmorphism header** with adaptive scroll detection
- 📱 **Mobile-first fluid responsiveness** with an animated drawer navigation

---

## ✨ Key Features

| Icon | Feature | Description |
| :---: | :--- | :--- |
| 🔄 | **Interactive 360° Dish Physics** | Dishes rotate with dynamic spring physics when hovered over, providing an engaging tactile feel. |
| 🌊 | **Lenis Inertial Scrolling** | Hardware-accelerated smooth scrolling with anchor offset calibration (`-120px`) for seamless in-page routing. |
| 🎭 | **Staggered Motion Entrances** | Built-in `<Animated />` motion component triggering spring-loaded animations (`stiffness: 320, damping: 70`) on viewport entry. |
| 🪟 | **Dynamic Blur Navbar** | Transparent on page top, seamlessly morphing into a frosted glass backdrop (`backdrop-blur-md bg-white/70`) upon scrolling down. |
| 📱 | **Responsive Slide-out Drawer** | Off-canvas mobile navigation with smooth transform transitions and quick-tap section targeting. |
| 📅 | **3-Step Table Booking Guide** | Frictionless reservation path backed by real-time guest review validation. |
| ❓ | **Accessible FAQ Accordion** | Semantic HTML5 `<details>` & `<summary>` accordion with dynamic SVG plus/close icon morphs. |
| 🍱 | **Floating Dish Conversion Banner** | High-contrast call-to-action section with 4 floating dish thumbnails and hover scale dynamics. |

---

## 🎨 Color Palette & Design System

The application uses an appetite-inspiring warm palette paired with neutral undertones and modern typography:

```
🟠 Primary Orange:      #F97316 (orange-500) / #EA580C (orange-600)  [Accents, Buttons, Badges, Highlights]
⚫ Jet Black:           #000000 / #18181B (zinc-900)                 [Headlines, Contrasting Buttons]
⚪ Pure Background:     #FFFFFF                                      [Canvas, Cards, Light Elements]
🔘 Neutral Slate:       #52525B (zinc-600) / #E2E8F0 (slate-200)     [Borders, Subtitles, Card Outlines]
🔤 Primary Font:        Geist Sans                                   [Clean, modern body typography]
🔤 Display Font:        Urbanist Display                             [Luxury titles, hero headlines]
```

---

## 🧩 Sections Deep Dive (`src/sections`)

### 1. 🌟 Hero Section (`HeroSection.jsx`)
- **Visuals**: Full-bleed hero banner backdrop (`/assets/heroBanner.png`) with centered content hierarchy.
- **Copy**: *"WHERE FLAVOR MEETS ELEGANCE"* & *"Crafted for unforgettable dining moments"*.
- **Social Proof**: 
  - Stacked overlapping guest avatar row (`user-1.jpeg` through `user-4.jpeg`).
  - ⭐ 5-star rating icon stack (`lucide-react`).
  - **4.8/5 Rating — 10,000+ satisfied reviews**.
- **Call-to-Action**: Direct anchor jump to the reservation funnel.

### 2. 📖 Story & Heritage (`About.jsx`)
- **Branding**: Decorative ornament badge with left/right flourishes (`iconL.png`, `iconR.png`) and uppercase label *"CRAFTED WITH PASSION"*.
- **Core Message**: *"Experience dining beyond expectations"*.
- **Venue Spotlight**: Interactive location card pointing to **Bistro Royale, NY** with venue preview image and map link.
- **Imagery**: High-resolution dish showcase card with gentle rounded corners (`rounded-3xl`).

### 3. 📊 Excellence Metrics (`Stats.jsx`)
Presents 3 core pillars of Bistro Royale with prominent display typography:
- 🥇 **01 — Premium Ingredients**: Handpicked fresh ingredients delivering authentic flavor profiles.
- 👨‍🍳 **02 — Chef's Expertise**: Meticulous culinary execution, culinary craft, and years of master technique.
- 🤝 **03 — Warm Hospitality**: Attentive, personalized table-side service from entrance to farewell.

### 4. 🍝 Interactive Dish Gallery (`Dishes.jsx`)
- **Category Badge**: *"CHEF'S SIGNATURE SELECTION"*.
- **Title**: *"Discover our signature dishes"*.
- **Grid Layout**: Responsive 2-column mobile to 4-column desktop display.
- **Motion Magic**: Powered by `motion/react`:
  ```jsx
  onMouseEnter={() => setRotate((prev) => ({ ...prev, [index]: (prev[index] || 0) + 180 }))}
  ```
  Dishes smoothly spin +180 degrees using spring physics (`stiffness: 80, damping: 15`).

### 5. 👨‍🍳 Culinary Highlights (`Features.jsx`)
- **Highlights List**:
  - 👨‍🍳 `ChefHat` — **Chef-Crafted Dishes**: Authentic chef recipes and culinary mastery.
  - 🌿 `Leaf` — **Farm Fresh Ingredients**: Daily local organic sourcing for crisp flavors.
  - ❤️ `Heart` — **Warm Hospitality**: Thoughtful service and an intimate dining ambiance.
- **Visual Anchor**: Side-by-side layout featuring portrait of the Executive Chef (`/assets/chef.png`).

### 6. 📅 3-Step Reservation Funnel (`BookingProcess.jsx`)
Splits into a testimonial spotlight and an easy 3-step walk-through:
- **Step (01)**: `Choose your date & time` — Pick ideal reservation slot and party size.
- **Step (02)**: `Enter your details` — Contact info and bespoke dietary/seating preferences.
- **Step (03)**: `Confirm your booking` — Instant verification and reservation assurance.
- **Verified Review**: 5-star rating spotlight from Sofia Martinez.

### 7. ⏰ Hours & Availability (`Timing.jsx`)
- **Design**: Encased within an ambient restaurant interior card (`/assets/restro-timing.png`).
- **Schedule Card**: Floating frosted white panel detailing hours for Monday through Sunday.
- **Quick Action**: Embedded "Book a table" reservation button.

### 8. 💬 Guest Stories & Reviews (`TestimonialSection.jsx`)
- **Headline**: *"LOVED BY FOOD LOVERS — What Our Guests Say"*.
- **Layout**: 3-column responsive card grid.
- **Reviewers**:
  - 🇮🇳 **Aarav Sharma** (Mumbai, India)
  - 🇮🇳 **Rohan Mehta** (Bangalore, India)
  - 🇬🇧 **Emily Carter** (London, UK)
  - 🇰🇷 **Daniel Kim** (Seoul, South Korea)
  - 🇪🇸 **Sofia Martinez** (Barcelona, Spain)
  - 🇦🇺 **Daniel Wong** (Sydney, Australia)

### 9. ❓ Interactive Accordion FAQs (`FAQs.jsx`)
- **Implementation**: Pure CSS & semantic HTML5 `<details>` / `<summary>` tags with zero unnecessary JavaScript re-renders.
- **Icon Morphing**: Lucide `Plus` rotates and toggles into an `X` on open state via Tailwind's `group-open` modifier.
- **Topics**: Vegetarian/vegan menus, online table booking, takeaway & delivery, organic ingredients, and private event celebrations.

### 10. 🎯 Floating Dish Call-To-Action (`CTA.jsx`)
- **Theme**: Vibrant, high-converting energetic orange canvas (`bg-orange-500`).
- **Interactive Elements**: 4 floating dish thumbnails (`dish1.png` - `dish4.png`) positioned in cardinal corners with `hover:scale-105` micro-interactions.
- **Action Button**: High-contrast white pill button with dark circular arrow badge (`ArrowRight`).

---

## 🧱 Components Architecture (`src/components`)

```
src/components/
├── 🧭 Navbar.jsx        # Glassmorphic responsive header with mobile navigation drawer
├── 🌊 LenisScroll.jsx   # Inertial smooth scroll engine with offset navigation
├── 🎭 Animated.jsx      # Reusable motion wrapper with spring-based entrance triggers
└── 🦶 Footer.jsx        # Multi-column footer with giant typographic background watermark
```

### 🧭 Navigation Bar (`Navbar.jsx`)
- **Smart Sticky Header**: Listens to window scroll events; dynamically adds `bg-white/70 backdrop-blur-md` once user scrolls past 10px.
- **Desktop Nav Links**: Smooth jump links for `#about`, `#dishes`, `#timing`, and `#faq`.
- **Mobile Menu**: Full-screen slide-over sheet triggered by `MenuIcon` / `XIcon` with backdrop blur.

### 🌊 Smooth Scrolling Engine (`LenisScroll.jsx`)
- Integrated with `@studio-freight/lenis` (`lenis: ^1.3.26`).
- Uses `requestAnimationFrame` loop with proper unmount cleanup (`lenis.destroy()`).
- Offset calibration configured to `-120px` to guarantee header clearance when clicking anchor links.

### 🎭 Viewport Motion Wrapper (`Animated.jsx`)
- Encapsulates motion physics into a reusable drop-in container.
- **Props**:
  - `delay` *(number, default: 0)* — Stagger delay for cascading card entries.
  - `y` *(number, default: 50)* — Vertical offset for upward float entrances.
  - `x` *(number, default: 0)* — Horizontal slide distance.
  - `scale` *(number, default: 1)* — Initial zoom scale.
  - `viewport` — Triggered once per viewport entry (`once: true`).
  - Spring tuning: `stiffness: 320`, `damping: 70`, `mass: 1`.

### 🦶 Luxury Footer (`Footer.jsx`)
- **Brand Column**: Logo, brand mission statement, and custom SVG social badges (Twitter/X, YouTube, Instagram).
- **Navigation Columns**: Quick Links, Direct Contact (`hello@restro.com`, `987-654-3210`), and Sitemap.
- **Typographic Art**: Massive 300px ambient watermark logo (`Restro`) rendered in the background using `text-zinc-100/70`.
- **Credits**: Designed by **[Sushanth Thakur](https://github.com/susha1122)**.

---

## 🍱 Signature Dishes Menu

| # | Dish Name | Price | Category / Description |
| :-: | :--- | :-: | :--- |
| **01** | 🍝 **Grilled Chicken Alfredo** | **$24** | Rich creamy fettuccine paired with char-grilled chicken breast |
| **02** | 🍄 **Mushroom Risotto** | **$22** | Slow-simmered arborio rice with wild forest mushrooms and parmesan |
| **03** | 🥗 **Caprese Salad** | **$16** | Heirloom vine tomatoes, fresh buffalo mozzarella, and basil reduction |
| **04** | 🍝 **Spaghetti & Meatballs** | **$23** | Traditional slow-simmered tomato marinara with hand-rolled beef meatballs |
| **05** | 🥬 **Caesar Salad** | **$15** | Crisp romaine hearts, garlic croutons, shaved parmigiano, and classic dressing |
| **06** | 🐟 **Grilled Atlantic Salmon** | **$29** | Pan-seared wild salmon filet served with seasonal lemon-herb greens |
| **07** | 🥩 **Grilled Ribeye Steak** | **$39** | Prime aged cut with rosemary butter glaze and roasted baby potatoes |
| **08** | 🦞 **Seafood Linguine** | **$29** | Fresh shellfish, prawns, and calamari tossed in white wine garlic butter |

---

## ⏰ Hours of Operation

| Day | Opening Hours | Status |
| :--- | :--- | :---: |
| **Monday** | 10:00 AM — 09:00 PM | 🟢 Open |
| **Tuesday** | 11:00 AM — 10:00 PM | 🟢 Open |
| **Wednesday** | 10:00 AM — 09:00 PM | 🟢 Open |
| **Thursday** | 10:00 AM — 10:00 PM | 🟢 Open |
| **Friday** | *Closed for Private Dining Preparation* | 🔴 Closed |
| **Saturday** | 11:00 AM — 10:00 PM | 🟢 Open |
| **Sunday** | 12:00 PM — 09:00 PM | 🟢 Open |

---

## 📂 Project Structure

```bash
restro/
├── 📁 public/
│   └── 📁 assets/                     # Optimized visual assets & photography
│       ├── about.png                  # About section preview
│       ├── chef.png                   # Executive chef portrait
│       ├── dish1.png - dish8.png      # High-res rotating dish assets
│       ├── heroBanner.png             # Full-width hero background
│       ├── iconL.png / iconR.png      # Decorative badge flourishes
│       ├── logo.svg                   # Brand vector logo
│       ├── restro-timing.png          # Ambient interior backdrop
│       └── user-1.jpeg - user-4.jpeg  # Verified guest avatars
├── 📁 src/
│   ├── 📁 components/                 # Reusable UI building blocks
│   │   ├── Animated.jsx               # Motion spring entrance wrapper
│   │   ├── Footer.jsx                 # Footer with background watermark
│   │   ├── LenisScroll.jsx            # Lenis smooth-scrolling setup
│   │   └── Navbar.jsx                 # Glassmorphic responsive navigation
│   ├── 📁 data/
│   │   └── data.jsx                   # Centralized dishes, reviews, & FAQs
│   ├── 📁 sections/                   # Page sections
│   │   ├── About.jsx                  # Brand story & venue location card
│   │   ├── BookingProcess.jsx         # 3-step table reservation workflow
│   │   ├── CTA.jsx                    # Floating dishes conversion banner
│   │   ├── Dishes.jsx                 # Interactive rotating menu gallery
│   │   ├── FAQs.jsx                   # HTML5 details/summary accordion
│   │   ├── Features.jsx               # Culinary highlights & chef portrait
│   │   ├── HeroSection.jsx            # Hero headline & social proof stats
│   │   ├── Stats.jsx                  # Key culinary metrics (01, 02, 03)
│   │   ├── TestimonialSection.jsx     # International guest reviews grid
│   │   └── Timing.jsx                 # Weekly operational hours
│   ├── App.jsx                        # Main root layout assembling all sections
│   ├── index.css                      # Tailwind v4 import & custom font rules
│   └── main.jsx                       # React 19 root entry point
├── .oxlintrc.json                     # Oxlint configuration
├── index.html                         # HTML entry template & favicon
├── package.json                       # Dependency definitions & scripts
└── vite.config.js                     # Vite build configuration
```

---

## 🛠️ Tech Stack & Libraries

| Technology | Badge | Purpose |
| :--- | :---: | :--- |
| **React 19** | `19.2.8` | Core UI library with modern server/client performance |
| **Vite** | `8.3.0` | Ultra-fast next-gen frontend tooling and HMR dev server |
| **Tailwind CSS v4** | `4.3.3` | Modern utility-first styling with `@tailwindcss/vite` |
| **Motion** | `13.4.6` | Spring animations, gestures, and viewport reveals |
| **Lenis** | `1.3.26` | Butter-smooth hardware-accelerated inertia scrolling |
| **Lucide React** | `1.49.0` | Clean, customizable modern icon set |
| **Oxlint** | `1.81.0` | Next-generation ultra-fast Rust-based linter |
| **Google Fonts** | `Geist & Urbanist` | Premium typography for editorial luxury presentation |

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally on your machine:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/susha1122/Restro-FrontendProject.git
cd restro
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Start Development Server
```bash
npm run dev
```
Open your browser at `http://localhost:5173` to explore the application!

### 4️⃣ Build for Production
```bash
npm run build
```
The optimized production bundle will be generated inside the `/dist` directory.

### 5️⃣ Run Linter
```bash
npm run lint
```

---

## 📜 Available Scripts

| Command | Action |
| :--- | :--- |
| `npm run dev` | Starts the Vite local development server with instant HMR |
| `npm run build` | Compiles and optimizes all React components for production |
| `npm run preview` | Locally previews the production build output from `/dist` |
| `npm run lint` | Runs `oxlint` to perform fast static code quality checks |

---

## 📬 Author & Contact

<div align="center">

Crafted with ❤️ and passion by **Sushanth Thakur**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/susha1122)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sushanth.athakur@gmail.com)
[![Portfolio](https://img.shields.io/badge/Website-Restro-orange?style=for-the-badge&logo=safari&logoColor=white)](https://github.com/susha1122/Restro-FrontendProject)

*⭐ If you like this project, please consider giving it a star on GitHub! ⭐*

</div>
