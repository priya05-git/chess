# Chess Game

A modern, interactive chess game built with React and Vite. Features smooth animations, responsive design, and an intuitive user interface.

![Chess Game Screenshot](public/images/king.png)

## Features

- **Interactive Chess Board**: Full chess game with piece movement and rules validation
- **Smooth Animations**: Powered by GSAP for fluid piece movements and transitions
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Parallax Effects**: Enhanced visual experience with tilt effects on interactive elements
- **Smooth Scrolling**: Lenis library for buttery smooth scrolling experience

## Technologies Used

- **React 19**: Latest React with modern hooks and features
- **Vite**: Fast build tool and development server
- **GSAP**: High-performance animation library
- **Lenis**: Smooth scrolling library
- **React Parallax Tilt**: 3D tilt effects for interactive components
- **ESLint**: Code linting and formatting

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd chess/vite-project
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint for code quality checks

## Project Structure

```
src/
├── components/
│   ├── Hero.jsx & Hero.css    # Landing page hero section
│   └── Navbar.jsx & Navbar.css # Navigation component
├── assets/                    # Static assets
├── App.jsx                    # Main application component
├── App.css                    # Global styles
├── main.jsx                   # Application entry point
└── index.css                  # Base styles
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Chess piece assets and game logic inspired by classic chess implementations
- UI components built with modern React patterns
- Animation effects powered by GSAP and Lenis libraries
