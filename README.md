# Smarthub Responsive Store Landing Page

A sleek, modern landing page for showcasing tech products, designed with responsiveness, clarity, and user experience in mind.

---

## Introduction

Smarthub is a responsive store landing page that showcases a curated selection of the latest smartphones. Built with HTML and CSS, the project emphasizes a minimal UI, consistent branding, and cross-device compatibility.

---

## Design Choices Summary

**Responsive Four-Column Grid Layout**  
Utilizes CSS Grid with `grid-template-columns: repeat(4, 1fr)` on large screens. Media queries adapt the layout to two columns for tablets and one column for mobile, ensuring accessibility across all devices.

**Uniform Product Image Dimensions**  
Product images maintain a consistent height of `250px` using `object-fit: cover`, which prevents uneven image presentation and enhances visual harmony.

**Clean, Minimal UI**  
The layout features centered containers, subtle box shadows, and rounded corners, contributing to a polished and clutter-free interface.

**Modern Interaction Cues**  
Interactive elements like buttons and cards include hover transitions on `transform`, `background-color`, and `color`, offering smooth visual feedback.

**Color Scheme and Branding**  
The design uses a soft gray background with cyan accents (`rgb(57, 180, 193)`) for the header and footer, projecting a clean, tech‑inspired brand identity.

**Responsive Navigation**  
Header and navigation adapt layout direction and spacing on smaller screens for better usability and accessibility.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/smarthub-landing-page.git
````

2. Navigate to the project directory:

   ```bash
   cd Smarthub_Responsive_Store_Landing_Page
   ```
3. Open `index.html` in your browser.

No build steps or dependencies are required.

---

## Usage

Open `index.html` in any modern web browser. The layout will adjust dynamically based on your screen size, displaying featured products in a user-friendly grid.

---

## Features

* Responsive design using CSS Grid and Flexbox
* Clean layout with minimalist aesthetics
* Interactive product cards with hover effects
* Mobile-friendly navigation
* Consistent branding throughout

---

## Dependencies

This project is built using:

* HTML5
* CSS3 (no frameworks)
* Google Fonts (optional if added)

No third-party libraries or frameworks were used.

---

## Configuration

No configuration needed. All content and styles are self-contained within:

* `index.html`
* `styles.css`

You can update product details and images directly within `index.html`.

---

## Documentation

### File Structure

```
Smarthub_Responsive_Store_Landing_Page/
│
├── index.html      # Main HTML structure  
└── styles.css      # Styling and responsive design
```

### Sections

* **Header**: Site logo and responsive navigation
* **Product Grid**: Four featured smartphone cards
* **Footer**: Copyright

---

## Examples

To add a new product, copy and paste the following inside the `.product-grid` container:

```html
<div class="product-card">
    <img src="IMAGE_URL" alt="Product Name" />
    <h3>Product Name</h3>
    <p>Short description of the product features.</p>
    <button>Shop Now</button>
</div>
```

---

## Troubleshooting

* **Images not loading**: Ensure URLs are valid or hosted correctly.
* **Layout broken on small screens**: Verify `media queries` in `styles.css` are not overridden.
* **Slow load times**: Optimize image sizes or use CDN-hosted versions.

---

## Contributors

* **JeffKagiri** —(https://github.com/JeffKagiri)

---

## License

This project is open-source and available under the [MIT License](LICENSE)

