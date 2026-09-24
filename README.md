# 💍 Kapin Kumar Patel — Matrimonial & Professional Biodata Web App

A modern, executive-grade, fully animated, responsive Matrimonial & Professional Biodata web application.

---

## 🚀 How to Host on Vercel (100% Free)

You can host this website on Vercel in less than 2 minutes using either of these two methods:

### Method 1: Push to GitHub & Import into Vercel (Recommended)
1. Initialize git in this folder and push to a GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Kapin Patel Biodata"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/kapin-biodata.git
   git push -u origin main
   ```
2. Go to **[vercel.com](https://vercel.com)** and sign in with GitHub.
3. Click **"Add New..."** ➔ **"Project"** ➔ Select your `kapin-biodata` repository.
4. Click **"Deploy"** (Leave all settings as default static project).
5. Done! Your site will be live instantly with a free `.vercel.app` domain and free SSL certificate!

### Method 2: Deploy via Vercel CLI
1. Open PowerShell / Terminal in this `d:\Biodata` folder.
2. Run:
   ```bash
   npx vercel
   ```
3. Follow the quick terminal prompts (log in with email/GitHub, select default options).
4. For production deployment:
   ```bash
   npx vercel --prod
   ```

---

## 📸 How to Add New Images to the Gallery

The system is built to make adding photos super easy:

1. **Place your new image** in the `assets/images/` folder (e.g. `assets/images/my_new_photo.jpg`).
2. Open `index.html` (and `Index.html`), find the `GALLERY_IMAGES` array around line 850:
   ```javascript
   const GALLERY_IMAGES = [
     {
       src: "assets/images/my_new_photo.jpg",
       caption: "Trip to Goa with Family",
       category: "travel" // options: 'travel', 'nature', 'village', or custom
     },
     // other images...
   ];
   ```
3. **Instant Browser Preview**: You can also click the **`+ Preview Local Image`** button directly in the photo gallery tab to test any photo on your computer before committing!

---

## ✨ Features

- **Hero Profile Cutout**: High-resolution floating transparent portrait with ambient glowing portal halo.
- **Rich Micro-Animations**: Floating particles, ambient light pulses, smooth page transitions, 3D card tilt & hover effects.
- **Dynamic Photo Gallery**: Responsive grid, category filters, full-screen lightbox with next/prev navigation, touch swipe & ESC close.
- **One-Tap WhatsApp & Call**: Directly initiates WhatsApp with pre-composed respectful matrimonial inquiry message.
- **Print & PDF Mode**: Specially formatted `@media print` layout so clicking "Print / Save PDF" produces a clean, crisp 2-page document for families.
- **Full Mobile Responsiveness**: Bottom action bar for quick WhatsApp, Call, and PDF access on phones.
