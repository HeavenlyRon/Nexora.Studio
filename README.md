# Nexora Studio

Nexora Studio is a premium, service-focused web development landing page built to represent a modern digital studio. It is designed to present a strong brand, showcase services clearly, collect project inquiries, and provide a hidden admin dashboard for managing contact submissions.

## What This Project Is For

This project is meant to act as a conversion-focused business website for a web development brand. It is useful for:

- Presenting a professional studio identity
- Showing core services such as full-stack web development, SaaS builds, landing pages, SEO, and custom web solutions
- Collecting contact messages from potential clients
- Managing inquiries through a private admin dashboard
- Serving as a deployment-ready frontend for Cloudflare Pages

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Framer Motion
- Three.js with React Three Fiber
- Convex for backend data and contact storage
- Lucide React for icons

## Key Features

- Responsive landing page with desktop, tablet, and mobile layouts
- Animated hero section with rotating headline text
- Service cards and branded about section
- Interactive 3D robots in the About and Contact sections
- Contact form connected to Convex
- Hidden admin dashboard at `/admin`
- Delete confirmation modal for admin message management
- Custom favicon, brand assets, and OG image
- Cloudflare Pages friendly build output

## Project Structure

- `src/` - Main React app and UI components
- `convex/` - Backend schema and contact message functions
- `public/` - Static assets, logo files, favicon, OG image, and redirect rules
- `supabase/` - Old migration files kept for reference

## Running Locally

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

Run type checking:

```bash
npm run typecheck
```

## Environment Variables

This project uses environment files for local development and backend connection settings.

- `.env`
- `.env.local`

Important: these files are intentionally included in the repository because you requested them to be committed before making the repo private later.

## Deployment

The project is set up to deploy cleanly on Cloudflare Pages.

Recommended settings:

- Build command: `npm run build`
- Build output directory: `dist`
- Base path: `/`

The repository also includes `public/_redirects` so direct routes like `/admin` work correctly on static hosting.

## Admin Dashboard

The admin dashboard is available at `/admin`.

It is used to:

- Sign in with the admin key
- View contact submissions
- Delete messages from the dashboard and database
- Return back to the home page from the admin screen

## Notes

- The site is branded as Nexora Studio, not a personal portfolio.
- Contact submissions are stored through Convex.
- The site includes custom OG and brand assets for sharing and production deployment.

## License

No license has been specified for this project.

