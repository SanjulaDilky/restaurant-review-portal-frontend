# Restaurant Review Portal - Frontend

Frontend application for the **Restaurant Review Portal**, developed as part of the MSc group project.

The application allows users to browse restaurants, view restaurant information, read reviews, submit reviews, and interact with other features provided by the Restaurant Review Portal.

## Technology Stack

* React
* Next.js
* TypeScript
* CSS/Tailwind
* Node.js / npm

## Prerequisites

Before running the project, make sure the following are installed:

* Node.js
* npm
* Git

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/<YOUR-GITHUB-USERNAME>/restaurant-review-portal-frontend.git
```

### 2. Navigate to the Project

```bash
cd restaurant-review-portal-frontend
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Run the Development Server

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:3000
```

## Project Structure

```text
src/
├── app/
├── components/
│   ├── common/
│   ├── layout/
│   └── ui/
├── features/
│   ├── auth/
│   ├── restaurants/
│   ├── reviews/
│   └── users/
├── hooks/
├── services/
├── types/
├── utils/
├── constants/
└── styles/
```

## Main Features

The planned frontend features include:

* User registration and login
* Restaurant browsing
* Restaurant search and filtering
* Restaurant details
* Restaurant ratings
* View customer reviews
* Submit restaurant reviews
* User profile management
* Responsive user interface
* Integration with the Restaurant Review Portal backend API

## Available Scripts

Run the development environment:

```bash
npm run dev
```

Build the application:

```bash
npm run build
```

Run the production build:

```bash
npm start
```

Run ESLint:

```bash
npm run lint
```

## Environment Variables

Environment-specific configuration should be stored in a local `.env` file.

Example:

```env
NEXT_PUBLIC_API_BASE_URL=http://localhost:5000/api
```

Do not commit `.env` files containing sensitive or environment-specific information to GitHub.

## Backend Integration

The frontend communicates with the Restaurant Review Portal backend through REST APIs.

Local backend example:

```text
http://localhost:5000/api
```

## Git Workflow

Developers should create separate branches for features or tasks.

Example:

```bash
git checkout -b feature/restaurant-list
```

After completing a feature:

```bash
git add .
git commit -m "Add restaurant listing feature"
git push origin feature/restaurant-list
```

Changes should be reviewed before being merged into the `main` branch.

## Project Status

This project is currently under development as part of an MSc group assignment.

## Team

Developed by the Restaurant Review Portal project team.

## License

This project is developed for academic purposes.
