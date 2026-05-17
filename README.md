# Truck Safety Dashboard

A comprehensive React-based dashboard for monitoring fleet safety, truck performance, audit metrics, and maintenance trends. This application provides real-time insights and analytics for truck fleet management with an intuitive user interface.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Configuration](#configuration)
- [Components](#components)
- [Contributing](#contributing)
- [License](#license)

## Features

✅ **Fleet Safety Status** - Monitor critical, moderate, and safe trucks at a glance
✅ **Audit Performance Trends** - Track audit metrics over time with visual charts
✅ **Truck Performance** - Individual truck performance analysis with detailed metrics
✅ **Common Defects** - Identify and track recurring vehicle defects
✅ **Vendor Performance** - Evaluate vendor performance metrics
✅ **Interactive Charts** - Bar charts, pie charts, and line charts for data visualization
✅ **Responsive Design** - Works seamlessly on desktop and tablet devices
✅ **Real-time Filtering** - Filter data by various parameters
✅ **KPI Dashboard** - Key performance indicators at a glance
✅ **Worst Trucks Table** - Detailed table showing trucks with highest risk

## Tech Stack

- **Frontend Framework:** React 19.1.0
- **Build Tool:** Vite 6.3.5
- **Styling:** Tailwind CSS 4.1.10
- **Routing:** React Router 7.6.2
- **Charts:** Chart.js 4.5.0 & react-chartjs-2 5.3.0
- **Icons:** React Icons 5.5.0 & Heroicons
- **Linting:** ESLint 9.25.0
- **Language:** JavaScript (ES Module)

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher recommended)
- npm (v6 or higher)
- Git

## Installation

1. **Clone the repository:**
```bash
git clone https://github.com/Tanveerkhann/Truck-Safety-Dashboard.git
cd Truck-Safety-Dashboard
```

2. **Install dependencies:**
```bash
npm install
```

3. **Install additional dependencies (if needed):**
```bash
npm install @heroicons/react chart.js react-chartjs-2 react-router-dom
```

## Usage

### Development

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the next available port).

### Production Build

Build for production:
```bash
npm run build
```

Preview the production build:
```bash
npm run preview
```

### Linting

Check code quality:
```bash
npm run lint
```

## Project Structure

```
Truck-Safety-Dashboard/
├── public/              # Static assets
├── src/
│   ├── assets/         # Images, fonts, and other static files
│   ├── charts/         # Chart components (BarChart, PieChart)
│   ├── components/     # Reusable components
│   │   ├── FilterBar.jsx          # Filtering component
│   │   ├── KPIBox.jsx             # KPI display component
│   │   ├── LineChart.jsx          # Line chart component
│   │   ├── WorstTrucksTable.jsx   # Trucks table component
│   │   └── layout/                # Layout components
│   │       ├── Layout.jsx         # Main layout wrapper
│   │       ├── Navbar.jsx         # Top navigation bar
│   │       └── Sidebar.jsx        # Side navigation menu
│   ├── pages/          # Page components
│   │   ├── AuditPerformance.jsx   # Audit performance page
│   │   ├── CommonDefect.jsx       # Common defects page
│   │   ├── FleetSafety.jsx        # Fleet safety dashboard
│   │   ├── TruckDetails.jsx       # Individual truck details
│   │   ├── TruckPerformance.jsx   # Truck performance page
│   │   └── VendorPerformance.jsx  # Vendor performance page
│   ├── App.jsx         # Main app component
│   ├── App.css         # App styles
│   ├── main.jsx        # Application entry point
│   └── index.css       # Global styles
├── .eslintrc.cjs       # ESLint configuration
├── vite.config.js      # Vite configuration
├── package.json        # Project dependencies
└── index.html          # HTML entry point
```

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot module replacement |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint to check code quality |

## Configuration

### Vite Configuration
Edit `vite.config.js` to customize build settings, server options, or plugin configurations.

### ESLint Configuration
Customize linting rules in `.eslintrc.cjs`.

### Tailwind CSS
Customize Tailwind configuration in `tailwind.config.js`.

## Components

### Layout Components
- **Navbar:** Top navigation bar with branding
- **Sidebar:** Left navigation menu with links to all pages
- **Layout:** Main wrapper component for consistent layout

### Data Display Components
- **KPIBox:** Displays key performance indicators in card format
- **WorstTrucksTable:** Shows trucks ranked by risk level
- **FilterBar:** Allows filtering of data by various parameters

### Chart Components
- **BarChart:** Display data using bar charts
- **PieChart:** Display proportional data using pie charts
- **LineChart:** Display trends over time using line charts

## Development Workflow

1. Create a new branch for your feature:
```bash
git checkout -b feature/your-feature-name
```

2. Make your changes and commit:
```bash
git add .
git commit -m "Add your meaningful commit message"
```

3. Push to your branch:
```bash
git push origin feature/your-feature-name
```

4. Create a Pull Request on GitHub

## Troubleshooting

### Port Already in Use
If port 5173 is in use, Vite will automatically try the next available port. Check the console output for the correct URL.

### Module Not Found
If you encounter import errors:
```bash
rm -rf node_modules package-lock.json
npm install
```

### Build Issues
Clear Vite cache:
```bash
rm -rf dist .vite
npm run build
```

## Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For issues, questions, or suggestions, please open an issue on [GitHub Issues](https://github.com/Tanveerkhann/Truck-Safety-Dashboard/issues).

## Author

**Tanveer Khan**
- GitHub: [@Tanveerkhann](https://github.com/Tanveerkhann)

---

**Last Updated:** May 2026
