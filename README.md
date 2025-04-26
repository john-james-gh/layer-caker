# 🍰 Layer Caker

**Layer Caker** is a content-driven web app built with **Next.js** and **Sanity** and deployed via **Vercel**. This project follows the official [Sanity + Next.js tutorial](https://www.sanity.io/learn/course/content-driven-web-application-foundations/building-a-content-editable-website) to provide a smooth foundation for fast, flexible content delivery and collaborative editing.

---

## 🛠️ Tech Stack

- 🖼️ [Next.js](https://nextjs.org/) — React-based framework for server-rendered apps
- 🧠 [Sanity.io](https://www.sanity.io/) — Headless CMS with real-time collaboration
- 🟢 [Vercel](https://vercel.com/) — Seamless deployment and hosting
- 🛠️ TypeScript — Strong typing for safety and DX
- 💅 ESLint + Prettier — Consistent code style
- 📦 pnpm — Fast, efficient package management
- 📸 Integrated image handling via Sanity and Next.js
- 📅 [dayjs](https://day.js.org/) — Lightweight date formatting

---

## 🚀 Getting Started

### 📥 Install dependencies
```bash
pnpm install
```

### 🌎 Start the dev server
```bash
pnpm dev
```

### 🧪 Sanity Studio setup (optional)
If you're using the paired Sanity Studio:
```bash
pnpm sanity start
```

---

## 📂 Project Structure

```
├── public/                # Static assets
├── src/                   # Application source code
├── sanity.config.ts       # Sanity client configuration
├── sanity.cli.ts          # Sanity CLI setup
├── sanity-typegen.json    # Sanity type generation config
├── next.config.ts         # Next.js config
├── tsconfig.json          # TypeScript config
├── eslint.config.mjs      # ESLint config
├── postcss.config.mjs     # PostCSS config
├── pnpm-lock.yaml         # Lockfile for reproducible builds
```

---

## 🧹 Available Scripts

| Script                 | Purpose                                 |
|------------------------|-----------------------------------------|
| `pnpm dev`             | Start Next.js dev server                |
| `pnpm build`           | Build the Next.js app for production    |
| `pnpm lint`            | Run ESLint on the project               |
| `pnpm format`          | Format the codebase with Prettier       |
| `pnpm sanity start`    | Start the Sanity Studio (if included)   |

---

## 🌐 Deployment

Deployed with [Vercel](https://vercel.com/) 🌩️  
Production URL: [layer-caker-peach.vercel.app](https://layer-caker-peach.vercel.app)

---

## 📜 License

MIT @ John James

---

> _"Horses don’t stop, they keep goin’."_ 🐎  
