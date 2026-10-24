# Autopoetic Community Laboratory Landing Page

A premium, high-performance, dark-tech aesthetic landing page tailored for the **Autopoetic Community Laboratory**. Built entirely using semantic HTML5 and vanilla CSS3 utilizing modern glassmorphism design principles, responsive grids, and optimization for instant global edge deployment.

## 🚀 Live Demo
You can view the deployed version of this website here: 
👉 **[https://pages.dev](https://cloudflare.com)** *(Replace this with your actual Cloudflare Pages URL once deployed)*

## ✨ Features
- **Modern Cyber-Organic Aesthetic:** Stunning dark theme featuring dynamic neon accent glows and glassmorphism elements.
- **Ultra Lightweight Performance:** Pure Vanilla HTML & CSS structure ensuring absolute zero exterior runtime overhead and immediate loading speed.
- **Fully Responsive Architecture:** Adaptable layout grid components seamlessly adjusting across mobile, tablet, and desktop viewports.
- **Cloudflare Pages Optimized:** Pre-configured structural footprint ready for instantaneous edge network CDN deployment.
- **Premium Typography Integration:** Clean, dual-font visual hierarchy powered by Google Fonts (`Space Grotesk` & `Plus Jakarta Sans`).

## 📁 File Structure
```text
├── index.html   # Main structural content markup
├── style.css    # Core styling, layouts, variables & animations
└── README.md    # Documentation sheet
```

## ⚡ Deployment to Cloudflare Pages

This repository is completely structured for a seamless automated deployment via Cloudflare Pages.

### Method 1: Git Integration (Recommended for Auto-Updates)
1. Push this project folder to your own GitHub account.
2. Log in to the [Cloudflare Dashboard](https://cloudflare.com).
3. Navigate to **Workers & Pages** > **Create application** > **Pages** tab.
4. Click **Connect to Git** and choose this repository.
5. In the configuration stage, leave **Build command** and **Build output directory** completely blank.
6. Click **Save and Deploy**. Cloudflare will automatically build your landing page every time you push a change to GitHub!

### Method 2: Manual Direct Upload
1. Log in to your Cloudflare Dashboard.
2. Go to **Workers & Pages** > **Create application** > **Pages** > **Upload assets**.
3. Drag and drop the folder containing your `index.html` and `style.css` files.
4. Click **Deploy**.

## 🎨 Customization
To match your specific brand or project accent colors, open `style.css` and simply update the variables declared inside the `:root` pseudo-class:

```css
:root {
  --bg-dark: #080b11;        /* Primary background tone */
  --accent-glow: #3b82f6;    /* Cyber blue blur element */
  --accent-neon: #10b981;    /* Futuristic matrix green */
}
```

## 📄 License
This layout template is open-source software licensed under the [MIT License](LICENSE). Feel free to use, modify, and build upon it!
