# ProspectIQ

AI-powered prospect analysis and lead qualification platform.

## Overview

ProspectIQ helps sales and marketing teams analyze prospects and qualify leads using AI-driven insights. The platform supports CSV data import, interactive data visualization, and intelligent lead scoring to streamline your prospecting workflow.

## Tech Stack

| Category | Technologies |
|---|---|
| **Frontend** | React 18, TypeScript, Vite |
| **UI Components** | shadcn-ui, Radix UI, Lucide Icons |
| **Styling** | Tailwind CSS, Class Variance Authority |
| **Routing** | React Router DOM |
| **State & Data Fetching** | TanStack React Query |
| **Forms & Validation** | React Hook Form, Zod |
| **Data Processing** | PapaParse (CSV), Recharts (visualization), date-fns |
| **Backend** | Supabase (database, auth, APIs) |
| **Theming** | next-themes (dark mode support) |

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher) &mdash; install via [nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
- npm (included with Node.js) or [Bun](https://bun.sh/)

### Installation

```sh
# Clone the repository
git clone https://github.com/GetRich235/Prospect_Pain.git

# Navigate to the project directory
cd Prospect_Pain

# Install dependencies
npm install
```

### Development

```sh
# Start the development server (runs on http://localhost:8080)
npm run dev
```

### Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the Vite dev server with hot reload |
| `npm run build` | Create a production build |
| `npm run build:dev` | Create a development-mode build |
| `npm run lint` | Run ESLint across the project |
| `npm run preview` | Preview the production build locally |

## Project Structure

```
├── index.html              # HTML entry point
├── package.json            # Dependencies and scripts
├── vite.config.ts          # Vite build configuration
├── tailwind.config.ts      # Tailwind CSS customization (ProspectIQ theme)
├── tsconfig.json           # TypeScript configuration
├── tsconfig.app.json       # TypeScript app config (ES2020 target)
├── tsconfig.node.json      # TypeScript build tools config
├── components.json         # shadcn-ui component configuration
├── eslint.config.js        # ESLint rules
├── postcss.config.js       # PostCSS plugins
└── src/                    # Application source code
    └── main.tsx            # App entry point
```

## Key Features

- **Prospect Analysis** &mdash; Analyze and score leads with AI-powered insights
- **CSV Import** &mdash; Bulk import prospect data via CSV file upload
- **Data Visualization** &mdash; Interactive charts and dashboards powered by Recharts
- **Lead Qualification** &mdash; Automated lead scoring and qualification workflows
- **Dark Mode** &mdash; Full light/dark theme support
- **Responsive Design** &mdash; Works across desktop and mobile devices

## Configuration

### Path Aliases

The project uses `@/` as a path alias pointing to the `src/` directory, configured in both `vite.config.ts` and `tsconfig.app.json`.

### Supabase

The backend is powered by Supabase. Configure your Supabase project credentials via environment variables:

```
VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
```

## Deployment

### Via Lovable

Open the [Lovable project](https://lovable.dev/projects/f901fd94-d7e0-49a8-98f1-a80a0438596d) and click **Share > Publish**.

### Custom Domain

To connect a custom domain, navigate to **Project > Settings > Domains** and click **Connect Domain**. See [Setting up a custom domain](https://docs.lovable.dev/tips-tricks/custom-domain#step-by-step-guide) for details.

### Manual Build

```sh
npm run build
```

The production-ready assets will be output to the `dist/` directory, which can be deployed to any static hosting provider.

## Development Workflow

This project is integrated with the [Lovable](https://lovable.dev) platform. You can edit the code in any of the following ways:

- **Lovable Platform** &mdash; Prompt-based editing at the [project dashboard](https://lovable.dev/projects/f901fd94-d7e0-49a8-98f1-a80a0438596d)
- **Local IDE** &mdash; Clone and push changes; they sync with Lovable automatically
- **GitHub** &mdash; Edit files directly via the GitHub web editor
- **GitHub Codespaces** &mdash; Launch a cloud development environment from the repository

## License

This project is private.
