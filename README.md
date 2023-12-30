## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load customs Google Fonts.

## Libraries this Template uses

### Tailwind CSS

Tailwind CSS is a utility-first CSS framework that empowers developers to rapidly build modern, responsive web interfaces.

To see more about the library and how to use it check the official documentation below:

[Tailwind Docs](https://tailwindcss.com)

### React Icons

Include popular icons in your React projects easily with react-icons, which utilizes ES6 imports that allows you to include only the icons that your project is using.

Check and see how to use more than **40k** icons in your project:

[React Icons Doc](https://react-icons.github.io/react-icons/)

Uninstalling:

```bash
npm uninstall react-icons
```

### CLSX and Tailwind-Merge

These two libraries allow constructing `classNames` strings conditionally by different ways and without style conflicts when merging the Tailwind CSS classes.

Combining these libraries into one function gives us the best of two worlds, and you can find this function in `src/services/utils/className.ts` as:

```bash
import { twMerge } from 'tailwind-merge'
import clsx, { ClassValue } from 'clsx'

export function cn(...inputs: ClassValue[]) {
  return twMerge(clsx(...inputs))
}
```

You can find full documentation of the libraries in the following links:

[clsx](https://github.com/lukeed/clsx)

[tailwind-merge](https://github.com/dcastil/tailwind-merge)

### Framer Motion

Complete documentation of the Framer Motion animation library. A production-ready motion library for React.

Framer motion helps developer in animating components and sections easily and in a rapid way, granting agility in developing, it's as easy as `import motion from "framer-motion"` and start creating an animated component.

See more of the library in the official documentation:

[Framer Motion Docs](https://www.framer.com/motion/)

Uninstalling:

```bash
npm uninstall framer-motion
```
