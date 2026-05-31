# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Status
This repository appears to be empty (containing only Git metadata and a .claudecode file). It is ready for new project initialization.

## Getting Started
Since there is no existing codebase, you'll need to initialize a project based on your intended technology stack. Common approaches:

1. **Choose a technology stack** (e.g., Python, JavaScript/TypeScript, Java, etc.)
2. **Initialize the project** using appropriate tools:
   - For Node.js: `npm init` or `yarn init`
   - For Python: `pip init` or create `setup.py`/`pyproject.toml`
   - For Java: Maven or Gradle initialization
   - For other languages: use their respective project initiators

3. **Set up version control** (already done via Git)
4. **Add essential files** like `.gitignore`, README, license, etc.

## Common Development Commands
Once a project is initialized, typical commands might include:

### Installation/Setup
- `npm install` / `yarn install` (JavaScript/TypeScript)
- `pip install -r requirements.txt` (Python)
- `mvn install` (Java Maven)
- `gradle build` (Java/Gradle)

### Development
- `npm run dev` / `yarn dev` (JavaScript/TypeScript development server)
- `python app.py` or `flask run` (Python)
- `mvn spring-boot:run` (Java Spring Boot)

### Testing
- `npm test` / `yarn test` (JavaScript/TypeScript)
- `pytest` (Python)
- `mvn test` (Java Maven)
- `gradle test` (Java/Gradle)

### Linting/Formatting
- `npm run lint` / `yarn lint` (JavaScript/TypeScript with ESLint)
- `flake8` or `black` (Python)
- `checkstyle` (Java)

## Project Structure Recommendations
When initializing your project, consider these common structures:

### For Web Applications
```
/ (root)
├── src/                 # Source code
│   ├── components/      # UI components (if frontend)
│   ├── pages/           # Page components
│   ├── services/        # API services
│   └── utils/           # Utility functions
├── public/              # Static assets
├── tests/               # Test files
├── package.json         # Node.js projects
├── requirements.txt     # Python projects
└── README.md
```

### For Libraries/Packages
```
/ (root)
├── src/                 # Source code
│   └── [package_name]/  # Main package code
├── tests/               # Test files
├── [package_name].egg-info/  # Python packaging
├── setup.py             # Python packaging
├── package.json         # Node.js packages
└── README.md
```

## Code Quality Practices
- Write meaningful commit messages
- Create unit tests for new functionality
- Follow language-specific style guides (PEP 8 for Python, ESLint standards for JS/TS, etc.)
- Keep dependencies up to date
- Use appropriate linting tools
- Document public APIs

## Next Steps
1. Determine what type of project you want to build
2. Initialize the project with appropriate tools
3. Establish your development workflow
4. Begin implementing features

Once you have initialized a project, consider updating this CLAUDE.md file with specific commands and guidance for your chosen technology stack.