# Student Result Management System

A web application for managing student results, grades, analytics, and reports for J. R. Preparatory School. Built with React, TypeScript, Vite, and Supabase.

## Features

- Student management: Add, edit, and view student details
- Grade entry: Record and manage grades for assignments, half-yearly, and final exams
- Report generation: Generate student result reports
- Analytics: Visualize student performance
- Admin panel: Manage teachers, subjects, and classes
- Authentication: Secure access for admins and teachers
- Responsive UI with Tailwind CSS

## Tech Stack

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Supabase](https://supabase.com/) (backend)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide React](https://lucide.dev/)
- [Recharts](https://recharts.org/)

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm

### Installation

```sh
npm install
```

### Development

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build

```sh
npm run build
```

### Preview

```sh
npm run preview
```

## Project Structure

```
src/
  App.tsx                # Main app component
  components/            # UI components (Auth, Dashboard, Grades, Reports, etc.)
  contexts/              # React context providers (Auth, Data)
  data/                  # Mock data
  lib/                   # Supabase client
  types/                 # TypeScript types
  utils/                 # Utility functions
public/
  _redirects             # Netlify redirects
supabase/
  migrations/            # Database migrations
```

## Environment Variables

Create a `.env` file for Supabase and other secrets.

## Deployment

Supports deployment on Netlify (see `netlify.toml`).
