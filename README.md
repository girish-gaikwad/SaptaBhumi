# SaptaBhumi

[Live Site](https://saptabhumi.vercel.app)

## Overview
SaptaBhumi is a modern web platform dedicated to preserving, showcasing, and promoting the rich artisanal heritage of India, with a special focus on Northeast Indian crafts. The platform bridges traditional craftsmanship with contemporary technology, offering a curated marketplace, educational resources, AI-powered tools, and a vibrant community for artisans, collectors, and enthusiasts.

## Vision & Philosophy
Our mission is to empower artisans, celebrate cultural heritage, and connect global audiences with authentic, handcrafted products. We believe in:
- **Sustainable Craftsmanship:** Supporting traditional methods and eco-friendly materials.
- **Community Empowerment:** Fostering a collaborative artisan and customer community.
- **Innovation:** Leveraging AI and modern web technologies to enhance discovery and commerce.

## Live Demo
Visit the live platform: [https://saptabhumi.vercel.app](https://saptabhumi.vercel.app)

## Features
### 🏺 Products Marketplace
- Curated collection of antique and handcrafted artifacts (pottery, jewelry, textiles, art, etc.).
- Advanced filtering by category, period, and price.
- Detailed product pages with history, materials, and artisan stories.

### 🤖 AI-Assisted E-Commerce
- AI-powered product detail generation for sellers.
- Smart upload and categorization tools.
- Dashboard with product stats and sales insights.

### 🎓 Courses & Workshops
- Online courses on pottery, weaving, sculpting, and more.
- Multilingual support (Assamese, Bodo, Manipuri, etc.).
- Workshop event listings and reservation system.

### 🏛️ Community Forum
- Q&A and discussion board for customers, artisans, and businesses.
- Real-time notifications, likes, replies, and bookmarking.
- Verified seller/admin responses and business support.

### 🖼️ Gallery
- Visual showcase of unique handcrafted pieces and award-winning collections.
- Bento-style grid for immersive browsing.

### 📞 Contact & Support
- Direct contact form for queries and support.
- Business hours, location, and multiple contact channels.

## Technical Architecture
- **Framework:** Next.js 15 (App Router, TypeScript)
- **Styling:** Tailwind CSS, custom themes, Framer Motion for animations
- **UI Components:** shadcn/ui, Radix UI, Lucide Icons
- **State & Data:** React hooks, local state (demo), extensible for backend integration
- **AI Integration:** Simulated AI product detail generation (ready for API integration)
- **Image Handling:** next/image for optimized media

## Project Structure
```
SaptaBhumi/
├── src/
│   ├── app/
│   │   ├── components/      # Reusable UI and feature components
│   │   ├── products/        # Marketplace page
│   │   ├── ai-com/          # AI commerce tools
│   │   ├── courses/         # Courses and workshops
│   │   ├── community-forum/ # Forum and Q&A
│   │   ├── contact/         # Contact page
│   │   └── ...
│   ├── components/ui/       # UI primitives (button, card, etc.)
│   └── lib/                 # Utilities
├── public/                  # Images and static assets
├── tailwind.config.ts       # Tailwind CSS config
├── package.json             # Dependencies and scripts
└── ...
```

## Getting Started
1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd SaptaBhumi
   ```
2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Run the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) to view the app.

## Deployment
- Deployed on [Vercel](https://vercel.com/)
- Production: [https://saptabhumi.vercel.app](https://saptabhumi.vercel.app)

## Contribution Guidelines
We welcome contributions! Please open issues or pull requests for improvements, bug fixes, or new features. For major changes, discuss them via an issue first.

## Contact & Support
- **Email:** r.dineshdinz12@gmail.com


## Credits & Acknowledgements
- Artisans and creators featured on SaptaBhumi
- Open source libraries: Next.js, Tailwind CSS, shadcn/ui, Framer Motion, Lucide Icons, Radix UI
- [Vercel](https://vercel.com/) for hosting

---
SaptaBhumi © 2025. All rights reserved.
