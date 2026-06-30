# 💈 Barber Booking

A full-stack web application for managing and booking barber appointments online.

**Live Demo:** [https://barber-booking-dega-tech.vercel.app](https://barber-booking-dega-tech.vercel.app)

## What This Is

Barber Booking is a modern appointment booking system built with a React frontend and Express backend. Users can browse services, check availability, and book appointments with their preferred barbers. This project is developed and maintained by [Dega-Tech](https://github.com/Dega-Tech).

## Stack

- **Frontend:** React 19 + Vite + JavaScript
- **Backend:** Node.js + Express 5 + JavaScript
- **Styling:** CSS3
- **Build Tool:** Vite with Hot Module Reloading (HMR)
- **Runtime:** Node.js (backend), Modern browsers (frontend)
- **Deployment:** Vercel (frontend)

## Repository Structure

```
barber-booking/
├── frontend/                           React + Vite frontend application
│   ├── src/
│   │   ├── App.jsx                    Main React component
│   │   ├── App.css                    App styling
│   │   ├── main.jsx                   React entry point
│   │   ├── index.css                  Global styles
│   │   └── assets/                    Static assets
│   │       ├── hero.png               Hero image
│   │       ├── react.svg              React logo
│   │       └── vite.svg               Vite logo
│   ├── public/                        Public static files
│   │   ├── favicon.svg                Favicon
│   │   └── icons.svg                  Icon set
│   ├── vite.config.js                 Vite configuration
│   ├── eslint.config.js               ESLint configuration
│   ├── index.html                     HTML entry point
│   ├── package.json                   Frontend dependencies
│   ├── package-lock.json              Dependency lock file
│   └── .gitignore                     Git ignore rules
│
├── backend/                            Express.js backend API
│   ├── index.js                       Server entry point
│   ├── package.json                   Backend dependencies
│   └── package-lock.json              Dependency lock file
│
├── .github/
│   └── CODEOWNERS                     PR review assignments
├── LICENSE                             Proprietary License
├── .gitignore                          Git ignore rules
└── README.md                           This file
```

## How It Works

1. **Frontend (React):** Built with Vite for fast development and optimal production bundles. The React app renders the booking interface and communicates with the backend API.

2. **Backend (Express):** Node.js server handling API requests, business logic, and data operations. Configured with CORS support for frontend communication.

3. **Communication:** The frontend makes HTTP requests to the backend API (default: `http://localhost:5000`).

## Getting Started

### Prerequisites

- Node.js 16+ and npm installed
- Git for cloning the repository

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Dega-Tech/barber-booking.git
   cd barber-booking
   ```

### Frontend Setup

2. **Install frontend dependencies:**
   ```bash
   cd frontend
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   The frontend will be available at `http://localhost:5173` (Vite default)

4. **Build for production:**
   ```bash
   npm run build
   ```

5. **Preview production build:**
   ```bash
   npm run preview
   ```

6. **Run linting:**
   ```bash
   npm run lint
   ```

### Backend Setup

2. **Install backend dependencies:**
   ```bash
   cd backend
   npm install
   ```

3. **Create `.env` file (in backend directory):**
   ```
   PORT=5000
   ```

4. **Start the backend server:**
   ```bash
   npm start
   ```
   The API will run on `http://localhost:5000`

### Running Both Together

From the root directory, you can start both services:
- Open one terminal and run `cd frontend && npm run dev`
- Open another terminal and run `cd backend && npm start`

## Contributing

We welcome contributions! Please follow these guidelines:

### Code Ownership

This project uses CODEOWNERS for PR reviews:
- **Frontend** (`/frontend/`): [@malchiel-d](https://github.com/malchiel-d)
- **Backend** (`/backend/`): [@mrfurr](https://github.com/mrfurr)

### How to Contribute

1. **Create a new branch** for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

2. **Make your changes** in the appropriate directory (frontend or backend)

3. **Follow the code style:**
   - Frontend: Run `npm run lint` to check ESLint rules
   - Use consistent formatting and naming conventions
   - Write clear commit messages

4. **Test your changes:**
   - Frontend: Verify the app runs with `npm run dev` and build succeeds with `npm run build`
   - Backend: Ensure the server starts without errors

5. **Commit your changes:**
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```
   Use conventional commits: `feat:`, `fix:`, `docs:`, `style:`, `refactor:`, `test:`, `chore:`

6. **Push to your branch:**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request:**
   - Go to [https://github.com/Dega-Tech/barber-booking/pulls](https://github.com/Dega-Tech/barber-booking/pulls)
   - Click "New Pull Request"
   - Select your branch and provide a clear description
   - The appropriate code owner will review your PR based on which files you changed
   - Address any requested changes

8. **PR Requirements:**
   - Your code must follow the project's linting rules
   - Frontend PRs must have approval from [@malchiel-d](https://github.com/malchiel-d)
   - Backend PRs must have approval from [@mrfurr](https://github.com/mrfurr)
   - Ensure your branch is up-to-date with `main` before merging

### Setting Up Your Development Environment

1. Install Node.js from [nodejs.org](https://nodejs.org/)
2. Clone the repo and navigate to the project
3. For frontend development: `cd frontend && npm install && npm run dev`
4. For backend development: `cd backend && npm install && npm start`
5. Create a feature branch and start contributing!

## License

This project is licensed under a **Proprietary License**. See the [LICENSE](LICENSE) file for full details.

All rights, title, and interest in the Software remain with Dega-Tech. For commercial use or licensing inquiries, contact the repository owner.

## Support & Issues

- **Report bugs:** [GitHub Issues](https://github.com/Dega-Tech/barber-booking/issues)
- **Discussions:** Use [GitHub Discussions](https://github.com/Dega-Tech/barber-booking/discussions) for questions
- **Wiki:** Check the [GitHub Wiki](https://github.com/Dega-Tech/barber-booking/wiki) for additional documentation

## Team

- **Organization:** [Dega-Tech](https://github.com/Dega-Tech)
- **Frontend Owner:** [@malchiel-d](https://github.com/malchiel-d)
- **Backend Owner:** [@mrfurr](https://github.com/mrfurr)

---

Made with ❤️ by [Dega-Tech](https://github.com/Dega-Tech)
