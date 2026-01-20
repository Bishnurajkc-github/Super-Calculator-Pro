# Scientific Calculator Web Application

## Overview
A Flask-based web calculator application with scientific functions, unit converters, memory operations, and financial tools.

## Project Structure
```
├── main.py              # Flask application with all calculator endpoints
├── templates/
│   └── calculator.html  # Frontend HTML template
├── requirements.txt     # Python dependencies (flask, gunicorn)
├── pyproject.toml       # Python project configuration
└── generated-icon.png   # Application icon
```

## Features
- **Basic Operations**: Add, subtract, multiply, divide, power
- **Scientific Functions**: Square root, sin, cos, tan, log, exp, factorial
- **Memory Operations**: Store, recall, clear memory
- **Unit Converters**: km/miles, kg/pounds, m/feet, liters/gallons, temperature, currency
- **Financial Tools**: Tip calculator, BMI calculator
- **History**: Tracks last 10 calculations

## Running the Application
The Flask application runs on port 5000 with debug mode enabled.

**Command**: `python main.py`

## API Endpoints
- `GET /` - Renders the calculator HTML page
- `POST /calculate` - Handles all calculator operations via JSON API

## Dependencies
- Flask
- Gunicorn (for production deployment)

## Recent Changes
- January 20, 2026: Initial import and Replit environment setup
