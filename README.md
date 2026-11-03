# GharPadharo Blog Platform

A modern, SEO-optimized blog platform featuring a public-facing reader experience and an administrative dashboard for content creation and management.

---

## Project Structure

```text
Gharpadharo-blog-NEW/
├── frontend/       # Next.js App Router, JavaScript, Tailwind CSS, shadcn/ui
├── backend/        # Node.js, Express.js, MongoDB, Mongoose API server
├── docs/           # Documentation, architecture specs, and guides
├── .gitignore      # Root Git ignore configuration
└── README.md       # Root project documentation
```

### Folder Breakdown

- **`frontend/`**: Contains the client application built with Next.js (App Router, JavaScript), styled with Tailwind CSS and shadcn/ui components. Houses both the public blog interface and the admin dashboard.
- **`backend/`**: Contains the Node.js/Express.js REST API, MongoDB/Mongoose models, authentication, and Cloudinary media upload integration.
- **`docs/`**: Holds technical documentation, API contracts, deployment instructions, and architecture diagrams.

---

## Technology Stack

- **Frontend Framework**: [Next.js](https://nextjs.org/) (App Router, JavaScript)
- **Styling & UI**: [Tailwind CSS](https://tailwindcss.com/) & [shadcn/ui](https://ui.shadcn.com/)
- **Backend Runtime**: [Node.js](https://nodejs.org/) & [Express.js](https://expressjs.com/)
- **Database & ORM**: [MongoDB](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/)
- **Rich Text Editor**: [Trix Editor](https://trix-editor.org/) (free and open-source)
- **Media Management**: [Cloudinary](https://cloudinary.com/) (image uploads and optimization)
- **SEO Architecture**: Dynamic metadata, Open Graph tags, sitemaps, JSON-LD structured data, and server-rendered articles

---

## Getting Started

### Prerequisites

- Node.js (v18.x or later recommended)
- npm, yarn, or pnpm
- MongoDB instance (local or MongoDB Atlas)
- Cloudinary account credentials

### Development Workflow

1. Configure environment variables in `frontend/` and `backend/`.
2. Install dependencies independently in each folder:
   - `cd frontend && npm install`
   - `cd backend && npm install`
3. Run the development servers:
   - Frontend: `npm run dev` (runs on `http://localhost:3000`)
   - Backend: `npm run dev` (runs on `http://localhost:5000`)
