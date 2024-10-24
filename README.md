# Planning Application

A modern task and resource planning application built with Next.js, PostgreSQL, and Vercel.

## Features

- Task Management & Planning
- Resource Allocation
- Team Collaboration
- Analytics & Reporting
- Custom Fields & Workflows

## Tech Stack

- Frontend: Next.js 14, React, TypeScript
- Styling: Tailwind CSS
- Database: PostgreSQL (Vercel Postgres)
- Authentication: NextAuth.js
- Deployment: Vercel
- CI/CD: GitLab CI

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- Git

### Installation

1. Clone the repository
```bash
git clone git@gitlab.com:your-username/planning-app.git
cd planning-app
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env.local
```

4. Run development server
```bash
npm run dev
```

## Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build production version
- `npm run start` - Start production server
- `npm run test` - Run tests
- `npm run lint` - Run linter

### Project Structure

```
planning-app/
├── src/
│   ├── app/          # Next.js app directory
│   ├── components/   # Reusable components
│   ├── lib/          # Utilities and helpers
│   └── styles/       # Global styles
├── prisma/           # Database schema
├── public/           # Static files
└── tests/           # Test files
```

## Deployment

Deployment is handled automatically through GitLab CI/CD and Vercel:

1. Push to `main` branch deploys to production
2. Create merge request for preview deployment

## Contributing

1. Create a new branch
2. Make your changes
3. Create a merge request

## License

MIT License - see LICENSE file for details
