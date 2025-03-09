# Node0 Operator Mobile Station

## Overview
Mobile control station for Node0 operations, developed by Digital Fabrica's technology division.

## Setup
1. Create and activate virtual environment:
```bash
python -m venv venv
.\venv\Scripts\activate  # Windows
source venv/bin/activate  # Unix/MacOS
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure environment:
- Copy `.env.template` to `.env`
- Fill in required environment variables

## Project Structure
```
├── backups/        # Backup data storage
├── configs/        # Configuration files
├── logs/          # Application logs
├── reports/       # Generated reports
├── scripts/       # Utility scripts
└── src/           # Source code
    └── main.py    # Application entry point
```

## Development Guidelines
- Follow PEP 8 style guide for Python code
- Document all functions and modules
- Write unit tests for new features
- Keep sensitive data in .env (never commit)

## Security
- All API keys and credentials must be stored in .env
- Regular security audits required
- Input validation on all user inputs

## Maintenance
- Regular dependency updates
- Backup strategy implementation
- Performance monitoring

Last Updated: 2025-03-08
