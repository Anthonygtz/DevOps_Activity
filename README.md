## DevOps - Activity 8

This project demonstrates a CI/CD pipeline for a Flask API using GitHub Actions.

## Endpoints

- GET /hello
- POST /echo

## Implementation

- Automated testing with pytest
- Flake8 linting workflow
- Codecov integration
- Dependabot
- CodeQL
- Matrix builds

## Issues

The main issue I ran into was the matrix build failing because the yml file interpreted 3.10 as 3.1. Wrapping the versions in quotes solved the problem.