---
applyTo: "src/backend/**/*.py,src/app.py"
---

## Backend Guidelines

- All API endpoints must be defined in the `routers` folder.
- Load example database content from the `database.py` file.
- Log internal error details on the server; return appropriate HTTP status codes and safe, actionable error messages to the frontend without exposing sensitive information.
- Ensure all APIs are explained in the documentation.
- Verify changes in the backend are reflected in the frontend (`src/static/**`). If possible breaking changes are found, mention them to the developer.
