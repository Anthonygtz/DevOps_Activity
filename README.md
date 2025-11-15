## DevOps - Activity 8

This project demonstrates a CI/CD pipeline for a Flask API using GitHub Actions.

## Endpoints

- GET /hello — returns a greeting.
- POST /echo — echoes JSON input.

## Implementation

- Automated testing with pytest + coverage
- Flake8 linting workflow
- Codecov integration for test coverage
- Dependabot for weekly dependency updates
- CodeQL static security analysis
- Matrix builds across Python

## Issues

- Needed to ensure pytest-cov was listed in requirements.txt
- Fixed minor Flake8 warnings for spacing and unused imports
- Adjusted CodeQL to use latest @v3 version to avoid deprecation warnings