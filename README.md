# Code with AI — AI Code Analyzer

A web-based AI-powered code analysis tool that helps inspect code for complexity, potential vulnerabilities, and notable features. Built with Vite + React for a fast, modern development experience.

## Features

- **AI Analysis**: Detects code smells, vulnerabilities, and complexity hotspots using AI integration.
- **Interactive Visualization**: Visual components including complexity charts and vulnerability cards.
- **Chat Integration**: Conversational assistant for follow-up questions about analysis results.
- **Feature Selection**: Customize which analysis features to run on your code.
- **Responsive UI**: Built with React and Tailwind CSS for a smooth user experience.

## Quick Start

### Requirements

- Node.js (>=14 recommended)
- npm

### Installation

```bash
npm install
```

### Development Server

```bash
npm run dev
```

Open your browser and navigate to the URL printed in the terminal (typically `http://localhost:5173`).

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
src/
├── components/
│   ├── ComplexityChart.jsx      # Displays code complexity metrics
│   ├── VulnerabilityCard.jsx    # Shows detected vulnerabilities
│   ├── Form.jsx                 # Main analysis form
│   ├── SelectFeatures.jsx       # Feature selection interface
│   ├── SendButton.jsx           # Submit button component
│   ├── ui/                      # Reusable UI primitives
│   │   ├── button.jsx
│   │   ├── card.jsx
│   │   ├── select.jsx
│   │   └── textarea.jsx
│   └── ...other components
├── pages/
│   ├── Home.jsx                 # Landing page
│   ├── Chat.jsx                 # Chat interface
│   └── ...
├── utils/
│   └── gemini.js                # AI integration helper
├── lib/
│   └── utils.js                 # Shared utilities
├── data/
│   └── features.js              # Feature definitions
├── App.jsx                      # Main app component
├── main.jsx                     # Entry point
└── index.css                    # Global styles
```

## Usage

1. **Open the Application**: Navigate to the local dev server.
2. **Input Code**: Paste or upload code using the form component.
3. **Select Analysis Features**: Choose which checks to run.
4. **View Results**: See complexity metrics and vulnerability reports.
5. **Chat for Details**: Use the Chat page to ask follow-up questions about findings.

## Configuration

- **Vite Config**: `vite.config.js` — Bundling and dev server settings.
- **Tailwind CSS**: `tailwind.config.js` — UI styling framework.
- **ESLint**: `eslint.config.js` — Code quality rules.
- **PostCSS**: `postcss.config.js` — CSS processing.

## Development Notes

- Components follow React best practices with functional components and hooks.
- UI primitives are in `src/components/ui/` for consistent styling.
- AI analysis logic is handled in `src/utils/gemini.js`; extend this for new analysis types.
- Keep styling consistent using the global `index.css` and Tailwind utilities.

## Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit: `git commit -m "Add your message"`.
4. Push to your fork and submit a pull request.

Please include a clear description of changes and any related tests.


## Contact & Support

For questions, bug reports, or feature requests, please open an issue on the [GitHub repository](https://github.com/realkeshav08/Code-with-Ai).

---

Happy coding with AI! 🚀
