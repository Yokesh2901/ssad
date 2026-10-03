# Shree Srinivasa Aluminium Designs 🏗️

> **Responsive aluminium fabrication & glass design website.**

A responsive business website for **Shree Srinivasa Aluminium Designs (SSAD)**, presenting aluminium fabrication, glass solutions, completed projects, company experience, and contact information through a modern single-page interface.

## ✨ Highlights

- 🏢 Professional business landing page
- 🪟 Aluminium & glass service showcase
- 🏗️ Completed project portfolio
- 📱 Responsive mobile navigation
- 🎞️ Swiper-powered service carousel
- ✨ ScrollReveal animations
- 🧭 Active navigation based on scroll position
- 🖼️ Project and company image gallery
- 📊 Experience and project statistics

## 🧩 Website Sections

### 🏠 Home
Hero section with business introduction, service/project CTAs, experience statistics, and project imagery.

### 👷 About Us
Highlights professional workers, quality, experience, and project quotation.

### 🛠️ Services

| Service | Focus |
|---|---|
| Aluminium Solutions | Architectural aluminium fabrication |
| Home Aluminium & Glass | Residential solutions |
| Maintenance & Repair | Maintenance and repair work |
| Installation | Aluminium and glass installation |

### 🏗️ Projects

The portfolio includes completed work such as:

- **Hanudev Info Park** — Coimbatore
- **PSS Multiplex** — Tirunelveli
- **BKR Resort**
- Additional completed projects

## 🏗️ Architecture

```text
                 SSAD Website
                      │
          ┌───────────┴───────────┐
          │                       │
      HTML / UI              Visual Assets
          │                       │
          ├─────────┐             │
          ▼         ▼             ▼
         CSS    JavaScript      Images
          │         │
          │    ┌────┴──────────┐
          │    │               │
          ▼    ▼               ▼
     Responsive Swiper     ScrollReveal
         UI    Carousel       Motion
          │       │              │
          └───────┴──────────────┘
                      │
                      ▼
             Responsive Website
```

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Responsive styling |
| JavaScript | Interactions and DOM logic |
| Swiper.js | Service carousel |
| ScrollReveal | Scroll animations |
| Remix Icon | UI icons |
| Google Fonts | Montserrat typography |

## 📂 Project Structure

```text
ssad/
├── website/
│   ├── main.html
│   ├── action.js
│   ├── style.css
│   ├── scrollreveal.min.js
│   ├── swiper-bundle.min.css
│   ├── swiper-bundle.min.js
│   ├── home-lines-bg.svg
│   └── images/
│       └── project / company images
└── .github/
    └── workflows/
        └── validate.yml
```

## 🚀 Run Locally

Clone the repository:

```bash
git clone https://github.com/Yokesh2901/ssad.git
cd ssad
```

This is a static website, so no backend installation is required.

Open `website/main.html` directly, or use a local server:

```bash
python -m http.server 5500 --directory website
```

Then open `http://localhost:5500`.

## ⚙️ Interactive Features

- **Responsive navigation** with mobile menu controls
- **Dynamic header** on scroll
- **Active section tracking** while scrolling
- **Swiper carousel** for services
- **ScrollReveal animations** for major sections
- **Project showcase** for completed work

## 📱 Responsive Design

The interface is designed for:

- Desktop
- Laptop
- Tablet
- Mobile

## ⚠️ Development Notes

Some current files contain machine-specific Windows paths such as:

```text
D:\SSAD\website\...
```

For deployment, replace these with relative paths such as:

```text
./img_1.jpg
./style.css
./home-lines-bg.svg
```

## 🔮 Roadmap

- [ ] Replace absolute Windows paths
- [ ] Add contact form handling
- [ ] Add WhatsApp enquiry integration
- [ ] Add project filtering
- [ ] Add project detail pages
- [ ] Add SEO/Open Graph metadata
- [ ] Optimize images
- [ ] Add Google Maps
- [ ] Deploy production version
- [ ] Add stronger CI validation

## 🎯 What This Project Demonstrates

**Responsive Web Design → DOM Manipulation → Animation → Carousel Components → Business Website Development**

The project turns a traditional aluminium and glass fabrication business profile into a structured digital presence focused on **services, portfolio credibility, and customer conversion**.

## 👨‍💻 Author

**Yokesh S.**

Built with HTML, CSS, JavaScript, and modern frontend UI techniques.

## 📄 License

No explicit open-source license is currently defined in this repository.

⭐ **Design. Fabricate. Build.**
