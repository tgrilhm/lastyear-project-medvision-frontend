# MedVision Frontend

MedVision is a React-based healthcare platform frontend for patient screening, dashboards, appointments, messaging, laboratory results, authentication, and account settings.

## Stack

- React
- Vite
- Tailwind CSS
- React Router
- Vitest and Testing Library

## Requirements

- Node.js 18+
- npm

## Setup

```bash
npm install
copy .env.example .env
npm run dev
```

Open `http://localhost:5173` in your browser.

## Commands

```bash
npm run dev       # Start development server
npm run build     # Create production build
npm run preview   # Preview production build
npm run test      # Run test suite
```

## Environment

Copy `.env.example` to `.env` and set values for API, authentication, realtime messaging, and AI service integrations used by your environment. Never commit `.env` or production secrets.

## Project Structure

```text
src/
  components/    Reusable UI, layout, and auth components
  config/        Runtime configuration
  context/       Authentication, language, and realtime state
  pages/         Application screens
  services/      API and AI service clients
  tests/         Unit and component tests
```

## License

Project license and usage terms are defined by the project owner.
