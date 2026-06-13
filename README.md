# Global Academy Pathway (GAP)

![GAP Logo](https://images.unsplash.com/photo-1524178232363-1fb2b075b655?q=80&w=2070&auto=format&fit=crop) <!-- Replace with actual logo/banner if available -->

Global Academy Pathway (GAP) is a comprehensive platform dedicated to A-Z school upgradation, focusing on human values, life skills, and world-class IGCSE standards. This project serves as the official website for GAP, offering insights into their holistic educational model, services, pricing, and contact information.

Designed and developed by **Team ProDevInfo**.

## 🚀 Features

*   **Modern, Premium UI/UX:** A clean, professional, and beautifully designed interface featuring a vibrant blue theme (`#6266ea`).
*   **Fully Responsive:** Seamlessly adapts to all screen sizes (mobile, tablet, desktop).
*   **Dark/Light Mode:** Integrated theme toggler for personalized user experience, utilizing CSS variables.
*   **Multi-Page Architecture:** Includes dedicated pages for Home, About Us, Work (Services), Pricing, and Contact.
*   **Phosphor Icons:** Utilizes lightweight and elegant vector icons.
*   **Smooth Animations:** Hover effects, transition animations, and a sleek subscribe section.

## 📁 Project Structure

The project is built as a static website using pure HTML, CSS, and Vanilla JavaScript.

```
GAP/
│
├── index.html       # Landing page / Home
├── about.html       # About Us, Vision, Mission, and Team
├── work.html        # Services and past work showcase
├── pricing.html     # Tiered pricing and packages
├── contact.html     # Contact form and information
│
├── style.css        # Global styles, variables, typography, and base components
├── gap_style.css    # Specific corporate styling and layout overrides
│
└── script.js        # JavaScript logic (Theme toggling, mobile menu, interactions)
```

## 🛠️ Technologies Used

*   **HTML5:** Semantic structuring.
*   **CSS3:** Custom properties (variables), Flexbox, CSS Grid, and media queries for responsiveness.
*   **Vanilla JavaScript:** Lightweight interactivity without external frameworks.
*   **Phosphor Icons:** Web icon library.
*   **Google Fonts:** Typography (Inter).

## 💻 Running Locally

Since this is a static website, you don't need any complex build tools to run it.

### Option 1: Using a Local Server (Recommended)
You can use a local development server like `serve` or VS Code's "Live Server" extension.

If you have Node.js installed, you can use `serve`:
```bash
# Install serve globally (if you haven't already)
npm install -g serve

# Run the server in the project directory
serve .
```
Then, open your browser and navigate to the local address provided (usually `http://localhost:3000`).

### Option 2: Direct File Execution
You can simply double-click the `index.html` file in your file explorer to open it directly in your web browser. *(Note: Some JavaScript features might have CORS restrictions if opened directly via the `file://` protocol, so Option 1 is preferred).*

## 🎨 Theme Customization

The site uses CSS custom properties defined in `style.css` and `gap_style.css`. To alter the color scheme, locate the `:root` variables.

```css
:root {
    --primary: #6266ea; /* Primary brand color */
    --secondary: #f0f4f8; 
    --background: #ffffff;
    --text-main: #1f2937;
    /* ... */
}
```

## 📄 License

&copy; 2026 Global Academy Pathway. All Rights Reserved.
Designed by Team ProDevInfo.
