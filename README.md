# Release Management System

This repository contains a minimal setup for a release management system using **NestJS** for the backend and **Vite** with **React**, **Tailwind CSS**, and **shadcn/ui** for the frontend.

## Structure

- `backend/` – NestJS application
- `frontend/` – React application bootstrapped with Vite

## Development

Because dependencies are not installed in this environment, run the following commands locally after cloning the repository:

```bash
# install backend dependencies
cd backend && npm install
# install the default Express adapter
npm install @nestjs/platform-express
# run the backend
npm start
```

```bash
# in another terminal, install frontend dependencies
cd frontend && npm install
# start the frontend in dev mode
npm run dev
```

The frontend expects Tailwind and shadcn/ui packages. Install them as needed using npm.
