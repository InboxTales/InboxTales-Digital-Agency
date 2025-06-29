# InboxTales – Digital Agency Website

A modern, responsive marketing/agency website built with **Next.js 14**, **TypeScript**, **Bootstrap 5** and **Framer-Motion**. The project showcases reusable React components, smooth animations and data-driven sections that can be easily adapted for any creative agency, portfolio or SaaS landing page.

---

## ✨ Features

- **Next.js App Router** (app/ directory) with server–side rendering and route segments.
- **TypeScript** for type-safe components and utilities.
- **Bootstrap 5** utility classes plus custom SCSS for rapid styling.
- **Framer Motion** & **React Scroll** for scroll-triggered animations and smooth section navigation.
- **Responsive design** – looks great on mobile, tablet and desktop.
- Data stored in simple TypeScript objects under `src/utils/fackData` – update content without touching components.
- Optimised images served from the `public/` directory via `next/image`.

---

## 🛠️ Tech Stack

| Purpose            | Library / Tool |
|--------------------|----------------|
| Framework          | Next.js 14 |
| Language           | TypeScript 5 |
| Styling            | Bootstrap 5, custom CSS/SCSS |
| Animation          | Framer Motion, React Scroll |
| Carousel / Slider  | Swiper.js |
| Misc UI            | React Fast Marquee, React Photo View |

---

## 🚀 Getting Started

### Prerequisites

• **Node.js** ≥ 18 (LTS recommended)  
• **npm** ≥ 9 (comes with Node) or **pnpm**/**yarn** if you prefer

### Installation

```bash
# clone the repo
$ git clone https://github.com/InboxTales/InboxTales-Digital-Agency.git
$ cd InboxTales-Digital-Agency

# install dependencies
$ npm install        # or yarn install / pnpm install
```

### Development

```bash
# start the local dev server at http://localhost:3000
$ npm run dev
```
The page will hot-reload when you edit files.

### Production build

```bash
# generate an optimised production build
$ npm run build

# start the production server
$ npm run start
```

---

## 📂 Project Structure

```
├── public/                 # Static assets (images, icons, …)
├── src/
│   ├── app/                # Next.js App Router entrypoints
│   │   ├── layout.tsx      # Root layout & metadata
│   │   └── page.tsx        # Landing page
│   ├── components/         # Reusable UI & section components
│   ├── utils/
│   │   ├── animations/     # Reusable Framer-Motion variants
│   │   └── fackData/       # Data objects powering each section
│   └── assets/             # Stylesheets & webfonts
└── tsconfig.json           # TypeScript configuration
```

---

## 🖥️ Deploying

The site can be deployed to any Node-compatible host (Vercel recommended).

1. Set the environment variable `NODE_ENV=production`.
2. Run `npm run build` to generate the `.next` output.
3. Start with `npm run start` (Next.js will listen on port 3000 by default).

For one-click deployment, press the **Deploy to Vercel** button in the repository or follow the [Next.js deployment docs](https://nextjs.org/docs/app/building-your-application/deploying).

---

## 🤝 Contributing

Pull requests are welcome! Open an issue first to discuss any major changes.

1. Fork the repo & create your branch: `git checkout -b feature/awesome`  
2. Commit your changes: `git commit -m "feat: add awesome thing"`  
3. Push to the branch: `git push origin feature/awesome`  
4. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
