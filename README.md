# nagarjunac.dev

My personal site and blog — a place to share technical writing, code snippets, and notes from my certification journey.

🔗 **Live at [nagarjunac.dev](https://nagarjunac.dev)**

## Tech Stack

- **[Astro](https://astro.build)** — content-focused web framework
- **[Tailwind CSS](https://tailwindcss.com)** — utility-first styling
- **TypeScript** — type safety
- **[Vercel](https://vercel.com)** — hosting and deployment
- **[Cloudflare](https://cloudflare.com)** — domain registrar and DNS

## Features

- Light / dark / system theme toggle with no flash on load
- Responsive, content-first design
- Blog powered by Astro content collections
- Fast by default — minimal JavaScript shipped to the browser

## Running Locally

```bash
# Clone the repo
git clone https://github.com/nchamid/nagarjunac-dev.git
cd nagarjunac-dev

# Install dependencies
npm install

# Start the dev server
npm run dev
```

The site will be available at `http://localhost:4321`.

## Commands

| Command           | Action                                       |
| ----------------- | -------------------------------------------- |
| `npm install`     | Install dependencies                         |
| `npm run dev`     | Start local dev server at `localhost:4321`   |
| `npm run build`   | Build the production site to `./dist/`       |
| `npm run preview` | Preview the build locally before deploying   |

## License

This project is open source and available under the [MIT License](LICENSE).
