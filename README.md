# My Docs

Built with [Viabl](https://viabl.dev).

## Getting Started

Install the Viabl CLI:

```bash
npm install -g viabl
```

Start the local development server:

```bash
viabl dev
```

Your docs will be available at `http://localhost:7777`.

---

## Building for Production

Build a production-ready bundle:

```bash
viabl build
```

Run the production build:

```bash
PORT=7777 node .viabl-out/start.js
```

---

## Project Structure

```
.
├── docs.json          # site configuration — navigation, branding, colors
├── docs/              # your documentation pages (.mdx files)
├── api-reference/     # API reference pages
├── images/            # images used in your docs
├── logo/              # logo files for light and dark mode
├── favicon.png        # site favicon
└── openapi.yaml       # OpenAPI spec for API reference pages
```

---

## Documentation

Full documentation on how to configure your project, write pages, and deploy is available at [docs.viabl.dev](https://docs.viabl.dev).
