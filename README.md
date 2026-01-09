# Opinion Board

A React application for collecting and displaying user opinions, built with modern web technologies.

## Features

- Submit new opinions with form actions
- Display list of submitted opinions
- Responsive design with React components
- Context-based state management for opinions

## Tech Stack

- **Frontend**: React 19, Vite
- **Backend**: Node.js with JSON Server
- **Development**: ESLint, Vite plugins

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd react-form-actions-advance-demo
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Install backend dependencies:
   ```bash
   cd backend
   npm install
   cd ..
   ```

## Usage

1. Start the backend server:

   ```bash
   cd backend
   npm start
   ```

2. In a new terminal, start the frontend development server:

   ```bash
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run lint` - Run ESLint for code quality checks
- `npm run preview` - Preview the production build locally

## Project Structure

```
src/
├── components/
│   ├── Header.jsx
│   ├── NewOpinion.jsx
│   ├── Opinion.jsx
│   ├── Opinions.jsx
│   └── Submit.jsx
├── store/
│   └── opinions-context.jsx
├── App.jsx
└── main.jsx

backend/
├── app.js
├── db.json
└── package.json
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## License

This project is private and not licensed for public use.
