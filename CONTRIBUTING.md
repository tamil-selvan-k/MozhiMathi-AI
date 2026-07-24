# Contributing to MozhiMathi AI

Thank you for your interest in contributing to MozhiMathi AI.

## Getting started

1. Fork the repository and clone your fork.
2. Create a branch for your work:
   - `git checkout -b feature/your-change`
3. Set up the project locally:
   - Backend: create a virtual environment in `backend/`, install `requirements.txt`
   - Frontend: install dependencies in `frontend/`

## Development guidelines

- Keep changes focused and small.
- Follow the existing project structure and naming conventions.
- Update documentation when behavior or APIs change.

## Validate your changes

Run checks before opening a pull request:

### Frontend

From `frontend/`:

- `npm run lint`
- `npm run build`

### Backend

From `backend/`:

- `pytest`

## Submitting a pull request

1. Push your branch to your fork.
2. Open a pull request to this repository.
3. Clearly describe:
   - What changed
   - Why it changed
   - How it was tested

Please keep pull requests easy to review and include only related changes.
