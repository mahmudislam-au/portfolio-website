# Task List: Scrollytelling Personal Portfolio

- [ ] **1. Project Setup**
  - [x] Scaffold Next.js 14 App Router project in `c:/Users/mahmu/Downloads/portfolio`
  - [x] Install dependencies (`framer-motion`, `lucide-react`, `clsx`, `tailwind-merge`)
  - [x] Copy image sequence to `public/sequence/`

- [x] **2. Core Components**
  - [x] Implement `ScrollyCanvas.tsx` (Canvas image sequence rendering, preloading, Framer Motion useScroll tied to 500vh container)
  - [x] Implement `Overlay.tsx` (Parallax text sections over the sequence)
  - [x] Implement `Projects.tsx` (Glassmorphism project grid below sequence)

- [x] **3. Assembly & Styling**
  - [x] Update `app/globals.css` with #121212 background and clean font
  - [x] Update `app/page.tsx` to compose ScrollyCanvas, Overlay, and Projects

- [x] **4. Verification**
  - [x] Run Next.js dev server and manually test the scroll interactions on desktop and mobile.

- [x] **5. Business/Data Analyst Content Refactor**
  - [x] Update `app/layout.tsx` metadata to "Mahmud Islam | Business & Data Analyst Portfolio"
  - [x] Implement `Hero.tsx` with primary intro and CTA (using Overlay+ScrollyCanvas)
  - [x] Implement `Toolkit.tsx` with two-column skill grid
  - [x] Update `Projects.tsx` texts for Vision Property & Finance
  - [x] Implement `Experience.tsx` timeline and `Footer.tsx`
  - [x] Update `app/page.tsx` assembly

- [x] **6. Deployment**
  - [x] Generate temporary public tunnel for immediate internet access
