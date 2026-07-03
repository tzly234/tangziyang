<p align="center">
  <img src="public/logo.svg" alt="CapsuleX Logo" width="120">
</p>

<h1 align="center">CapsuleX</h1>

<p align="center">
  A minimal, modern blog theme for Astro with capsule floating navigation.
</p>

<p align="center">
  <a href="https://github.com/wangjacks/capsule-x">GitHub</a>
</p>

---

## Features

- 🎯 **Capsule Floating Navigation** — Glassmorphism nav bar with backdrop blur
- 🌗 **Tri-State Theme** — Auto (follow device) / Light / Dark
- ⚡ **Fast** — Static generation with Astro, zero client JS by default
- 📝 **MDX Support** — Write content with Markdown + JSX components
- 🏷️ **Tag System** — Filter posts by tags
- 📱 **Responsive** — Mobile-first design
- 🔍 **Search Ready** — Pagefind integration (coming soon)
- 📊 **Mermaid Diagrams** — Render diagrams in your posts (coming soon)

## Getting Started

```bash
npm create astro@latest -- --template your-username/capsule-x
```

Or add to an existing project:

```bash
npm install capsule-x
```

## Project Structure

```
capsule-x/
├── src/
│   ├── components/       # UI components
│   ├── layouts/          # Page layouts
│   ├── content/
│   │   └── blog/         # Blog posts (Markdown)
│   ├── pages/            # Route pages
│   └── styles/           # Global CSS
├── public/               # Static assets
└── docs/                 # Project documentation
```

## Configuration

Create `src/config.ts` to customize your site:

```ts
export const siteConfig = {
  title: 'Your Blog',
  description: 'Your blog description',
  author: 'Your Name',
  // ...
};
```

## Development

```bash
npm run dev       # Start dev server
npm run build     # Build for production
npm run preview   # Preview production build
```

## License

[Apache 2.0](LICENSE)
