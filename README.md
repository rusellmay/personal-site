# personal-site

My personal site.

## Prerequisites

- Node.js 26 LTS and npm
- Docker (optional)

## Installation

```bash
npm install
```

## Usage

### Run locally with npm

```bash
npm run dev      # development server at http://localhost:4321
npm run build    # static build into dist/
npm run preview  # serve the production build locally
```

### Run with Docker

```bash
docker compose up --build -d   # site at http://localhost:8080
docker compose down            # stop the container
```

Or build and run the image directly:

```bash
docker build -t personal-site .
docker run --rm -p 8080:80 personal-site
```
