# 🕶️ SpectreKit

**Stealth Components. Visible Results.**

**SpectreKit** is a performance-first, mobile-optimized component library for [Astro](https://astro.build). Built by [PHCDevworks](https://phcdevworks.com), it’s designed for elite developers who value speed, scalability, and conversion.

---

## 🚀 Features

- 🧹 Plug & play Astro components
- 🎯 Conversion-optimized layout and UI primitives
- 📱 Mobile-first, responsive out of the box
- 🎨 Token-based design (Tailwind v4 or custom variables)
- 🩶 Zero JS bloat – static, fast, and SEO-friendly
- 🔧 Developer experience first: typed, modular, maintainable
- 🛆 Easy NPM integration and versioning

---

## 📦 Install

```bash
npm install @phcdevworks/spectrekit
```

or with pnpm:

```bash
pnpm add @phcdevworks/spectrekit
```

---

## 🛠 Usage

In your Astro project:

```astro
---
import { Button, Card, Section } from '@phcdevworks/spectrekit';
---

<Section>
  <Card>
    <h2>Welcome to SpectreKit</h2>
    <p>Elite UI components built for performance.</p>
    <Button variant="primary">Deploy Now</Button>
  </Card>
</Section>
```

---

## 📚 Components

| Component    | Description                                       |
| ------------ | ------------------------------------------------- |
| `Button`     | Flexible button with variant + size options       |
| `ButtonLink` | Anchor element styled as a button                 |
| `Card`       | Clean layout block with slot support              |
| `IconBox`    | Icon with label/description, perfect for features |
| `Section`    | Wrapper with spacing + alignment control          |
| ...more      | New components added weekly                       |

> Full docs and preview site coming soon.

---

## 🎨 Theming

SpectreKit uses CSS variables and Tailwind tokens so you can easily override:

```css
:root {
  --color-primary: #00f0b5;
  --color-accent: #ff4794;
}
```

Coming soon: `spectre.config.js` for full theming control.

---

## 🥪 Dev & Contribute

```bash
git clone https://github.com/phcdevworks/spectrekit
cd spectrekit
pnpm install
pnpm dev
```

Open a PR or issue if you’ve got ideas, bug fixes, or component contributions.

---

## 🧪 Roadmap

- ***

## 🧂 License

MIT — free to use, scale, and modify.

> Built by [PHCDevworks](https://phcdevworks.com) for the next-gen web.\
> Great devs don’t waste time—they deploy with SpectreKit.
