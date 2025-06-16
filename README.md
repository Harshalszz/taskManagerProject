# Task Management System

A modern task management system built with Angular, featuring real-time updates, team collaboration, and project management capabilities.

## Features

- 🔐 User Authentication & Authorization
- 📋 Task Management
- 👥 Team Collaboration
- 📊 Project Management
- 📈 Analytics Dashboard
- 🔔 Real-time Notifications
- 📱 Responsive Design

## Tech Stack

- Angular (Latest Version)
- Angular Material
- NgRx (State Management)
- RxJS
- Firebase
- Jest (Unit Testing)
- Cypress (E2E Testing)

## Prerequisites

- Node.js (v20.19 or higher)
- npm (Latest version)
- Git

## Getting Started

1. Clone the repository:
   ```bash
   git clone [your-repository-url]
   cd task-management-system
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   ng serve
   ```

4. Navigate to `http://localhost:4200/`

## Development

- `ng serve` - Start development server
- `ng build` - Build the project
- `ng test` - Run unit tests
- `ng e2e` - Run end-to-end tests
- `ng lint` - Lint the code

## Project Structure

```
src/
├── app/
│   ├── core/           # Singleton services, guards, interceptors
│   ├── shared/         # Shared components, directives, pipes
│   ├── features/       # Feature modules
│   └── store/          # NgRx store, actions, reducers
├── assets/            # Static files
└── environments/      # Environment configurations
```

## Contributing

1. Create a feature branch (`git checkout -b feature/amazing-feature`)
2. Commit your changes (`git commit -m 'feat: add amazing feature'`)
3. Push to the branch (`git push origin feature/amazing-feature`)
4. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 